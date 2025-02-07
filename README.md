# Voice Gender Recognition Using Neural Networks

## Overview
This project utilizes deep learning techniques to classify speaker gender based on voice features. Using neural networks, the system predicts whether a given voice sample belongs to a male or female speaker.

## Features
- Gender classification based on audio inputs
- Preprocessing of voice signals for feature extraction
- Deep learning model trained on voice datasets
- High accuracy prediction using neural networks
- Visualizations for training and evaluation metrics

## Clone Repository
1. Clone the repository:
   ```sh
   git clone https://github.com/omar0930/Voice-Gender-Recognition-Using-Neural-Networks
   ```

## Dataset
The dataset consists of (https://www.kaggle.com/datasets/primaryobjects/voicegender):
- Recorded voice samples from male and female speakers
- Extracted features such as MFCCs, pitch, and frequency components
- Preprocessed data for training and testing

## Workflow
1. **Data Collection:** Voice samples are gathered and labeled.
2. **Feature Extraction:** Audio signals are processed to extract relevant features.
3. **Model Training:** A neural network is trained using the extracted features.
4. **Prediction:** The trained model classifies new voice samples as male or female.
5. **Evaluation:** Performance metrics such as accuracy, precision, and recall are computed.

## Results
The neural network model demonstrates a high level of accuracy in gender classification. The model was trained on a diverse dataset, ensuring it generalizes well to unseen voice samples. Key findings include:
- **Training Accuracy:** The model achieves over 95% accuracy on the training dataset.
- **Validation Accuracy:** The model maintains strong performance on validation data, reducing overfitting with techniques like dropout and batch normalization.
- **Real-World Testing:** When tested on real-world audio samples, the model maintains a high prediction success rate, confirming its robustness.
- **Feature Importance:** Spectral features such as Mel-Frequency Cepstral Coefficients (MFCCs) significantly contribute to the classification decision, indicating that pitch and frequency components play a crucial role in distinguishing gender.

## Technologies Used
- Python
- TensorFlow/Keras for neural network implementation
- Librosa for audio processing
- NumPy & Pandas for data handling
- Matplotlib for visualization
