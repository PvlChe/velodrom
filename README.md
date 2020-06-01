Command line instructions
You can also upload existing files from your computer using the instructions below.
    
    Git global setup
    git config --global user.name "Vitaly Tolstik"
    git config --global user.email "vital.tol90@gmail.com"

Create a new repository
    
    git clone https://gitlab.com/VitalyTolstik/test-project.git
    cd test-git-project
    touch README.md
    git add README.md
    git commit -m "add README"
    git push -u origin master

Push an existing folder
    
    cd existing_folder
    git init
    git remote add origin https://gitlab.com/VitalyTolstik/test-project.git
    git add .
    git commit -m "Initial commit"
    git push -u origin master

Push an existing Git repository
    
    cd existing_repo
    git remote rename origin old-origin
    git remote add origin https://gitlab.com/VitalyTolstik/test-project.git
    git push -u origin --all
    git push -u origin --tags