# A template repo for Machine learning projects

## Features

- Includes a github action workflow to run pytests and deploy to kubernetes cluster on push to main branch
- Uses pyproject.toml to manage dependencies and uses poetry for dependency management
- Uses docker to build and push docker images
- Uses kubernetes to deploy docker images
- While setting up, following parameters are asked: 

```json
{
  "repo_name": "ml", 
  "project_name": "ml (Used in pyproject toml, default same as repo_name)",
  "project_version": "0.0.1",
  "project_description": "ML",
  "project_author": "Mohit Sharma",
  "python_version": "^3.11",
}

```
