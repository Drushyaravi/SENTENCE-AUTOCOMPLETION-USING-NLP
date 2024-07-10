# SENTENCE-AUTOCOMPLETION-USING-NLP

## Overview
This project is a Python-based NLP (Natural Language Processing) mini-project developed as part of the DRUSHYA_NLP lab. The project utilizes the SwiftKey dataset, which contains 4 million tweets, blogs, and news articles, for text generation and language modeling tasks.

## Dataset
The dataset used in this project is the SwiftKey dataset, which includes:
- **Tweets**
- **Blogs**
- **News articles**

Total dataset size: 4 million samples.

## Project Features
- **Data Preprocessing:** Cleaning and preparing text data for analysis.
- **Text Generation:** Building models to generate coherent text based on input prompts.
- **Language Modeling:** Training models to understand and predict text patterns.
- **Evaluation:** Assessing model performance using appropriate metrics.

## Installation
To run this project, you need to have Python installed. You can install the required packages using `pip`:

```bash
pip install -r requirements.txt
```

## Usage
After setting up the environment, you can execute the main script to run the project:

```bash
python main.py
```

Make sure you have the dataset files placed in the correct directory as specified in the `config.py` file.

## Directory Structure
```
DRUSHYA_NLP_LAB_MINI_PROJECT/
│
├── data/
│   ├── tweets.csv
│   ├── blogs.csv
│   └── news.csv
│
├── notebooks/
│   ├── data_preprocessing.ipynb
│   ├── model_training.ipynb
│   └── evaluation.ipynb
│
├── src/
│   ├── data_preprocessing.py
│   ├── model.py
│   ├── text_generation.py
│   └── evaluation.py
│
├── config.py
├── main.py
├── requirements.txt
└── README.md
```

## Contributing
Feel free to fork the repository and submit pull requests with improvements or fixes. Please ensure that you follow the project's coding standards and include tests for your changes.
