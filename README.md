# Final Project
# ECE MAE 148 Spring 2023
![UCSD Logo](UCSDLogo.jpeg)
## Team 1 Members

Brandon Breeze - ECE
  
Liam Carmody - MAE
  
Dominic Orlando - ECE

## What we have promised

#### Must have

Our idea is to have the robot car return to a pre-designated “Home Base” (GPS location) when it detects that is has disconnected from it’s controller. Additionally, if time allows we also would like to add obstacle avoidance so that the car can make it home safely. 


#### Nice to have

I would be also nice to be able to detect is the program crashes or if a computer that is ssh’d into it loses connection 

## Video Demonstration

### Controller Disconnect Detection 

The way that we are detecting if the controller is disconnected is by using a threshold number. After a certain number of callbacks without controller inputs changing, it assumes that the controller is disconnected.

[![IMAGE ALT TEXT](http://img.youtube.com/vi/uU5O4HXrWTc/0.jpg)](http://www.youtube.com/watch?v=uU5O4HXrWTc "Video Title")

