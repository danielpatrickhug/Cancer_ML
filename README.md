# Cancer_ML
# Machine Learning Algorithms Against Cancer

#### CancerNet_1: Convolution Neural Network Model using Tensorflow(Keras) and Breast Histopathology Images dataset to predict Invasive Ductal Carcinoma in mammogram images
- Dataset: https://www.kaggle.com/paultimothymooney/breast-histopathology-images
- Trained on Google colab free GPU
- Accuracy: 85%

#### CancerNet_2: CNN Model using Pytorch(FastAI) and the Breast Histopathology Images Dataset to predict Invasive Ductal Carinoma in mammogram images
- Dataset: https://www.kaggle.com/paultimothymooney/breast-histopathology-images
- *High Accuracy I have to update metrics to include a confusion matrices.
- Trained on a NVidia Tesla V100
- Used Transfer learning technique. ie) finetuned a pretrained imagenet NN with cancer data which improved preformance and speed
- Accuracy: 95% in about 2 hours
- In the included notebook I experimented and tested out several different hyper parameter tuning tasks such as
- Learning rate scheduling
- Different batch sizes
- resnet34 vs resnet50
- Batch data augmentation 



