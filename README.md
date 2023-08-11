# Project 2

Source: [https://www.kaggle.com/datasets/wenruliu/adult-income-dataset]

Description of data and Business Problem:

Our dataset provides an individual's income and various other features such as their education level, age, gender, occupation etc. Intuitively, our stakeholders believe that an individuals income is influenced by many factors, such as the features listed previously. They want to better predict an individual's income using these factors.

Analytical Insights:

Based on one of our multivariate plots, the stakeholders, who would like to predict our target feature income, would be interested to know that those individuals who make >50k are on average older (>40 years old ) than those who make <=50k (~38 years old). This could be due to individuals who are older having more work experience, resulting in higher incomes.

![image](https://github.com/anjalixprakash/Project2/assets/134672983/3198a90d-dd63-4975-b21e-fece2ac41b07)


They would also be interested to know that amongst the labelled races, white individuals seem to have higher capital-gain than other races. Races labelled under "other" (could potentially be unidentified individuals, or individuals of many races) have the least capital gain. This could be due to many factors, such as generational wealth, lack of opportunities etc.

![image](https://github.com/anjalixprakash/Project2/assets/134672983/51734b28-3abf-4999-9ca9-b2982b201257)

Best Model:

![image](https://github.com/anjalixprakash/Project2/assets/134672983/88f4ae53-5ac5-4ea9-a50f-84a03e61309a)


It appears that amongst the 4 models in our report, the tuned Random Forest Classification model that has been feature engineered performed the best. It has a recall macro average of 0.76, precision of 0.83,  a true positive ratio of 0.95 and true negative ratio of 0.6. Based on these metrics, we can be confident that our model will correctly identify an individual who makes >50k with 95% accuracy and <=50k with a 60% accuracy. 

Based on the analytical findings, I would recommend stakeholders, who are trying to predict the income of an individual, ideally apply even more feature engineering techniques to raise the accuracy of predicting individuals who make <=50k. I would also notify that stakeholders that many features can be good identifiers of how the income may be. Such as gender, age, and race. 
