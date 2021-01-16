  # Medical-Diagnosis-with-CNN-Transfer-Learning
With the help of CNN and Transfer Learning we will diagnosis the Pneumonia cancer from X_ray images

### AI for Medical Diagnosis
Computer Vision (CV) has a lot of applications in medical diagnosis:

# Dermatology
# Ophthakmology
# Histopathology.
X-rays images are critical for the detection of lung cancer, pneumenia ... In this notebook you will learn:

![X-ray](https://user-images.githubusercontent.com/57557590/104820505-46962000-584a-11eb-9146-73c4af1e0de3.PNG)

**Data pre-processing**

**Preprocess images properly for the train, validation and test sets.**

**Set-up a pre-trained neural network to make disease predictions on chest X-rays.**

In this notebook you will work with chest X-ray images taken from the public ChestX-ray8 dataset.

# What is Pneumonia ?
From Mayo Clinic's Article on pneumonia

Pneumonia is an infection that inflames the air sacs in one or both lungs. The air sacs may fill with fluid or pus (purulent material), causing cough with phlegm or pus, fever, chills, and difficulty breathing. A variety of organisms, including bacteria, viruses and fungi, can cause pneumonia.

Pneumonia can range in seriousness from mild to life-threatening. It is most serious for infants and young children, people older than age 65, and people with health problems or weakened immune systems.

![download](https://user-images.githubusercontent.com/57557590/104820294-10a46c00-5849-11eb-8615-c4630a912f13.png)

# Computer Vision
Computer vision is an interdisciplinary scientific field that deals with how computers can gain a high-level understanding from digital images or videos. From the perspective of engineering, it seeks to understand and automate tasks that the human visual system can do. We can use Computer Vision to determine whether a person is affected by pneumonia or not.

**Pneumonia Detection with Convolutional Neural Networks**
Computer Vision can be realized using Convolutional neural networks (CNN) They are neural networks making features extraction over an image before classifying it. The feature extraction performed consists of three basic operations:

**Filter an image for a particular feature (convolution)**

**Detect that feature within the filtered image (using the ReLU activation)**

**Condense the image to enhance the features (maximum pooling)**

The accuracy of the CNN model could be shown as below:

![accuracy](https://user-images.githubusercontent.com/57557590/104820572-e18efa00-584a-11eb-8487-6534cdf7569f.PNG)

### Transfer Learning
In deep learning, transfer learning is a technique whereby a neural network model is first trained on a problem similar to the problem that is being solved. One or more layers from the trained model are then used in a new model trained on the problem of interest.

**DenseNet**
Densenet is a convolutional network where each layer is connected to all other layers that are deeper in the network:

. The first layer is connected to the 2nd, 3rd, 4th etc.
. The second layer is conected to the 3rd, 4th, 5th etc.
**VGG16**
**ResNet**
**InceptionNet**


