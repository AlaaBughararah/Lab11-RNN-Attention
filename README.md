# Lab 11: Attention with RNN

An NLP lab exploring attention weights in a PyTorch RNN for question classification.

## Dataset
The dataset contains 168 questions organized into 12 answer groups.

## Workflow
- Preprocess questions using tokenization and padding.
- Run the provided RNN with attention.
- Visualize attention weights for three questions.
- Compare attention for two questions with similar meanings.

## Observations
For “What’s your age?” and “How old are you?”, the highest-attention words among the displayed tokens were “age” and “old.” These words relate to the same topic despite the different wording.

The provided model also assigns attention to padding positions, which are omitted from the word charts.

## Tools
Python, PyTorch, TensorFlow/Keras, pandas, and Matplotlib.

## Acknowledgment
The base model and training code were provided by the course instructor. The lab tasks extend the attention visualizations and discuss the observed results.
