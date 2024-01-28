# kidney-disease-mlops-project
A repository with and practical example of an end-to-end flops project.

## Workflows
1. Update config.yaml
2. Update secrets.yaml [Optional]
3. Update params.yaml
4. Update the entity
5. Update the configuration manager in src config
6. Update the components
7. Update the pipeline
8. Update the main.py
9. Update the dvc.yaml
10. app.py

## Virtual Environment
`python -m venv .venv` <br>
`source .venv/bin/activate`<br>

`conda deactivate` to deactivate base environment.

## Github
`git add .` <br>
`git commit -m "commit name"` <br>
`git push origin main` <br>

## Template
`template.py` should be executed to create folder structure.

## Requirements
`pip install -r requirements.txt` <br>
`pip freeze > requirements.txt` <br>

## Git Checkout Remote Branch
`git fetch origin` <br>
`git branch -a` <br>
`git checkout -b jerf_branch origin/jerf_branch` <br>
`git add .` <br>
`git commit -m "example"` <br>
`git push` <br>