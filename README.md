# Application of Deep Learning for Breast Cancer Metastasis Detection in Sentinel Lymph Node Biopsies
## Author: Manuel Cossio
## Director: Dr. Laura Igual


### Link to dataset
It's necessary to download the dataset and make it available in the Google Drive directory where the Colab notebooks are going to be executed.

[Dataset SNL](https://drive.google.com/file/d/1psav3-ACuMjTVkvqXQBic8XtSV6YilcY/view?usp=sharing)

## Sections
### 1. Data exploratory analysis

[Data exploratory analysis notebook](https://github.com/cossiomanuel/Thesis_files/blob/main/Data_analysis.ipynb)

This notebook provides the code for the data exploratory analysis. 

### 2. Classification with hand-crafted features and shallow classifiers

[Hand-crafted features classification notebook](https://github.com/cossiomanuel/Thesis_files/blob/main/Classification_hand_crafted.ipynb)

This notebook provides the code to:
* Produce the handcrafted features
  * Color histograms
  * Mean brightness
* Classify with linear classifiers
  * Support Vector Classifier
  * Stochastic Gradiend Descent
* Classify with non-linear classifiers
  * Random Forest Regressor

### 3. Classification with Deep Learning

[Deep Leaning classification notebook](https://github.com/cossiomanuel/Thesis_files/blob/main/Deep_learning_classification.ipynb)
  
This notebook provides the code to:
* Data augmentation
* Outlier extraction
* Trasnfer learning architectures
* Explainability 
  * Automatic feature extraction
  * Gradient-Weighted Class Activation Mapping (Grad-CAM)



### Consulted resources
[Complete beginner's guide](https://www.kaggle.com/gomezp/complete-beginner-s-guide-eda-keras-lb-0-93)

[CNN Nasnet Mobile](https://www.kaggle.com/CVxTz/cnn-starter-nasnet-mobile-0-9709-lb)

[Baseline Keras CNN - ROC - FAST](https://www.kaggle.com/fmarazzi/baseline-keras-cnn-roc-fast-10min-0-925-lb)

[ML pipeline](https://www.kaggle.com/qitvision/a-complete-ml-pipeline-fast-ai)
