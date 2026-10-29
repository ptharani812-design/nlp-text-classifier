# Task 05 — Deep Learning / NLP Text Classifier with PyTorch

**Student:** Tharani P  
**Department:** Artificial Intelligence and Data Science

## Project overview
A sentiment-analysis pipeline that classifies text as **positive** or **negative** using TF-IDF features and a multi-layer PyTorch neural network.

## Features
- Text vectorization with TF-IDF and unigrams/bigrams
- Train/validation/test split
- Multi-layer neural network with ReLU, Batch Normalization, and Dropout
- Validation-loss monitoring and early stopping
- Training/validation loss and accuracy plots
- Test accuracy, classification report, and confusion matrix
- Unseen text predictions with class probabilities/confidence
- Saved model weights and TF-IDF vectorizer

## Files
- `Task05_NLP_Sentiment_Classifier.ipynb` — main notebook and expected proof
- `requirements.txt` — Python dependencies

## How to run
### Google Colab (recommended)
1. Download this repository as a ZIP or upload the notebook to Google Colab.
2. Run the notebook cells from top to bottom.
3. Confirm that training curves, the classification report, confusion matrix, and sample predictions appear.
4. Save the notebook with outputs and upload it to your public GitHub repository.

### Local Python
Install dependencies:
```bash
pip install -r requirements.txt
```
Then open the notebook in Jupyter Notebook or VS Code and run all cells.

## Dataset note
The notebook generates a balanced, template-based demonstration dataset (1,280 examples) so it runs without external downloads. The high scores reflect the simple synthetic templates and must NOT be presented as real-world performance. For a genuine evaluation, replace the generated examples with a real labeled sentiment dataset, rerun all cells, and report the new results honestly.

## Notebook outputs\nThe saved notebook includes execution outputs, training/validation loss and accuracy plots, a test classification report, a confusion matrix, and confidence-scored sample predictions.\n\n## Submission checklist
- [ ] Run all notebook cells successfully
- [ ] Keep output plots and prediction examples in the notebook
- [ ] Push the notebook and README to a **public** GitHub repository
- [ ] Submit the public repository URL on the task portal
