# face_recognition_app
Face Recognition App

Current Flask App Functionality
Manual Face Recognition: Users capture a snapshot from their webcam via the browser.
The image is sent to the Flask backend, where face_recognition detects faces and matches them with known faces.
Rectangles and labels are drawn around detected faces, and the processed image is sent back to the browser for display.
Limitations:
Recognition only occurs after manually capturing an image.
No real-time face tracking or live label updates.
Potential with Real-Time Face Recognition (face-api.js)
Real-Time Processing: Using face-api.js in the browser, the app can continuously detect and recognize faces while the camera is active, eliminating the need to manually capture images.
Live Labels and Rectangles: Faces will be labeled in real-time as they appear in the video stream.
Client-Side Processing: The face recognition can happen entirely on the client-side, improving performance and reducing server load.
This enhancement would turn the app into a real-time face recognition tool, ideal for live scenarios, without needing manual image captures.
