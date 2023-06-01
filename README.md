# Colab GPT Document Semantic Search PoC

## Overview

This app is designed to allow users to easily query PDF documents using OpenAI's GPT-3.5  (ChatGPT) language model. 
The app is designed to be run in Google Colab and utilizes Google Drive for storage and access to PDF documents.
It is only meant for experiementation and to provide a very quick PoC integration.


## How to Use

1. To use the app, navigate to the [run_query.ipynb](https://github.com/svorwerk-dentsu/DocsGPT/blob/main/run_query.ipynb) notebook in the repository.
2. Click on the "Open in Colab" button to open the notebook in Google Colab using this [link](https://colab.research.google.com/github/svorwerk-dentsu/DocsGPT/blob/main/run_query.ipynb).
3. Run the cells in the notebook.
4. When prompted, click on "Connect to Google Drive" and select your Google account. Click "Allow" to permit access to your Google Drive. This will mount your Google Drive in Google Colab.
5. The app will begin downloading and installing any necessary packages.
6. Next, you will be prompted to enter your OpenAI API key.
7. After entering your API key, you will be prompted to upload your PDF file. This file will be saved in your Google Drive in the following address: `/content/drive/MyDrive/repo_path`.
8. Finally, submit your queries (ask your questions) about the uploaded document. Make sure to type "stop" once you have no further questions.
