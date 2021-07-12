# Automated-Robotic-Arm-for-Face-Mask-Detection

CURRENT MODEL READS DATA FROM CAMERA MODULE AND DETECTS MASK TO MOVE THE SERVO MOTOR ACCORDINGLY

1.) The Entire Robot Model is right now configured to work on a "Raspeberry Pi 3" , it only requires a power supply to start

2.) Once the robot starts, the camera module detects a face and classifies it as "Masked" or "Not Masked" based on a DL based pre trained Python model

4.)If a Mask is detected , the servo is made to rotate at +90 Degrees thus simulating a barrier open motion

5.) If a Mask is not detected , the servo goes back to 0 Degrees thus simulating a barrier closed motion


