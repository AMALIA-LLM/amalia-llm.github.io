## AMALIA Documentation, built with Sphinx

To recreate the conda env used for sphinx:

````shell
conda create -n sphinx_env python=3.14 -y
conda activate sphinx_env
pip install sphinx
pip install sphinx-autobuild
pip install sphinx-book-theme
pip install sphinx-copybutton
````

Use ``run_sphinx.sh`` to deploy the webpage. Here you can change the conda env, build directory, and the host and port for deployment.

### TODO List

- Replace QwenGuard reference to AmaliaGuard when available
- Add links to use cases when available
- Remove reference to IAEdu if the model won't be available that way