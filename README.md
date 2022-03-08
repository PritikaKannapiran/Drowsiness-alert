# Driver-Drowsiness-Alert-System
The Drowsiness-alert system is a computer vision system that makes use of 68 landmark detectors as well as the Dlib library's face detector.

This is an ingenious innovation to curtail road accidents. Our Drowsiness-alert system warns the user to drive more carefully, hence preventing imminent accidents on the road. 

Potential features include:-
-Use of API servers to notify respective government authorities or traffic police when driver fails to turn off the drowsy/sleepy warning in under 1 minute.
-Mobile app integration 
-Future prospects may include contacting vehicle brand owners to implement our Drowsiness-alert system software onto in-built devices in order to enhance road safety measures.

Dlib and OpenCV were used to create this project that detects driver drowsiness with Python as the backend language.
<h3>Logic of project</h3>
The project features direct interaction with the 68 facial landmark detector as well as the Dlib library's face detector. The 68 facial landmark detector is a well-trained, high-performance detector that detects the spots on the human face that are used to assess whether the eyes are open or closed.</br></br>

<b>The 68-landmark detector data (.dat) file can be found <a href="http://dlib.net/files/shape_predictor_68_face_landmarks.dat.bz2"> By clicking here</a></B>

<h3>The working of the project</h3>
<li>We are taking the ratio which is described as <i>'Sum of distances of vertical landmarks divided by twice the distance between horizontal landmarks'</i>.
<li>This ratio is now entirely based on your system, which you can configure for sleeping, drowsy, and active thresholds.</ul>



