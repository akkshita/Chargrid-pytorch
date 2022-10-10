
## Installation
After cloning this repository

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install the requirements.

```bash
pip install -r requirements.txt
```
Copy `env.sample` to `.env`
Then add folder paths for the dataset in `.env` file


## Usage
Run following to preprocess the dataset

```bash
python -m data_pipeline.preprocessing
python -m data_pipeline.preprocessing_bis
python -m data_pipeline.preprocessing_ter
```

Once you have data preprocessed run `train.py`.
```bash
python train.py
```
Or for resumable training run 
```bash
python resumable.py
```
