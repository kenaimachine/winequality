
#### Sharing Part of my project work done while taking Specialist Diploma In Applied Artificial Intelligence
# winequality
The goal of this project is to predict the wine quality rating class from actual rating. Several neural models are constructed to compare against classical Machine learning models. 


## 1.	Summary Of Work

The goal of this project is to predict the wine quality rating class from actual rating. Several neural models are constructed to compare against classical Machine learning models. 

Essentially this project is comprised of  4 tasks, each experimenting on different aspects of feedforward, fully connected neural networks as well as classical machine learning.

There are many interesting findings from the project. These are separately discussed throughout the report. In general, there are three important key steps noted to have strong impact on results. 1) Standardization of data. 2) Creating a balanced dataset using oversampling methods. 3) Regularization using Dropout helped prevent overfitting during training. 

Another observation was that feature selection did not lead to better outcomes for neural network model. 

Composition Of Tasks For This Project: 

|Task Description|	Experiments	|Jupyter Notebook File|
-----------------|--------------|---------------------|
|Task1|	Experiment 1 : Decision Tree Classifier, Experiment 2 : Decision. Tree Clasifier (GridSearch), Experiment 3 : SVM (GridSearch)|	Task1_Traditional ML Red And White Wine.ipynb|
|Task2-1|	Experiment 1: Basic Neural Network|	Task2_1-WineQuality-RedWineOnly.ipynb|
|Task2-1|	Experiment 2 : Deep Neural Network|	Task2_1-WineQuality-RedWineOnly.ipynb|
|Task2-2|	Experiment 1: Basic Neural Network|	Task2-2-WIneQuality-WhiteWineOnly.ipynb|
|Task2-2|	Experiment 2 : Deep Neural Network|	Task2-2-WIneQuality-WhiteWineOnly.ipynb|
|Task3|	Experiment 1 :Classify Wine Quality. Basic Neural Network	|Task3_WIneQuality_WineType.ipynb|
|Task3| Experiment 2 : Classify Wine Quality. Deep Neural Network	|Task3_WIneQuality_WineType.ipynb|
|Task3|	Experiment 3 : Predict Wine Quality (Regression Task)	|Task3_WIneQuality_WineType.ipynb|
|Task3|	Experiment 4 : Classify Wine Type	| Task3_WIneQuality_WineType.ipynb|
|Task4|	Experiment 1 : Single Input, Multiple Output Complex Neural Network|	Task4_FunctionalAPI_WIneQualityType.ipynb|
|Task4| Experiment 2 : Multiple Input, Multiple Output Complex Neural Network|	Task4_FunctionalAPI_WIneQualityType.ipynb|


## 2.	Notes On Dataset

Dataset is from UCI Machine Learning Repository. Briefly, there are two datasets related to red and white wine samples from Portugal.  There is no data about grape types, brand, selling price etc.)

Links to download the files:
•	http://archive.ics.uci.edu/ml/machine-learning-databases/wine-quality/winequality-white.csv
•	http://archive.ics.uci.edu/ml/machine-learning-databases/wine-quality/winequality-red.csv
•	https://archive.ics.uci.edu/ml/datasets/wine+quality

![alt text](https://user-images.githubusercontent.com/61535921/111034847-6749b300-8452-11eb-9822-979234f768db.png?raw=true)

![alt text](https://user-images.githubusercontent.com/61535921/111034883-995b1500-8452-11eb-9bd3-4e7f2d8e5ca9.png?raw=true)

![alt text](https://user-images.githubusercontent.com/61535921/111034928-dc1ced00-8452-11eb-831a-16965084f3be.png?raw=true)

![alt text](https://user-images.githubusercontent.com/61535921/111034945-e939dc00-8452-11eb-9f6c-ba3db82f9564.png?raw=true)

![alt text](https://user-images.githubusercontent.com/61535921/111034947-e9d27280-8452-11eb-9187-a012f5692d52.png?raw=true)

![alt text](https://user-images.githubusercontent.com/61535921/111035070-91e83b80-8453-11eb-9ce9-a6b85eaa60b7.png?raw=true)

![alt text](https://user-images.githubusercontent.com/61535921/111035069-8eed4b00-8453-11eb-8124-e8e24935735e.png?raw=true)

![alt text](https://user-images.githubusercontent.com/61535921/111035083-9f9dc100-8453-11eb-94be-a9b325c1a813.png?raw=true)

![alt text](https://user-images.githubusercontent.com/61535921/111035081-9c0a3a00-8453-11eb-9481-5a4a3e389aaf.png?raw=true)

![alt text](https://user-images.githubusercontent.com/61535921/111035084-a1678480-8453-11eb-9956-f8ed5d80b2d4.png?raw=true)

