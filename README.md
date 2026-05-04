CSCI-544 NLP Final Project Code

Group 36: Jeslyn Yang, Wenwen Han, Ivan Loh, Rachel Lin, Neil Bai

Detection of AI-Generated Text

This project was developed on Google Colab using two different approaches with the same dataset, "Training_Essay_Data.csv", downloaded from Kaggle.

Environment:
The code is designed to run in Google Colab. To set up the environment, open the notebook in Google Colab and run the setup/import cells at the beginning of the notebook. All required Python packages will be installed or imported inside the notebook. The dataset file, "Training_Essay_Data.csv", should be uploaded to the /content directory before running the code.

Device/System Used:
The experiments were run on Google Colab. It is recommended to use a GPU runtime type. The runtime can vary significantly depending on the Google Colab runtime type used.

DetectGPT:
Group36_detectgpt.ipynb contains our recreation of the DetectGPT model. To run the notebook, import the .ipynb file into Google Colab and upload the Training_Essay_Data.csv file to the /content directory. After that, the program will be ready to run. The random state of the program is set to 42 to keep the threshold value and accuracy stable across multiple runs, but the result and threshold may still vary between 0.13 and 0.14. After running, the program prints the accuracy, score matrices, graphs, and results in the notebook cells. The program also outputs "detectgpt_val_results.csv" and "detectgpt_test_results.csv" for evaluation purposes.

BiLSTM-CNN:
Group36_blstm_cnn.ipynb contains the BiLSTM-CNN model. To run the notebook, import the .ipynb file into Google Colab and upload the Training_Essay_Data.csv file to the /content directory. After that, the program will be ready to run. The random state of the program is also set to 42 to keep the results stable at around 97% accuracy across multiple runs. After running, the program outputs "blstm_cnn_results.csv" and other .csv, .json, and .pt files for evaluation purposes.
