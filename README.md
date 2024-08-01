# Defect-detection-from-drone-images-of-Wind-turbine

<img src="https://github.com/RE-NY/Defect-detection-from-drone-images-of-Wind-turbine/blob/main/nordtank_turbine.jpeg" alt="NordTank Wind Turbine" width="1000" height="700">

### Overview
This project utilizes image processing techniques and Convolutional Neural Networks (CNNs) to detect defects in wind turbine images captured by drones. The dataset, provided by DTU, consists of images from nordtank wind turbines in Denmark taken during 2017 and 2018.

This project aims to automate the defect detection process using state-of-the-art deep learning models.

VGG-19 model, pre-trained on the ImageNet dataset, was used for transfer learning.
- All layers of VGG-19 were frozen to retain pre-trained weights.
- A custom dense layer was added on top of the VGG-19 model for binary classification.
- The model was compiled using the Adam optimizer and binary cross-entropy loss function.

### Relevant Links
- [link to "correct" dataset](https://drive.google.com/drive/folders/18-OXCH8E4f69cNyIpoOfmspUpdEN4MSJ?usp=drive_link)
- [link to "defected" dataset](https://drive.google.com/drive/folders/1Vpdj5Y8XCDYoDpjnc30CCEGuXjS_xSUz?usp=drive_link)

### References
- [DTU defect detection Dataset](https://b2find.dkrz.de/dataset/64bd49c0-069a-535d-9f43-f5b5fba929a1)
- [Keras Documentation](https://keras.io/)
- [OpenCV Documentation](https://docs.opencv.org/4.x/index.html)

