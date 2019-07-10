# tomography-notebooks

*Reference notebooks for tomography reconstructions, image quantification and phase retrieval.*

```bash
# setup local repo (once)
cd /mxn/home/$USER/jupyter_notebooks # (optional, do this when you want to use it in jupyterhub.maxiv.lu.se)
git clone https://github.com/tomograms/tomography-notebooks.git

# update from gitlab (from time to time when there is something new on the server)
git pull

# edit your notebooks
# ....
# ....

# add recent changes in the notebook(s) or add a new notebook
git add my-updated-notebook1.ipynb
git add my-new-notebook2.ipynb

# commit the changes
git commit -m "Added new method in reconstructions methods."

# synchronise changes to server
#   you need to setup proper ssh-keys
#   or you will be prompted for a password with https 
git push
```

Note: You can do all above directly in JupyterHub terminal. Left panel-> plus icon -> lunch terminal
