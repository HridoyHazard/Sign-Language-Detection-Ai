<h3 align="center" >Signify - A Sign Language Detection </h1>

The Idea Of “Signify” A Sign Language Detection Using Image 
Processing. In this project, we present a technique to detect American Sign Language (ASL) from images that performs in real time.

## Objective
* The Objective Of This Project Is To Identify The Symbolic 
Expression Through Images So That The Communication Gap Between 
A Normal And Hearing Impaired Person Can Be Easily Bridged.
* To Develop An Automatic Sign Language Detection System With The 
Help Of Image Processing And Computer Vision Techniques.
* Communication Is Always Having A Great Impact In Every Domain 
And How It Is Considered The Meaning Of The Thoughts And 
Expressions That Attract The Researchers To Bridge This Gap For 
Every Living Being.
* To Provide A Real Time User Interface So That Signers Can Easily 
And Quickly Communicate With Non-Signers.
* To Efficiently And Accurately Recognize Signed Words, From 
ASL, Using A Minimal Number Of Training 

## Device
Webcam is used for the object detection.

## Project Features 
* Detecting Sign Language From Human Pose Estimation.
* Labeling New Images.
* Train Images For Sign Language.
* Real Time Sign Language Recognition Using Image 
Processing.
* Hand Gesture Recognition For Sign Language.
* Finger Detection For Sign Language Recognition.
* OpenCV For Faster Image Processing.
* Use of TensorFlow give flexibility and control with feature.

## How It Works
First of all, we start with collecting the images for deep learning using our webcam and OpenCV. We take a handsome amount of pictures of each class of signs. Then we label the images for sign language detection using LabelImg. To do that, we crop out the irrelevant region to remove the noise, mark only the portion of the image containing the sign relevant to us, and then label the image. This will produce an label map file containing the annotations.We then create the record file to fix how many signs we’re going to train our system with as well as their order. It creates record files for both training and testing.After training the system with the datasets, it is then time to test it.

## Tutorial : [Youtube Link ](https://youtu.be/cpqQ0-TOVMA)
## Screenshorts
<p align="center">
  <br>
    <img src="ss/call.png" height="350px" width="550px"><br>
   <b>Call Sign</b><br>
    <img src="ss/nice.png" height="350px" width="550px"><br>
    <b>Nice Sign</b><br>
    <img src="ss/start.png" height="350px" width="550px"><br>
    <b>Start Sign</b><br>
    <img src="ss/stop.png" height="350px" width="550px"><br>
    <b>Stop Sign</b><br>
    <img src="ss/victory.png" height="350px" width="550px"><br>
    <b>Victory Sign</b><br>
</p>


## Future Work
Future work will be extended for further improvement in recognition accuracy and also for movement detection  of hand for word recognition. We will try to detect alphabets , numbers also.
