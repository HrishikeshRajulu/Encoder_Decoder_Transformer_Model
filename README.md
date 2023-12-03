# Encoder_Decoder_Transformer_Model
Description
This project aims to develop an advanced language translation model that translates text from English to Marathi. Utilizing cutting-edge machine learning techniques, the model is designed to handle the complexities of language translation, focusing on maintaining the nuances and contextual relevance in translations.

# Features
Bilingual Translation: Capable of translating between English and Hindi, addressing both linguistic accuracy and cultural context.
Custom Transformer Model: Uses a self-designed transformer model (model.py) for effective and efficient translation tasks.
Dataset Preparation: A dedicated script (dataset.py) for preparing and tokenizing bilingual datasets, ensuring data quality and consistency.
Flexible Training: Includes two training scripts (train.py and train_wb.py) allowing for different training approaches and parameter tuning.
Direct Translation: The translate.py script provides a direct way to translate text using the trained model, simplifying the translation process.
Installation
Prerequisites
Python 3.x
PyTorch
Additional Python libraries as required in the scripts (e.g., torchtext, datasets from Huggingface)
Setup
Clone the repository to your local machine.
Install the required dependencies.
Configure the model parameters in config.py as per your requirements.
Usage
Training the Model
Run python train.py for the standard training process.
Use python train_wb.py for an alternative training method.
# Translating Text
Execute python translate.py followed by the text you want to translate.

