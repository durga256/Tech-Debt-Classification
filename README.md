# Tech-Debt-Classification

The goal of this project is to analyse commit messages to classify whether that specifc commit includes Technical Debt or not. While this relies on Developer cooperation to provide comprehensive commit messages, this project proves itself useful in managing such TD in large projects(open source for example). Automatic classification can help manage TD in older and more mature projects where proper guidelines were not established to track Technical Debt. 

# Dataset

The dataset is too large to be uploaded to github. A representational dataset is uploaded here with the file name [vs_code_TD_dataset.csv](https://github.com/durga256/Tech-Debt-Classification/blob/main/vs_code_TD_dataset.csv)

# BERT Model

The file [VS_code_Train_30TD.ipynb](https://github.com/durga256/Tech-Debt-Classification/blob/main/VS_code_Train_30TD.ipynb) implements DeBerta as mentioned in the our base paper <br /> [Technical Debt Classification in Issue Trackers using Natural Language Processing based on Transformers](https://ieeexplore.ieee.org/document/10207085) 

The precision and accuracy scores for the Positive and Negative classes are given below

![image](https://github.com/durga256/Tech-Debt-Classification/assets/41239586/37efe4d5-981c-4f52-b137-a46937066535)

# LSTM


