

# Splitting a subfolder out into a new repository

## https://help.github.com/articles/splitting-a-subfolder-out-into-a-new-repository/

  git clone https://github.com/USERNAME/REPOSITORY-NAME

  git filter-branch --prune-empty --subdirectory-filter FOLDER-NAME 
  
  git remote set-url origin https://github.com/USERNAME/NEW-REPOSITORY-NAME.git
  
  git push -u origin BRANCH-NAME
