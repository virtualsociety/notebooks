# ![Jupyter](./doc/img/jupyter.svg) Notebooks

This repo contains a collection Jupyter Notebooks as research projects that are usefull for the development of Virtual Society.

## Requirements

For research projects, the following requirements should be met:

8 Notebooks should be in described in the English language
* Notebooks should not have dependencies that can not be resolved.
* Dependencies that need be resolved should be available as a repo in the Virtual Society GitHub organization. This means that external repo's should be forked first.
* Dependencies should be described under the `Current Notebooks` section.
* Temporary file storage needed for research project should be placed on Google Drive
* Notebooks should have clear descriptions in any stage of its work flow
* New notebooks will be reviewed, verified and then placed by the Administrators of this Repo
* A short description of the notebook indicating the value for Virtual Society should be placed in this readme under section `Current Notebooks`
* If there's a project definition for the research field, it should be placed alongside with the notebook in Markdown format

## Current Notebooks

### Dataset Deviation Algorithm
![status](https://img.shields.io/badge/notebook-unhealthy-red)

This notebook demonstrates how datasets from virtual society can be selected based on rule engine definition.

This is beneficial for assisting in automated tests in virtual society. The test dataset will be automatically selected based on the algorithm. From which we can derive significant persona's from the population in virtual society.

### StyleGAN2
[![status](https://img.shields.io/badge/notebook-verified-green)](./notebooks/adveserial-networks/generative/StyleGan2/StyleGan2.ipynb)

This notebook demonstrates how to run NVIDIA's StyleGAN2

StyleGAN2 can potentially be used as part of the Persona's image generator for its population.

For information on StyleGAN2, see:
* Paper: https://arxiv.org/abs/1812.04948
* Video: https://youtu.be/kSLJriaOumA
* Code: https://github.com/virtualsociety-forks/stylegan2
* FFHQ: https://github.com/virtualsociety-forks/ffhq-dataset

Dependencies: 

* https://github.com/virtualsociety-forks/StyleGan2
* https://github.com/virtualsociety-forks/ffhq-dataset