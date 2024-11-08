
##### Create new environment pip : 
`conda create -n myenv  pip`

##### Create new environment: 
`conda create --name myenv`

##### List all existing environments
`conda env list`

##### Create a new environment (e.g., "myenv" with Python 3.9)
`conda create -n myenv python=3.9`

##### Activate an environment
`conda activate myenv`

##### Deactivate the current environment
`conda deactivate`

##### Remove an environment
`conda env remove -n myenv`

##### List installed packages in the current environment
`conda list`

##### Search for a package
`conda search <package-name>`

##### Install a package (e.g., numpy)
`conda install numpy`

##### Install multiple packages at once
`conda install numpy pandas matplotlib`

##### Update a package
`conda update numpy`

##### Remove a package
`conda remove numpy`

##### Install a package from conda-forge channel
`conda install -c conda-forge <package-name>`

##### Set conda-forge as the default channel
`conda config --add channels conda-forge`
`conda config --set channel_priority strict`

##### Export the environment to a YAML file
`conda env export > environment.yml`

##### Create an environment from a YAML file
`conda env create -f environment.yml`

##### Clean the package cache
`conda clean --all`

##### Check for unused packages and dependencies
`conda env update --prune`
