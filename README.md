# Vision-Based-Attendance-System

A vision-based attendance system using the Haar Cascade frontal face model is a computer vision application designed to automate the process of recording attendance. This system leverages the Haar Cascade classifier, a popular method for detecting faces in images or video frames, particularly frontal faces.

Here's how it typically works:

## Face Detection: 
The system uses the Haar Cascade frontal face model to detect faces within a camera's field of view. The model scans the input images or video stream to identify regions that likely contain a face based on patterns learned during training.
![alt text]()

## Face Recognition
After detecting a face, the system can further process the face images to recognize individuals using additional algorithms like Local Binary Patterns (LBP), Histogram of Oriented Gradients (HOG), or deep learning-based methods such as convolutional neural networks (CNNs).

![alt text](https://github.com/SiddharthKrSingh/Vision-Based-Attendance-System/blob/main/iMAGES/Screenshot%202024-08-26%20190013.png)

## Attendance Logging
Once a face is detected and possibly recognized, the system logs the attendance by recording the time and date. This data is then stored in a database for future reference.
![alt text](https://github.com/SiddharthKrSingh/Vision-Based-Attendance-System/blob/main/iMAGES/Screenshot%202024-08-26%20185524.png)

## Real-Time Operation
The system operates in real-time, continuously monitoring and updating attendance records as people enter the camera's view.

This system is particularly useful in environments like schools, workplaces, and events, where automated, non-intrusive attendance recording can save time and reduce errors compared to traditional manual methods.


## Steps To Run:-
1. open comand promp
2. create virtual environment
3. download all the requirements
4. run Python Add_face.py ( This Command will Add the faces in dataset).
5. run Python test.py command ( Once the image is recoginsed press =o to record it)
6. run streamlit app.py ( It help us to view the data in csv format)





