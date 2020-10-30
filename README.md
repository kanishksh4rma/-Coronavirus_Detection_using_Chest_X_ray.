# Coronavirus_Detection_using_Chest_X_ray

---

[![Open Source Love](https://badges.frapsoft.com/os/v3/open-source.svg?v=102)](https://github.com/kanishksh4rma/Parkinson-Disease-Prediction-in-Early-Stages) [![Code Climate](https://codeclimate.com/github/boennemann/badges.svg)](https://github.com/kanishksh4rma/Parkinson-Disease-Prediction-in-Early-Stages)

### Most people infected with the COVID-19 virus will experience mild to moderate respiratory illness and recover without requiring special treatment. Older people, and those with underlying medical problems like cardiovascular disease, diabetes, chronic respiratory disease, and cancer are more likely to develop serious illness.

### The best way to prevent and slow down transmission is be well informed about the COVID-19 virus, the disease it causes and how it spreads. Protect yourself and others from infection by washing your hands or using an alcohol based rub frequently and not touching your face.

---

## Objectives

> ###  The COVID-19 virus spreads primarily through droplets of saliva or discharge from the nose when an infected person coughs or sneezes, so it’s important that you also practice respiratory etiquette (for example, by coughing into a flexed elbow).

> ### *Deep learning* can be used to detect COVID-19 in a patient as recent studies has shown that people suffering from covid19 has infectiuos lung diseases. So in this project I am using deep learning to detect CoronaVirus using chest X-ray.

---


## **Installation**

### Copy and Run this in terminal: 

```
pip3 install -r requirements.txt

git clone https://github.com/kanishksh4rma/Coronavirus_Detection_using_Chest_X_ray.git
```

![demo_install](/screenshots/demo.png)

---

### Libraries used : 

```
  * pandas
  * numpy
  * matplotlib
  * keras
  * sklearn
  
```
---

## Algorithms Used

> * VGG16 (Transfer Learning in Deep Learning)

---

## Steps/Approach :

```
 * Plot some X-rays for analysis purpose.
 * Resize the X-rays.
 * Arrays for images and labels was created. And LabelBinarizer used on labels.
 * Data Augementation used (with rotation range 15).
 * VGG16 model  used as base model.
 * Head model created which consists of- AveragePooling2D, Flatten and two Dense layers.
 * Compile and fit the model, epochs set to 10.
 * Predict the test data and plot it.
 * Metrices tests - F1 score, precision, recall, sensitivity, specificity.
 * Plot lossval and accval graph.
```

## Accuracy : 
 
![accuracy](/screenshots/accuracy.png)

---

> Developed by: [Kanishk Sharma](github.com/kanishksh4rma)

[![forthebadge](https://forthebadge.com/images/badges/built-with-love.svg)](https://github.com/kanishksh4rma/Coronavirus_Detection_using_Chest_X_ray)
