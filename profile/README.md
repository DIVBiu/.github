**README**

## Introduction

This README file provides an overview and instructions for the House Committee Management Application. The application is designed to facilitate the management and communication within a shared residential building. It allows tenants to report faults, participate in group chat, answer surveys, register vehicles, and check parking availability. The server-side of the application is written in Python using the Flask framework and the MongoEngine library, while the client-side is developed for Android using Java with Android Studio.

## Necessary Installations

To run the House Committee Management Application, you need to ensure that the following dependencies and installations are in place:

1. Python: Make sure you have Python installed on your system. You can download Python from the official website: [python.org](https://www.python.org/).

2. Flask: Install the Flask web framework by running the following command:

   ```bash
   $ pip install flask
   ```

3. MongoEngine: Install the MongoEngine library for connecting to the MongoDB database:

   ```bash
   $ pip install flask-mongoengine
   ```

4. OpenCV: Install OpenCV library for image processing:

   ```bash
   $ pip install opencv-python
   ```

5. Requests: Install the Requests library for making HTTP requests:

   ```bash
   $ pip install requests
   ```

6. PIL: Install the Python Imaging Library (PIL) for image manipulation:

   ```bash
   $ pip install pillow
   ```

7. EasyOCR: Install the EasyOCR library for optical character recognition (OCR):

   ```bash
   $ pip install easyocr
   ```

8. Android Studio: Install Android Studio to run the client-side application. You can download Android Studio from the official website: [developer.android.com/studio](https://developer.android.com/studio).

## Application Purpose

The House Committee Management Application aims to enhance the living experience in shared residential buildings. It provides various features to simplify communication, fault reporting, vehicle registration, and parking management. The key features of the application include:

1. Fault Reporting: Tenants can submit calls to address faults or issues within the building.

2. Group Chat: Tenants can engage in a group chat with other tenants in the building to discuss common topics and share information.

3. Surveys: Tenants can participate in surveys conducted through the application.

4. Vehicle Registration: Tenants can register their vehicles to be included in the list of authorized vehicles for entering the building's parking lot.

5. Parking Status: Tenants can check the availability of parking spots in the building, identifying which spots are vacant and which are occupied.

## Image Processing and Machine Learning Models

The House Committee Management Application incorporates two models to support its functionality:

1. Vehicle Number Recognition: The application utilizes an image processing and machine learning model capable of recognizing vehicle numbers from a photo. This model enables automatic extraction of vehicle numbers for registration purposes.

2. Parking Lot Availability Recognition: The application employs a second model that can determine the availability of parking spots by analyzing images of the parking lot. This model identifies free and occupied parking spots, providing real-time information to the tenants.

Please note that these models require additional installations and dependencies specific to the image processing and machine learning algorithms. For further details and instructions on setting up these models, please refer to the relevant documentation.

## Conclusion

The House Committee Management Application aims to improve the quality of living in shared residential buildings by streamlining communication, fault reporting, vehicle registration, and parking management. By following the installation instructions provided in this README, you can set up the necessary dependencies and run the application on your local environment. Should you encounter any issues or have any questions, please refer to the documentation or reach out to the project maintainers for assistance.
