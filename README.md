# Audio Classification using FastAI

This project focuses on building an audio classifier using FastAI. It processes audio files, converts them into spectrogram images, and trains a deep learning model to classify them.

## Steps
1. **Data Preparation**: Load and inspect audio files from the dataset.
2. **Spectrogram Generation**: Convert audio signals into spectrogram images.
3. **Dataset Organization**: Structure images into train and test sets.
4. **Model Training**: Use FastAI’s vision learner with a ResNet model.
5. **Evaluation**: Assess the model's performance using validation data.
6. **Prediction**: Classify new audio files based on their spectrograms.

## Requirements
- FastAI
- Librosa
- PyTorch
- Torchaudio
- Matplotlib
- Kaggle Notebook environment

## Usage
1. Run the script to generate spectrograms.
2. Train the model using FastAI’s DataBlock.
3. Use the trained model to classify new audio samples.

## Results
The model achieves a reasonable accuracy in distinguishing between different audio classes using spectrogram images as input.

