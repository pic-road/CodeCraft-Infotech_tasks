# Cat vs Dog Image Classification using SVM

This project implements a **Support Vector Machine (SVM)** classifier to distinguish between images of **cats** and **dogs**.

## Dataset
The dataset used is from [Kaggle's Dogs vs. Cats competition](https://www.kaggle.com/c/dogs-vs-cats/data).

### What is an SVM?

Support Vector Machine(SVM) is a supervised machine learning algorithm used for classification tasks. 

It works by finding the optimal hyperplane that best separates the data into different classes. SVMs are effective beacause it maps non-linearly separable data onto high-dimensional spaces, thus making it suitable for binary classification problems such as this. 

---

## Tasks Performed

- Loaded and preprocessed image data (resizing, normalization).
- Extracted features from images using a pretrained model (VGG16).
- Trained a linear SVM classifier on the extracted features.
- Evaluated the model using accuracy, F1-score, and confusion matrix.
- Visualized classification results.

---

##  Tools & Frameworks Used

- **Python** – Core programming language.
- **PyTorch** – For building DataLoaders and handling image data efficiently.
- **scikit-learn** – For SVM, performance metrics, and evaluation.
- **VGG16** – A pretrained model for feature extraction.
- **Matplotlib / Seaborn** – For data visualization.


>PyTorch made handling image datasets and DataLoaders efficient.
> 
>scikit-learn provides built-in tools for building and evaluating SVM models. 
>
>Pretrained models like VGG16 saved training time and ensure better performance by extracting useful features.

---

## Result

- **Accuracy**: ~98%
- **Precision/Recall/F1**: All ~0.98 for both classes.
- The SVM classifier performed very well, indicating that the features extracted from images were highly separable for this task.Thus the use of VGG16 proved beneficial.

---

## What I Learned

- How to process and load image datasets in PyTorch.
- How to use a pretrained CNN model for feature extraction.
- How to implement an SVM classifier for image classification.
- How to evaluate classification models using different performance metrics.

---

## Acknowledgements

Thanks to the [Kaggle community](https://www.kaggle.com/) for hosting this dataset and challenge, and to my internship mentor for this opportunity to apply machine learning to a real dataset.

