# Network Traffic Classification with Machine Learning

## Abstract
This report presents a comprehensive analysis of network traffic classification focusing on machine learning models using the N-BaIoT dataset, comprising benign and attack traffic. The methodology involves data processing, model selection, training, and evaluation using algorithms such as Logistic Regression, Random Forest, Isolation Forest, Support Vector Machine (SVM), and Naive Bayes. Performance metrics are analyzed, providing insights into model effectiveness and limitations.

## Introduction
IoT devices, due to their vulnerabilities, are susceptible to Denial of Service (DoS) attacks, making them potential targets for botnet attacks. The increasing prevalence of IoT devices has led to a rise in botnet attacks, posing challenges for detection and mitigation.

## Objectives
The objectives include understanding the N_BaIoT dataset, implementing data mining techniques for botnet attack detection, and evaluating algorithms for real-time monitoring of IoT devices.

## Literature Review
Existing literature on supervised detection of IoT botnet attacks, fuzzy rule interpolation, and machine learning for botnet attack detection in IoT devices serves as the foundation for enhancing detection capabilities.

## Dataset
The N-BaIoT dataset comprises traffic data from nine IoT devices, containing both benign and attack traffic categorized into ten classes of attacks. Statistical features extracted from packet streams provide rich data for analysis.
Download it from here[N-BaIoT dataset](https://archive.ics.uci.edu/dataset/442/detection+of+iot+botnet+attacks+n+baiot)

## Methodology
### Data Processing
- Data Collection and Loading
- Data Combination
- Data Imbalance Handling
- Feature Selection

### Model Selection
- Logistic Regression
- Random Forest Classifier
- Isolation Forest
- Naive Bayes
- One-Class SVM

### Model Training
- Training selected models on prepared datasets

### Model Evaluation
- Confusion matrices construction
- Performance metrics calculation (precision, recall, accuracy)

## Output Generated
### Random Forest Classifier
- Confusion matrix analysis
- Precision, recall, accuracy metrics

### Isolation Forest
- Confusion matrix analysis
- Performance metrics

### Naïve Bayes
- Confusion matrix analysis
- Performance metrics

## Explanation of Output
Performance analysis highlights the robustness of Random Forest, followed by Isolation Forest and Naive Bayes.

## Future Work
Continuous refinement of detection models, exploration of additional features, and integration of real-time threat intelligence are suggested for creating more robust detection systems.

## Conclusion
Machine learning algorithms, particularly Random Forest, show promise in detecting IoT botnet attacks. Continuous monitoring and improvement of models are essential for addressing evolving attack strategies and strengthening IoT ecosystem security.

