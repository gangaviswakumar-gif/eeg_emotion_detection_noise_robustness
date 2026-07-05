# eeg_emotion_detection_noise_robustness
Noise Robustness in EEG Emotion Recognition

Dataset:
- DREAMER

Pipeline:
EEG
 ↓
Preprocessing
 ↓
Feature Extraction
 ↓
AWGN Injection
 ↓
Wavelet Denoising
 ↓
Feature Extraction
 ↓
ML Classifier
 ↓
Accuracy Comparison

Expected:
Pristine Accuracy
      >
Denoised Accuracy
      >
Noisy Accuracy
