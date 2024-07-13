# Big Five Personality Classification using YOLOv8

This project was made to fulfill undergraduate thesis program with the title **PERSONALITY CLASSIFICATION BASED ON THE BIG FIVE PERSONALITY THROUGH HANDWRITTEN IMAGES USING YOU ONLY LOOK ONCE VERSION 8**

## Background
Graphology is the study of handwriting analysis to identify, evaluate and understand a person's personality well and is very useful for many organizational processes, for example in the recruitment selection process in companies. There is a well-known model and widely used in various fields including industry called Big Five Personality, which groups human personality into five characteristics, namely Openness, Conscientiousness, Extraversion, Agreeableness, and Neuroticism. The analysis process is generally carried out manually by experts and the results also depend on the experience of the expert. This will also take a relatively long time so it is considered less efficient as the number of samples that need to be examined increases. Therefore, to increase efficiency and avoid subjectivity in personality examination results, a system can be developed that is able to classify personality types quickly and accurately. This research implements the You Only Look Once version 8 to develop a personality classification system based on the big five personalities.

## General Architecture
![image](https://github.com/user-attachments/assets/ff6bd32d-721b-407a-9fa4-8a4aa8bef5c1)

## Training Result
![image](https://github.com/user-attachments/assets/eb069428-849d-4cf2-91a4-ef83c1c20f4e)

Box loss measures how accurately the model predicts the location of the bounding box on an object. Box loss calculates the difference between predicted and actual bounding box coordinates. The smaller the box loss value, the more accurately the model predicts the location of the bounding box. Training ends with a box_loss value of 0.33062. 

Classification loss or cls loss measures how well the model predicts the class of each object. Classification loss calculates the difference between the predicted possible class and the actual class. The smaller the classification loss value, the more accurately the model recognizes the class for each detected object. Training ended with a cls_loss value of 0.45829. 

Distribution focal loss or dfl loss functions to improve bounding box predictions. Dfl loss focuses on objects that are similar or difficult to distinguish. The smaller the dfl loss value, the better the model is at detecting similar objects. Training ended with a dfl_loss value of 0.80276.

## Testing Result
The classification model that has been created is then implemented into an Android-based mobile application and can carry out real-time classification with an inference time of 300-1000 ms depending on the specifications of the device used. The test results obtained 88% precision, 88,8% recall, 87,6%  f1-score, and overall accuracy of 88%. With the evaluation metric values obtained, the classification system result is categorized as good classification.

## Data Availability
Data is not shared publicly. Please contact the author for data requests.
