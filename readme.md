## HDB Technical Test Documentation
## Name: Wong Yoke Yong

#### Introduction

There are two submission files:

1. production_etl.ipynb - Part 1
2. AWS Data Architecture.drawio.png - Part 2

#### IDE

Visual Studio Code

#### Setup

Execute in the terminal to prepare the following environments.

```
python -m venv .hdbtechnicaltest
source .hdbtechnicaltest/bin/activate
pip install -r requirements.txt
```

Open the jupyter notebook "production_etl.ipynb"
Select the kernel of the jupyter notebook to be .hdbtechnicaltest

#### Expected Output

Folder "output_files" will be created, with the five datasets
(Raw, Cleaned, Transformed, Failed, Hashed) to be inside this
folder.

If the raw datasets are not downloaded, the files will be
automatically downloaded from data.gov.sg by identification
from the dataset id.