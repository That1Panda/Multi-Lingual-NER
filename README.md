# Multilingual Fine-tuning Project

This project demonstrates how to fine-tune a pre-trained model on a multilingual corpus and evaluate its performance across multiple languages, even on those not included in the fine-tuning process or languages with low resource availability.

## Project Overview

In this notebook-based project, we aim to:

1. Fine-tune a language model on a specific language within a multilingual corpus.
2. Explore the transfer learning effects of this fine-tuning to other languages.
3. Measure how well the model generalizes across languages that were not explicitly used during fine-tuning.

The code and implementation are entirely contained within this Jupyter Notebook, making it easy to follow along, understand, and replicate the steps.


## Languages and Datasets

We fine-tune the model on one or more languages from the 'Xtreme' dataset 'PanX' subset and evaluate its performance on others.


## Usage

To run the project:

1. Open the notebook in Jupyter or any notebook-compatible environment.
2. Follow along with the code, executing the cells step-by-step.
3. The notebook will guide you through data preparation, model loading, fine-tuning, and evaluation.
   
## Results

At the end of the notebook, the evaluation section provides insight into how well fine-tuning on a specific language benefits other languages. Detailed results and performance metrics are provided for each evaluated language.

## Acknowledgments

- [Natural Language Processing with Transformers by Lewis Tunstall, Leandro von Werra, Thomas Wolf](https://www.oreilly.com/library/view/natural-language-processing/9781098136789/) for the Book that guided me through the project

