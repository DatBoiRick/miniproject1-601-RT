# GITflow Workflow

## Introduction

##### Gitflow Workflow is a Git workflow that helps with continuous software development and implementing DevOps practices. It was publishe by Vincent Driessen.
##### Gitflow is ideally suited for projects that have a scheduled release cycle and for the DevOps best practice of continuous delivery.

## Getting Started 
##### Gitflow is really just an abstract idea of a Git workflow. This means it dictates what kind of branches to set up and how to merge them together.

## How It Works
![Image of Git Flow](https://wac-cdn.atlassian.com/dam/jcr:2bef0bef-22bc-4485-94b9-a9422f70f11c/02%20(2).svg?cdnVersion=1446)

## Develop and Master Branches
#### Instead of a single master branch, this workflow uses two branches to record the history of the project. The master branch stores the official release history, and the develop branch serves as an integration branch for features. It's also convenient to tag all commits in the master branch with a version number.

The first step is to complement the default master with a develop branch. A simple way to do this is for one developer to create an empty develop branch locally and push it to the server:

###### git branch develop
######git push -u origin develop
####This branch will contain the complete history of the project, whereas master will contain an abridged version. Other developers should now clone the central repository and create a tracking branch for develop.

When using the git-flow extension library, executing git flow init on an existing repo will create the develop branch:

