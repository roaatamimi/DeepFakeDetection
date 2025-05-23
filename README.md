
# DeepFake Detection

Deepfakes pose a serious threat on security and can potentially harm individuals. With the advancement of Deepfake technologies, the creation of fake images and spread of misinformation is made quite easier which makes the development of advanced deepfake detection models necessary to ensure safeguarding and protection against malicious uses of deepfakes.
There have been multiple attempts on creating DF-detection models like the Facebook DFGC challenge. The solutions to the challenge included implementing transfer learning and using facial-recognition models to solve the problem.
We will create a deepfake detection model using CNNs and Capsule Networks which are designed to detect anomalies. First, we will use a pretrained CNN model as an encoder to extract features from the images dataset that will be passed to the capsule network. The Capsule Network itself will consist of multiple layers of capsules, which are groups of neurons that learn to recognize specific features of the object. For example, one set of capsules may learn to recognize the shape of the face, while another may learn to recognize the texture of the skin. We then will train our model on batches of real and fake images.

Potential Dataset: [deepfake and real images | Kaggle](https://www.kaggle.com/datasets/manjilkarki/deepfake-and-real-images)
