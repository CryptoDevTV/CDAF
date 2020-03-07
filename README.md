# Cryptocurrency Development Audit Framework

CDAF - Cryptocurrency Development Audit Framework is a tool which will help you in your own research of cryptocurrency project. Follow each point and investigate the repository, after this quick process you should get to know more about work progress and development status of the project.

## Overview

### 1. Organization vs. user account

*Indicators:*

Q1.1 - Is it organization account?
 
* [ ] `YES`
* [ ] `NO`

> Why does it matter?

> Organizations are shared accounts where businesses and open-source projects can collaborate across many projects at once. Owners and administrators can manage member access to the organization's data and projects with sophisticated security and administrative features.

*Sources:* 
[GitHub personal dashboard](https://help.github.com/en/github/setting-up-and-managing-your-github-user-account/about-your-personal-dashboard),
[GitHub organizations](https://help.github.com/en/github/setting-up-and-managing-organizations-and-teams/about-organizations)

### 1.1 Organization Header (Name, Description, Is verified)

*Indicators:*

Q1.1.1 - Is description provided?
 
* [ ] `YES`
* [ ] `NO`

Q1.1.2 - Is location provided?
 
* [ ] `YES`
* [ ] `NO`

Q1.1.3 - Is homepage address provided?
 
* [ ] `YES`
* [ ] `NO`

Q1.1.4 - Is email provided?
 
* [ ] `YES`
* [ ] `NO`

Q1.1.5 - Is account verified?
 
* [ ] `YES`
* [ ] `NO`

*Sources:*
[Organization's settings](https://help.github.com/en/github/setting-up-and-managing-organizations-and-teams/accessing-your-organizations-settings)

### 1.2 Pinned repositories

*Indicators:*

Q1.2.1 - Are there any pinned repositories?

* [ ] `YES`
* [ ] `NO`

*Sources:*
[Pinning items](https://help.github.com/en/github/setting-up-and-managing-your-github-profile/pinning-items-to-your-profile)

### 1.3 People from organization

*Indicators:*

Q1.3.1 - Are there any people involved in organization?

* [ ] `YES`
* [ ] `NO`

Q1.3.2 - Do they have activity in public repositories?

* [ ] `YES`
* [ ] `NO`

*Sources:*
[Enrich user profile](https://help.github.com/en/github/setting-up-and-managing-your-github-profile/about-your-profile)

### 1.4 Public projects

*Indicators:*

Q1.4.1 - Are there any open projects in organization?

* [ ] `YES`
* [ ] `NO`

*Sources:*
[Project boards](https://help.github.com/en/github/managing-your-work-on-github/about-project-boards)

### 1.5 Repositories list (topics)

*Indicators:*

Q1.5.1 - Is there developers activity visible in repositories?

* [ ] `YES`
* [ ] `NO`

Q1.5.2 - Do repositories have topics specified?

* [ ] `YES`
* [ ] `NO`

*Sources:*
[Repository topics](https://help.github.com/en/github/administering-a-repository/classifying-your-repository-with-topics)

## 2. Single repository

### 2.1 Repository overview

*Indicators:*

Q2.1.1 - Is description provided?
 
* [ ] `YES`
* [ ] `NO`

Q2.1.2 - Are topics provided?
 
* [ ] `YES`
* [ ] `NO`

*Sources:*
[About repository](https://help.github.com/en/github/getting-started-with-github/create-a-repo)

### 2.2 Code

*Indicators:*

Q2.2.1 - Is it forked repository?
 
* [ ] `YES`
* [ ] `NO`

Q2.2.2 - Is it *monorepo*?
 
* [ ] `YES`
* [ ] `NO`

*Sources:*
[Managing files](https://help.github.com/en/github/managing-files-in-a-repository)

#### 2.2.1 Branches

*Indicators:*

Q2.2.1.1 - Are there any branches?
 
* [ ] `YES`
* [ ] `NO`

Q2.2.1.2 - Are there any active branches?
 
* [ ] `YES`
* [ ] `NO`

*Sources:*
[About branches](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/about-branches)

#### 2.2.2 Packages

*Indicators:*

Q2.2.2.1 - Are there any packages?
 
* [ ] `YES`
* [ ] `NO`

Q2.2.2.2 - It is possible to check packages popularity?
 
* [ ] `YES`
* [ ] `NO`

*Sources:*
[GitHub Packages](https://github.com/features/packages)

#### 2.2.3 Releases

*Indicators:*

Q2.2.3.1 - Are there any releases?
 
* [ ] `YES`
* [ ] `NO`

Q2.2.3.2 - Are releases verified?
 
* [ ] `YES`
* [ ] `NO`

Q2.2.3.3 - Are releases different?
 
* [ ] `YES`
* [ ] `NO`

*Sources:*
[Releases](https://help.github.com/en/github/administering-a-repository/about-releases)

#### 2.2.4 License

*Indicators:*

Q2.2.4.1 - Is license file provided?
 
* [ ] `YES`
* [ ] `NO`

*Sources:*
[Licensing a repository](https://help.github.com/en/github/creating-cloning-and-archiving-repositories/licensing-a-repository), 
[Which license is appropriate](https://opensource.guide/legal/#which-open-source-license-is-appropriate-for-my-project)

#### 2.2.5 Readme

*Indicators:*

Q2.2.5.1 - Is README file provided?
 
* [ ] `YES`
* [ ] `NO`

*Sources:*
[Documenting project](https://guides.github.com/features/wikis/), 
[Template](https://gist.github.com/PurpleBooth/109311bb0361f32d87a2), 
[Suggestions](https://www.makeareadme.com/)

### 2.3 Issues

*Indicators:*

Q2.3.1 - Are there any open issues?
 
* [ ] `YES`
* [ ] `NO`

Q2.3.2 - Are there any closed issues?
 
* [ ] `YES`
* [ ] `NO`

Q2.3.3 - Are there any pinned issues?
 
* [ ] `YES`
* [ ] `NO`

Q2.3.4 - Are there people assigned to the issues?
 
* [ ] `YES`
* [ ] `NO`

Q2.3.5 - Do issues use labels?
 
* [ ] `YES`
* [ ] `NO`

Q2.3.6 - Do issues have conversations?
 
* [ ] `YES`
* [ ] `NO`

Q2.3.7 - Are issues a part of milestones?
 
* [ ] `YES`
* [ ] `NO`

*Sources:*
[About issues](https://help.github.com/en/github/managing-your-work-on-github/about-issues)

#### 2.3.1 Labels

*Indicators:*

Q2.3.1.1 - Are there labels in use?
 
* [ ] `YES`
* [ ] `NO`

Q2.3.1.2 - Are there any custom issues?
 
* [ ] `YES`
* [ ] `NO`

*Sources:*
[Milestones, Labels, and Assignees](https://guides.github.com/features/issues/)

#### 2.3.2 Milestones

*Indicators:*

Q2.3.2.1 - Are there milestones in use?
 
* [ ] `YES`
* [ ] `NO`

Q2.3.2.2 - Are existed milestones frequently updated?
 
* [ ] `YES`
* [ ] `NO`

Q2.3.2.3 - Are existed milestones have due date set?
 
* [ ] `YES`
* [ ] `NO`

*Sources:*
[Milestones, Labels, and Assignees](https://guides.github.com/features/issues/)


### 2.4 Pull Requests

*Indicators:*

Q2.4.1 - Are there pull requests in use?
 
* [ ] `YES`
* [ ] `NO`

Q2.4.2 - Are there any open pull requests?
 
* [ ] `YES`
* [ ] `NO`

Q2.4.3 - Are there any closed pull requests?
 
* [ ] `YES`
* [ ] `NO`

Q2.4.4 - Do pull requests use labels?
 
* [ ] `YES`
* [ ] `NO`

Q2.4.5 - Do pull requests have conversations?
 
* [ ] `YES`
* [ ] `NO`

*Sources:*
[About pull requests](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/about-pull-requests)

### 2.5 Projects

*Indicators:*

Q2.5.1 - Are there any open projects?
 
* [ ] `YES`
* [ ] `NO`

Q2.5.2 - Are there any closed projects?
 
* [ ] `YES`
* [ ] `NO`

*Sources:*
[Project boards](https://help.github.com/en/github/managing-your-work-on-github/about-project-boards)

### 2.6 Security

*Indicators:*

Q2.6.1 - Are there any security advisories?
 
* [ ] `YES`
* [ ] `NO`

Q2.6.2 - Does repository have any security policy?
 
* [ ] `YES`
* [ ] `NO`

*Sources:*
[Adding a security policy](https://help.github.com/en/github/managing-security-vulnerabilities/adding-a-security-policy-to-your-repository)

### 2.7 Insights

*Indicators:*

Q2.7.1 - Is it possible to see any work result during the last month?
 
* [ ] `YES`
* [ ] `NO`

Q2.7.2 - Do repository have any watchers?
 
* [ ] `YES`
* [ ] `NO`

Q2.7.2 - Do repository have any stars?
 
* [ ] `YES`
* [ ] `NO`

Q2.7.2 - Does repository have any forks?
 
* [ ] `YES`
* [ ] `NO`

*Sources:*
[Viewing insights](https://help.github.com/en/github/setting-up-and-managing-organizations-and-teams/viewing-insights-for-your-organization)

#### 2.7.1 Community

*Indicators:*

Q2.7.1.1 - Did repository community profile pass test?
 
* [ ] `YES`
* [ ] `NO`

*Sources:*
[Community profiles](https://help.github.com/en/github/building-a-strong-community/about-community-profiles-for-public-repositories)

#### 2.7.2 Dependency graph

*Indicators:*

Q2.7.2.1 - Does repository have any dependents?
 
* [ ] `YES`
* [ ] `NO`

*Sources:*
[Listing dependencies](https://help.github.com/en/github/visualizing-repository-data-with-graphs/listing-the-packages-that-a-repository-depends-on), 
[Listing](https://help.github.com/en/github/visualizing-repository-data-with-graphs/listing-the-projects-that-depend-on-a-repository)