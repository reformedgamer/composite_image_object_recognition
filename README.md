# composite_image_object_recognition
 This project is intended to identify the presence of specific objects in images associated with 40 individuals and determine which object identifies 8 of them as members of the same group.

It relies on the use of the object detection package YOLOv7, which can be cloned from the following link: 

https://github.com/WongKinYiu/yolov7

Copy the train, valid, test, and unlabeled images folders from this project's repository, as well as the main.ipynb and .pt files, and paste them all in the cloned yolov7 repository folder. Copy the custom.yaml file and paste it in the data folder within the yolov7 directory. Copy the yolov7.yaml file and paste it in the cfg/training/ folder in the yolov7 directory. Make sure to install the packages from the requirements.txt file in the yolov7 folder. Install the packages associated with PyTorch v1.11.0 as appropriate for your specific computer setup according to the information at the following link:

https://pytorch.org/get-started/previous-versions/

Once you have completed these steps, execute the code in the main.ipynb file copied to the yolov7 folder to produce the model results analyzed in this project.