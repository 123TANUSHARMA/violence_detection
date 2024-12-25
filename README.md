# Violence Detection Using Deep Learning

## Project Overview
This project aims to develop a deep learning-based system for detecting violence in images and videos. The solution utilizes pre-trained deep learning models and datasets to classify scenes into violent and non-violent categories, with potential applications in public safety and surveillance.

## Features
- **Video-Based Detection**: Processes video frames to detect violent activities in real-time.
- **Pre-Trained Models**: Utilizes transfer learning with models such as ResNet.
- **Emergency Response Integration**: Plans for integration with automated emergency services.

## Technology Stack
- **Programming Language**: Python
- **Deep Learning Framework**: TensorFlow/Keras
- **Computer Vision**: OpenCV
- **Development Tools**: Jupyter Notebook, Git

## Dataset

- **Video Dataset**: Real Life Violence Situations Dataset (Optional)
  - Categories:
    - Violence: 1000 videos
    - Non-Violence: 1000 videos

## Setup Instructions

### Prerequisites
1. Install Python 3.8 or above.
2. Install the following libraries:
   ```bash
   pip install tensorflow keras opencv-python
   ```
3. Clone the project repository:
   ```bash
   git clone https://github.com/your-repo/violence-detection.git
   ```
4. Navigate to the project directory:
   ```bash
   cd violence-detection
   ```

### Usage
1. **Train the Model**:
   - Place the dataset in the `data/train` and `data/test` directories.
   - Run the training script:
     ```bash
     python train_model.py
     ```

2. **Run Inference**: 
   - For videos:
     ```bash
     python app.py
     ```
- Then you just have to copy the path that is displayed over the screen and run it onto chrome

### Output
- The trained model saves predictions for test data.
- Detection results are displayed with confidence scores.

## Future Enhancements
- **Real-Time Processing**: Optimize performance for real-time surveillance.
- **Multi-Class Classification**: Extend to detect specific types of violent activities.
- **Alert Mechanism**: Integrate with SMS or email notifications for automated alerts.

## Contributing
1. Fork the repository.
2. Create a feature branch:
   ```bash
   git checkout -b feature/your-feature
   ```
3. Commit your changes and push:
   ```bash
   git commit -m "Add your feature"
   git push origin feature/your-feature
   ```
4. Open a pull request.

