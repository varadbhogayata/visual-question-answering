# Visual-Question-Answering
The Intelligent system which gives answer to an Image and a Natural Language Question related to image. This is a simple updated demo of VQA by [VQA_Demo](https://github.com/iamaaditya/VQA_Demo/) which uses pretrained models (VGG, VQA) to answer a given question.

# Model Architecture
The arhitecture behind the implementation is based on the model proposed in this[paper](https://arxiv.org/pdf/1505.00468v6.pdf)

![LSTM + Q Model](https://github.com/varadbhogayata/Visual-Question-Answering/tree/master/Images/LSTM+Q.png)

# Dependencies
1. Keras
2. Tensorflow
3. Scikit-learn
4. Spacy
5. VGG-16 pretrained weights

# Run
Put image in the data/ directory to test the image on this model, after run this file: 

python VQAdemo.py

