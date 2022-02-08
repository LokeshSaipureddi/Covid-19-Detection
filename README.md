# Covid-19-Detection
### Proposed Architecture
A Convolutional Neural Network (Conv Net) is a special category of neural 
network architectures that takes an image as input, assigns importance to distinct 
aspects in the image, and can distinguish between them [9], [5]. They have made 
significant progress toward improved image classification performance. The 
proposed model exploited various state-of-the-art CNN models for classification 
such as InceptionV3, Resnet50V2, and Efficient Net b7 for extracting features. 
The high-dimensional nature of the transfer learned deep features produced from 
multiple deep convolutional models could have a negative impact on the 
classification model. This unveils the limitation of this study. High-level features 
obtained from the final FC layer of the aforementioned deep learning models are 
then fed into machine learning models to analyze how well the ML models are 
performing on the deep learning features. The workflow of the proposed model is 
shown in Figure.
![alt text](https://github.com/LokeshSaipureddi/Covid-19-Detection/blob/main/Screenshot%202022-02-08%20130831.png)
### Results
We got the best results using a combination of InceptionV3 and SVM out of all
the Transfer Learning Models we tried. Tables 2 and 3 show the results obtained
with and without image pre-processing as explained in Section 3.2. On the SVM
model, we achieved an accuracy of 86.12 percent, 85.24 percent, and 78.19
percent with the Incep-tionV3, Resnet 50V2, and Efficient B7, respectively.
According to Tables 2 and 3, there is an increase in accuracy for all three models
after applying to pre-process.
Table 2: Performance Comparison of various combinations of deep learning and
machine learning models on classification without Image pre-processing
![alt text](https://github.com/LokeshSaipureddi/Covid-19-Detection/blob/main/Screenshot%202022-02-08%20131249.png)
Table 3: Performance Comparison of various combinations of deep learning
and machine learning models on classification with Image pre-processing
![alt text](https://github.com/LokeshSaipureddi/Covid-19-Detection/blob/main/Screenshot%202022-02-08%20131325.png)

