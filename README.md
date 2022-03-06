# Social-distancing-detector

   The detection tool was developed to alert people to maintain a safe distance with each other by evaluating a video feed. The video frame from the camera was used as input, and the open-source object detection pre-trained model based on the YOLOv3 algorithm was employed for pedestrian detection.

This tool has following features:

Detect humans in the frame with yolov3.

Calculates the distance between every human who is detected in the frame.

Shows how many people are at High, Low and Not at risk.

Bounding Box color

Red - High risk

Yellow - Low risk

Green - Safe

**Requirements**

For human detection:
yolov3.weights file is not present in model folder because of the size issue.

Save the input video file in data folder as "example.mp4"

**Output**

![frame](https://user-images.githubusercontent.com/53997811/118671552-33558a00-b815-11eb-960b-d19ee7e7d6ff.JPG)
