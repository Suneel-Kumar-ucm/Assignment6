# Assignment6


1.Use the use case in the class: 
a. Add more Dense layers to the existing code and check how the accuracy changes. Apart from orginal code we have added extra dense layers by loading the dataset and by creating the model then hidden layer ane then added output layer...

![image](https://github.com/Suneel-Kumar-ucm/Assignment6/assets/156639138/f0a4e737-0078-406d-9aa3-df0a75cc4195)




2.Change the data source to Breast Cancer dataset * available in the source code folder and make required changes. Report accuracy of the model. Then we have added the breast cancer dataset then extracting features and labelsthen encoding the label then splitting the data into training and testing dataset and then evaluting the data set.

![image](https://github.com/Suneel-Kumar-ucm/Assignment6/assets/156639138/ec73e5bb-a654-42d8-bd05-068c7ec52cb3)

3.Normalize the data before feeding the data to the model and check how the normalization change your accuracy (code given below). from sklearn.preprocessing import StandardScaler sc = StandardScaler() Breast Cancer dataset is designated to predict if a patient has Malignant (M) or Benign = B cancer




first we have loaded the dataset and then extract the features and labels then encoded the lables and then scale the input features then split the training and test data then print the data

In class programming: Use Image Classification on the hand written digits data set (mnist)

1.Plot the loss and accuracy for both training data and validation data using the history object in the source code. 
Next we have plotted the model loss and model accuracy with title,xlabel and ylabel and legends function


![image](https://github.com/Suneel-Kumar-ucm/Assignment6/assets/156639138/4be420d8-2cda-401a-8cb3-3f746649adb3)


![image](https://github.com/Suneel-Kumar-ucm/Assignment6/assets/156639138/606826f0-c105-4a63-9964-457330b1ac21)

2.Plot one of the images in the test data, and then do inferencing to check what is the prediction of the model on that single image. 
Plotting the single image in the test data and then getting the prediction of the model

![image](https://github.com/Suneel-Kumar-ucm/Assignment6/assets/156639138/4f8f7a62-c0a4-42bf-91cc-2bab57a9d760)

3.We had used 2 hidden layers and Relu activation. Try to change the number of hidden layer and the activation to tanh or sigmoid and see what happens.
we have changed the hidden layers to tanh and sigmoid to see the output and finding the accuracy

![image](https://github.com/Suneel-Kumar-ucm/Assignment6/assets/156639138/8d0c9aa3-2f5c-473c-9798-f1defe4f1bda)

4. Run the same code without scaling the images and check the performance?
  we have ran the same code to without checking the performance and scaling of the images
