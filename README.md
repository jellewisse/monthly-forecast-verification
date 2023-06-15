# monthly forecast

## setup python environment
conda env create -f environment.yml
this command will install python 3.9 and required packages

## activate environment
conda activate energy39

## add environment to jupyter notebook
python -m ipykernel install --user --name=energy39

## installing cdsapi for downloading SEAS5 forecast
https://cds.climate.copernicus.eu/api-how-to
