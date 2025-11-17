# Programming II

Data processing Programming II course for the master Data Science for Life Science.

This repo has the following directories:

- `assessment`: In this folder you find all the assignments.
- `demos`: Lots of notebooks that we are using during the module, or not. Feel free to open one that seems to offer what you are interested in.
- `exercises`: Notebooks with some extra exercises (hence the name).
- `images`: Images that are used in any of the notebooks.
- `scripts`: Demo scripts such as unit testing scripts and creating sql database. All the _on-the-fly-scripts_ that we will work on during the lectures will also be put into this directory.
- `example_cases`: Examples of study cases for analysis of both continous and categorical data.
- `tutorials`: Tutorials for specific topics.
- `study_cases`: Notebooks that you need to work on in preperation for the lessons.

## Create a virtual environment to install the dependencies

Login the linux grid. Open the terminal. Choose a path and a name for your virtual environment, for instance `.venv/dsls`. Have a look at [the file `requirements.txt`](requirements.txt) to see what we are using.

```
#create a new environment
python3 -m venv {path/to/new/virtual/environment} {name}

#activate the virtualenv
source {path/to/new/virtual/environment}{name}/bin/activate

#install the necessary requirements
python -m pip install -r requirements.txt

#create jupyter notebook kernel for venv
python -m ipykernel install --user --name={name}
```

Make sure that you use the created kernel in your jupyter notebook or visual studio code (you should be able to do that by now).

contact information: m.kempenaar@pl.hanze.nl & p.c.kroon@pl.hanze.nl
