# Character-Level Language Modeling Playground

This project is a hands-on playground for experimenting with character-level language models using PyTorch.  
The main focus is on **learning by building models from scratch** — implementing forward and backward passes manually, rather than relying on high-level built-in functions.  
The project includes Jupyter notebooks for exploring and visualizing different character-level models, designed to generate names and analyze character sequences.

## Project Structure

- `code/`
  - `bigram_probabilistic_model.ipynb`: Notebook for the bigram probabilistic model.
  - `bigram_1NN_model.ipynb`: Notebook for the bigram model using a single neural network layer.
  - `mlp_char_level_model.ipynb`: Notebook for the MLP character-level model using 3 characters as context to predict the next one.
- `data/`
  - `names.txt`: Dataset of names, one per line, used for training and sampling.

## How to Use

1. Install dependencies: `pip install numpy matplotlib torch` (or use your preferred environment)
2. Open and run the notebooks for interactive exploration and visualization.

## Models Included
- Bigram Probabilistic 
- Bigram model using single layer neural network
- MLP Character-Level 

## Suggested Project Title
**MakeMore: Character-Level Language Modeling Playground**

This title reflects the project's focus on generating more names and experimenting with various character-level models.

---
Feel free to update this README with more details as you add new notebooks, datasets, or results!
