# parkinson-s-classsification
Here’s the README with a new title:  

---

# **Parkinson’s Disease Classification Using Attention-Based CNNs**  

## **Overview**  
This project applies deep learning techniques to classify Parkinson’s disease from spiral drawings. It utilizes **InceptionV3** and **Xception** architectures, integrated with an **Attention Mechanism**, to enhance feature extraction and classification performance.  

## **Dataset**  
The dataset consists of images of spiral drawings labeled as:  
- **Healthy**  
- **Parkinson’s**  

These images undergo preprocessing before being used for training, validation, and testing.  

## **Methodology**  
- Data augmentation and preprocessing  
- Splitting into **Training (80%)**, **Validation (10%)**, and **Testing (10%)**  
- Implementing **InceptionV3** and **Xception** models with Multi-Head Attention  
- Fine-tuning with Adam optimizer and binary cross-entropy loss  
- Performance evaluation using **Accuracy, Precision, Recall, F1-Score, and Confusion Matrix**  

## **Model Architecture**  
The models are enhanced with:  
- **Pretrained CNN Backbones:** InceptionV3 and Xception  
- **Multi-Head Attention Mechanism**  
- **Batch Normalization, Dropout, and Gaussian Noise**  
- **Sigmoid activation for binary classification**  

## **Results**  
- InceptionV3 achieved **100% accuracy** on the test set.  
- Xception achieved **88% accuracy**, with slightly lower performance on Parkinson’s cases.  
- Comparative evaluation is visualized using bar plots.  

## **Installation**  
To run this project, install the dependencies:  

```bash
pip install tensorflow numpy pandas matplotlib seaborn scikit-learn
```  

## **Usage**  
1. Clone the repository:  
   ```bash
   git clone https://github.com/yourusername/parkinsons-detection.git
   cd parkinsons-detection
   ```  
2. Run the preprocessing and training scripts:  
   ```bash
   python train_model.py
   ```  
3. Evaluate the model:  
   ```bash
   python evaluate.py
   ```  

## **Results Visualization**  
- **Accuracy and Loss Graphs**  
- **Confusion Matrix**  
- **Comparative Performance of InceptionV3 vs. Xception**   

## **License**  
This project is licensed under the MIT License.  
