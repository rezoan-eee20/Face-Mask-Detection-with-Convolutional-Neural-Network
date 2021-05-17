# Face-Mask-Detection-with-Python-and-Convolutional-Neural-Network

Applied Cascade classifier to get the region of interest (ROI) of the face from the webcam; resized the ROI into 100×100 pixel image and then pass it to my trained Convolutional Neural Network (CNN) model to get the output probability of face with a mask and without a mask; preprocessed the image by OpenCV; used 2 CNN layer model, 1st and 2nd layer consists of 3×3 200 and 100 kernels respectively, applied RELU layer and pooling layer for both of the layers; introduced flatten layer and included dropout layer to avoid overfitting, finally connected with a dense layer of 50 neurons and the output layer(dense layer) has 2 neurons; used a dataset of 1376 images with mask 690 images and without mask 686 images; achieved 96% accuracy.</br>
Tools: Python, OpenCV, Tensorflow, Keras, Numpy, Scikit-learn, Pandas, Matplotlib, Google Colab.</br> 

Please visit my personal website to know more about my research experiences. Personal Website: https://sites.google.com/view/mdrezoanferdous

Full Code with Dataset:https://drive.google.com/drive/folders/1l-zUnDFviMDmvqei1btQ8XtJu_TBuuYL?usp=sharing
