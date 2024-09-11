Driver Drowsiness Detection System.​ ​
April 08, 2022
Purpose​ of making this project.
​ 

Road accidents have become a matter of concern due to the huge increase in traffic. The main or the primary cause of accidents is due to the drowsiness of drivers during the night time. Fatigue and drowsiness are some of the leading causes of major accidents on Highways.

The only solution to this problem is detecting the drowsiness and alerting the driver.

Tools and technology used.
Open-Cv.
Python language.
Libraries used.
CV2:- For image processing functions.
Dlib:- For deep learning and also for more accuracy of landmarks. 
Numpy:- For array related functions.

Logic of project
The project includes direct working with the 68 facial landmark detector and also the face detector of the Dlib library. The 68 facial landmark detector is a robustly trained efficient detector which detects the points on the human face using which we determine whether the eyes are open or they are closed.




The 68-landmark detector data (.dat) file can be found http://dlib.net/files/shape_predictor_68_face_landmarks.dat.bz2 

The working of the project
As you can see the above screenshot where the landmarks are detected using the
detector.
Now we are taking the ratio which is described as 'Sum of distances of vertical landmarks divided by twice the distance between horizontal landmarks'.
Now this ratio is totally dependent on your system which you may configure accordingly for the thresholds of sleeping, drowsy, active.
