# SCT_ML_3
# CAT VS DOG CLASSIFIER
# ABOUT
This project is a machine learning-based image classifier that can determine whether an uploaded image is of a cat or a dog.
The tool comes with a beautiful, colorful, and user-friendly Tkinter GUI, making it attractive for presentations, demonstrations, and learning purposes.

---

# FEATURES
1) Upload any image (JPG, JPEG, PNG) to classify it as a cat or dog.
2) Professional yet playful design with color-coded results:
3) Pink background for Cats
4) Light blue background for Dogs.
5) Image preview inside the application.
6) Hover effects on buttons for interactivity.
7) Uses a pre-trained machine learning model for predictions.
---

# TECHNOLOGY USED
1) Python (preferably version 3.10 or higher)
2) scikit-learn – for machine learning model loading and prediction.
3) OpenCV – for image preprocessing and resizing.
4) Pillow (PIL) – for image display in the Tkinter GUI.
5) Tkinter – for creating the interactive desktop application.
---

# SAMPLE OUTPUT

Inputs:
Upload any cat or dog image from your system.

Outputs:
Prediction Label: Displays "Cat" or "Dog".

Image Preview: Shows the uploaded image.
Color-coded background based on prediction.

Example Screenshots:

<img width="1920" height="1080" alt="Screenshot (44)" src="https://github.com/user-attachments/assets/755b9a53-15c5-4696-a7ad-e980bb6ce447" />

Dog Prediction: 
<img width="1920" height="1080" alt="Screenshot (45)" src="https://github.com/user-attachments/assets/b95b8d9c-4c42-4524-bf50-7b241b457222" />

Cat Prediction: 
<img width="1920" height="1080" alt="Screenshot (46)" src="https://github.com/user-attachments/assets/345aafaf-73f4-48b2-ac94-8b53d84a1ad4" />

---

# POINTS TO NOTE

This is a basic-level project designed for learning and demonstration purposes.
For real-world accuracy, train the model with more diverse and high-quality data.
Ensure the file model.pkl (pre-trained model) is in the same directory as this script before running.
---

# TECHNIQUES USED
Machine Learning (Classification): Uses a pre-trained model trained on grayscale, resized images (64x64).
Image Preprocessing: Resizing, grayscale conversion, and flattening for model input.
GUI Development: Tkinter used to create a modern, user-friendly interface.
Interactive Design: Color-coded predictions, hover effects, and emoji integration.

# Built with eagerness to learn.
