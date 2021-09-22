# Pandas_Introduction_Tutorial
An Introduction to using Pandas.  Intended to give give some basic usage with pandas, and reading from CSV and xlsx files. 

Data for the Putting it all together is sourced from https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/42MVDX&version=6.0
Converted to an xlsx and tabbed by decade

## Installation

Open the command line and navigate to the root folder you wish to install. Then type the following commands:
```bash
git clone https://github.com/mathewrtaylor/Pandas_Introduction_Tutorial.git WordCloud
cd Pandas_Introduction_Tutorial
conda env create -f environment.yml
```
Then start running with these commands:
```bash
source activate Pandas_Introduction_Tutorial
conda install --force-reinstall -y -q --name Pandas_Introduction_Tutorial -c conda-forge --file requirements.txt
jupyter lab
```
## Usage
- Open the Jupyter notebook up in your directory.

## Credits
Thanks to the Pandas team https://github.com/pandas-dev/pandas

## License
[MIT](https://choosealicense.com/licenses/mit/)
