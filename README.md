# Malenoma Detection
> Outline a brief description of your project.
To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.


## Table of Contents
* [General Info]
Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution which can evaluate images and alert the dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.

* [Technologies Used](Python -- Numpy,Pandas, Matplotlib,Tensorflow,Google Colab(GPU), CNN,Keras )
* [Conclusions]
 Final Machine Learning Model is created using CNN alogorith to detect Malenoma Cancer with a Training accuracy is 95.51% and validation accuracy is 87.3 %.
  Final model shows no overfitting or underfitting 

* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Provide general information about your project here.
- What is the background of your project?
Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution which can evaluate images and alert the dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.

- What is the business probem that your project is trying to solve?
To build a CNN based model which can accurately detect melanoma.
The fiffrent types of cancers are considered here are:
Actinic keratosis

Basal cell carcinoma

Dermatofibroma

Melanoma

Nevus

Pigmented benign keratosis

Seborrheic keratosis

Squamous cell carcinoma

Vascular lesion
- What is the dataset that is being used?
Skin cancer ISIC The International Skin Imaging Collaboration  -- images for Train and Test 

Multiple models are created:
--Model 1 Building , Training , Evaluation and Findings -- CNN Model without Dropout layer
--Model 2 Building , Training , Evaluation and Findings -- CNN Model with Dropout layer
--Model 3 Building , Training , Evaluation and Findings -- CNN Model with Augmented data and Dropout layer
-- Model 4 Building , training , Evaluation and Findings - CNN Model with Augmentor to rectify imbalance class data

Steps followed are:

Data Reading/Data Understanding → Defining the path for train and test images 
Dataset Creation→ Created train & validation dataset from the train directory with a batch size of 32 with images to 180*180.
Dataset visualisation → To visualize one instance of all the nine classes present in the dataset 
Model Building & training : 
Create a CNN model, which can accurately detect 9 classes present in the dataset. While building the model, rescale images to normalize pixel values between (0,1).
Choose an appropriate optimiser and loss function for model training

--Model 1 Building , Training , Evaluation and Findings -- CNN Model without Dropout layer
--Model 2 Building , Training , Evaluation and Findings -- CNN Model with Dropout layer to improve the model performance and prevent overfitting

Train the model for ~20 epochs to improve the model performance but still overfitting was observed.

--Model 3 Building , Training , Evaluation and Findings -- CNN Model with Augmented data and Dropout layer with an appropriate optimiser and loss function for model training ad Train the model for ~20 epochs

-- Model 4 Building , training , Evaluation and Findings - CNN Model with Augmentor to rectify imbalance class data 
- Rectified class imbalances present in the training dataset with Augmentor library and train the model with epoch ~30 to improve the model performance and prevent overfitting.
<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Training accuracy is 95.51% and validation accuracy is 87.3 %

- After using Augmentor and using imbalance of all classes, significance improvement in the training and validation accuracy are observed.

- More epochs can be added to increase the accuracy Further but too much epoch would cause overfitting too. so epoch =30 is quite great enough

- Overfitting or underfitting issues are resloved in the final model

- Training and validation loss has been decreased due to increase in epoch
- Conclusion 2 from the analysis
- Conclusion 3 from the analysis
- Conclusion 4 from the analysis

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- library - version 1.0
- library - version 2.0
- library - version 3.0

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by...
- References if any...
- This project was based on [this tutorial](https://www.example.com).


## Contact
Created by [@githubusername] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->