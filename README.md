 <!-- code .  [opnen  microsoft visual code]
ctrl + ? [comments lot of rows]
ctrl + ~   [open the mvc termnial]
prtscn     [open keyboard if the keybord is lock from writing]
pip install pipenv                         [to create thebinvirment]
pipenv shell                               [to get in the invarmment]
pip install pandas django matplotlib pillow  opencv-Python       [install the needed packeges]
exit                                                           [to get out from the envroment]
pip freeze                                                      [see the packages]

git init                                                   [build git repository]
main.py                                                    [start the application]
README.md                                                  [for upload to git]
.gitignore                [we dont want Pipfile will be upladed and be ignore by github]
git add .    
git commit -m "Initial commit+"
gh repo create      [Push an existing local repository to GitHub]
 git push --set-upstream origin master
 git push  -u origin master
 gh repo view --web    [view the repository in the site]
  -->
 [to be ensure the project will run in any invaierment force the same packeges version]
 
 pipenv shell 
 pip freeze  
 pip freeze > requirements.txt [crate the txt file with the packages]
 pip install -r requirements.txt   [fourse to use this packages with ther version]

 ------------

 git init
 git add .   [save everything]   [update the github repository]
 git commit -m 'add html and css file'
 git remote add orign https//github.com/ilang975/MyApp.git
 git push -u origin master
 gh repo view --web 
 