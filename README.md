# **Customer Churn Prediction Using Artificial Neural Networks (ANN)**  

## **Overview**  
This project focuses on predicting customer churn using a deep learning model built with Artificial Neural Networks (ANN). The final model is deployed using Streamlit for easy accessibility.  

---

## **Steps Involved**  

### **1. Data Preprocessing**  
- **Label Encoding**: Converted categorical features into numeric labels.  
- **One-Hot Encoding**: Applied to avoid ordinal relationships in multi-class categorical variables.  
- **Standard Scaling**: Scaled numerical features to improve model convergence.  

### **2. Building the ANN**  
- Designed a dense ANN architecture with input, hidden, and output layers.  
- Used **ReLU** activation for hidden layers and **Sigmoid** activation for the output layer.  

### **3. Compiling the Model**  
- **Loss Function**: Binary Cross-Entropy.  
- **Optimizer**: Adam.  
- **Metrics**: Accuracy.  

### **4. Model Optimization**  
- **TensorBoard**: Used for monitoring training and validation performance.  
- **Early Stopping**: Configured to stop training when validation loss stops improving.  
- **Callbacks**: Saved the best-performing model automatically.

### **5. Model Training**  
Trained the ANN on the processed dataset and evaluated it using validation data.  

### **6. Deployment with Streamlit**  
Deployed the trained model as an interactive web app, enabling users to 
