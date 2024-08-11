This project is a real-time face verification application using the DeepFace library and OpenCV. The application captures video from your webcam, checks if the current frame matches a reference image, and displays the result on the video feed. The verification process runs in a separate thread to ensure the application remains responsive.

Features
Real-time face capture: Captures video from the webcam in real-time.
Face verification: Compares the current frame from the webcam with a reference image to verify if they match.
Threading for efficiency: The face verification runs in a separate thread to avoid freezing the video feed.
Visual feedback: Displays "MATCH!" if the faces match, and "NO MATCH!" if they don't.
