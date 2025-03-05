# inceptionv2
# banana-disease-detection-inceptionv2
# InceptionV2-Based Banana Plant Disease Detection  

## Overview  
This project implements **InceptionV2**, a deep learning model for **banana plant disease detection** using leaf images. InceptionV2 enhances feature extraction by using **multiple kernel sizes (1x1, 3x3, 5x5) simultaneously**, making it **efficient and accurate** for detecting various plant diseases.  

## Features  
✅ **High-Accuracy Disease Detection** – Identifies banana plant diseases with precision.  
✅ **Multi-Scale Feature Extraction** – Uses multiple convolutional filters to detect different disease patterns.  
✅ **Optimized for Speed & Efficiency** – Faster than standard CNN models like ResNet.  
✅ **Real-Time Deployment Ready** – Works on cloud, mobile, and IoT-based applications.  

## Dataset  
The model is trained on a dataset containing banana leaf images categorized into:  
- **Healthy Leaves**  
- **Diseased Leaves** (Black Sigatoka, Fusarium Wilt, Banana Bunchy Top Virus, etc.)  

## Workflow  
### **1. Data Preprocessing**  
- Load high-resolution banana leaf images.  
- Resize images to **299×299 pixels** (InceptionV2 input size).  
- Apply **image augmentation** (rotation, flipping, contrast adjustment) to improve generalization.  

### **2. Model Architecture (InceptionV2)**  
InceptionV2 improves on the original **Inception model** by:  
- **Using Factorized Convolutions** to reduce computational cost.  
- **Batch Normalization** for stable training and faster convergence.  
- **Efficient Grid Size Reduction** to maintain feature map dimensions.  

### **3. Training the Model**  
- **Loss Function**: Categorical Cross-Entropy  
- **Optimizer**: Adam (Adaptive Learning Rate)  
- **Evaluation Metrics**: Accuracy & Loss on Training/Validation Set  

### **4. Classification & Prediction**  
- The trained model classifies banana leaf images into **disease categories**.  
- Provides **confidence scores** for predictions.  
- Can be integrated into **mobile apps, web platforms, and IoT devices** for real-time detection.  

## Installation  
1. Clone the repository:  
   ```bash
   git clone https://github.com/yourusername/inceptionv2-banana-disease-detection.git
   cd inceptionv2-banana-disease-detection
Install dependencies:
bash
Copy
Edit
pip install -r requirements.txt
Train the model:
bash
Copy
Edit
python train.py
Run inference on a sample image:
bash
Copy
Edit
python predict.py --image sample_leaf.jpg
Results
Achieved high accuracy in detecting banana plant diseases.
Faster inference time compared to traditional CNN models.
Future Improvements
🔹 Train on larger datasets for improved generalization.
🔹 Optimize for edge computing & mobile deployment.
🔹 Implement real-time disease monitoring with drones & IoT sensors.
