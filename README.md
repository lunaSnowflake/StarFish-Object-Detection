<h1 style="background-color: #01b0ed; color: white; text-align: center;">Star-Fish Detection ⭐</h1>

<p align="center"><img src="https://i.ibb.co/jzhW8V6/starfish-sample2.png" alt="Seabed with starfish"></p>

## In this computer vision problem, we will be focused on starfish detection in seabed imagery.

### Some of the biggest challenges we have to face, are the following:

- **We encounter a notable challenges known as the "small object problem." This refers to the difficulty of accurately detecting small objects compared to larger ones.**

Fortunately, there are effective techniques available to mitigate this problem, one of which is the "Mosaic data augmentation" approach. This technique involves combining four images and dividing them into four randomly-sized tiles, allowing the model to learn from a more diverse range of object sizes and spatial arrangements. 

In addition to mosaic data augmentation, there are several other methods and techniques that can be employed to address the small object problem. Some examples include adjusting anchor box sizes, implementing focal loss to focus on harder examples, using progressive resizing to train the model on larger image sizes, and incorporating object detection algorithms specifically designed for small objects, such as EfficientDet or YOLO Nano.

- **Another challenge we face is the imbalance in the dataset due to a significant number of frames without starfish. To tackle this issue, we can selectively include only a subset of these empty frames for training, effectively reducing the class imbalance. However, this approach may result in a relatively small amount of training data.**

To overcome the limited data concern, data augmentation techniques can be leveraged. These techniques involve applying various transformations such as rotation, scaling, translation, and flipping to artificially expand the training dataset. This augmentation increases the diversity of the available data and helps the model generalize better to unseen images.

By combining mosaic data augmentation, strategies to address the small object problem, and careful handling of imbalanced data through selective frame inclusion and data augmentation, we can enhance the performance and robustness of our starfish detection model.

The Data Augmentation Techniques can be performed manually, but as we are using YOLOv5, it will be handled by yolov5 itself.
