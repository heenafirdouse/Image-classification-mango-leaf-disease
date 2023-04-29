# Image-classification-mango-leaf-disease
"Downloading and Unzipping a Kaggle Dataset in Google Colab"

Install the Kaggle package using pip: !pip install kaggle

Upload your Kaggle API key (kaggle.json) to Google Colab: from google.colab import files files.upload()

Create a directory for your Kaggle API key: !mkdir ~/.kaggle

Move your Kaggle API key into the newly created directory: !cp kaggle.json ~/.kaggle/

Set permissions for your Kaggle API key: !chmod 600 ~/.kaggle/kaggle.json

Download the Kaggle dataset using the Kaggle CLI:!kaggle datasets download -d aryashah2k/mango-leaf-disease-dataset

Unzip the downloaded dataset: !unzip /content/mango-leaf-disease-dataset.zip
