<div align="center"><h1>Star-Fish Detection ⭐</h1></div>

<!-- <p align="center"><img src="https://i.ibb.co/jzhW8V6/starfish-sample2.png" alt="Seabed with starfish"></p> -->
<p align="center"><img src="https://i.ibb.co/QfM9nMs/Clouds-Convert-maxresdefault-1685913043.jpg" alt="hq720" width=1280></p>

## In this computer vision problem, we will be focused on starfish detection in seabed imagery.

### Some of the biggest challenges we have to face, are the following:

- **We encounter notable challenges known as the "small object problem." This refers to the difficulty of accurately detecting small objects compared to larger ones.**

Fortunately, there are effective techniques available to mitigate this problem, one of which is the "Mosaic data augmentation" approach. This technique involves combining four images and dividing them into four randomly-sized tiles, allowing the model to learn from a more diverse range of object sizes and spatial arrangements. 

In addition to mosaic data augmentation, there are several other methods and techniques that can be employed to address the small object problem. Some examples include adjusting anchor box sizes, implementing focal loss to focus on harder examples, using progressive resizing to train the model on larger image sizes, and incorporating object detection algorithms specifically designed for small objects, such as EfficientDet or YOLO Nano.

- **Another challenge we face is the imbalance in the dataset due to a significant number of frames without starfish. To tackle this issue, we can selectively include only a subset of these empty frames for training, effectively reducing the class imbalance. However, this approach may result in a relatively small amount of training data.**

To overcome the limited data concern, data augmentation techniques can be leveraged. These techniques involve applying various transformations such as rotation, scaling, translation, and flipping to artificially expand the training dataset. This augmentation increases the diversity of the available data and helps the model generalize better to unseen images.

By combining mosaic data augmentation, strategies to address the small object problem, and careful handling of imbalanced data through selective frame inclusion and data augmentation, we can enhance the performance and robustness of our starfish detection model.

The Data Augmentation Techniques can be performed manually, but as we are using YOLOv5, it will be handled by yolov5 itself.

## 🌟 Acknowledgements:
The Data can be found here [Tensorflow Great Barrier Reef](https://www.kaggle.com/competitions/tensorflow-great-barrier-reef) <br/>

Check out the Notebooks:
<div align="left">
  <a href="https://colab.research.google.com/github/lunaSnowflake/StarFish-Object-Detection/blob/main.ipynb">
    <img src="https://github.com/ultralytics/yolov5/releases/download/v1.0/logo-colab-small.png" width="10%" /></a>
    <img src="https://github.com/ultralytics/assets/raw/main/social/logo-transparent.png" width="5%" alt="" />
  <a href="https://www.kaggle.com/code/lunaticsain/star-fish-object-detection">
    <img src="https://github.com/ultralytics/yolov5/releases/download/v1.0/logo-kaggle-small.png" width="10%" /></a>
    <img src="https://github.com/ultralytics/assets/raw/main/social/logo-transparent.png" width="5%" alt="" />
</div>

I am open to any suggestions, connect with me anywhere! <br/>
Also, I would appreciate it if I can get a 🌟 for this repository from your side. ☺

## 💻 Tech Stack:
<img src="https://i.ibb.co/vByQbTM/OIP.jpg" alt="Yolov5" width="auto" height="100"> </br>

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) 
![PyTorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge&logo=PyTorch&logoColor=white)
![OpenCV](https://img.shields.io/badge/opencv-%23white.svg?style=for-the-badge&logo=opencv&logoColor=white) 
![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-%230C55A5.svg?style=for-the-badge&logo=scipy&logoColor=%white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)

## 💫 About Me:
![Dev Gif](https://media.giphy.com/media/f3iwJFOVOwuy7K6FFw/giphy.gif) <br/>

I am a Data Scientist/Analyst and a Developer <br/>
Check out my [GitHub](https://github.com/lunaSnowflake) profile for more details! See you on the other side :)

## 🌐 Socials:
[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/hussainkhatumdi/) 
[![Kaggle](https://img.shields.io/badge/Kaggle-035a7d?logo=kaggle&logoColor=white)](https://www.kaggle.com/lunaticsain)
[![Medium](https://img.shields.io/badge/Medium-12100E?logo=medium&logoColor=white)](https://medium.com/@hussainkhatumadi53) 
[![Twitter](https://img.shields.io/badge/Twitter-%231DA1F2.svg?logo=Twitter&logoColor=white)](https://twitter.com/lunatic_sain) 
