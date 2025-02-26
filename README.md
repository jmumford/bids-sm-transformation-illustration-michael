## Transformation History Illustration & bug explainer

A quick illustration of how Transformation History can be used to help check that your regressors are being constructed as intended.

Additionally, I have added a `problem_explainer_003245.ipynb` to explain the root of a bug that was found when a json sidecare for bold files is present in the database.  

### Generate the `.venv` for the notebook using uv
```
uv sync
```


## Do NOT clone ds003245 to run the explainer!  Use the light version I have supplied in Data (otherwise the code for this data set will not work)


## For 000102, 002741 and 003507
If you want to run the notebooks for these datasets, after cloning this repo, do the following (e.g. for 000102)
```
cd data
git clone https://github.com/OpenNeuroDatasets/ds000102.git
```