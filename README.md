## How to run
1) Download the files and open them in a single folder in any code editor
2) Keep the value to be 0 in cv2.videocapture in camera.py file if real time emotion on human face using webcam is to be captured else keep the path of a videofile 
3) Run the app.py file using python -m flask run command in the terminal of that file

## Project Overview
1) Developed a Convolutional Neural Network model to classify the real time emotion on human face into 7 categories.
2) Used Haarcascade classifier from OpenCV library to detect faces and resized them into 48 x 48 numpy arrays
3) Applied 4 convolutional blocks, 2 fully connected dense layers and a dense layer with softmax activation function
4) Achieved an accuracy of 0.82 on validation set using Adam as the optimizer, categorical crossentropy as the loss function
5) Designed the basic template of app layout using HTML and deployed the model to web interface  using Flask framework
