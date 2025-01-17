# CNN-Model-for-Face-Emotion-Classification
I trained a CNN model to predict emotions on faces in an image. The model is able to detect the expression of the face, and the persons emotion through facial expression recognition.

I trained the model using the FER2013 dataset which i downloaded from kaggle
https://www.kaggle.com/datasets/msambare/fer2013
The dataset comprises of gray scale images of size (48, 48). The images are of 7 classes including: Angry, Disgust, Fear, Happy, Neutral, Sad, and Surprise.

The CNN model summary is shown below:
![Model Summary](https://github.com/user-attachments/assets/03483f53-ef89-4c20-83b2-247fde943c2f)

I trained the model for 40 epochs and the model accuracy and loss during training was plotted and shown below:
![Model Accuracy](https://github.com/user-attachments/assets/a64eb58d-9492-4799-9db8-a590c1d14d23)

![Model Loss](https://github.com/user-attachments/assets/66ee02c8-f0b1-478a-a2f8-633403e5a164)

After training the model, i evaluated for accuracy and perfomance.
The confussion matrix is shown below:
![Confusion Matrix](https://github.com/user-attachments/assets/dd229625-790c-4cd8-ab4e-c1207f1543ff)



