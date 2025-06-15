# AI/ML Soccer Analysis System with YOLO, OpenCV, and Python

** output video link: https://drive.google.com/file/d/1zCO7vpr-WTD8tCp1ZQcAhmncmKipMTxk/view?usp=share_link **

This soccer analysis system offers 5 unique features:
1) player, referee, and ball detection (with team differentiation)
2) real-time speed of individual players in the center trapizoidal area
3) real-time distance covered of individual players in the center trapizoidal area
4) camera movement in the x and y directions
5) team control percentages display

Tools and techniques used:
1) Utralytics and YOLOv8 to detect objects images and videos. I also trained the YOLO model custom to my own dataset.
2) KMeans to cluster pixels and segment players' team jerseys from background. This allowed me to visually compartmentalize players into their teams.
3) Optical flow to measure camera movements on the y and x axis
4) OpenCV's perspective transformation to aquire information on the visual depth and perspective of the footage. This allowed me to measure the speed and distance covered by the players.

Courtesy to Code In a Jiffy on YouTube for the learning material and resources on this topic. 

