# QA-SPA-TTR
Finding Answers to Questions: Bridging between Type-based and Computational Neuroscience Approaches

# Usage
Should work with Python 3.6 or above (implemented using Python 3.12).

1. Set up a virtual environment for Nengo and the other required libraries, called nengovenv (choose another name if you like):

```console
python3 -m venv nengovenv
```

2. Activate the virtual environment:

```console
source nengovenv/bin/activate
```

3. Install the requirements:

```console
python3 -m pip install -r requirements.txt
```

4. Install jupyter and create a new kernel for nengovenv:

```console
python3 -m pip install jupyter
ipython kernel install --user --name=nengovenv
```

5. Start the notebook server:

```console
juypter notebook
```

6. Select the Python notebook ("qa_spa-ttr_ft_typecheck.ipynb"). Select "nengoenv" as kernel, if not already set as kernel, and go ahead!

7. When finished, shut down the server and deactivate the virtual environment.

