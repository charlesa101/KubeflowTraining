# Setting up Kale

Kale can be easily set up on your local jupyter lab environment using the following commands:
#
First we install the Kale package

`pip install kubeflow-kale`{{execute}}

Then we need to install the jupyter lab where our notebooks can be run

`pip install "jupyterlab>=2.0.0,<3.0.0"`{{execute}}

After that we need to install the kale extension for Jupyter lab

`jupyter labextension install kubeflow-kale-labextension`{{execute}}

You can confirm the extension is installed with this next command. Jupyter lab should be listed.
`jupyter labextension list`{{execute}}

Launch the jupyter lab to start on your notebooks.

`jupyter lab`{{execute}}
#