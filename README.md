# Donors_Choose_Project_Funding_Approval_Prediction
# Context
<b><br>DonorsChoose.org receives hundreds of thousands of project proposals each year for classroom projects in need of funding. Right now, a large number of volunteers is needed to manually screen each submission before it's approved to be posted on the DonorsChoose.org website.</b></br>
# Task
<b><br> Task is to predict whether or not a DonorsChoose.org project proposal submitted by a teacher will be approved, using the text of project descriptions as well as additional metadata about the project, teacher, and school. DonorsChoose.org can then use this information to identify projects most likely to need further review before approval.</br></b>

# Steps to solve problem
<b><br>1: Performed Exploratory Data Analysis to understand the dataset by plotting plots for each features for analysis </br></b>
<b><br>2: Performed Data Preprocessing by removing data inconsistencies for the features of the dataset </br></b>
<b><br>3: Performed Encoding for handling categorical and numerical features, text columns using (Bag of Words and TF IDF vectorizer) </br></b>
<b><br>4: Implemented Machine Learning Models like Naive Bayes, Random Forest with HyperParameter Tuning and evaluated the model with metrics AUC and Accuracy. By Plotting results. Understanding the model by getting the most important features for model results </br></b>
<b><br>5: Implemented the 3 different LSTM architecture models by using Tokenizer for text column essay and using predefine Glove Vectors. Executed the 3 different LSTM architecture models and evaluated the models with metric.</br></b>

# Few Snapshots of Visualization and Analysis done

![image](https://user-images.githubusercontent.com/55294349/132895293-07ef19da-a9d0-412b-9c4b-898a7e8a53e7.png)
![image](https://user-images.githubusercontent.com/55294349/132895241-373bc2f3-234a-4fbf-82a7-da2347586113.png)
![image](https://user-images.githubusercontent.com/55294349/132895536-f466ee3d-da8a-40dd-8cf9-0406fa74a75d.png)
![image](https://user-images.githubusercontent.com/55294349/132895547-b44c4a05-db3c-46ee-bccd-3f737738932f.png)
![image](https://user-images.githubusercontent.com/55294349/132895583-ffdb58df-ee5d-4d07-9cc4-0bd7af92837a.png)
![image](https://user-images.githubusercontent.com/55294349/132895648-b8c17589-5332-47a3-aa8a-bb15e0e46f35.png)
<b><br> Results of Naive Bayes Model with Bag of Words Vectorizer </b></br>
![image](https://user-images.githubusercontent.com/55294349/132895771-446b94ed-a330-4416-886a-ffd7502a0f1d.png)
<b><br> Results of Naive Bayes Model with HyperParameter Tuning with TF IDF Vectorizer </b></br>
![image](https://user-images.githubusercontent.com/55294349/132895978-34c51e2c-9369-4c9b-9047-77b6b26e07bf.png)
<b><br> Important features for Naive Bayes with Hyperparameter Tuning with Tf IDF Vectorizer </br></b>
![image](https://user-images.githubusercontent.com/55294349/132896059-c65d4cbe-cb5f-409a-b2a9-a9ccd345615d.png)
<b><br> Results of Random Forest with HyperParameter Tuning with Bag of words vectorizer </br></b>
![image](https://user-images.githubusercontent.com/55294349/132896561-bf881ee2-0877-4a90-baf1-e445d2bd7946.png)
![image](https://user-images.githubusercontent.com/55294349/132896599-4ff21527-f679-4953-9078-a1c9580841a1.png)
![image](https://user-images.githubusercontent.com/55294349/132897027-4f0214eb-3374-43ea-b0b1-20aa563b0fee.png)







