# Streamline_text_classification_pytorch

This project is a text classification system developed as a proof-of-concept (POC), a company pioneering AI-powered customer service solutions. The goal is to automatically classify customer complaints into categories such as mortgage, credit card, money transfers, debt collection, and more. The project uses deep learning techniques to process textual complaints and assign them to the correct category.

This system is designed to assist support agents by automating complaint triage, improving response efficiency, and reducing manual handling errors.

## 📂 Project Structure

- `notebook.ipynb`: Jupyter notebook containing the complete pipeline for preprocessing, model training, evaluation, and performance reporting.


## 📊 Problem Description

Each input is a textual complaint submitted by a customer. The task is to classify this text into one of several predefined categories, helping to route the case to the appropriate department or agent.

This classification system will:

- Ingest raw complaint text.
- Tokenize and vectorize the input.
- Train a neural network to classify each complaint to a specific label (category).
- Evaluate performance using common classification metrics.

## 🧱 Dataset

- Data consists of customer complaints, each labeled with its corresponding issue type.
- Preprocessing includes tokenization (`nltk`), cleaning, and encoding.
- Dataset is split into training and validation sets using `train_test_split`.

## ⚙️ Dependencies

Ensure the following packages are installed:

```bash
torch
torchmetrics
pandas
scikit-learn
nltk