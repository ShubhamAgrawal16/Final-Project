AIM 
Data Analysis process of finding the meaningful insights from the IRIS dataset 

DEFINATION OF IRIS 
Iris Dataset is considered as the Hello World for data science. It contains five columns namely – Petal Length, Petal Width, Sepal Length, Sepal Width, and Species Type. Iris is a flowering plant, the researchers have measured various features of the different iris flowers and recorded them digitally.

DESCRIPTION
Iris dataset is very common in data science. My iris dataset contains 150 rows and 6 coloumns . We have id,petal length, petal width, sepal length, sepal width, Species etc . 
My Datasource was Kaggle website which i am collected my iris data . We are uploading that file in pandas for Data Analysis process for finding the menaingful insights so fost we are doing data prepartaion then we have data processing, data manipulation , data cleaning, EDA process,and then at last we have model building process vy using either it was a supervised learning model or unsupervised learning model. i am doing data cleaning process on pandas by finding the errors by using isnull() functions and there are various other methods also for finding the error and to permamnently delete the data from the dataframe we use axis=1, inplace=True. It will delete permanent from the dataframe. in data manipulation we are use concatenation , join , merge , sort etc in dataframe . 
The Data Set
There are 150 flower records in total and 3 flower classes (setosa, versicolor, verginica). Each class has 50 records. Each flower has 4 measures in Petal Length, Petal Width, Sepal Length and Sepal Width.
The Approach
The idea is to use the 4 measures like Petal Length, Petal Width, Sepal Length and Sepal Width to cluster the data. The resulting clusters will need to compare with the actual flower classes
We are using the Support Vector Machine and KNN algorithm to find out the accuracy score, f1_score,recall and precision in model building to check how many percantage our model work or not??
support vector machine will give the highest F1_score that is 97percent

Conclusion
Visualizing easily come to know which is smaller and which is larger between sepal length, sepal width, petal length, petal width. When we add model the model will be able to classify what kind of the color it is because iris dataset is completely based on the classification. 
