# Efficient Image Segmentation for Self-Driving Cars Using U-Net

## Summary:
Developed a robust image segmentation method utilizing U-Net architecture to enhance object detection in self-driving cars. The model was trained on a specialized dataset, achieving high accuracy in segmenting key elements such as cars, trucks, and pedestrians. This approach significantly improved the vehicle's ability to navigate complex environments, directly contributing to advancements in autonomous driving technology and safety.



## Dataset
This dataset is dedicated to self-driving car research and development. 
link: https://www.kaggle.com/datasets/alincijov/self-driving-cars

### Credits
Full credit goes to **Udacity** for creating the images and for the dataset labeling.

### Labels
The dataset contains the following **classic_id** labels:
- **car**
- **truck**
- **pedestrian**
- **bicyclist**
- **light**

### Project Goals

The primary goal of this project is to implement a robust object detection system using the YOLO (You Only Look Once) architecture, enabling real-time identification and classification of objects relevant to self-driving applications. By leveraging deep learning techniques, this system aims to enhance safety and efficiency in autonomous vehicle navigation.


![image](https://github.com/user-attachments/assets/dd8545cc-ef78-4856-ae2e-82e9899ef598)


![image](https://github.com/user-attachments/assets/2c178d51-9a2e-4823-929e-678fb78da899)



# Modeling: 

U-Net is a deep learning architecture primarily used for image segmentation tasks. It consists of a symmetrical U-shaped structure with two main parts: a contracting path (encoder) that captures context through convolutional and pooling layers, and an expanding path (decoder) that enables precise localization via upsampling. Skip connections between corresponding layers of the encoder and decoder help retain fine-grained details. U-Net is widely used in medical imaging, autonomous driving, and other applications where accurate pixel-wise predictions are required. Its strength lies in efficiently learning both global context and detailed spatial information.

![image](https://github.com/user-attachments/assets/6a028bed-4f46-47d9-bb90-e3afef4e24c7)

Ref: https://towardsdatascience.com/u-net-explained-understanding-its-image-segmentation-architecture-56e4842e313a






![image](https://github.com/user-attachments/assets/ae70105e-ad7f-4871-8de6-c12d2490de27)

