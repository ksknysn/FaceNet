# FaceNet
I tried to implement a face authentication code using facenet_keras, open-cv and mtcnn

You can scan camera, photo or video. You should change the FaceRecognition class in the main.py to choose.

The default face detection algorithm is mtcnn, so if you would like to use open-cv you should change:
config.detectionAlgorithm to 'open-cv'
