# Github React Skeleton Documentation

https://docs.google.com/document/d/1ppQ1fpGBaqmdkRiba8dO6UyhJTYX8IN43_MWA-V10FE/edit?usp=sharing

## Overview: 
A guide on how to easily set up a git repository of a react web application. The gh-react-skeleton is a repo we’ve made in hopes of an easier start to creating a react project with github. 

## Requirements: 
Before we start creating our project, there are a few things we must download onto your computer in order to create a react environment. <br/> 
Node.js: https://nodejs.org/en/ \
Git must be installed, follow this documentation on how to install git onto your device: https://git-scm.com/book/en/v2/Getting-Started-Installing-Git	<br/> 

To check if the to packages we need are successfully installed in your home directory of your terminal (mac), or git bash terminal (Windows) run these commands: \
	<p align="center">
		`` node --version `` \
		`` npm --version `` \
		`` npx --version `` \
	</p>
They should each output the version number. 

## Setting Up the React Environment and Creating Your Git Repository: 
In github create a new repository: DON’T add a readme, .gitignore, or license to the repo. \
In the home directory of your computer's terminal (mac) / git bash (Windows) run the command: \
	<p align="center">
                `` mkdir my-app `` \
                `` cd my-app `` \
	</p>
This line of code makes a folder called my-app and then we want to enter the folder so we “cd” into it. \
Next we want to initialize git in this directory we are in. To do that type: \
     	<p align="center"> `` git init ``  </p>
We will now add an upstream and an origin to remote. The upstream will be the github repo we want to clone (the club repo: gh-react-skeleton), and the origin will be the github repo you made in step 1. \
        <p align="center">
		`` git remote add upstream https://github.com/bhassan6621/react-gh-skeleton.git `` \
                `` git remote add origin https://{your-github-repo-url} `` \
	</p>
The first line sets the upstream to the club repo \
In the second line the url that needs to be pasted after “origin” is from the github repo you’ve made. <br/>

Next line in the terminal gets the code from the club’s repo: \
	<p align="center">
                `` git pull https://github.com/bhassan6621/react-gh-skeleton.git main `` \
	</p>
Then to push the code into your repo we type: \
	<p align="center">
                  `` git pull origin master `` 
	</p>


## Refresh your github repository on github and you will see your new react web app all set up :)) 

/ * To make a react project and push it to github on your own these are some helpful websites to follow along: \
https://github.com/facebook/create-react-app \
https://github.com/gitname/react-gh-pages    */
