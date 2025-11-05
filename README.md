Edunet Foundation – Sustainability Project
Waste Classification using CNN

This project is part of the Edunet Foundation Internship on Sustainability.
It focuses on developing a Convolutional Neural Network (CNN) model to automatically classify waste into categories — promoting sustainable waste management and recycling automation.

Dataset

Source: Garbage Classification v2 – Kaggle
Classes: Battery, Biological, Cardboard, Clothes, Glass, Metal, Paper, Plastic, Shoes, Trash

Preparation Steps:

Downloaded and verified data integrity
Removed duplicates and unreadable files
Resized images to 128×128 pixels
Organized into labeled subfolders for training and validation
Applied data augmentation to increase variability

Objective

To design and train an image classification model that can automatically identify and categorize waste images — enabling efficient waste segregation for smart and sustainable recycling systems.

Tools & Libraries

Programming Language: Python
Frameworks: TensorFlow, Keras
Libraries: NumPy, Pandas, Matplotlib, scikit-learn, OpenCV

Week 1 Progress

-Selected and cleaned the dataset
-Conducted exploratory data analysis (EDA)
-Implemented preprocessing: resizing, normalization, augmentation
-Created organized project folder structure
-Initialized GitHub repository

Week 2 Progress

-Implemented CNN model using TensorFlow/Keras
-Trained on 10 waste categories using Garbage Classification v2 dataset
-Applied image augmentation and validation split (80:20)
-Achieved ~85–90% validation accuracy
-Evaluated using confusion matrix and classification report
-Tested with real waste images via Google Colab
-Saved trained model (waste_classification_final.h5) for future inference

Next Steps (Week 3 Plan)

-Fine-tune model using Transfer Learning (MobileNetV2)
-Improve accuracy and generalization
-Deploy model or prepare demo presentation (PPT)

Project Structure
Edunet-Foundation-Week1-sustainability-waste-classification/
│
├── data/                 # Dataset folders (train/test)
├── notebooks/            # Jupyter/Colab notebooks
│   ├── 01_data_exploration.ipynb
│   └── 02_model_training.ipynb
├── src/                  # Python source scripts
├── models/               # Saved trained models
├── results/              # Model outputs and plots
├── requirements.txt
└── README.md