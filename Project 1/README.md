I have used the test and training dataset you can download from this drive URL
https://drive.google.com/file/d/1v2-KEYSOuN313JqQcQh0JGZz_llnJLu-/view

Reading data

train_images='/content/drive/MyDrive/Colab Notebooks/Firedetection/Train/Train'
test_images='/content/drive/MyDrive/Colab Notebooks/Firedetection/Test/Test'

Defining the images in the folder and image size

IMAGE_SIZE = (32,32)
trainLables, trainImages=[], []
testLables, testImages=[], []
type_fire =["Fire","No_Fire"]

Train and Test Images

![image](https://user-images.githubusercontent.com/77781909/116537580-53f98680-a8de-11eb-8f43-747dd65b2889.png)
