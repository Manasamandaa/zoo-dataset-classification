# zoo-dataset-classification
using data mining techniques I want to classify the type of the animal based on their features using Orange tool

#about the data set
The Zoo dataset is a popular dataset frequently used in the fields of machine learning and 	data 	mining for classification tasks.The primary aim of the Zoo dataset is to serve as a benchmark for various classification 	algorithms. It provides a straightforward and well-defined set of features 	that allow practitioners to 	test, compare, and evaluate the performance of different classification methods. This includes 	algorithms such as: Decision Trees,k-Nearest Neighbors (K-NN),Naive Bayes,Support Vector 	Machines (SVM),Neural Networks.The Zoo 	dataset comprises 101 animal records, each 	characterized by a set of attributes that describe 	various features of the animals. These attributes are designed to help classify the animals into one of 	seven predefined categories. The dataset is particularly useful for demonstrating classification 	algorithms, feature selection, and data preparation techniques.


# Tool used
# Orange  tool description

It is an open-source data visualization, data mining, and machine learning tool. Orange is a 	scriptable  environment for quick prototyping of the latest algorithms and testing patterns. It is a group 	of python-based modules that exist in the core library. It implements some functionalities for which 	execution time is not essential, and that is done in Python.
Orange is a set of graphical widgets that utilizes strategies from the core library and orange modules and gives a decent user interface. All these together make an orange an exclusive component-based algorithm for data mining and machine learning. Orange is proposed for both experienced users and analysts in data mining and machine learning who want to create and test their own algorithms while reusing as much of the code as possible, and for those simply entering the field who can either write short python contents for data analysis.

# Preprocessing Techniques applied

# i)Continuze  discrete values: 
In Orange, "continuizing" discrete variables refers to the process of converting categorical (discrete) variables into continuous (numeric) variables. This conversion is necessary because many machine learning algorithms and statistical methods require numerical input. By transforming categorical data into a continuous format, these methods can process the data effectively. 
# ii)Select random features:
The "Select Random Features" function is used to randomly choose a subset of features (attributes or variables) from your dataset. This can be particularly useful in several scenarios. For instance, when training a machine learning model, selecting a random subset of features can help reduce computational time and resources, allowing for quicker experimentation and model evaluation. 

# Classification techniques applied
1.Naive Bayes
2.Support Vector Machine
3.Tree
4.KNN

# Analysis Part
•	From the above analysis,Naive Bayes has more accuracy.Before preprocessing Naïve Bayes has accuracy of 0.921.After applying preprocessing technique(continuize discrete variables) the accuracy is increased to 0.999.after applying select random features the accuracy is increased to 0.950.
•	Therefore ,Naïve Bayes gives the best accuracy for classifying the animals based on their features.

  

