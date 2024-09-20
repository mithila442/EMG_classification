# Developing a Robust EMG-Based Gesture Classification System.

This project aims to develop a robust system for classifying hand gestures using electromyography (EMG) data. The project leverages advanced deep learning models including LSTM, 1D CNN, Vision Transformer (ViT), and Swin Transformer to interpret EMG signals for applications in prosthetic control and rehabilitation.

## Dataset
- **Source**: UCI Machine Learning Repository
- **Description**: EMG signals were captured using the MYO Thalmic bracelet from 36 subjects performing various hand gestures.

## Methodology
- **Models**: LSTM, 1D CNN, Vision Transformer, Swin Transformer
- **Preprocessing**: Data normalization, segmentation into fixed-length sequences, overlapping windows
- **Training**: Addressed challenges like class imbalance and overfitting using class weighting and hyperparameter tuning.

## Results
- Evaluated using accuracy, precision, recall, and F1-score.
- Swin Transformer showed the best balance between training and testing performance, while LSTM faced overfitting challenges.

## Future Work
- Improve model generalization with advanced data augmentation and regularization techniques.
- Explore real-time classification and few-shot learning to handle class imbalances.

## Contributors
- Mayesha Maliha Rahman Mithila
- Md Shahriar Kabir

## References
- [EMG Data for Gestures - UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/481/emg+data+for+gestures)
