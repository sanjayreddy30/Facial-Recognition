## Convolution Neural Network:
In In deep learning, a convolutional neural network (CNN, or ConvNet) is a class of artificial neural  network (ANN), most commonly applied to analyze visual imagery.CNNs are also known as Shift Invariant or Space Invariant Artificial Neural Networks (SIANN), based on the shared-weight architecture of the convolution kernels or filters that slide along input features and provide translation equivariant responses known as feature maps. Counter-intuitively, most convolutional neural networks are not invariant to translation, due to the downsampling operation they apply to the input.They have applications in image and video recognition, recommender systems, image classification, image segmentation, medical image analysis, natural language processing, brain–computer interfaces and financial time series.

CNNs are regularized versions of multilayer perceptrons. Multilayer perceptrons usually mean fully connected networks, that is, each neuron in one layer is connected to all neurons in the next layer. The "full connectivity" of these networks make them prone to overfitting data. Typical ways of regularization, or preventing overfitting, include: penalizing parameters during training (such as weight decay) or trimming connectivity (skipped connections, dropout, etc.) CNNs take a different approach towards regularization: they take advantage of the hierarchical pattern in data and assemble patterns of increasing complexity using smaller and simpler patterns embossed in their filters. Therefore, on a scale of connectivity and complexity, CNNs are on the lower extreme.

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
