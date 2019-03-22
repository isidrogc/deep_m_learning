# dlnd_tv_script_generation

This project generates your own [Simpsons](https://en.wikipedia.org/wiki/The_Simpsons) TV scripts using `RNNs`. 
It uses part of the [Simpsons dataset](https://www.kaggle.com/wcukierski/the-simpsons-by-the-data) of scripts from 27 seasons. 
The Neural Network built will generate a new TV script for a scene at [Moe's Tavern](https://simpsonswiki.com/wiki/Moe's_Tavern).


## Usage


run command while in dlnd_tv_script_generation directory

```
jupyter notebook
```

You'll be seing a similar output in your terminal
```
[I 21:26:41.666 NotebookApp] [nb_conda_kernels] enabled, 6 kernels found
[I 21:26:42.460 NotebookApp] JupyterLab beta preview extension loaded from /anaconda3/lib/python3.6/site-packages/jupyterlab
[I 21:26:42.460 NotebookApp] JupyterLab application directory is /anaconda3/share/jupyter/lab
[I 21:26:43.001 NotebookApp] [nb_anacondacloud] enabled
[I 21:26:43.006 NotebookApp] [nb_conda] enabled
[I 21:26:43.099 NotebookApp] ✓ nbpresent HTML export ENABLED
[W 21:26:43.099 NotebookApp] ✗ nbpresent PDF export DISABLED: No module named 'nbbrowserpdf'
[I 21:26:43.103 NotebookApp] Serving notebooks from local directory: /Users/admin/tmpdlnd/deep_m_learning/dlnd_tv_script_generation
[I 21:26:43.103 NotebookApp] 0 active kernels
[I 21:26:43.103 NotebookApp] The Jupyter Notebook is running at:
[I 21:26:43.103 NotebookApp] http://localhost:8888/?token=5f1104c958547d8430c7dcdb86b9d8f4a90e933bace32d0a
[I 21:26:43.103 NotebookApp] Use Control-C to stop this server and shut down all kernels (twice to skip confirmation).
[C 21:26:43.107 NotebookApp] 
    
    Copy/paste this URL into your browser when you connect for the first time,
    to login with a token:
        http://localhost:8888/?token=5f1104c958547d8430c7dcdb86b9d8f4a90e933bace32d0a
[I 21:26:43.314 NotebookApp] Accepting one-time-token-authenticated connection from ::1
```
After running this command a new tab will be opened in your browser window. Run all the cells in the notebook. It may tell a while before it completes. 

## Example of generated TV script
```
  moe_szyslak: homer, you're doin' great. you're way ahead in the polls... even those negative campaign ads aren't hurting you.
  waylon_smithers: simpson barely even comes into work anymore. he pays a homeless man to do it for him.
  bum:(to dog) i, um, i don't feel so good, blue.
  homer_simpson:(chuckles) hey, people may not love homer simpson, but they love this suit.(chuckles) just like they love their stupid american flag.


  moe_szyslak: okay, homer, i got a great way to make money-- i'm a human guinea pig.
  homer_simpson: you mean, like, medical testing?
  barney_gumble: yeah, medical... military... chewin' stuff...
  moe_szyslak: chewin' stuff?
```

