# Sign Language Detection with CNN  

This repository contains a project aimed at recognizing sign language alphabets using a custom Convolutional Neural Network (CNN) model. The project includes the creation of a manual dataset, model training, and a small interactive user interface using OpenCV.  

## Features  
- **Custom Dataset**: Manually created dataset with 1800 black-and-white images per alphabet (A-Z).  
- **Custom CNN Model**: Designed and trained using Kaggle GPU resources.  
- **Interactive UI**: Built using OpenCV, allowing users to make sign gestures and set HSV values for detection.  
- **Real-Time Prediction**: The model processes the captured frame and predicts the corresponding alphabet.  

## Motivation  
This project was developed as a hands-on learning experience while studying Convolutional Neural Networks (CNNs) in deep learning. It provided practical insights into data preparation, model building, and integration with OpenCV.  

## Requirements  
- Python 3.x  
- OpenCV  
- TensorFlow/Keras  
- Kaggle (for training)  

## Installation  
1. Clone the repository:  
  ```bash
   git clone https://github.com/yourusername/Sign-Language-Recognition-CNN.git
   cd Sign-Language-Recognition-CNN
  ```

2. Install the required libraries:
   ```bash
     pip install -r requirements.txt
   ```
## Dataset
 - The dataset was manually created with 1800 black-and-white images per alphabet. Each image captures hand gestures representing alphabets A-Z.

## Model Architecture
- The CNN model was designed from scratch, optimized for this specific task. It includes layers for convolution, pooling, and dense connections to accurately classify the images.

## Training
- The model was trained on Kaggle using GPU acceleration. Training details:

* Batch size: 32
* Optimizer: Adam
* Loss Function: Categorical Crossentropy

## How to Use
1) Run the UI application
  ```bash
  python recognise.py
  ```
2) Adjust HSV values to isolate hand gestures in real-time.
3) Perform a gesture, and the model will predict the corresponding alphabet.

## Limitations
- This project was built as a learning exercise and is not intended for production use. It can serve as a foundation for more advanced sign language detection systems.

## Future Work
* Extend the dataset to include numbers and common words.
* Implement transfer learning with pre-trained models for improved accuracy.
* Enhance UI for better user experience.

## Acknowledgements
* Kaggle: For providing GPU resources.
* OpenCV: For enabling real-time image processing.
* Deep learning tutorials and resources that guided the project development.

## License
- This project is licensed under the MIT License.

## Contact
- For any queries or collaborations, feel free to contact me at harshbhanushali.ai@gmail.com
