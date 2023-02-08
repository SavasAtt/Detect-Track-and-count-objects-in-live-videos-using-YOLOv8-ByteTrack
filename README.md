# Detect-Track-and-count-objects-in-live-videos-using-YOLOv8-and-ByteTrack
This project includes two COLAB notebooks (Train and Test) for detecting, tracking and counting falling bolts and nuts in live videos. We use YOLOv8 which is most updated and powerful version of YOLO model. It is super fast and accurate and tehrfore its best choice for our project.

the 'Train Notebook' is used for training the YOLOv8 model but the trained model (for 40 epochs) is already provided in this repository (best_model_YOLOv8s.pt) and it colud be used directly in 'Test Notebook' which contains necessary codes and libraries for tracking and counting objects using a pre-trained YOLO model and ByteTracker.

The tracking process is done using ByteTrack method in 'Test Notebook'. The dataset is consists of three subsets (train - test - valid).

the train dataset is 4 min long while test and valid videos are 1 min long for each. The annotations related to each dataset is provided in JSON format.

All Colab notebooks and datasets are provided in this repository and Colab Notebooks.

