# Face-Recognition-using-Eigen-Spaces

## Project Name: Face Detection using Eigenfaces

## Project Description:
The Face Detection using Eigenfaces project is an application that employs Eigenfaces, a popular face recognition technique, to detect and recognize faces in images or real-time video streams. The project utilizes the concept of eigenvectors and eigenvalues to represent faces as low-dimensional feature vectors, allowing for efficient and accurate face detection and recognition.

## Key Features:

## Face Detection:

Image Input: The application accepts input images or video streams containing faces.
Face Localization: The project utilizes advanced computer vision algorithms to detect and localize faces within the input images or video frames.
Face Region Extraction: Detected faces are extracted as separate regions of interest (ROIs) for further processing.
Eigenface Representation:

Feature Extraction: Eigenfaces are computed by performing Principal Component Analysis (PCA) on a training set of face images. The principal components (eigenvectors) and corresponding eigenvalues are derived to represent the face images.
Face Representation: Each face image is represented as a low-dimensional feature vector using the eigenfaces, capturing the essential facial characteristics.
Face Recognition:

Similarity Calculation: The project compares the extracted face regions with the eigenface representations to calculate the similarity between the input faces and the trained face database.
Recognition Threshold: A recognition threshold is set to determine whether a detected face matches any known faces in the database or is classified as unknown.
Identity Classification: If a match is found, the system identifies the person by associating the detected face with the corresponding identity from the database.
Real-time Face Detection and Recognition:

Continuous Tracking: Once a face is detected and recognized, the system can track the identified person across subsequent frames, providing real-time updates and tracking information.

## Technologies and Techniques Used:

OpenCV: The project leverages the OpenCV library, which provides a comprehensive set of computer vision algorithms and tools for face detection and image processing.
Eigenfaces: The application utilizes the concept of eigenvectors and eigenvalues to create a low-dimensional representation of face images.
Principal Component Analysis (PCA): PCA is applied to extract the eigenfaces and reduce the dimensionality of face images.
Image Processing: The project employs various image processing techniques, such as face localization, feature extraction, and similarity calculations, to achieve accurate face detection and recognition.
The Face Detection using Eigenfaces project showcases the application of advanced computer vision techniques to detect and recognize faces using eigenface representations. By employing Eigenfaces and PCA, the project enables efficient face detection, accurate recognition, and real-time tracking in both static images and video streams. This project aims to contribute to the field of computer vision and facial recognition by providing a robust and effective tool for face detection and recognition tasks.






