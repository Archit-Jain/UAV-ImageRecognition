# UAVImageRecognization

Program is designed and developed to take the images from the on board camera and processing unit.
The on board camera pi camera is attached to the raspbeery pi to read, capture and process and send the data to ground station from the UAV.

To use
Clone the repo into raspberry pi and connect a camera

inside raspberry do
sudo apt-get install fswebcam

1. npm install
2. npm install q

To Start app

node index.js 

The app should run in port 3000 of raspberry

To to take a pic 
Hit the URL 
http://rapiIP:3000/camera

This will return the image from camera 


