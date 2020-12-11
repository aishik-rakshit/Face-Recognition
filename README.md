# Face-Recognition
# 1 Face Recognition using Facenet-Keras and MTCNN

For the webcam implementaion of the code a folder needs to be created in the working directory called "myfaces" with the pictures of the different people to be recognized 
in seperate folders within it.

To benchmark the model i have used the tuft d3100 dataset of 560 images of 112 distinct people and have achieved 100% accuracy on trining set and 98%-100% accuracy on test set.
The model used is Facenet keras to recognise the faces and MTCNN to locate the faces.

Currently the model strugges a little bit with face allignment but that will be improved in following iterations.

For Benchmarking the model we need the uncomment the code extracting the embeddings and preprocessing the image and comment out the code loading the embedding and image array fro the .npz file.

for a more detailed explanation on the basic implementation of the mtcnn and keras-facenet face detection model visit : https://machinelearningmastery.com/how-to-develop-a-face-recognition-system-using-facenet-in-keras-and-an-svm-classifier/?fbclid=IwAR0V_HoUdmi3RBVV708PMhoKtbXCQ4__apTA09m5WXT5Dibn0QevCLPsWSQ

tuft face detection database on canon d3100:http://tdface.ece.tufts.edu/downloads/TD_RGB_E/

facenet_keras model can be downloaded from : https://drive.google.com/drive/folders/1pwQ3H4aJ8a6yyJHZkTwtjcL4wYWQb7bn


 # 2 Face recognition using python face recognition module

Link:https://pypi.org/project/face-recognition/

Extra functions added to simplify training and testing.

FPS counter integrated into code to display fps on top of window.

Must have dlib and opencv installed to run the code
