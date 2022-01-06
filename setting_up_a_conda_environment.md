## How to set up a conda environment using Anaconda Navigator GUI

**Step 1: Installation** 

First install [Anaconda individual edition](https://www.anaconda.com/products/individual). Once it is installed, launch Anaconda Navigator.

**Step 2: Create an environment** 

1. Tap the plus button to create an environment

![photo1](https://raw.githubusercontent.com/cuinfoscience/Docs/main/images/setting_up_a_conda_environment/create_env.png)

2. Name your environment. In this example we will use the name "DS". But you can call your environment anything you'd like.

![photo2](https://github.com/cuinfoscience/Docs/blob/main/images/setting_up_a_conda_environment/create_env2.png?raw=true)

**Step 3: Update index**

Be sure to also click update index to make sure Anaconda navigator can see the latest versions of packages. This is especially important if you installed Anaconda navigator in a previous semester. Developers update packages all the time.

![photo3](https://github.com/cuinfoscience/Docs/blob/main/images/setting_up_a_conda_environment/create_env3.png?raw=true)

**Step 4: Install packages into your environment**

Now install packages in the DS environment. To install the packages, you will first need to set the dropdown to the left of "channels" to show "Not installed". This tells conda to search for uninstalled packages. This example shows how to install the Altair package. But you can follow the same steps to install other packages like numpy or pandas. 

![photoAlt](https://github.com/cuinfoscience/Docs/blob/main/images/setting_up_a_conda_environment/create_env5.png?raw=true)

**Step 5: Install Jupyter notebook**

This step is very important. You will have to install jupyterlab to access Juptyer notebooks in your environment.

This is how to install Jupyter lab
![photoJup](https://github.com/cuinfoscience/Docs/blob/main/images/setting_up_a_conda_environment/create_env4.png?raw=true)

Click the triangle beside the environment name and select "Open with Jupyter Notebook" to open the notebook
![photoJup2](https://github.com/cuinfoscience/Docs/blob/main/images/setting_up_a_conda_environment/create_env6.png?raw=true)

**Step 6: Checking it worked**

Once you create a new notebook, you should be able to run a cell like this in the notebook to confirm you have the right software installed. 

![confirmation](https://github.com/cuinfoscience/Docs/blob/main/images/setting_up_a_conda_environment/create_env7.png?raw=true)