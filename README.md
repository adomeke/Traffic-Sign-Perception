# Traffic-Sign-Perception
Traffic Sign Recognition and Classification using Tensorflow Python

I utilized Python and MATLAB for the development of this project. MATLAB was used
more for inspecting and organizing the datasets, while Python was my central platform for
development. I created a custom TensorFlow model for more straightforward implementation.
Then, I compared YOLO (You Only Look Once) last version and my custom TensorFlow
model to pick the superior one for a real-life vehicle. Lastly, I installed CUDA and cuDNN
for a faster processing rate, but it is optional. 

Perception is about providing the robot with an adequate vision to operate. The "eyes"
of the vehicle are radar, lidar, ultrasonic sensors, and cameras. Even though all these sensors
provide important data in different situations, cameras are the most prominent source of
information about the outside world. The footage is continuously supplied to the deep
learning systems to analyze the objects in the scene. Video footage captured by the cameras is
raw data. The computer needs to capture the footage as input, contemplate the areas of
interest, draw a small rectangle or line borders outside the objects detected, classify, and track
these boxes. After this stage, sensor fusion occurs, which is information coming from the
sensors and cameras being combined to achieve labeled objects with verified depth and
localization.

Perception is vital to calculate the next steps the vehicle needs to take in order to
achieve the destination. There are four general subgoals of perception: traffic light detection,
traffic sign detection, lane detection, and object detection. In this research, I worked on traffic
sign detection, which helps the vehicle read, understand, and obey all traffic rules imposed by
the government. Since all governments have different traffic rules and designs for traffic
signs, we agreed on a starting point dataset, the German benchmark. As the research proceeds,
we will be adding more countries and eventually reach international functionality. 
