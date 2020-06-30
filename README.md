# YOLOv4 Object Detection on Windows

**Objective**: To accurately detect the obstacles in the field so that our robot can avoid these obstacles.

**Dataset**: 53 images of obstacles in the field

## Approach

Use AlexeyAB darknet implementation of Yolov4, which has support for Windows. 

## Steps

1. [Set up GPU and darknet](https://github.com/agrilive/yolov4-object-detection/blob/master/yolov4_windowsSetup.ipynb)
    - Set up virtual environment
    - Install CUDA and cuDNN
    - Set up vcpkg library manager
    - Set up darknet on Windows
2. [Generate augmented images](https://github.com/agrilive/yolov4-object-detection/blob/master/yolov4_dataAugmentation.ipynb)
    - 4 augmentations per given image were generated
    - Augment bounding box in the image augmentation process
3. [Train and test model](https://github.com/agrilive/yolov4-object-detection/blob/master/yolo4_trainAndTestModel.ipynb)
    - Follow [darknet tutorial](https://github.com/AlexeyAB/darknet#how-to-train-to-detect-your-custom-objects) to train on custom dataset
    - Visualize predictions

The detailed steps can be found in the Jupyter Notebooks.
