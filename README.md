#  Face Mask Detection Using CNN

## 📌 Project Overview  
This deep learning project uses **Convolutional Neural Networks (CNNs)** to classify images as **"With Mask"** or **"Without Mask"**, helping automate public safety measures.  

## 📊 Dataset  
- **With Mask**: Labeled images of individuals wearing masks  
- **Without Mask**: Labeled images of individuals without masks  

## 🔧 Technologies & Libraries Used  
- **Python**, with:  
  - **Pandas** and **NumPy** for data manipulation  
  - **Seaborn** and **Matplotlib** for visualization  
  - **TensorFlow** and **Keras** for deep learning  
  - **Scikit-learn** for evaluation metrics  

## 🔄 Preprocessing Steps  
- Loaded and labeled images (**1: Mask, 0: No Mask**)  
- Shuffled dataset for better learning  
- Resized images to **64×64 pixels** for model compatibility  
- Split dataset into **training (70%)** and **testing (30%)**  

## 🤖 Model Architecture  
- **Conv2D Layers**: Extract spatial patterns  
- **MaxPooling Layers**: Reduce feature map size  
- **Flatten Layer**: Convert matrices into a vector  
- **Dense Layers**: Fully connected layers for prediction  
- **Sigmoid Activation**: Final layer for **binary classification**  

## 📈 Results & Evaluation  
- **Accuracy** evaluated on test data  
- **Confusion matrix** visualization  
- Model predicts face mask presence with **high accuracy**  

