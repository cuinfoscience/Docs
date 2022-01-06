#### Setting up a conda environment using the GUI

**Step 1: Installation** First install [Anaconda individual edition](https://www.anaconda.com/products/individual). Once it is installed, launch Anaconda Navigator.

**Step 2: Create an environment** 

1. Tap the plus button to create an environment
2. Then create an environment with a name. In this example we will use the name "DS". But you can call your environment anything you'd like.

![test](https://raw.githubusercontent.com/cuinfoscience/Docs/main/images/setting_up_a_conda_environment/create_env.png)

**Step 3: Update index**
Be sure to also click update index to make sure Anaconda navigator can see the latest versions of packages. This is especially important if you installed Anaconda navigator in a previous semester. Developers update packages all the time.

**Step 4: Install packages into your environment**

Now install packages in the DS environment. To install the packages, you will first need to set the dropdown to the left of "channels" to show "Not installed". This tells conda to search for uninstalled packages. This example shows how to install the Altair package. But you can follow the same steps to install other packages like numpy or pandas. **Important**: *Note you will have to install jupyterlab to access Juptyer notebooks in your environment*.

**Step 5: Checking it worked**

Once you create a new notebook, you should be able to run a cell like this in the notebook to confirm you have the right software installed. 