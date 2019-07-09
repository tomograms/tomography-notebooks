# tomography-notebooks

*Reference notebooks for tomography reconstructions, image quantification and phase retrieval.*

```bash
# setup local repo (once)
git clone https://gitlab.maxiv.lu.se/scisw/tomography-notebooks.git

# update from gitlab (from time to time when there is anything new on the server)
git fetch

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