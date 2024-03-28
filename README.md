## install conda <br />
Go to https://docs.conda.io/en/latest/miniconda.html <br />
Then download proper installer for your OS  <br />
`bash [proper installer] ` <br />
## install tensorflow2.0 and all dependencies <br />
`conda create  -n dl_lab tensorflow` <br />
`conda install pillow opencv scipy matplotlib scikit-image scikit-learn pandas jupyterlab numpy` <br />
`conda activate dl_lab` <br />
## Conda environment for the tensorflow transformer tutorial <br />
`conda create -n transformer python==3.10` <br />
`conda activate transformer` <br />
`pip install jupyterlab`<br />
## When we deactivate conda environments <br />
`conda deactivate`
## Dataset <br />
- PM2.5 in South Korea, from 2019 to 2020. 6-hourly <br />
`https://drive.google.com/file/d/1gm0oD6N3puTgV_n0IOwEFTlbn37cvza3/view?usp=sharing`
- Hurricane Dataset <br />
`https://library.ucsd.edu/dc/object/bb94252168`
