# Malanoma Detection
> To build a CNN based model which can accurately detect melanoma.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## General Information
- Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths.
- A solution of CNN based model that can evaluate images and alert dermatologists about the presence of melanoma.
- It has the potential to reduce a lot of manual effort needed in diagnosis.
- The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC).

## Conclusions
- "seborrheic keratosis" class has the least number of sample, while "pigmented benign keratosis" has the most.
- "melanoma" has 19.5 % sample images.
- We have used 'Relu' activation function, 'adam' optimizer.
- Initially there was case of overfitting due to class imbalance.
- Overfitting and information loss has been tackled using class resemblance and drop out technique.
- Overall training accuracy after 30 epochs is 95%, validation accuracy is 83%.

## Technologies Used
- Google Collab

## Acknowledgements
- This project is based on CNN tutorial(https://www.upgrad.com).

## Contact
Created by [@kaushikpaul34] - feel free to contact me!

