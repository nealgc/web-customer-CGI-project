# web-customer-CGI-project



# -- THIS creates a new repository in a non git repositriy folder VIP ..
* step1
git clone git@github.com:nealgc/web-customer-CGI-project.git

-- this ABOVE command alse DOES THIS command IMPLICITLY so it links the local copy back to the remote (ypu do not need to do this)
git remote add origin git@github.com:nealgc/web-customer-CGI-project.git

# Check repository linked

* step2

check the remote auto linked ok from local to github

git remote -v


need to add this for jenkons build
git config --global core.longpaths true