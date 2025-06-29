## How to Run

### 1. Install Requirements

```bash
pip install emoji numpy pandas keras scikit-learn
```

### 2. Prepare Data

Ensure the following files are present in the working directory:
- `train_emoji.csv`
- `test_emoji.csv`
- `glove.6B.50d.txt`

You can download GloVe from [https://nlp.stanford.edu/projects/glove/](https://nlp.stanford.edu/projects/glove/)

### 3. Run the Notebook

Open the notebook in Jupyter or any compatible environment:

```bash
jupyter notebook Emoji-Predictor.ipynb
```

---

## Example Output

```
I love you ❤️
He is very sad 😞
Let us play baseball ⚾
I eat food 🍴
```

---

## Features

- Uses a dictionary of emojis mapped to textual labels.
- Converts text to vector representation using GloVe.
- Trains a neural network for multi-class classification.
- Evaluates accuracy on a test set.
- Displays emoji predictions alongside input sentences.

---

## License

This project is provided for educational purposes and does not include licensing for GloVe embeddings, which are distributed by Stanford NLP under their own terms.
