# Object_Detection
This code utilizes the OpenCV and cvzone libraries along with the YOLO model from the ultralytics library for object detection. Here's a summary of what the code does:


1.It initializes the video capture from the default camera and sets the frame size.


2.The YOLO model is loaded with the "yolov5s.pt" pre-trained weights.


3.A list of class names is defined, representing various objects that the model can detect.


4.The code enters a loop to continuously read frames from the video capture.


5.Each frame is passed through the YOLO model to obtain object detection results.


6.For each detected object, the bounding box coordinates, class label, and confidence are extracted.


7.The bounding box and text information are drawn on the frame using cvzone functions.


8.The code uses pyttsx3 to convert the object name and confidence into speech.


9.The frame rate of the video stream is calculated and displayed.


10.The processed frame is shown in a window, and the loop continues until the user interrupts it.

The code enables real-time object detection from the webcam feed, displays bounding boxes and labels on the detected objects, and uses text-to-speech to announce the objects and their confidence levels.
