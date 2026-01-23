---
title: "Software stack"
weight: 9
header_menu_title: "Software stack"
header_menu: true
---

Here are some steps to get you started for the hackathon. These should be done before the Hackathon begins.

#### 1. Hackathon python environment 

In order to be able to run the notebooks provided for the hackathon and conduct data analysis using the tools for the hackathon, the official global hackathon software stack needs to be installed. To do this, please follow this [link](https://github.com/digital-earths-global-hackathon/tools/tree/um-transform/python_envs) and download the environment.yaml file. Then install the python environment with the following command (note: you need to have conda installed and the base environment activated to do this):

`conda env create --name hackathon -f environment.yaml`

Activate the environment with:

`conda activate hackathon`

Instead of hackathon you can also choose any other name for your environment.

#### 2. Notebook kernel

If you are planning on running your code on the Jasmin Jupyter server open the terminal on the Jasmin notekook web interface, activate your environment from step 1 and then type: 

 `python -m ipykernel install --user --name=name-of-environment`


(as explained in step 2 [here](https://help.jasmin.ac.uk/docs/interactive-computing/creating-a-virtual-environment-in-the-notebooks-service/))

This will allow you to use your environment in your notebooks (you might have to reload the page to see the change).

#### 3. Test your environment

To make sure everything is working and to familiarize yourself with the available tools run the demo notebook in this [link](https://github.com/digital-earths-global-hackathon/hk25-teams/blob/main/hk25-UKnode/online/intake_demo_UM_DYAMOND3_sims.ipynb).

It shows you how to access the data by using the intake catalog and creates some simple plots.

#### 4. Further reading

If you would like to learn more about the healpix format in which all the model data is stored please follow this [link](https://easy.gems.dkrz.de/Processing/healpix/index.html).

