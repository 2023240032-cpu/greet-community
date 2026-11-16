# Contributing to greet-community

## Set up for development

Activate a Python 3.11+ virtual environment, then install the package in editable mode:

```bash
python -m pip install -e .
```

## Run the tests

```bash
python -c "from greet_community import greet; print(greet('Hee'))"
```

Expected output: `Hello, Hee!`

## Send a change

1. Create a branch from `main`: `git switch -c my-change main`
2. Commit your change on that branch: `git commit -am "Describe the change"`
3. Push the branch: `git push -u origin my-change`
4. On GitHub, open a pull request from your branch into `main`.
