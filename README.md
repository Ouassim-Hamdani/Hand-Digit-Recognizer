# AI University Project: Classifying Hand-written Digits

This project develops an Ensembled deep learning model to classify hand-written digits

**Key Features:**

* Implements VGG19 & ResNET50 finetunned models.
* Achieves an accuracy of 99.0% on the test dataset.
* Provides insights into the key factors from data laoding all the way to deployment

**Installation:**

1. Clone the repository: `git clone https://github.com/Ouassim-Hamdani/Hand-Digit-Recognizer.git` or extract zip.
2. Install dependencies: `pip install -r requirements.txt` or `make install`  if you have `make` installed
3. Run the main script: `python src/main.py` or `make run`

For a detailed description, analysis, and results, please refer to the full report: [report.md](report/report.md) or report.pdf in `report/report.pdf`.


**Project Folder Architecture**

```
├── notebooks
│   └── training_notebook.ipynb       # Jupyter notebook for training the model.
├── models
│   └── RESNET50.keras                # Trained ResNET50 Keras model.
│   └── VGG19.keras                   # Trained VGG19 Keras model.
├── data
│   └── train.csv                     # Dataset used for training (CSV format).
│   └── test_gen.csv                  # Generated Dataset used for testing (CSV format).
├── report
│   ├── report.pdf                    # Project report (PDF).
│   ├── report.md                     # Project report (Markdown).
│   ├── report.html                   # Project report (HTML).
│   └── figures                       # Figures Folder used in the report.
├── src
│   ├── main.py                       # Main script for running the project & visualizing.
│   ├── model.py                      # Ensembled Model architecture, class and prediction functions.
│   └── utils.py                      # Utility functions.
├── Makefile                          # Shortcuts for commands to build & run project.
└── requirements.txt                  # Python packages required to run the project.
```


**Author :** Ouassim HAMDANI

**Class :** Master 1 IIA - Techniques d’apprentissage artificiel