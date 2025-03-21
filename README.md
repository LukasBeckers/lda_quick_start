# LDA Quick Start

## Installation

The tested python-version for this project is `3.12.6`

(Optional) It is recommended to use a virtual environment (venv) for this project. You can create a venv using the following command: 
```bash
python -m venv .venv
```

Now activate the venv (Windows): 
```bash
.venv/Scripts/activate
```
(Mac/Linux)
```bash
source .venv/bin/activate
```

To install the requirements run 
```bash
pip install -r requirements.txt
```

Now install the ipykernel
```bash
python -m ipykernel install --user --name lda_quick_start 
```