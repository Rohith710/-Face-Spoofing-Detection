# -Face-Spoofing-Detection

Introduction:
Face spoofing is one of the most difficult problems in biometrics. Biometric authentication systems are secured using face spoofing detection systems. To prevent spoofing, we use live detection.
The use of computer vision technology to detect the harmless presence of a live user, rather than a representation such as a picture, a fake video, or a mask, is known as facial liveness detection biometrics.
Active or passive face liveness detection methods can be used in Presentation Attack Detection (PAD) technologies. Although it is most commonly associated with liveness detection in face recognition, it can also be used in voice recognition to distinguish people in front of the scanner, speakers recording audios, or in all scanning situations. 

HOW DOES FACE RECOGNITION LIVENESS DETECTION WORK?    

The use of each person's unique biological identifiers to verify their identity with maximum accuracy and minimum error is known as liveness detection for face recognition with biometrics.
This authentication is based on each person's biometric heritage and is the most advanced authentication method available, requiring the possession of unique and irreplaceable data from each individual.
This data is undoubtedly difficult to alter, and research is underway to develop systems for detecting face liveness that can detect facial spoofing without errors or mistakes. For all of these reasons, biometric authentication is vulnerable to spoofing attacks that attempt to disrupt a legitimate biometric authentication process of liveness detection for face recognition. Such attacks are unusual, and every effort is being made to prevent them.

Implementation:
The system's workflow is as follows: 
The input image is first captured with a webcam, and then a face detection algorithm is applied to it. The detected face is then forwarded to the liveness network, which determines whether or not the image is from a real person.

Requirements:
opencv-python==4.4.0.40
tensorflow==2.5.0
google colab / pycharm /jupyter Notebook
Mobile net - mobilenetv2-epoch_01
