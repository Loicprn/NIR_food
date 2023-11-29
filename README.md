# NIR spetra analysis

Research project from the conference article "A Decision support tool to analyze food properties from near infrared spectroscopy"
This GitHub repository is an explanatory guide to the code used to produce the results obtained on the conference article and will provide a basis for reflection or development of new solutions adapted to specific problems. 

## Set-up & Installation

### Create new environment in Anaconda & Setup 
```bash

#Create new envrionment
conda create --name firstEnv

#Activate environment
conda activate firstEnv

#Install Tensorflow
conda install -c conda-forge tensorflow

#Install ipykernel
conda install -c anaconda ipykernel

#Access kernel from Jupyter Notebook
python -m ipykernel install --user --name=firstEnv

#Install all required package for working with this files
pip install -r requirements.txt

```



## License

[MIT](https://choosealicense.com/licenses/mit/)

## Cite us
Do you use or draw inspiration from this code in your project or research? Please cite us!
