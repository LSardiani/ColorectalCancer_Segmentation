# ColorectalCancer_Segmentation

Final Project - Enteroscope Biopsy Histopathological Hematoxylin and Eosin Image Dataset for Image Segmentation Tasks (EBHI-Seg)


Hello there! This was the final project from IndonesiaAI Computer Vision (CV) Bootcamp Batch 2.


We used the **EBHI-Seg Dataset** by Shi L, Li X, Hu W, Chen H, Chen J, Fan Z, Gao M, Jing Y, Lu G, Ma D, Ma Z, Meng Q, Tang D, Sun H, Grzegorzek M, Qi S, Teng Y, Li C. EBHI-Seg: A novel enteroscope biopsy histopathological hematoxylin and eosin image dataset for image segmentation tasks. Front Med (Lausanne). 2023 Jan 24;10:1114673. doi: 10.3389/fmed.2023.1114673. PMID: 36760405; PMCID: PMC9902656.


The Dataset is available for public: 
https://figshare.com/articles/dataset/EBHISEG/21540159/1

# Background

Computer-aided diagnosis (CAD) → increasing trends in development and popularity.

CAD is widely used in many biomedical image analysis tasks, such as: microorganism image, COVID- 19 image, **histopathological image**, cytopathological image analysis, and etc.

Fundamental tasks of CAD : IMAGE SEGMENTATION, which can be used as key evidence in the pathologists’ diagnostic processes. Therefore each case can be accurately and efficiently examined with the help of computers.



Colon cancer is a common deadly malignant tumor, the fourth most common cancer in men, and the third most common cancer in women worldwide. Colon cancer is responsible for 10% of all cancer cases.

EBHI-Seg Dataset countains six classes from Colorectal cancer:

Normal - Polyp - Serrated adenoma - Low-grade intraepithelial neoplasia - High-grade intraepithelial neoplasia - Adenocarcinoma.

We defined the different colors for each stages:
![EBHI-Seg3](https://github.com/LSardiani/ColorectalCancer_Segmentation/assets/135226112/fe22aa5f-3c95-43f4-9667-7226ac6a23e3)


Histopathological images from the normal condition to benign and malignant stages.

![EBHI-Seg1](https://github.com/LSardiani/ColorectalCancer_Segmentation/assets/135226112/7d94c45b-e5c1-43b4-b096-2136962979b1)


# Getting started

Download the Dataset from https://figshare.com/articles/dataset/EBHISEG/21540159/1

All pictures are in .png format with 224 x 224 pixel

The Dataset consists of each stages in separate folders

![EBHI-Seg2](https://github.com/LSardiani/ColorectalCancer_Segmentation/assets/135226112/22f0059e-8d6d-4b28-a9b7-88a3ec47ec2a)

We split the training-validation-testing Dataset into 70-20-10.

Therefore,

Training = 1558 images and labels

Validation = 447 images and labels

Testing = 221 images and labels

The train-val-test data.csv can be downloaded on this page


# Model
Multi-class image segmentation

We used UNet, ResUNet, and AttUnet architectures in this project.
![Model comparison](https://github.com/LSardiani/ColorectalCancer_Segmentation/assets/135226112/ee5dcbb4-8354-43fd-bdef-647c2c798fce)

Parameters are applied same Lr, epochs, batch size to all models.

Lr = 0.00001

Epochs = 250

Batch size = 6


# Results


# Summaries from models


# Conclusions


# Contact

Please reach me by email: lilysilva.dr@gmail.com for any further discussion.

Thank you!
