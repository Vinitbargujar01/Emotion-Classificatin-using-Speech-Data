# Emotion Classificatin using Speech Data

Here's a short and clear README for the uploaded notebook `mars_emotion_class.ipynb` based on a typical structure for an emotion classification project:

---

# Mars Emotion Classification

This Jupyter Notebook implements a deep learning pipeline for **emotion classification** using the **MARS (Multimodal Annotated Recap Scenarios)** dataset. The goal is to predict emotional states from visual and audio data.

## Features

* Multimodal data processing (video + audio)
* Emotion classification into predefined categories
* Deep learning using PyTorch and HuggingFace Transformers
* Model evaluation and performance visualization

## Files

* `mars_emotion_class.ipynb`: Main notebook containing data preprocessing, model training, and evaluation code.

## Dependencies

* Python 3.8+
* PyTorch
* Transformers (HuggingFace)
* NumPy, pandas, scikit-learn
* OpenCV
* Librosa (for audio processing)
* tqdm, matplotlib

Install dependencies with:

```bash
pip install -r requirements.txt
```

## Usage

1. Clone the repository and navigate to the folder.
2. Place the MARS dataset in the appropriate path.
3. Run the notebook `mars_emotion_class.ipynb` cell by cell.

## Output

* Model accuracy and loss plots
* Confusion matrix for emotion prediction
* Optionally saved trained model
