# Cloud Computing for Data Science — Week 7 Lab

[![Python](https://img.shields.io/badge/Python-3.10%2B-3776AB?logo=python&logoColor=white)](https://www.python.org/)
[![Google Colab](https://img.shields.io/badge/Google-Colab-F9AB00?logo=googlecolab&logoColor=white)](https://colab.research.google.com/)
[![scikit-learn](https://img.shields.io/badge/scikit--learn-ML-F7931E?logo=scikitlearn&logoColor=white)](https://scikit-learn.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

A beginner-friendly teaching repository for learning how cloud notebooks support practical data-science workflows. Students inspect a cloud runtime, configure optional GPU access, explore the Iris dataset, train and evaluate a machine-learning model, and persist the trained model to Google Drive.

## Learning outcomes

After completing this lab, students can:

- describe cloud computing and common data-science use cases;
- compare Google Colab, Amazon SageMaker, and Azure Machine Learning;
- inspect CPU, memory, disk, and optional GPU resources in Colab;
- install and import Python packages in a cloud notebook;
- load, explore, and visualize a dataset;
- train and evaluate a reproducible Random Forest classifier; and
- save, reload, and use a trained model from Google Drive.

## Repository contents

| Resource | Purpose |
| --- | --- |
| [`Lab_Cloud_Jupyter_Setup.ipynb`](Lab_Cloud_Jupyter_Setup.ipynb) | Main hands-on Colab lab with guided explanations and exercises. |
| [`LECTURE_Cloud_Computing_Easy_English.docx`](LECTURE_Cloud_Computing_Easy_English.docx) | Accessible lecture notes for cloud-computing concepts. |
| [`Session35_Project_Work_Session2.docx`](Session35_Project_Work_Session2.docx) | Follow-up project session on feature engineering and model selection. |
| [`portfolio.html`](portfolio.html) | Responsive data-science portfolio template for student projects. |
| [`index.html`](index.html) | Professional repository landing page that links all learning resources. |
| [`requirements.txt`](requirements.txt) | Python dependencies for running the ML portions locally. |

## Run the lab in Google Colab

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/sohailblockchain/ds-week7-cloud-computing-lab/blob/main/Lab_Cloud_Jupyter_Setup.ipynb)

1. Select the **Open in Colab** badge above.
2. In Colab, choose **File → Save a copy in Drive**.
3. Run each cell in order and read the explanation before continuing.
4. If required, choose **Runtime → Change runtime type** and select an available accelerator.
5. Complete at least two bonus challenges and save your work.

> Colab resources are dynamic. GPU type, memory, availability, usage limits, and session duration can vary. The core Iris exercise works on CPU and does not require a GPU.

## Run locally

```bash
git clone https://github.com/sohailblockchain/ds-week7-cloud-computing-lab.git
cd ds-week7-cloud-computing-lab
python -m venv .venv
```

Activate the virtual environment:

```bash
# Windows (Git Bash)
source .venv/Scripts/activate

# macOS or Linux
source .venv/bin/activate
```

Install dependencies and open Jupyter:

```bash
python -m pip install --upgrade pip
python -m pip install -r requirements.txt
jupyter lab
```

Google Drive mounting uses `google.colab` and therefore only runs inside Colab. When working locally, save the model to a local path instead.

## Lab workflow

1. Inspect the cloud machine.
2. Check optional GPU access.
3. Mount Google Drive.
4. Install an additional library.
5. Load and inspect the Iris dataset.
6. Visualize relationships between features.
7. Create a stratified train/test split.
8. Train and evaluate a Random Forest model.
9. Save, reload, and test the model.

## Student submission

- Complete all required notebook sections.
- Attempt at least two bonus challenges.
- Rename the notebook to `Lab32_Cloud_YourName_RollNumber.ipynb`.
- Restart the runtime and run all cells before submission.
- Confirm there are no unexpected errors or exposed private Drive files.
- Submit the notebook according to the instructor's LMS instructions.

## Responsible cloud use

- Never commit passwords, API keys, access tokens, or private datasets.
- Confirm that you are allowed to upload a dataset before placing it in cloud storage.
- Stop paid cloud resources when they are no longer required.
- Treat notebook outputs as part of the submission and remove sensitive information.
- Do not load untrusted `.pkl` or `joblib` files because serialized Python objects may execute unsafe code.

## Instructor guidance

A suggested 75-minute delivery plan:

| Activity | Time |
| --- | ---: |
| Cloud concepts and platform comparison | 20 minutes |
| Runtime and accelerator demonstration | 10 minutes |
| Guided notebook lab | 35 minutes |
| Review, questions, and challenges | 10 minutes |

## Technology stack

- Python 3
- Google Colab / JupyterLab
- pandas
- seaborn and Matplotlib
- scikit-learn
- joblib
- Yellowbrick

## Author

**Sohail Ahmed**

Senior Software Engineer | Blockchain Engineer | Technical Instructor

[GitHub](https://github.com/sohailblockchain)

## License

This project is available under the [MIT License](LICENSE). Educational examples and third-party services remain subject to their respective terms.
