# ResNet152 & Keras-TensorFlow - Image & Vision Classification of Futurama Frames  

🏆 **Achievements**:  
- 🥈 **2nd Place** in Public Leaderboard  
- 🥉 **3rd Place** in Private Leaderboard  

This repository presents two different approaches to tackle a multi-label image classification problem using **Futurama frames** as the dataset.  

---

## Table of Contents  
- [Overview](#overview)  
- [Approaches](#approaches)  
  - [Keras Conv Approach](#keras-conv-approach)  
  - [ResNet152 Approach](#resnet152-approach)  
- [Kaggle Competition](#kaggle-competition)  
- [Requirements](#requirements)  
- [Results](#results)  
- [More Info](#more-info)  
- [License](#license)  

---

## Overview  

This project was part of the **Futurama Kaggle Competition** hosted by Mediavida, focusing on classifying characters in frames from the show.  

Two distinct methodologies were used:  
1. A custom **Keras CNN model** for character identification.  
2. A **ResNet152 model** pretrained with the **Imaginet_v2** dataset.  

Both approaches achieved competitive results, demonstrating robust performance in multi-label image classification tasks.  

---

## Approaches  

### Keras Conv Approach  

- **Objective**: Identify characters in Futurama frames using a custom convolutional neural network built with Keras.  
- **Competition Score**:  
  - **MCRMSE**: 0.12527  
- **Notebook**: [Keras Conv Notebook](https://www.kaggle.com/code/joseparedesc/keras-conv-identification-characters-futurama/notebook?scriptVersionId=101579385)  

---

### ResNet152 Approach  

- **Objective**: Utilize the ResNet152 architecture pretrained on **Imaginet_v2** to identify characters in Futurama frames.  
- **Competition Score**:  
  - **MCRMSE**: 0.09149  
- **Notebook**: [ResNet152 Notebook](https://www.kaggle.com/code/joseparedesc/resnet152-imaginet-image-vision-classification/notebook?scriptVersionId=102675904)  

---

## Kaggle Competition  

- **Competition Page**: [Futurama Kaggle Competition](https://www.kaggle.com/competitions/comp-mediavida-2-futurama/overview)  
- **Public Leaderboard**: [View Public Scores 🥈](https://www.kaggle.com/competitions/comp-mediavida-2-futurama/leaderboard?tab=public)  
- **Private Leaderboard**: [View Private Scores 🥉](https://www.kaggle.com/competitions/comp-mediavida-2-futurama/leaderboard#)  

---

## Requirements  

- **Python 3.x**  
- **Keras & TensorFlow** for the custom CNN approach.  
- **PyTorch & torchvision** for the ResNet152 approach.  
- **Other Libraries**:  
  - `numpy`  
  - `pandas`  
  - `matplotlib`  
  - `seaborn`  

---

## Results  

The project achieved excellent results on both the public and private leaderboards:  
- **Public Leaderboard**: 2nd Place 🥈  
- **Private Leaderboard**: 3rd Place 🥉  

Scores were measured using **Mean Columnwise Root Mean Square Error (MCRMSE)**:  
- Keras Conv: **0.12527**  
- ResNet152: **0.09149**  

---

## More Info  

- **Community**: [Mediavida Dev Forum](https://www.mediavida.com/foro/dev/segunda-competicion-machine-learning-futurama-689127)  

---

## License  

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.  
