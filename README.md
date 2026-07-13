Dog-Cat-Image-Classifier

## Project Description
This project is an image recognition model trained using Google's Teachable Machine. It loads a trained Keras model using Python to predict and classify new input images.

## Repository Contents
- `main.py` (or Jupyter Notebook): The Python script used to load the model and test images.
- `keras_model.h5`: The trained AI model file.
- `labels.txt`: The file containing the class names (Dog, Cat).
- `screenshot.png`: A screenshot showing the final output and successful prediction.

## 🛠️ Steps to Recreate the Project
1. Opened **Google Teachable Machine** and started a new **Image Project**.
2. Created two classes named **Dog** and **Cat**, and uploaded 8 images for each class.
3. Clicked **Train Model** and waited for the training to finish.
4. Exported the model and downloaded it in **TensorFlow (Keras)** format. I also copied the generated Python code.
5. Opened a new **Google Colab** notebook and pasted the code.
6. Uploaded the downloaded model files (`keras_model.h5` and `labels.txt`) to the Colab files section.
7. Uploaded a test image named `test1.jpg`.
8. Ran the script to test the image, and the model successfully predicted the correct class!
