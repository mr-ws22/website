# Anaconda environment

This section contains an overview about the programming environments you will need for our course. 


## Create environment: mr

We install some modules in a new Anaconda environment. We call this new environment `mr` (for market research). 


> On *Windows* open the Start menu and open the "Anaconda Command Prompt". 

> On *macOS*: Open a terminal ([learn how to open a terminal](https://support.apple.com/guide/terminal/open-or-quit-terminal-apd5265185d-f365-44cb-8b09-71a064a42125/mac)) 


- Copy this code and run it in your terminal: 

```bash
conda create -n mr python=3.9 pandas openpyxl jupyter scikit-learn altair vega_datasets matplotlib seaborn
```

Activate the new environment:

```bash
conda activate mr
```

## How to select your environment

In Visual Studio Code:

1. [Create or open a Jupyter Notebook](https://code.visualstudio.com/docs/datascience/jupyter-notebooks#_create-or-open-a-jupyter-notebook)

1. Next, select a kernel using the kernel picker in the top right (select the Anaconda environment)

![](https://code.visualstudio.com/assets/docs/datascience/jupyter/native-kernel-picker.png)




