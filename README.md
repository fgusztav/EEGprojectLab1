# EEG Signal Processing with Deep Learning

This project explores EEG signal classification using deep learning, specifically implementing the EEGNet architecture for two distinct applications:

1. **Visual Oddball Task Classification** (US Army Research Lab Dataset)
   - Binary classification of target vs. non-target visual stimuli
   - Achieved 92.42% accuracy and 0.93 AUC score
   - Compared standard vs. class-weighted model approaches

2. **Motor Imagery Classification** (BCI Competition IV Dataset 2a)
   - Four-class classification of imagined movements (left hand, right hand, feet, tongue)
   - Implemented comprehensive preprocessing pipeline with ICA and frequency filtering
   - Achieved 63.5% accuracy (baseline: 25%) with 0.864 AUC score
   - Strong performance in hand movement classification (70-75% recall)

## Technical Stack

- **Languages & Libraries**: Python, TensorFlow, Keras, MNE, PyRiemann
- **Development Environments**: 
  - Google Colab (Visual Oddball Task)
  - VSCode with Jupyter notebooks (Motor Imagery Task)

## Key Features

- Advanced EEG signal preprocessing techniques
- Independent Component Analysis (ICA) for artifact removal
- Custom data pipelines for both binary and multi-class classification
- Experimentation with model architectures and hyperparameters
- Comprehensive performance evaluation metrics

## Results

The project demonstrates the versatility of deep learning approaches for EEG signal processing across different types of classification tasks. While binary classification achieved higher accuracy, the four-class motor imagery task showed significant improvement over random chance, particularly in distinguishing between left and right hand movements.
