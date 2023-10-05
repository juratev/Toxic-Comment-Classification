# Toxic-Comment-Classification
Identify and classify toxic online comments - multilabel classification task.

Project completed on **September 29, 2023.**

### **Dataset**
The dataset consists of a large number of Wikipedia comments, labeled by human raters for toxic behavior. The train dataset contains 159K labeled comments, and there are 63K in the test dataset. <br>
<a href="https://www.kaggle.com/c/jigsaw-toxic-comment-classification-challenge"> The link to the dataset in Kaggle.</a>  <br> 
The comments are categorized under the following types of toxicity: toxic, severe_toxic, obscene, threat, insult, and identity_hate.

### **Goal**
The aim is to develop a model that predicts the probability of each type of toxicity for every comment. The evaluation metric is the mean column-wise ROC AUC. In other words, the score is the average of the individual AUCs for each predicted column.

### **Project Outline**
1. Loading the data from Kaggle.
2. Explanatory Data Analysis (EDA).
3. Classification using a pre-trained Roberta model.
4. Evaluation using the ROC-AUC score.
5. Summary.
