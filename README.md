SigmaML Quiz 4 : CNN practice with CIFAR 100
===================================================

Project Details
---------------

* Training data : https://www.tensorflow.org/api_docs/python/tf/keras/datasets/cifar100/load_data

* Problem Statement : To Build a CNN for classification on the Cifar-100 dataset & perform using the following methods: Building from Scratch, Using a Pre-existing network & Transfer Learning + Fine Tuning.

* Github Repository : https://github.com/maybiswas/SigmaML_CNN
* Shared GDrive : https://drive.google.com/drive/folders/1DAcTNhotpDdtz9vV9pmmjZzcDoKhfAP8?usp=sharing

* Main Notebook : ![CNN_CIFAR100.ipynb](https://github.com/maybiswas/SigmaML_CNN/blob/main/CNN_CIFAR100.ipynb)

* Output Results : ![Results Table](https://github.com/maybiswas/SigmaML_CNN/blob/main/output/CIFAR100_performance_report.csv)
  
|Experiment No.|Experiment Directory|Experiment Title|Accuracy%|
|---|---|---|---|
|1|CIFAR100_SimpleCNN|Simple CNN : Conv2D filters (3x3)(ReLU) + Max Pooling(2x2) + 64 FC layers (ReLU) + 100 FC layers|37.08|
|2|CIFAR100_CNNfromScratch|CNN From Scratch : Conv2D filters (3x3)(eLU) + Max Pooling(2x2) + 1024 FC layers (eLU) + 512 FC layers (eLU)) + 100 FC layers|42.43|
|3|CIFAR100_PretrainedCNN|Pre-Trained CNN : ConvNeXtSmall with Imagenet weights + 512 FC layers (ReLU) + 100 FC layers|47.50|
|4|CIFAR100_TransferLearning|Transfer Learning : ConvNeXtSmall with Imagenet weights + 512 FC layers (ReLU) + 100 FC layers + LR=0.001|11.95|
|5|CIFAR100_FineTuning|Fine Tuning : ConvNeXtSmall with Imagenet weights + 512 FC layers (ReLU) + 100 FC layers + LR=0.00001|36.13|

* Conclusion : Using Pre-Trained CNN model method gave the best accuracy for classification.

