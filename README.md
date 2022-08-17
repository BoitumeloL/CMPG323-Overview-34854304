# Overview-CMPG323-34854304
This repository is for project 1. This is where I will be keeping track of the workload for this module (CMPG323) for this semester

## Repositories to be created
This module (CMPG 323) will have 5 Projects and a Portfolio of Evidence to be submitted at the end of the year. For the projects, each project will have its own repository, same way that this Project (Project 1) has its own repository.

## Branching Strategy

The branching strategy to be used will be the **Git Flow** strategy. This branching strategy will be used in all the projects throughout this semester, unless stated otherwise.

### Primary Branches

There will be 2 primary branches **Main** and **Develop**. The main branch is where all the final code will be stored, and the develop branch is where the development of the specific project will happen. Once the code in the Develop branch is completed, tested and free of bugs, the changes in the Develop branch will be merged to the main branch.

### Support Branches

These branches will be created for specific features in the code or project with the Develop branch as their base.
Some of these branches could be: 
* **Feature**: This branch will  be used to make new features
* **Hotfix**: This branch will be used to deal with any required fixes. It can branch off from the main branch, but has to be merged to both primary branches.
* **Release**: This branch will be used to gather all the fixes and improvements made to the code and prepare the project for release. It will branch off from the develop branch and merged to both the primary branches.

## The use of a .gitignore file within each project
The **.gitignore** file will be used to hide files and/or directories that we do not want github to have access to. This ensures that git does not track these files.

## Storage of credentials and sensitive information
To store credentials and sensitive information in the upcoming projects, we will use a GitHub feature called **secrets**. This feature allows us to store sensitive information in a repository and to limit access to these secrets.





