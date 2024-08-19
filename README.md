# Face Detection and Recognition

This project demonstrates how to create a dataset, train a model, and detect faces in real-time using a webcam. The process involves capturing images through a live camera feed, storing them in a dataset, training a model, and using it to detect faces with labels.

## Steps to Run the Project

### 1. Download the Haarcascade File

Download the `haarcascade_frontalface_default.xml` file from the following link:  
[haarcascade_frontalface_default.xml](https://github.com/kipr/opencv/blob/master/data/haarcascades/haarcascade_frontalface_default.xml)

### 2. Create the Dataset

Run the following command to capture images through your webcam and store them in the `dataset` folder:

```bash
python3 dataset_creator.py
