# Automated Essay Grading System

This project aims to develop an Automated Essay Grading (AEG) system using machine learning techniques. The system is designed to assist educators by automating the grading process, providing a consistent and efficient way to evaluate written essays.

## Overview

Grading essays is a critical yet time-consuming task in education, especially in large-scale settings such as standardized tests and university assessments. The AEG system leverages advanced machine learning models to automatically grade essays based on their content and structure, helping to reduce the workload of educators and ensure unbiased, consistent grading.

## Dataset

- **Source:** Kaggle ASAP Automated Essay Scoring dataset
- **Size:** 10,685 essays
- **Grades:** Scores ranging from 0 to 6 for each essay

## Preprocessing

The data was preprocessed using the following steps:
1. **Text to Integer Conversion:** Essays were tokenized and converted into sequences of integers.
2. **Padding and Truncating:** Sequences were padded or truncated to ensure uniform length across all inputs.

## Models Implemented

1. **Random Forest:** 
   - Implemented using the Scikit-Learn library.
   - Tuned with 1000 trees and a maximum depth of 1000.
   - Achieved higher accuracy compared to neural networks.

2. **Neural Network:**
   - Implemented using TensorFlow and Keras.
   - Applied with a Softmax activation function.

## Technology Stack

- **Programming Language:** Python 3.0
- **Libraries:**
  - TensorFlow
  - Keras
  - NumPy
  - Pandas
  - Matplotlib
  - Scikit-Learn
- **Development Environment:** Jupyter Notebook

## Performance

- **Random Forest Accuracy:** 68%
- **Neural Network Accuracy:** 45%

## Future Work

The model can be further enhanced by implementing Long Short-Term Memory (LSTM) networks, which are a type of Recurrent Neural Network (RNN). Additionally, plans include deploying the model using Flask to create an online portal where users can input essays and receive grades in real-time.

## Contributors

- **Saurabh Jain** (171342)
- **Sarthak Vinayaka** (171368)

## Acknowledgments

This project was developed under the supervision of **Dr. Pradeep Kumar Gupta**, Associate Professor at the Department of Computer Science and Engineering, Jaypee University of Information Technology.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

This section provides a comprehensive summary of your project, including key details about its purpose, implementation, and future improvements.
