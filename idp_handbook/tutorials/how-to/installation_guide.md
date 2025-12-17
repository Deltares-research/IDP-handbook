# Executing the tutorials

The tutorials can be either executed locally or in Jupyter Hub. These options are described in more detail below:


::::::{tab-set}

:::::{tab-item} Local computer

Running tutorials on your own local computer allows for full customization and most freedoms in use. However it also requires setting up the Python environment and retrieving the tutorials from GitHub.

:::{admonition} Setup instructions :class: note
 - Clone git repository [IDP-workbench](https://github.com/Deltares-research/IDP-workbench/tree/tutorials) (note: 'tutorials branch').
 - In miniforge (or other conda installer), navigate to the folder where the repository was cloned.
 - Install python environment from [environment.yml](https://github.com/Deltares-research/IDP-workbench/blob/tutorials/environment.yml).
 - Activate the environment `idp-tutorials`
 - Launch JupyterLab interface to execute tutorials, these are found in the `tutorials` folder.
::: 
:::::

:::::{tab-item} Deltares JupyterHub

```{image} ../../images/jupyter-hub-logo.svg
:target: https://jupyter.org/hub
:width: 150px
:align: left
:name: jupyterhub-deltares
```

A JupyterHub instance is hosted by Deltares and provides a ready-to-use environment for running tutorials. 
:::::
::::::