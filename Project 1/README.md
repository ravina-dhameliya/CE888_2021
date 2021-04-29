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

Building the Model

![image](https://user-images.githubusercontent.com/77781909/116537690-72f81880-a8de-11eb-8012-eb29cf337e60.png)


Evaluating the Model
Loss and Accuracy

![image](https://user-images.githubusercontent.com/77781909/116537717-7b505380-a8de-11eb-90a3-7082514132ea.png)

Train and Validation Accuracy

![image](https://user-images.githubusercontent.com/77781909/116537734-82776180-a8de-11eb-9d44-0c3c093dc677.png)


Confusion Matrix

![image](https://user-images.githubusercontent.com/77781909/116537757-899e6f80-a8de-11eb-950b-76fc580fb4e6.png)

