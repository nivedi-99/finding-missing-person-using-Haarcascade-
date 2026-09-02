# finding-missing-person-using-Haarcascade-

```markdown
# Finding Missing Person Using Haar Cascade

A computer vision project designed to identify and recognize missing individuals using
Haar Cascade classifiers for face detection and identification models.

## 📌 Features
* **Face Detection**: Utilizes OpenCV's pre-trained Haar Cascade classifier (`haarcascade_frontalface_default.xml`)
to detect human faces in images/video streams.
* **Model Training**: Pipeline script to process dataset images and
train recognition models for registered individuals.
* **Testing & Authentication**: Scripts to verify and match input images
against the trained database for identification.

## 📁 Repository Structure

```

Authentication.ipynb                     
### Notebook for user verification and testing pipeline
TEST.py                                   
### Python script for running inference/testing on input images
TRAIN.PY                                  
### Python script for training the face recognition model
haarcascade_frontalface_default.xml       
### Haar Cascade XML model for face detection
train and test person identification.zip  
### Sample dataset for training and testing
README.md                                
### Project documentation

```

## 🛠️ Prerequisites & Installation

Ensure you have Python 3.x installed along with the required dependencies:
pip install opencv-python numpy



*(Optional)* If using Jupyter Notebook for running `Authentication.ipynb`:

pip install notebook

## 🚀 How to Run

### 1. Data Setup

Extract the dataset archive to populate training and testing directories:


unzip "train and test person identification-20230626T203613Z-001.zip"

### 2. Train the Model

Run the training script to process the training dataset and build face representations:
python TRAIN.PY



### 3. Run Identification / Testing

To test face recognition on test samples:
python TEST.py


Alternatively, open and step through `Authentication.ipynb` using Jupyter Notebook for an interactive workflow:

jupyter notebook Authentication.ipynb

## 📜 License

This project is open-source and available under the standard repository terms.
