# Face Recognition

This project is a face recognition program that uses the OpenCV and face_recognition libraries to detect and identify faces in real-time video. The program is able to recognize 5 people by default (Fikri, Boufal, Bounou, Regragui, Mouhib) and their images are stored in the corresponding folders.

To run the program, you need to have OpenCV and face_recognition libraries installed on your machine. You can install them using pip by running the following command:

- pip install opencv-python
- pip install face_recognition

Then, you can run the program by executing the python script.

The program captures video from the default webcam, so make sure that you have a webcam connected to your machine.

You can add new people to the program by adding their images to the corresponding folder and updating the known_face_encodings and known_face_names variables in the code accordingly.

The program also includes a feature that only detects faces in every other frame of video to save processing time. You can adjust the processing frame rate as per your requirement.

This program is just a basic example of face recognition and can be further improved and customized as per the requirement.
