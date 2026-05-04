CSCI-544 NLP Final Project Code

Group 36: Jeslyn Yang, Wenwen Han, Ivan Loh, Rachel Lin, Neil Bai

Detection of AI-Generated Text

This project was developed on Google Colab with two different approaches using the same dataset, "Training_Essay_Data.csv", downloaded from Kaggle.

Group36_detectgpt.ipynb contains our recreation of the DetectGPT model. To run the notebook, import the .ipynb file into Google Colab and upload the Training_Essay_Data.csv file into the /content directory. After that, the program will be ready to run. The random state of the program is set to 42 to keep a stable threshold value, but the result and threshold may still vary between 0.13 and 0.14. After running, the program outputs "detectgpt_test_results.csv" for evaluation purposes.

Group36_blstm_cnn.ipynb contains the BiLSTM-CNN model. To run the notebook, import the .ipynb file into Google Colab and upload the Training_Essay_Data.csv file into the /content directory. After that, the program will be ready to run. The random state of the program is also set to 42 to keep the results stable at around 97% accuracy. After running, the program outputs "blstm_cnn_results.csv" and other .csv, .json, and .pt files for evaluation purposes.
