# Assignment 3 video server

## Running the Application

To run the application:
you can run application with gradle

./gradlew build
./gradlew run

## Overview
important:

1.video client need to know video server ip before your upload videos to server
2.to get the ip use command ifconfig (mac) or ipconfig (windows)
3.update videoClient java file com/coursera/videoclient/retrofit/VideoSvcApi.java:101

for instance, if you ip is 192.168.0.1

  //update me to your video server ip
 line 101:  final String sVideo_Service_URL_Retro = "http://192.168.0.1:8080";






