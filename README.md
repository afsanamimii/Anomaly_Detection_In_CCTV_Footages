# Anomaly_Detection_In_CCTV_Footages

#Sample Output 

https://user-images.githubusercontent.com/61627644/162009765-4d553007-b7be-4aaa-be6c-eca0219d2e36.mp4

# Dataset:
Total 2030 files were extracted from a video using openCV. The first part of the file contains normal events and the last part contains  an amolaous event. For the training purposes only the normal events were considered.

#Process:
I used Autoencoder Based system for training the data. I extracted features using a sequential model containing 7 layers of convolutional and maxpooling layer. I used mean square error (MSE) as a loss function.
