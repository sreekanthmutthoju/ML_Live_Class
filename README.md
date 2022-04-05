# ML_Live_Class
Machine Learning Datasets Implementation

# Commands Used
```bash
conda env list
mkdir utils
touch utils/__init__.py #to treat utility as a package
touch utils/model.py
touch utils/all_utils.py (keep all helper functions in all_utils folder)
from utils.model import class
touch requirements.txt
conda create -n sagar python==3.8 -y
conda activate sagar
pip freeze > requirements.txt
pip install -r requirements.txt
git add . && git commit -m "docstring updated" && git push origin main
git remote -v #shows the remote repository URL
git pull #to bring changes from remote repository and merge into local branch
git branch -M # to rename current branch
git checkout "committed id no" (to go to specific version)
pip install notebook #to install jupyter notebook in the vs code
jupyter notebook
cp sample\ notebook/demo.ipynb .
#to see utils as a pckage, just type python in the terminal
import utils
utils.__version__ #check utils package version

#Change your remote's URL from SSH to HTTPS with the git remote set-url command.
git remote set-url origin https://github.com/USERNAME/REPOSITORY.git

git push -f origin main # To force push to github. This will overwrite existing files.

git checkout <existing_branch> | git switch <existing_branch> # To change to an existing brance

git checkout -b <new_branch> | git switch -c <new_branch> # To create a new branch and change into it

git status #Gives the git status on current branch like staging area, untracked files

```
