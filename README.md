# github-actions-CI-tests


Building to test CI with Github actions
Reference:
Practical MLOps - Oriely
https://www.youtube.com/watch?v=4gbUYOgALik&t=434s

# CI Objectives
 Test
 Lint
 Automatic
 Repeat
 
 Earlier it was done using Jenkins, now it can be done using Git Actions too, it is a SaaS based solution
 

# To use my project you can
Create virtual env first
'''python3 -m venv~/.github-actions-demo'''
source activate it 
'''source ~/.github-actions-demo/bin/activate'''

## Create reqiurement.txt
'''touch requirement.txt'''
'''pip install -r requirements.txt'''
 
 ## Create Makefile
 '''touch Makefile'''
immediately use this command:
'''make install'''

## To push intermittent files to git :
 git add *
 git commit -m "" 
 you may get git config user name and email, do that if not set
 git push
 
## Git Actions test
 After previous steps we can check Git actions
 Open requirement.txt on Github
 Go to Actions
 set up yaml file
 then go back to actions and build- this will be in a new environment
 
 get status badge : [![Python application test with Github Actions]
 (https://github.com/bharatbajoria/github-actions-CI-tests/actions/workflows/main.yml/badge.svg)](https://github.com/bharatbajoria/github-actions-CI-tests/actions/workflows/main.yml)
 this tells us if processes are running fine
 
 
 
 