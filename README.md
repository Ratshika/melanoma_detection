## Melanoma Skin Cancer Detection using CNN

### Project Overview
- Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths.
- The model built can evaluate images and can be used to alert the dermatologists about the presence of melanoma, which has the potential to reduce a lot of manual effort needed in diagnosis.
- The dataset used was put together by the **International Skin Imaging Collaboration (ISIC).**
- Data imbalance was handled using the **Augmentor** python package.
- Since the number of images for training was less, Data augmentation techniques such as **Flipping, Random Zoom, Contrast** was done to produce more similar images.
- A custom CNN model was built with around **8 lakh** trainable parameters.
- The model trained after artificial generation of image data had a great improvement in performance, both in training as well as validation dataset.
- Training accuracy of **85%** and Validation accuracy of **80%** was achieved.

### Different Types of Skin Cancer:
![skin_cancer](/images/skin_cancer.png)

### Class Imbalance:
![data_imbalance](/images/class_im.png)

### Data Augmentation:
![data_augmentation](/images/data_aug.png)

### Final Accuracy and Loss:
![final_result](/images/final_acc.png)
