## Transformation History Illustration

Just a quick illustration of how Transformation History can be used to help check that your regressors are being constructed as intended.

After cloning this repo do the following
```
mkdir data
cd data
git clone https://github.com/OpenNeuroDatasets/ds000102.git
```

Then you'll want to create the .venv that should be used when running the notebook
```
uv sync
```

I'm assuming you're using VSCode?  If so, just back up to the main dirctory (I'm assuming you're still in data) and launch VSCode.

```
cd ..
code ./
``

Then open `transformation_history_example.ipynb` and select the `.venv` as the Python Kernel.  Then things should just run!