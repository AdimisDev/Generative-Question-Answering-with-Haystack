# Generative Question Answering with Haystack

**Description:**
This project demonstrates how to use the Haystack library for Generative Question Answering (QA) in a Jupyter Notebook on Google Colab. It utilizes the Haystack library to perform QA tasks, combining a Dense Passage Retriever and a Sequence-to-Sequence (Seq2Seq) Generator to answer questions. The project is particularly geared towards answering questions based on a set of documents, making it suitable for various information retrieval and QA tasks.

## Features
- Mounting Google Drive to access data.
- Installation of required dependencies and libraries.
- Setting up logging for monitoring.
- Importing and configuring a FAISS Document Store for efficient document storage and retrieval.
- Loading and converting documents from a directory into dictionaries.
- Indexing the documents into the Document Store with embeddings.
- Configuring a Dense Passage Retriever for question and passage embeddings.
- Initializing a Seq2Seq Generator for generative question answering.
- Creating a GenerativeQAPipeline to combine the retriever and generator.
- Defining a function to accept user questions and return generated answers.

## Prerequisites
- Basic understanding of Python and Jupyter Notebooks.
- Access to Google Colab for running the notebook.
- Adequate knowledge of the Haystack library.

## Installation
To run this notebook, you will need to install the required dependencies. Please follow the installation steps provided in the notebook.

## Usage
1. Upload your document files to a directory in your Google Drive.
2. Execute the notebook cells step by step to set up the environment.
3. Enter your questions when prompted, and the notebook will provide generated answers based on the documents you uploaded.

## Acknowledgments
- This project uses the Haystack library, developed by deepset-ai. Visit their GitHub repository for more information: [Haystack](https://github.com/deepset-ai/haystack).
- Pretrained models for Dense Passage Retriever and Seq2Seq Generator are used in this project.

---

# Readme.md

## Generative Question Answering with Haystack

### Overview

This repository contains a Jupyter Notebook demonstrating how to perform Generative Question Answering (QA) using the Haystack library in a Google Colab environment. The project combines a Dense Passage Retriever with a Sequence-to-Sequence (Seq2Seq) Generator to answer user questions based on a set of documents.

### Prerequisites

- Python knowledge.
- Access to Google Colab.
- Familiarity with the Haystack library.

### Installation

1. Clone this repository:

   ```
   git clone https://github.com/adimis-ai/Multiple-Document-Abstractive-Long-Form-Q-A.git
   ```

2. Open the Jupyter Notebook in Google Colab.

3. Follow the installation steps provided in the notebook to install the required dependencies.

### Usage

1. Upload your document files to a directory in your Google Drive.

2. Execute the cells in the notebook one by one to set up the environment, import documents, and configure the QA pipeline.

3. When prompted, enter your questions. The notebook will provide generated answers based on the documents you uploaded.

### Features

- Mount Google Drive to access data.
- Install necessary dependencies.
- Set up logging for monitoring.
- Import and configure a FAISS Document Store for document storage and retrieval.
- Load and convert documents from a specified directory into dictionaries.
- Index the documents into the Document Store with embeddings.
- Configure a Dense Passage Retriever for question and passage embeddings.
- Initialize a Seq2Seq Generator for generative question answering.
- Create a GenerativeQAPipeline to combine the retriever and generator.
- Define a function to accept user questions and return generated answers.

### Acknowledgments

- This project uses the Haystack library developed by deepset-ai. Visit their GitHub repository for more information: [Haystack](https://github.com/deepset-ai/haystack).
- Pretrained models for Dense Passage Retriever and Seq2Seq Generator are used in this project.
