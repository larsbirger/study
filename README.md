# study [replace with subject code and name]
Describe the subject at hand with a few words.
Please mention what is to be taught,
things to learn and what is expected.

## settng up python environment
The python environment is cool to have so you don't have to
keep unecessary modules after you finished with the class.

All commands written in the template files do assumes that they are comitted
inside the foot directory of the repository.

Setting up environment:
```Bash
python -m venv .venv
```

Activating the environment:
```bash
source .venv/bin/activate
```

The following command assumes virtual environment to be activated.

Installing recommended modules i the virtual environment:
```bash
pip install -r venv_installer
```

saving currently installed modules to the venv_installer file:
```bash
pip freeze > venv_installer
```

## usefull links(s)

- [convert `.ipynb` to `.pdf`](https://github.com/larsbirger/Trivia/blob/master/jupyter-to-pdf.md)