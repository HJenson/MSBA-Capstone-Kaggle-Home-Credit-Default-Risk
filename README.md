# MSBA Capstone Kaggle Home Credit Default Risk

The included notebooks in this repository were my efforts in competing in the online Kaggle competition with three other students. The notebooks are representative of my individual contributions to the team's efforts. This was an exciting project, and I learned a great deal about working with imbalanced data. 

In this project, we were asked to build and train a predictive machine learning model to estimate customers’ likelihood of loan default. Home Credit provided the data. Home Credit is a financial lending service provider striving to offer financial services to customers with little or no credit history. Their goal is to provide loans to their clients, who will most likely repay them. Through machine learning and data analysis, they want to maximize their ability to identify customers who can pay their loan payments on time. Home Credit desires to maximize the number of loans to customers capable of repayment, as it will boost the company's financial returns. The ‘MSBA Capstone EDA-Project.ipynb’ notebook will walk through the process used to create the final dataset used to train and test the final model. The ‘MSBA Capstone Models-Project.ipynb’ notebook builds on the EDA to develop and test 5 different models and create the final ensemble model.

The final result of the work completed in these two notebooks was developing a single ensemble model. It was built by taking the three top-performing models from each sampling method used in the analysis. The final model achieved a Kaggle score of 71.3%, which was 21.3% higher than the majority class.
 
The two notebooks depict my efforts in the initial exploration of the provided datasets from the Kaggle website. The EDA walks you through my initial process of cleaning the data and creating additional features for the final model. My work for the EDA focussed on exploring the target variable, creating new variables, and addressing null values. The Model notebook is my addition to the final EDA and contributions to model development. My work was to train and test linear models on our final dataset. In addition to linear models, I chose to add XGBoost as another modeling method to try. This proved helpful as XGBoost was one of the best-performing methods for this data. Additionally, the Model notebook includes three sampling methods used to try and correct for the significant imbalance contained within the target variable. We wanted to determine which sampling method and model combination would produce the best results. Ultimately, we used the top-performing model using each of the three sampling techniques to develop our final ensemble model.
 
This competition aimed to help home credit correctly identify customers likely to default on loans. Our model increased accuracy by 21.3% compared to using the majority class of the target variable. This is very significant, as correctly identifying customers as likely to default would protect Home Credit from potential losses from working with clients that are not likely to repay any loans provided to them. The model can also effectively determine which customers are likely to repay their loans. This would benefit Home Credit, as they could make additional revenue when working with customers who repay their loans. It is recommended that Home Credit use this model as a part of their loan application-creating process. By implementing this model, business revenue will increase, and Home Credit can continue to pursue its mission of helping those with limited access to credit.

This project had a variety of challenges along the way. One of the primary challenges I faced for my portion of the competition was keeping the train, and test sets the size they needed. In the initial EDA notebook, there was an error in the number of features in the train set. It had three more features than the test set when it should have only one additional column. The first task when working with the model assignment was to fix the datasets. It took some troubleshooting of my code to find where the error occurred and correct the code. It was a great exercise in patients and online research to correct coding mistakes. The only other limitation our group faced was the computer power of our laptops. The datasets could be extensive, and running the models would take hours. It was painful to find an error in the code after waiting four-plus hours for the code to complete. In the end, our group was able to succeed through determination, and it paid off in the end with a successful model.

The biggest takeaway from this project was the magnitude of the datasets. Working with complex data that had little to no meaning to me was fun. It's what I would imagin a lot of data scientists face when working for a company. The features may not have any meaning to you, but you can still create a successful model without knowing the data's context. I was excited to try new models or create a new feature and see how it may impact the overall model performance. It was fun using knowledge from previous classes to help drive the success of this project. Now that this project is complete, I’m excited about what other projects I will have the chance to work on.

The project uses data from the kaggle website to attempt to predict credit default.
Please see the link below for specific Kaggle competition information and data.
https://www.kaggle.com/competitions/home-credit-default-risk
