**Project overview:**

Big companies involved in financial engagements and banks are using machine learning for fraud detection. This helps companies to keep consumers safe. Machine learning can also be valuable to companies that handle credit card transactions. The technology is trained to flag transactions that appear to be fraudulent based on certain criteria according to the company’s rules. By detecting such mishaps, companies can be prevented from falling prey to a big loss. Besides, an enterprise can also gain insights into its competitive landscape and consumer loyalty and forecast sales or demand in real-time with machine learning.Fraud detection methods are continuously developed to defend criminals in adapting to their fraudulent strategies.This project covers credit card fraud and is meant to look at a dataset of transactions and predict whether it is fraudulent or not. 
  
  
**Problem statement:**

With the growth of e-commerce websites, people and financial companies rely on online services to carry out their transactions that have led to an exponential increase in the credit card frauds.The goal of this project is to help a bank to detect fraudulent credit card transactions.
  

**Solution applied:**

This data is fit into a model and the following outlier detection modules are applied on it:
	    • Local Outlier Factor
	    • Isolation Forest
      
      
**Results:**

Isolation Forest: 43
0.9972200672355831
              precision    recall  f1-score   support

         0.0       1.00      1.00      1.00     15424
         1.0       0.51      0.52      0.52        44

    accuracy                           1.00     15468
   macro avg       0.75      0.76      0.76     15468
weighted avg       1.00      1.00      1.00     15468

Local Outlier Factor: 87
0.9943754848719938
              precision    recall  f1-score   support

         0.0       1.00      1.00      1.00     15424
         1.0       0.02      0.02      0.02        44

    accuracy                           0.99     15468
   macro avg       0.51      0.51      0.51     15468
weighted avg       0.99      0.99      0.99     15468


**Conclusion:**

Our Isolation Forest method (which is Random Forest based) was able to produce a better result. Looking at the f1-score 26% (or approx. 30%) of the time we are going to detect the fraudulent transactions.


**References used:**

https://www.google.com/search?q=credit+card+fraud+detection

https://www.kaggle.com/mlg-ulb/creditcardfraud
  
  
