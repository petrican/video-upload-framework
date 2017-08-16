Video Upload Framework - Demo 

 Provides a Video Upload Page

 - Enables Video Upload to pick a video from local comp for any MOV, MP4,WEBM, AVI file with max size of 500MB

 - Upload function converts the file into multiple small parts and initiates video upload.
iv.
 - backend logic to checksum and connect the video file together

 - Shaped on top of react-resumable-js

 - After Post upload, same file can be played on the page with Video.JS

 Preq: I assume you are using a Linux or Mac box. You need to have the ports 8888 and 3000 free. (To check run from terminal : `netstat -anp | less` look for those ports and then quit). If those ports are not in use we can proceeed on the intallation.

 Installation: 

 Step1: Open a terminal. Clone the repo

 $ git clone https://github.com/petrican/video-upload-framework

 Step2: Change directory to `video-upload-framework`

 $ cd video-upload-framework

 Step3: Install dependencies
 
 $ npm install

 Step4: Run demo
 
 $ npm run demo

 At this step theoretically you should be able to have the browser opened with http://localhost:8888/webpack-dev-server/ where you can see the app.

 If that does not happen open http://localhost:8888/webpack-dev-server/

 Enjoy!


 Note to stop the app: $ cd example; npm run stop.

 


 


