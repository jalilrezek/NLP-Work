# CS 601.471/671: Self-supervised Models
## Homework 1: Text Classification with PyTorch and Word Embeddings

### Overview
In this project, I 
- built a simple text classifier with Pytorch for sentiment classification, and tested its performance on a database of movie reviews.
- explored different word representational choices (i.e. pre-trained word embeddings) and their effects on the performance of the classifier.

## Features
- A custom-built text classifier in PyTorch
- Comparative analysis of different word representation techniques
- Evaluation metrics and performance analysis
- Modular design for easy experimentation with different architectures

## Installation

This project uses Python 3.10.13. I recommend using Anaconda to manage the Python environment and dependencies.

1. First, install [Anaconda](https://www.anaconda.com/download#downloads) for your operating system:
   - [Windows Installation Guide](https://docs.anaconda.com/free/anaconda/install/windows/)
   - [macOS Installation Guide](https://docs.anaconda.com/free/anaconda/install/mac-os/)
   - [Linux Installation Guide](https://docs.anaconda.com/free/anaconda/install/linux/)

2. Create a new environment:
```bash
conda create -n sentiment_analysis python=3.10.13
```

3. Install dependencies:
```bash
conda activate sentiment_analysis
pip install -r requirements.txt
```

## Usage
You can test specific parts of the code by uncommenting the corresponding lines in main.py and running main.py.
Running the entire script will train the model and generate evaluation charts.


## Project Structure
```
.
├── main.py          # Main execution script
├── model.py          # Model implementations
└── requirements.txt # Project dependencies
```
I have also included sample charts showing the results when I ran the model myself.
