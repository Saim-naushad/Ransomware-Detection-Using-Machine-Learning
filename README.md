# Ransomware-Detection-Using-Machine-Learning

## Project Description
This project focuses on developing a machine learning-based model to detect and classify ransomware network traffic. The dataset used in this project contains various network traffic features, and the primary goal is to predict whether the traffic is benign, suspicious, or an attack. The model aims to assist in proactive cybersecurity efforts by identifying potential ransomware threats before they cause significant damage.

The prediction layer of the model categorizes traffic into three classes:

1. S (Safe): Benign or non-malicious network traffic.
2. SS (Suspicious): Potentially suspicious traffic that warrants further investigation.
3. A (Attack): Confirmed malicious or ransomware-related traffic.

### Technologies used within the project
* TensorFlow/Keras was used for the model architecture and training because of its flexibility and efficiency in deep learning tasks.
* Pandas and Numpy were employed for data preprocessing and analysis.
* Matplotlib and Seaborn were chosen for visualizing the performance metrics, confusion matrix, and dataset distribution.
* Scikit-learn was chosen for splitting data into training, validation and test set, and evaluating model performance.

### Challenges faced during the compilation of the project
**Scaling and  Normalizing Dataset** < br / >
Ensuring that the input features were on a similar scale was an essential part of training a robust neural network. < br / >

**Hyperparameter Tuning** 

Finding the right combination of hyperparameters (e.g., learning rate, batch size, number of layers) was a time consuming task required for optimal model performance. 

**Feature Selection**

Understanding the relationship between the input/ feature layers and the output layer required extensive visualization of the dataset. 
