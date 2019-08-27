# Open Government of Canada Architecture Git Repository

The canada-ca/architecture repository is meant for the storage of architecture models for use within and about the Government of Canada. The contents of this repository are provided without any warranty or guarentee, and does not necisarily accurately reflect the Government of Canada's current state of Enterprise Architecture management at any given moment.

In line with [Open Government](https://open.canada.ca) principles, this repository supports open government. "Open Government is about making government more accessible to everyone. This means giving greater access to government data and information to the Canadian public and the businesses community.[About Open Government](https://open.canada.ca/en/about-open-government).

This repository is governed using an informal, community driven governance model.

## What you will find here

This repository will contain elements created from open and accessible information and data sources such as:

* Legislation
* Acts
* Regulations
* Policies
* Directives

## What you wont find here

This repository is not mean to expose non-public or protected information sources such as:

* Internal business transformation
* Internal departmental policies
* personal or self-identifiable information
* any information presenting exposing security threats or internal network topologies

## About Enterprise Architecture within Government of Canada

Enterprise Architecture in its current form within the Government of Canada is heavily focused on the Management of IM/IT, however its principles can be found across all viewpoints of the organization within the Architecture Development Model (ADM) including Business, Information and systems, as well as technology.

The [Government of Canada Strategic Plan for Information Management and Information Technology 2017 to 2021](https://www.canada.ca/en/treasury-board-secretariat/services/information-technology/strategic-plan-2017-2021.html#toc8-2-2) states, "Sound IM-IT management starts with consistent planning based on documented descriptions of the enterprise. With an understanding of what is in play, managers can adopt solutions that best address their business needs while advancing government-wide architecture."

[Directive on Management of Information Technology](https://www.tbs-sct.gc.ca/pol/doc-eng.aspx?id=15249), provides guidance on how to assess Enterprise Architecture through Appendix C - Mandatory Procedures for Enterprise Architecture Assessment.

## Getting Started

### Background infomration and conttext

* Familiarize yourself with [TOGAF 9.12](https://pubs.opengroup.org/architecture/togaf91-doc/arch/index.html)
* Familiarize yourself with [Archimate 3.0.1](http://pubs.opengroup.org/architecture/archimate3-doc/)
* Familiarize yourself with [Gitflow](https://nvie.com/posts/a-successful-git-branching-model/)
* Government of Canada Policies related to architecture

### Install Archi Modeling Tool

* Install [Archi Tool](https://www.archimatetool.com/)
* Install [Archi Tool Collaboration Plugin](https://www.archimatetool.com/plugins/)

### Fork The Repository

* If you are new to the project please experiment with modeling and workflows by forking your project.
* Create a GitHub account
* Fork the repository to your own workspace

### Load Model Into Archi

* Once you have forked the project you can load the model into Archi
* Start Archi
* Go to Collaboration menu
* Collaboration > Import Remote Model to Workspace
  * URL: Use "clone" URL
  * User Name: e-mail used to register at GCCode
  * Passowrd: Passowrd used to log in to GCCode

### Git Flow Workflow

* Refresh Model (aka Git-Pull)
  * this step will pull in any updates to the model from the repository
* Commit Changes (aka Git-Commit)
  * after making any changes to the model committing will ad them to your local copy of the git repo on your local machine
  * please provide meaningful comments for each commit
  * Keep commits to a managable size
  * Each commit should related to changes that are logical (eg updating a single view, or adding related objects, or adding a new set of relationships)
  * Commiting changes does not share them back to the community, only locally on your machine
* Publish Changes (aka Git-Push)
  * Pushing your committed changes shares your contribution back to the community or at least your forked project.

### Contribute upstream

* once you have made changes to your forked project, please consider submitting changes up stream
* if you have created various branches in your forked project, it is likely best to migrate all changes to you forked "Master"
* Submit a [Pull Request](https://help.github.com/en/articles/about-pull-requests)
  * New Pull Request
  * base repository: This is the parent canada-ca/architecture repository
  * Head repository: This is likely your forked repo
* Consider pulling FROM your repositories MASTER branch into the base repository DEVELOPMENT or other branch

## Alternative workflow

* Clone this project into your own repository
* Submit Merge requests back to this project
