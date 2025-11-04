# Project Overview

This project showcases various Natural Language Processing (NLP) tasks using the Hugging Face `transformers` library. The project is structured as a Jupyter notebook that provides a hands-on walkthrough of core Transformer applications.

<a href="https://colab.research.google.com/github/lk-montoedi/nlp-pipeline-showcase/blob/main/src/nlp_basics.ipynb" target="_parent"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>

**Main Technologies:**

*   Python
*   Jupyter Notebook
*   Hugging Face Transformers
*   Pandas

**Architecture:**

The project consists of a single Jupyter notebook (`nlp_basics.ipynb`) that demonstrates the following NLP tasks:

*   **Text Classification:** Classifying the sentiment of a given text.
*   **Named Entity Recognition (NER):** Identifying and extracting named entities (such as persons, organizations, and locations) from text.
*   **Question Answering:** Answering questions based on a given context.
*   **Summarization:** Generating a concise summary of a long text.
*   **Translation:** Translating text from one language to another.
*   **Text Generation:** Generating text based on a given prompt.

# Building and Running

To run this project, you need to have Python and Jupyter Notebook installed. You also need to install the required libraries by running the following command:

```bash
pip install transformers pandas
```

Then, you can run the Jupyter notebook by navigating to the `src` directory and running the following command:

```bash
jupyter notebook nlp_basics.ipynb
```

# Development Conventions

*   The code is written in a Jupyter notebook, with each NLP task demonstrated in a separate section.
*   The notebook uses the Hugging Face `pipeline` API for easy implementation of the NLP tasks.
*   The results of each task are displayed using Pandas DataFrames.
