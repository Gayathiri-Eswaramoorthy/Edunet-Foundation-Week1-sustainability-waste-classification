# Dataset Information

## Source
Garbage Classification Dataset by Suman Kunwar 
[Kaggle Link](https://www.kaggle.com/datasets/sumn2u/garbage-classification)

## Description
This dataset contains images of **six waste categories**:
- Cardboard
- Glass
- Metal
- Paper
- Plastic
- Trash

Each image represents a real-world waste object for recycling classification tasks.

## Structure
data/
│
├── train/ # Training images (by category)
└── test/ # Testing images


## Preprocessing Performed
- Removed corrupted/unreadable files  
- Resized all images to **128×128 pixels**  
- Normalized pixel values  
- Applied augmentation (rotation, flip, zoom)