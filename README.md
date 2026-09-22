# BERT Attention Visualizer (CS50 AI)

## What it does
* This is a Python program that uses a pre-trained BERT masked language model (via Hugging Face Transformers and TensorFlow) to predict missing words in text.
* It extracts multi-head self-attention weights from the model layers and automatically generates visual grid diagrams to show how words attend to one another.

## Technologies Used
* Python
* TensorFlow & Hugging Face Transformers
* Pillow (PIL) for image and diagram generation
* Git / GitHub

## How to Run It
* Make sure you have the required Python packages installed by running this in your terminal:
* "```bash"
* pip install tensorflow transformers pillow
* Run the main script: python attention.py
* Type a sentence containing a masked token (e.g., Paris is the [MASK] of France) to see predictions and generate your attention layer images!
