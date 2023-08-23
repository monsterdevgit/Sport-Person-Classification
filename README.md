# Sport-Person-Facial-Recognition-using-ML-Classification-Model
The Sport Person Facial Classifier System is a user-friendly application that utilizes Machine Learning to classify sports personalities based on their facial features. This system allows users to upload a photo of a sports person's face and accurately predict their identity from a selection of five well-known sports personalities: Maria Sharapova, Lionel Messi, Cristiano Ronaldo, Rafael Nadal, and Serena Williams.

## Project Description
This project employs [opencv haarcasades](https://docs.opencv.org/3.4/d2/d99/tutorial_js_face_detection.html) for face detection and [wavelet transform](https://docs.opencv.org/3.4/d2/d99/tutorial_js_face_detection.html) to extract distinctive facial features. The ML algorithm uses this data to accurately predict the identity of these sports personalities.

The model has been trained on a dataset containing the unique facial characteristics of these five sports personalities. By learning their distinctive facial features, the classifier system can make precise predictions about their identities.

## How It Works
Upload: Users can upload a photo of a sports person's face through the application's user-friendly interface.
![UISCREENSHOT](https://github.com/monsterdevgit/Sport-Person-Facial-Recognition/blob/master/UI/UI%20screenshot.png)

Facial Recognition: The system utilizes facial recognition algorithms to analyze the uploaded image and extract facial features.

Identity Prediction: Based on the extracted facial features, the classifier system compares them to the unique characteristics of Maria Sharapova, Lionel Messi, Cristiano Ronaldo, Rafael Nadal, and Serena Williams. It then predicts the most likely identity of the person in the photo.

Display Results: The system displays the predicted identity along with the probability score.

## Deployment using Front End and Python Flask
The Sport Person Facial Classifier System is deployed using a combination of front-end technologies(HTML, CSS, JS) and the Python Flask framework. Flask provides a powerful backend infrastructure, while the user-friendly front-end components facilitate seamless interaction.

![PROJECTARCHITECTURE](https://github.com/monsterdevgit/Sport-Person-Facial-Recognition/blob/master/Project%20Architecture.png)

To use the application, users can easily upload a photo of a sports person's face and receive instant predictions about their identity.

## Real-World Applications
The Sport Person Facial Classifier System has practical applications in various scenarios, including:

**Agriculture**: ML algorithms can aid in weather prediction, disease detection, and weed identification. By analyzing real-time data from sensors and satellite imagery, farmers can proactively address potential issues and take preventive measures. ML also facilitates livestock monitoring, ensuring optimal conditions for animal welfare.

**Medicine**: By training these algorithms on large datasets of known cases, the system can learn to recognize specific patterns associated with certain diseases. When presented with a new patient's image, the ML model compares their features to the learned patterns and provides a probability score indicating the likelihood of the presence of a disease. This aids physicians in making more accurate diagnoses and enables timely interventions and potentially saving lives.

**Crime fighting**: By utilizing a vehicle-mounted facial recognition system, the police can scan and analyze the faces of individuals in real-time, comparing them to a database of stored facial images. This technology enables law enforcement to identify and locate individuals on their watchlist, aiding in the apprehension of suspects involved in criminal activities.

