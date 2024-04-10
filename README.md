# Face_Mask_Detection
# Requirments :
tensorflow>=1.15.2
keras==2.3.1
imutils==0.5.3
numpy==1.18.2
opencv-python==4.2.0.*
matplotlib==3.2.1
scipy==1.4.1

# Introduction :
In recent times, the COVID-19 pandemic has necessitated the widespread adoption of face masks as a preventive measure against the spread of the virus. Consequently, automated systems for detecting whether individuals are wearing masks have gained significant interest and importance. In this project, we propose a machine learning-based approach for face mask detection, aimed at assisting authorities in enforcing mask-wearing policies in public spaces.

The primary objective of this model is to accurately identify whether individuals within images or video streams are wearing masks or not. This task is challenging due to variations in facial expressions, lighting conditions, and the diverse array of mask types and wear styles. To address these challenges, we leverage state-of-the-art deep learning techniques, specifically convolutional neural networks (CNNs), which have demonstrated remarkable performance in various computer vision tasks.


# About Model :
Our proposed model is trained on a large dataset of annotated images containing individuals with and without masks. We employ transfer learning, utilizing pre-trained CNN architectures MobileNet which enables us to achieve high accuracy even with limited training data. Furthermore, we employ data augmentation techniques to enhance the robustness of the model and mitigate overfitting.The model is also computationally efficient and thus making it easier to deploy the model to embedded systems(Raspberry Pi, Google Coral, etc.).

The developed face mask detection system holds significant potential for real-world applications, including monitoring compliance with mask mandates in public spaces, enhancing safety measures in workplaces, and aiding law enforcement agencies in ensuring public health regulations are adhered to. By providing an efficient and automated solution for mask detection, our model contributes to efforts aimed at controlling the spread of infectious diseases and safeguarding public health.


# Dataset:
 Contains images with both mask and no mask which is collected from kaggle.
 

# Real-Time Application :
 These types of models could be integrated with CCTV cameras to detect and identify people without masks, in areas like Public Transportation Hubs,Retail Stores and Malls,Healthcare Facilities,Smart Cities and Urban Planning ETC.
