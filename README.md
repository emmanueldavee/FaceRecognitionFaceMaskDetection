# Face Recognition with Face Mask Detection
This project is a development from my laboratory project in university. The project in class purely uses LBPH Face Recognizer to recognize faces of korean celebrities. However, I was curious whether this LBPH Face Recognizer is applicable to recognize faces in real time. I decided to develop this project that can provide solution for the new normal that we have to face due to the pandemic. Indonesian government have released health protocols where citizens must do social distancing, wear masks and more. 

Amidst of this pandemic there are certain businesses that still require their employees to come to office. Responding to this problem, a new attendance system is needed to avoid contact. Majority attendance system used today still require contacts like using a card (RFID technology) or even fingerprint. These systems are dangerous. Every employee should scan their finger on the fingerprint device. Hence, small liquid particles exerted by the employee can be left at the device. Other employees that are using the same device will come in contact with the small liquid particles left by other employees. This type of interaction has high probability to spread the virus.

Responding to the problem mentioned above, a new attendance system is needed that does not require contact. The proposed system will integrate face recognition with face mask detection which is extremely useful nowadays. A company can take attendance of their employees with no contacts and at the same time ensure that their employees are using a face mask. Relying on humans to detect whether everyone is wearing a face mask is too risky. A slight of an eye can cause someone to get infected by the virus. 

The dataset for the LBPH Face Recognizer is provided by my class in university. I added some pictures of myself to test the application in real time. The Mask Detection is trained using a deep learning model based on MobileNet. I used the dataset from kaggle to train the deep learning model. The dataset used can be accessed through this link https://www.kaggle.com/omkargurav/face-mask-dataset .

Code implementation can be checked on the following files:

1. **FaceRec Training.ipynb**: LBPH Face Recognizer Training for Face Recognition

2. **MaskTraining.ipynb**: MobileNet Deep Learning Training for Mask Detection

3. **Detector.ipynb**: final application that integrates Face Recognition with Mask Detection

The face detection used are haarcascade classifier and OpenCV's DNN Caffe Model.

In the future, I would like to conduct further research to optimize the face recognition model. As of now, the face recognition model is too sensitive towards environmental changes, such as lighting, movements, angle and more. In addition, I haven't tested the model in identifying multiple faces in real time yet and whether the system is able to differentiate identical twins or not. 

A short example of how the system works is shown below. Feel free to email me at emmanuel.dave02@gmail.com to request for the full demo or even to ask for further details regarding this project. 

![Demo without Mask](https://github.com/emmanueldavee/FaceRecognitionFaceMaskDetection/blob/master/demo1.png)

