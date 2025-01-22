![pyLDAvis capstone](https://github.com/user-attachments/assets/2bd314e7-2671-4fec-b9fb-75ebb0204852)
![capstone word cloud](https://github.com/user-attachments/assets/022e75a4-1ea6-4f17-bbff-ce2410a29c51)
![capstone top 10 feature importance ](https://github.com/user-attachments/assets/5c740ce0-bac3-40b0-93e4-5f11957b8cce)
![capstone project sentiment analysis picture](https://github.com/user-attachments/assets/9a07778b-6041-4c16-aaaa-ed8bfe448f88)
![capstone project Proportion of sentiment categories](https://github.com/user-attachments/assets/9a6ba82f-ca3b-4691-bc32-fd8846e6adcb)
![capstone project pridiction  value](https://github.com/user-attachments/assets/071b81c4-405a-4e58-8dda-57c563b36b21)
![capstone project logistic regression prediction value ](https://github.com/user-attachments/assets/b397b414-fd54-46e4-b95e-6762320fc8e6)
![capstone project Distribution of reviews sentiment](https://github.com/user-attachments/assets/f4e134e6-6327-445a-9c01-bd18009fbdd8)
![capstone importance combined head](https://github.com/user-attachments/assets/60bcac93-5ee8-4d79-9f46-aa206fb414ac)
# Ai-Capstone-_project-_Amazon_E-Commerce
Ai Capstone_project_Amazon_E_Commerce
AI-Capstone-Project-on-E-Commerce-Amazon-Domain-

Project Task: Week 1 Class Imbalance Problem: 
1. Perform an EDA on the dataset.
 a) See what a positive, negative, and neutral review looks like.
 b) Check the class count for each class. It’s a class imbalance problem.
2. Convert the reviews in Tf-Idf score.
3. Run multinomial Naive Bayes classifier. Everything will be classified as positive because of the class imbalance.
          
Project Task: Week 2 Tackling Class Imbalance Problem:
Oversampling or undersampling can be used to tackle the class imbalance problem. 
In case of class imbalance criteria, use the following metrices for evaluating model performance: precision, recall, F1-score, AUC-ROC curve. Use F1-Score as the evaluation criteria for this project. Use Tree-based classifiers like Random Forest and XGBoost. Note: Tree-based classifiers work on two ideologies namely, Bagging or Boosting and have fine-tuning parameter which takes care of the imbalanced class.

Project Task: Week 3 Model Selection: Apply multi-class SVM’s and neural nets. Use possible ensemble techniques like: XGboost + oversampled_multinomial_NB. Assign a score to the sentence sentiment (engineer a feature called sentiment score). Use this engineered feature in the model and check for improvements. Draw insights on the same.

Project Task: Week 4 Applying LSTM: Use LSTM for the previous problem (use parameters of LSTM like top-word, embedding-length, Dropout, epochs, number of layers, etc.) Hint: Another variation of LSTM, GRU (Gated Recurrent Units) can be tried as well.
Compare the accuracy of neural nets with traditional ML based algorithms. 
Find the best setting of LSTM (Neural Net) and GRU that can best classify the reviews as positive, negative, and neutral. Hint: Use techniques like Grid Search,
Cross-Validation and Random Search Optional Tasks: Week 4 Topic Modeling:
1. Cluster similar reviews. Note: Some reviews may talk about the device as a gift-option. Other reviews may be about product looks and some may highlight about its battery and performance. Try naming the clusters.
2. Perform Topic Modeling Hint: Use scikit-learn provided Latent Dirchlette Allocation (LDA) and Non-Negative Matrix Factorization (NMF). Download the Data sets from here .
