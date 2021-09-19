#install conda
Goto https://docs.conda.io/en/latest/miniconda.html
bash [proper installer]
#install tensorflow2.0 and all dependencies
conda env create --force --file environment.yml
source activate climate-ai
