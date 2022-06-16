Thanks for downloading this template!

Template Name: Butterfly
Template URL: https://bootstrapmade.com/butterfly-free-bootstrap-theme/
Author: BootstrapMade.com
License: https://bootstrapmade.com/license/


Tech stack:
1. Github
2. Netlify
3. Zoho mail
4. Godaddy domain
5. vscode editor

To make changes tot he contents of the page
* Open the terminal and navigate to the project root (serg911.com)
* type "code ./" to open the project in vscode
* create a branch and name it using this format "sa/new-feature-branch"
* click the file you want to edit
* make changes to the file
* save the file (ctrl+s)
* Create Pull Request
   * git add [filepath/name]
   * git commit -m "message"
   * git push origin [branch name]
   ** if you are on the master branch, you can use "git push" instead

* merge the branch into master (or do it from github)
    * git checkout master
    * git merge [branch name]
    * git push origin master
    * git branch -d [branch name]

* update local master and delete the feature branch
    * git pull origin master
    * git push origin master
    * git branch -d [branch name]

* Run the page locally
    * netlify serve
    * netlify deploy

    or

    docker-compose build
    docker-compose up -d

    View the page locally at:
    http://lvh.me
    
