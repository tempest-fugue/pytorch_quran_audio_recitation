# Pytorch Quran Audio Recitation Multiclassifier
This notebook uses a dataset of audio recordings of recitations of the Quran to create a multiclassifier capable of recognizing the speaker of a recording. As such, this notebook converts audio recordings into spectograms for a PyTorch model to train, validate, and test the model's effectiveness.

Dataset is accessible through the following. The dataset is too large to save via GitHub.

```
!pip install opendatasets --quiet
import opendatasets as od
od.download('http://www.kaggle.com/datasets/mohammedalrajeh/quran-recitations-for-audio-classification', force=False)
```

Quick Start:
- Clone the repository:
'''
git clone https://github.com/your-username/quran-audio-classifier.git
cd quran-audio-classifier
'''
- Install dependencies:
'''
pip install -r requirements.txt
'''

- Launch the notebook:
'''
jupyter notebook Quran_Audio_Classifier.ipynb
'''
### Confusion Matrix for Final Model on Test Set

![Confusion Matrix](visualizations/confusion_matrix.jpeg)


## Plots for Model
![Output Plots](visualizations/output_plots.jpeg)
