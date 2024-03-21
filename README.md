# Berkeley Capstone project - Convolutional neural network to classify traffic signs
This is the final Capstone project for the Berkeley professional certificate in Machine learning and artificial intelligence program, for this final project I followed the CRISP-DM model to develop a Machine learning model that can be used to identify traffic signs

A key component of Autonomous vehicles is the accurate detection and interpretation of traffic signs, as it plays a crucial role in enabling these vehicles to navigate intelligently and interact seamlessly with their surroundings. In addition, safety is a critical requirement for autonomous vehicles so the accurate recognition of traffic signs is vital for the proper operation of these vehicles.

in this exercise, we implemented a convolutional neural network using the Kaggle dataset GTSRB - German Traffic Sign Recognition Benchmark, which is a multi-class, single-image classification dataset. since this is a scholastic exercise we aim to achieve ~90% on test accuracy

The dataset is from Kaggle.com and can be found at this location: https://www.kaggle.com/datasets/meowmeowmeowmeowmeow/gtsrb-german-traffic-sign

Below, it is a sample picture of the traffci signs in the data set 

![image](https://github.com/PedroPachucaHerrera/Capstone_final/assets/39275405/025d9ef2-4c4b-4a8f-a97c-5ed9925f4a76)

the following libraies were used during this exercercise
* ####  Pandas
#### - Numpy
#### - Keras
#### - CV2
#### - tensorflow
#### - sklearn

A convulational neural network model was implemeneted with excellent results above and beyond the target:

### Trainin accuracy = 96%
### Validation accuracy: 98%
### Test accuracy : 93%

for the deployment a ramdom sample was tested and the result was positive 

## Conclusions
the convulational neural network provided outstanding results however, for a real life implementtaion more work needs to be done, the test accuracy is still low to be deployed in a real autunomous vehicle       
