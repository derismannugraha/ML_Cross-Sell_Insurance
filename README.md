***Predicition Cross-Sell Health and Vehicle Insurance***

This project about predicting feature which important to increase sell Vehicle insurance service using Supersived Learning Classification(K-Nearest Neighbors, Decision Tree, and Random Forest

**Summary**

Dataset is known to be unbalanced (oversampling), the author performs an imbalance oversampling treatment for effectively run machine learning algorithm.The results of research conducted to predict heart disease and its causes. from the modeling carried out including *K-Nearest Neighbors, Decision Tree, and Random Forest*. The modeling results above show that ***Random Forest*** has the most significant accuracy of all the modeling algorithms with , and average Cross Validation with 3 Folds have scores **85.15%**. 

Next, the authors carry out further evaluations using ***Random Forest*** with Randomize search CV hyperparameter tuning with instrument *<i>bootstrap=False, max_depth=30, min_samples_leaf=4, min_samples_split=8, n_estimators=50, random_state=10<b>*. After Hyperparamater tuning the Random Forest Accuracy became **84.32%**, with Confussion Matrix Value in data train 48.080 with response yes and 3.426 with Response No. In data test 16.991 with response yes, and 61.757 with response no.
 
In predicting and knowing the cause of Cross sell insurance by the existing sample data with using the ***Permutation Importance*** methods, conclusion from the entire sample it shows ***Policy Sales Channel ,Age, Previously Insure 1 (Yes), Region Code, Vehicle Damage (Yes), Previously Insure 1 (Yes), Premis status ( Base on size of Annual Premium)Vehicle Damage (No)*** which are influential factors Upselling the Vehicle Insurance Service

**Recommendation**
 
For recommendations, The Executetive Insurance Company should consider these 8 influential variables early so that the selling Vehicle Insurance service to Customer more effective and efficient. For example, re-offering customer with Sales Channel Policy that effective to sells vehicle insurance, and expanding to the Region area which have the most customer who didn't have Insurance. with unique and creative promotion or benefit to prospective customer sells their insurance service
