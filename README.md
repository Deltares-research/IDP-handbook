# IDP Handbook

Handbook for the International Delta Plaform project.

The handbook is published at [https://idp-handbook.eu]

## Usage

### Building the book 
#### Building the book for the first time

If you'd like to develop and/or build the IDP Handbook book, you should:

1. Clone this repository
   ```bash
    git clone git@github.com:Deltares-research/IDP-handbook.git
    ```
2. Go to the the `IDP-handbook/` directory that was created by git in the previous step
   ```bash
   cd IDP-handbook
   ```
3. Create a Python or Conda virtual environment (example for Conda)
   ```bash
    conda create -n idp_handbook python=3.11 pip
    ```
4. Activate the environment
    ```bash
    conda activate idp_handbook
    ```
5. Install the libraries:
   ```bash
   pip install -r requirements.txt
   ```
6. Find the markdown files and edit what you need.
7. Remove any existing builds by running
    ```bash
   jupyter-book clean idp_handbook/
    ```
8. Build the book
    ```bash
    jupyter-book build idp_handbook/
    ```

3. (Optional) Edit the books source files located in the `idp_handbook/` directory
4. Run `jupyter-book clean idp_handbook/` to remove any existing builds
5. Run `jupyter-book build idp_handbook/`

A fully-rendered HTML version of the book will be built in `idp_handbook/_build/html/index.html`.

#### Updating the book

The Python/Conda environment is needed only for building the book, so you can activate it after editing the files.

1. Edit the book's source files located in the `IDP-handbook/` directory
   ```bash
   cd /IDP-handbook/idp_handbook
   ```
2. Activate the environment
   ```bash
    conda activate idp_handbook
    ```
3. Remove any existing builds by running
    ```bash
   jupyter-book clean idp_handbook/
    ```
4. Finally build the book
    ```bash
   jupyter-book build idp_handbook/
    ```
## Contributors

We welcome and recognize all contributions. You can see a list of current contributors in the [contributors tab](https://github.com/Deltares-research/IDP-handbook/graphs/contributors).

## Credits

This project is created using the excellent open source [Jupyter Book project](https://jupyterbook.org/) and the [executablebooks/cookiecutter-jupyter-book template](https://github.com/executablebooks/cookiecutter-jupyter-book).
