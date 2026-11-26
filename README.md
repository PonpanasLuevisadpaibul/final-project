# Fake News Classification



## Project Description

This project evaluates a fine-tuned BERT text classification model on a labeled dataset of real and fake news articles. It includes exploratory data analysis (EDA) on class balance, article length, and punctuation/digit frequencies, followed by model inference, quantitative evaluation (accuracy, precision, recall, F1-score, and confusion matrix), and qualitative error analysis of misclassified articles. AI assistants were used to assist in generating some parts of the code such as the visualisation and calculations. All code execution and model evaluation were verified.



## Dataset

* **Name:** [GonzaloA/fake\_news](https://huggingface.co/datasets/GonzaloA/fake_news) (hosted on Hugging Face)
* **Splits:** `train` (24,353 rows), `validation` (8,117 rows), and `test` (8,117 rows)
* **Features:**

  * `title`: News headline
  * `text`: Full article body
  * `label`: Binary target (`0` = Fake News, `1` = Real News)

## Model

* **Name:** [adityaG04/fake-news-bert-finetuned](https://huggingface.co/adityaG04/fake-news-bert-finetuned)
* **Architecture:** Fine-tuned BERT sequence classifier (`transformers` text-classification pipeline)
* **Output:** Predicts `LABEL\_0` (Fake) or `LABEL\_1` (Real) with a confidence score



## How to Run the Code

1. Open `24224531_FinalProject_FakeNews.ipynb` in [Google Colab](https://colab.research.google.com/).
2. Run all cells from top to bottom.

