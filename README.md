# ECG Heartbeat Classification Project
This project implements a model based on the [paper](https://arxiv.org/pdf/1805.00794). The authors propose a deep convolutional neural network (CNN) for ECG heartbeat classification, aiming for robust performance in distinguishing five arrhythmia types as per the AAMI EC57 standard. Furthermore, they introduced a transferable learning approach, enabling the model to generalize to myocardial infarction (MI) classification.

### Key Highlights from the Paper:
- Model: Deep CNN architecture for ECG classification.
- Datasets: [MIT-BIH arrhythmia dataset](https://www.physionet.org/content/mitdb/1.0.0/) and [PTB Diagnostic ECG database](https://www.physionet.org/content/ptbdb/1.0.0/) (PhysionNet).
- Performance: Achieved 93.4% accuracy for arrhythmia classification and 95.9% for MI classification.

- Arrhythmia: A cardiac condition characterized by irregularities in heart rhythm due to atypical electrical conduction within the myocardium.
- Myocardial Infarction (MI): Also known as acute myocardial infarction (AMI), it occurs when ischemia leads to necrosis of heart tissue, typically due to an obstructed coronary artery.
- Electrocardiogram (ECG): An ECG is a 1D signal that records the heart's electrical activity over time, capturing voltage changes across leads. This trace helps identify key features like P waves and QRS complexes for diagnosing arrhythmias and myocardial infarction.

In this project, we are utilizing an [annotated dataset](https://www.kaggle.com/datasets/shayanfazeli/heartbeat) that provides labeled ECG recordings, allowing for supervised learning in the classification of heart conditions such as arrhythmias and myocardial infarction. 

Results from our model evaluations:
### Arrhythmia Classifier
- Test Accuracy: 0.9091
- F1 Score: 0.9101

### Myocardial Infarction (MI) Model
- Accuracy: 0.8815
- Overall F1 Score: 0.8831
