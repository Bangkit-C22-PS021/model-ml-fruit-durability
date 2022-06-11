# Fruit Durability Machine Learning Models
In this folder, there are some Machine Learning Models to predict the level of fruit resistance (durability). We use google colab and Tensorflow 2.8.2 version to build these models. For now, the fruit is only limited to 3 types: **Apple, Orange and Banana**. The model is separated by type of fruit in order to avoid prediction errors. In the process of making this ML Model, the model is created using several types of algorithms including:


* Convolutional Neural Network (CNN)
* MobileNetV2 (Pre-Trained Model) 
* InceptionV3 (Pre-Trained Model) 
* VGG16 (Pre-Trained Model) 

# 1. Apple Model
For this model, besides the self-taken pictures, you can get the information of our dataset [here](https://drive.google.com/file/d/1EGFqvaKpCLA--3i42cupKdD0ygItK0MA/view?usp=sharing). We label our data manually based on its color or texture and estimate its durability based on daily home observations or time lapse videos

Here is the ML Model for Apple fruits 
* [Model Apple with InceptionV3](https://github.com/Bangkit-C22-PS021/model-ml-fruit-durability/blob/main/Apple/Model-Apple-Inception-rmsprop.ipynb) **(Best Model)**

# 2. Orange Model
For this model, besides the self-taken pictures, you can get the information of our dataset [here](https://drive.google.com/file/d/1KB0PmD3Ej1V9Jt-M_-F37QsShcPHpqiS/view?usp=sharing) 

Here are some ML Model for Orange fruits 

* [Model Orange with InceptionV3 RMSPROP Optimizer](https://github.com/Bangkit-C22-PS021/model-ml-fruit-durability/blob/main/Orange/Model-Orange-InceptionV3-rmsprop.ipynb) **(Best Model)**
* [Model Orange with VGG16](https://github.com/Bangkit-C22-PS021/model-ml-fruit-durability/blob/main/Orange/Model-Orange-VGG16.ipynb)
* [Model Orange with CNN](https://github.com/Bangkit-C22-PS021/model-ml-fruit-durability/blob/main/Orange/Model-Orange-CNN.ipynb)
* [Model Orange with InceptionV3 Adam Optimizer](https://github.com/Bangkit-C22-PS021/model-ml-fruit-durability/blob/main/Orange/Model-Orange-InceptionV3-Adam.ipynb)

# 3. Banana Model
For this model, besides the self-taken pictures, you can get the information of our dataset [here](https://drive.google.com/file/d/1PEhuekpGf34Yp2GGNvxi3Flqtk2kBNFz/view?usp=sharing) 

Here are some ML Model for Orange fruits 

* [Model Orange with CNN Adam Optimizer](https://github.com/Bangkit-C22-PS021/model-ml-fruit-durability/blob/main/Banana/Model-Banana-CNN-Adam.ipynb) **(Best Model)**
* [Model Orange with InceptionV3](https://github.com/Bangkit-C22-PS021/model-ml-fruit-durability/blob/main/Banana/Model-Banana-InceptionV3.ipynb)
* [Model Orange with CNN RMSPROP Optimizer](https://github.com/Bangkit-C22-PS021/model-ml-fruit-durability/blob/main/Banana/Model-Banana-CNN-rmsprop.ipynb)
* [Model Orange with MobileNet](https://github.com/Bangkit-C22-PS021/model-ml-fruit-durability/blob/main/Banana/Model-Banana-MobileNet.ipynb)


*Note : All of the models above is just for comparison. To deploy Fruitology application, we use the model that has the label **Best Model**
