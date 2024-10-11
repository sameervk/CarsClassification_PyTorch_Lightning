# Identification of Car Manufacturer

- Data: Stanford Car Dataset
- ML framework: Pytorch Lightning
- Transfer learning to develop a NN model



## Python virtualenv creation
1. Using Poetry: https://python-poetry.org/, so please install poetry at the global level
2. From the folder, run `poetry install`
	- This should create a virtual environment in the project folder.
	- Add the virtualenv to .gitignore
3. Run `poetry shell` to activate the virtualenv.
4. Assuming `jupyter lab` is already installed globally (if not, please install at the global level), add the virtualenv to the jupyter kernel using (from the terminal with the virtualenv activated)
	- `ipython kernel install --user --name=[virtualenv name]`