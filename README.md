**QCMG ( Questionnaire à Choix Multiple Generation )** is an AI-powered tool whose objective is to generate Quizzes from an academic paragraph. 
This is meant to help students and engineers prepare for their exams and interviews by quickly generate questions based on their textual resources. 


---

## **Dataset:**
This model has been trained on the [SQuAD](https://rajpurkar.github.io/SQuAD-explorer/) dataset: 

> **SQuAD2.0** combines the 100,000 questions in SQuAD1.1 with over 50,000 unanswerable questions written adversarially by crowdworkers to
> look similar to answerable ones. To do well on SQuAD2.0, systems must
> not only answer questions when possible, but also determine when no
> answer is supported by the paragraph and abstain from answering.


---

## **Training:**

We finetuned a **bert-base-cased**. The following tables show the hyper parameters that has been used during the training: 

| Hyper parameter|Value |
|--|--|
|Learning rate | 5e-5|
|Optimizer|AdamW|
|Epochs|5|
|Scheduler|Linear Schedule|
|Loss function|Cross Entropy Loss|


