# sentiment-analysis

Web application to predict sentiment of a movie review


This kernel does build a recurrent neural network to predict sentiment of a movie review. It uses [IMDb dataset](https://www.imdb.com/interfaces/) to train the network. Finally uses Amazon's SageMaker to deploy trained model to the cloud.

A simple web application is also provided to interacts with the model. 



## Requires

GPU enabled device to train the model. AWS account to deploy the trained model


## Usage

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


## Example generated predictions

[Positive review](positive_review.png)

[Negative review](negative_review.png)
