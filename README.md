# Spatialproteomics Workshop
To follow this workshop, you first need to download the material by cloning the git repository. You can download the corresponding data from [here](http://www.huber.embl.de/users/matthias/spatialproteomics_workshop_data.tar.gz). Unzip the file and place it into a folder called `data`.

After obtaining the code and the data, you need to set up a virtual environment. You can either do this with conda or venv.


## Instructions for conda
- Create the virtual environment: `conda env create -f environments/environment.yml`
- Activate the environment: `conda activate eccb_env`


## Instructions for venv
- The notebooks were tested on python 3.11. You can check your version using `python --version`. Anything after python 3.9 should work too, but if you run into issues, it is recommended to update your python version.
- Create the virtual environment: `python -m venv eccb_env`
- Activate the virtual environment: `source eccb_env/bin/activate` (on Windows: `eccb_env\\Scripts\\activate`)
- Install packages: `pip install -r environments/requirements.txt`


## Getting help
This tutorial is based on `spatialproteomics`. You can always refer to the [documentation](https://sagar87.github.io/spatialproteomics/index.html) or have a look at the [GitHub repository](https://github.com/sagar87/spatialproteomics/tree/v0.5.4).
