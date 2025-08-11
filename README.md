# SCT_ML_3
# CAT VS DOG IMAGE CLASSIFIER 

## ABOUT
This project demonstrates a simple **machine learning model** that classifies images as **Cat** or **Dog** using a **Support Vector Machine (SVM)**.  
It automatically downloads images from the internet, processes them, trains a model, and evaluates its accuracy.

---

## FEATURES
1. Classifies images into **Cat** or **Dog**.
2. Automatically downloads images from the internet using **DuckDuckGo Search API**.
3. Uses **OpenCV** for image preprocessing.
4. **Support Vector Machine (SVM)** classifier from scikit-learn.
5. Displays **accuracy score** and a **classification report**.
6. Skips unreadable/broken images automatically.

---

## TECHNOLOGY USED
1. **Python** (Preferably version 3.10 or higher)
2. **OpenCV** – For image reading, resizing, and preprocessing.
3. **scikit-learn** – For training and evaluating the Support Vector Machine (SVM) model.
4. **tqdm** – For showing progress bars while downloading images.
5. **requests** – For fetching images from the internet.
6. **ddgs** – DuckDuckGo Search API for downloading images.

---

## TECHNIQUES USED
- **Image Preprocessing**:  
  - Resizing all images to a fixed size (128x128).  
  - Converting images into flat numerical arrays for model input.  
  - Skipping broken or unreadable images.

- **Machine Learning Model**:  
  - Used **Support Vector Machine (SVM)** for binary classification (Cat vs Dog).
  - Split dataset into **Training (80%)** and **Testing (20%)**.
  - Measured **Accuracy, Precision, Recall, and F1-score**.

- **Automation**:
  - Automatically downloads and stores training images for each category.
  - Uses progress bars for better user experience.

---

## SAMPLE OUTPUT
**Process:**
- Downloads ~30 images for both cats and dogs.
- Resizes and flattens each image.
- Trains an SVM classifier.
- Evaluates model on test data.

**Output:**
<img width="1920" height="1080" alt="Screenshot (42)" src="https://github.com/user-attachments/assets/5687c427-fa48-47a9-ade5-76b0aca17dce" />
<img width="1920" height="1080" alt="Screenshot (43)" src="https://github.com/user-attachments/assets/431142f6-77b3-4b42-b5a4-a3f70ec67653" />
