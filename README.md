# Driver-Drowsiness-Detection
Dlib and OpenCV were used to create this project that detects driver drowsiness with Python as the backend language.
<h3>Logic of project</h3>
The project features direct interaction with the 68 facial landmark detector as well as the Dlib library's face detector. The 68 facial landmark detector is a well-trained, high-performance detector that detects the spots on the human face that are used to assess whether the eyes are open or closed.</br></br>

<b>The 68-landmark detector data (.dat) file can be found <a href="http://dlib.net/files/shape_predictor_68_face_landmarks.dat.bz2"> By clicking here</a></B>

<h3>The working of the project</h3>
<ul><li>As you can see the<b> above screenshot</b> where the landmarks aredetected using the detector.
<li>Now we are taking the ratio which is described as <i>'Sum of distances of vertical landmarks divided by twice the distance between horizontal landmarks'</i>.
<li>Now this ratio is totally dependent on your system which you may configure accordingly for the thresholds of sleeping, drowsy, active.</ul>



