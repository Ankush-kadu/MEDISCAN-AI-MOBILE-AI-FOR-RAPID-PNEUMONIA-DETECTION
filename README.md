# MEDISCAN-AI-MOBILE-AI-FOR-RAPID-PNEUMONIA-DETECTION

Project Overview

MediScan AI is designed to detect pneumonia from chest X-rays using a MobileNet model optimized for mobile devices, utilizing TensorFlow Lite. This solution aims to provide real-time, low-latency predictions directly on mobile devices, enhancing accessibility and efficiency in medical diagnostics.
Features

    MobileNet Architecture: Leveraging the lightweight and efficient MobileNet model allows for rapid inferences and minimal resource usage on mobile devices.
    TensorFlow Lite: Optimizes the CNN model to run efficiently on mobile platforms.
    Grad-CAM Visualization: Implements Gradient-weighted Class Activation Mapping to offer interpretable visualizations of the model's predictions, enhancing trust and clarity in results.
    Distributed Training: Utilizes TensorFlow's TPUs and distributed training strategies to decrease model training time and scale performance effectively.

Dataset

The dataset consists of chest X-ray images categorized into two classes: Normal and Pneumonia. The training process addresses the class imbalance by applying class weights, improving the model’s ability to learn from underrepresented classes effectively.
Model Training

    TPUs for Training: The model utilizes TensorFlow's TPU support to expedite the training process, taking advantage of their powerful processing capabilities to handle extensive computations.
    Class Weights: Due to the imbalance in the dataset, class weights were calculated to ensure fair exposure during training, mitigating bias.
    Performance Metrics: The model's performance is evaluated based on accuracy, precision, and recall, ensuring the model's reliability and effectiveness in a real-world setting.
