# **Breast Cancer Classification**  

## **Overview**  
This project uses the Breast Cancer Wisconsin Dataset from scikit-learn to build a deep learning model for classifying breast cancer as malignant or benign. This dataset contains clinical measurements such as mean radius, texture, perimeter, and area of cells. The model leverages fully connected neural networks to perform classification.

### **Features**  
The dataset includes property attributes such as:  

- mean radius	
- mean texture	
- mean perimeter	
- mean area	
- mean smoothness	
- mean compactness	
- mean concavity	
- mean concave points	
- mean symmetry	
- mean fractal dimension	
- radius error	
- texture error	
- perimeter error	
- area error	
- smoothness error	
- compactness error	
- concavity error	
- concave points error	
- symmetry error	
- fractal dimension error	
- worst radius	
- worst texture	
- worst perimeter 
- worst area	
- worst smoothness	
- worst compactness	
- worst concavity	
- worst concave points	
- worst symmetry	
- worst fractal dimension

Dataset Features:

30 numerical features describing cell nuclei.  
569 instances:  
212 malignant (class 0).  
357 benign (class 1).  
  
#### **Approach**  
**Data Preprocessing** : No NULL Values to be handled. All features are in numeric form.   

**Model Architecture**  

Flatten(input_shape = (30,)),# X is in the form if matrix and we will flatten these values in a single 1d array  
Dense(20, activation = 'relu'), # rectified linear unit  
Dense(2 , activation = 'sigmoid')  

**Model Evaluation:**  
- Accuracy on Training Data: 99.30%  
- Accuracy on Testing Data: 96.27%  
- Accuracy on Validation Data: 97.83%

##### **Getting Started** 
Clone the repo and install dependencies.
