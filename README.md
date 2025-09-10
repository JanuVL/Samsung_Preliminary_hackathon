# Condition-Aware Audio Dereverberation using 2D CNN

This project focuses on **audio dereverberation**, the process of removing echo and reverberation from audio recordings using deep learning. We developed a custom **2D Convolutional Neural Network (CNN)** that transforms noisy, reverberant audio into clean, clear signals.

##  Key Highlights
- **Custom 2D CNN Architecture**  
  Designed an end-to-end neural network optimized for processing spectrograms and performing dereverberation.

- **Condition-Aware Training**  
  The model leverages the **Mean T60 (Reverberation Time)** as additional input, making it acoustically aware and capable of adapting to different room conditions.

- **Spectrogram-Based Approach**  
  Converts audio signals into spectrograms, enabling the model to perform audio enhancement as an image-to-image translation task.

- **Efficient Data Pipeline**  
  Structured Python scripts to load, preprocess, and manage audio data and metadata from CSV files, ensuring reproducibility.

##  Technologies Used
- **PyTorch** – Deep learning framework for model development and training  
- **NumPy & pandas** – Data manipulation and handling of audio metadata  
- **SciPy & Matplotlib** – Signal processing and visualization of results  

##  Outcome
The condition-aware model showed significant improvements in dereverberation performance across different reverberation settings, demonstrating the importance of acoustic context in ML-based audio processing.

---

