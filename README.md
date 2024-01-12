# Food Classifier - Ceviche & Donuts

## How to Run Predictions

1. If not already in notebook form, convert `food-classification.md` to a notebook using jupytext 
```
jupytext --to notebook food-classification.md
```

2. Update the config yaml `food-classification.yaml` with your imagery & chosen model. It is currently pointing to a set of test images.

3. Run the notebook `food-classification.ipynb`. Note: your yaml must be in the same folder as your notebook

## Assumptions
- Input images are food
