# Face-Recognition
Face Recognition using Facenet-Keras and MTCNN

For the webcam implementaion of the code a folder needs to be created in the working directory callmed "myfaces" with the pictures of the different people to be recognized 
in seperate folders within it.
To benchmark the model i have used the tuft d3100 dataset of 560 images of 112 distinct people and have achieved 100% accuracy on trining set and 98%-100% accuracy on test set.
The model used is Facenet keras to recognise the faces and MTCNN to locate the faces.
Current the model strugges a little bit with face allignment but that will be improved in following iterations
