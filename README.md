# Bias Detection Using Interpretability

This project aims to use interpretability for detection of bias in AI/ML models, particularly for models meant for Hate-Speech detection.

The datasets used for this project are:
* **ULI dataset**: https://www.kaggle.com/datasets/akshatwa99/
uli-dataset
* **HateXplain dataset**: https://github.com/hate-alert/HateXplain

The models used for this project are:
* **RoBERTa**: facebook/roberta-hate-speech-dynabench-r4-target
* **mDeBERTa**: MoritzLaurer/mDeBERTa-v3-base-xnli-multilingual-nli-2mil7
* **MuRIL**: google/muril-base-cased

The codes used for fine-tuning the models are in the folder ```training_code```

The fine-tuned models are also saved in: https://www.kaggle.com/datasets/sansahaiiitd/all-models/data

We have also created an app, which can be run by running the code provided in the ```app_code``` folder.

All the ```.ipynb``` files were run in google colab, and minor changes might be required if they need to be run on other platforms.

**Disclaimer:** This is an experimental analysis intended solely for academic purposes. We do not support or advocate for any of the hate speech
examples presented. This work does not intend to offend any religious, cultural, or personal beliefs.