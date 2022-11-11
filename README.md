# Overview-CMPG323-34854304
This repository is for project 1. This is where I will be keeping track of the workload for this module (CMPG323) for this semester

## Repositories to be created
This module (CMPG 323) will have 5 Projects and a Portfolio of Evidence to be submitted at the end of the year. For the projects, each project will have its own repository, same way that this Project (Project 1) has its own repository.

### PROJECT 2 - CRUD RESTFUL API
An API is software that is used to send information back and forth between the user and a web-app.

![image](https://user-images.githubusercontent.com/110591480/201393822-aaa8b47d-b405-49ed-bcbe-48472f1f6c80.png)

In this project, we implemented an API web service that made use of the REST and CRUD architectural styles.
The RESTful API is able to communicate and transfer information to the cloud, an application, or other system. A RESTful API can be connected to a datasource so it can manage and communicate with the datasource. Lastly it has methods (HTTP commands) to access, manipulate and insert data. 
CRUD is an acronym for Create, Read, Update and Delete; as seen from the acronym, it is a way to manipulate data, and describing how the application should work.

![image](https://user-images.githubusercontent.com/110591480/201395606-b2a6f8c9-00cc-4c13-b117-a56d597e50ac.png)




## Branching Strategy

The branching strategy to be used will be the **Git Flow** strategy. This branching strategy will be used in all the projects throughout this semester, unless stated otherwise.

![image](https://user-images.githubusercontent.com/110591480/185218289-96de49f4-de51-4c17-9d98-50963fc9ba3f.png)


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

## CHARTS

### BURN DOWN CHART

![burndownChart](https://user-images.githubusercontent.com/110591480/188153249-99fef03b-a32a-4a3a-bfbb-39eacc27fb45.png)

A burndown chart is a graphical representation of the work that has been done and the work to be done versus time, hence the items are grouped according to status and it indicates the number of items or work to be done during the course of the semester in the sprints.

### NUMBER OF ITEMS BY LABEL CHART

![number of items by label](https://user-images.githubusercontent.com/110591480/188165838-013728d5-df08-45eb-b184-bf9b9c012ccd.png)

This chart shows the number of items in each label. 

### NUMBER OF ITEMS BY SPRINT

![number of items by sprint_](https://user-images.githubusercontent.com/110591480/188153367-40d301bf-c7b3-484a-a0ef-cc4f98f88199.png)

This chart shows the number of items or work that has been done - or to be done - in each sprint

### NUMBER OF ITEMS BY STATUS CHART

![number of items by status](https://user-images.githubusercontent.com/110591480/188154230-b2803775-bcd3-4b8b-bb7a-845a6d2ef33a.png)

This chart groups the items by milestones (items with no milestones are class related) and it shows the number of items that are yet *to be done (To Do)*, *In Progress* and are *Done*

## REFERENCE LIST

GitHub Docs. *Viewing your milestones progress*. https://docs.github.com/en/issues/using-labels-and-milestones-to-track-work/viewing-your-milestones-progress Date Accessed: 17 August 2022

GitHub Docs. *About milestones*. https://docs.github.com/en/issues/using-labels-and-milestones-to-track-work/about-milestones Date Accessed: 17 August 2022

GitHub Docs. *Filtering issues and pull requests by milestone*. https://docs.github.com/en/issues/using-labels-and-milestones-to-track-work/filtering-issues-and-pull-requests-by-milestone Date Accessed: 17 August 2022

https://uploads.sitepoint.com/wp-content/uploads/2019/06/155993572204-gitflow.png Date Accessed 17 August 2022

GitHub Docs. *Encrypted Secrets*. https://docs.github.com/en/actions/security-guides/encrypted-secrets Date Accessed: 17 August 2022

Wickramasinghe, S. (2021). *DevOps Branching Strategies Explained*. https://www.bmc.com/blogs/devops-branching-strategies/ Date Accessed: 17 August 2022





