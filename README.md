# GitHub Actions Fundamentals

Repo for the `GitHub Actions Fundamentals` training.

## 👉 Objectives

- Understand the __basic components__ and vocabulary of GitHub Actions
- Understand the __YAML__ syntax (scalar types, quotes, literal blocks, maps, and sequences)
- Understand the __workflow syntax__ and how to write workflows using intellisense
- Understand events that can __trigger__ workflows
- Learn the __context and expression syntax__ as well as workflow commands
- Know the different types of __actions__ and how to create/publish them
- Understand the different hosting options for __runners__
- Use __Secrets__ and __Environments__ for staged deployments
- Workflow templates and __reusable workflows__

## Getting ready

Please follow [these instructions](GettingReady.md) and make sure you have set up everything correctly following the [prerequisites](#-prerequisites).

## 📆 Agenda

### Day 1: 🚀 Getting started

- [ ] Introduction and Icebreaker
- [ ] GitHub Actions Fundamentals
- [ ] The YAML syntax
- [ ] Basic workflow syntax
- [ ] Events that trigger workflow
- [ ] Jobs and steps
- [ ] :mag: Demo: Creating a workflow
- [ ] 🔨 Hands-on: [My first Action workflow](hol/01-My-first-workflow.md)
- [ ] Advanced [workflow syntax](https://docs.github.com/en/actions/using-workflows/workflow-syntax-for-github-actions)
- [ ] :coffee: Break
- [ ] GitHub Actions
- [ ] Types of Actions
- [ ] 🔨 Hands-on: [My first container Action](hol/02-My-first-action.md)
- [ ] Typescript and composite actions
- [ ] Sharing and releasing actions
- [ ] Using the GitHub API and Octokit
- [ ] Job descriptions

### Day 2
- [ ] Introduction
- [ ] Actions for CI/CD
- [ ] Permissions for GitHub Token
- [ ] Environments and Secrets
- [ ] Staged deployments with environments, approvals, and deployment gates
- [ ] 🔨 Hands-on: [Staged deployments](hol/03-Staged-deployments.md)
- [ ] :coffee: Break
- [ ] Action policies
- [ ] Running your workflows
- [ ] Sharing workflows
- [ ] 🔨 Hands-on: [Reusable workflows](hol/04_Reusable-workflows.md)
- [ ] Best practices and security


## ⚡ Prerequisites

The workshop is designed for developers that have used other platforms like Azure DevOps, GitLab, or Bitbucket and now want to switch to GitHub. But it is also suitable for people that are new to topics like git, CI/CD, and DevOps.

For this workshop you need the following:

- A laptop (Windows, Mac, or Linux)
- A free account for https://github.com
- It is recommended to have a second screen for the hand-on labs


## More informations
https://docs.github.com/en/rest/overview/libraries
https://github.blog/2022-05-09-supercharging-github-actions-with-job-summaries/

https://docs.github.com/en/actions/learn-github-actions/environment-variables#default-environment-variables

https://github.com/wulfland/AccelerateDevOps/edit/main/.github/workflows/job_summaries.yml
SOLID design principles: https://en.wikipedia.org/wiki/SOLID
Semantic versioning https://semver.org/

Publish to the Marketplace: https://docs.github.com/en/actions/creating-actions/publishing-actions-in-github-marketplace 
Actions templates: https://github.com/actions 
github.com/actions/toolkit: https://github.com/actions/toolkit 
TypeScript template from ActionsDesk: https://github.com/ActionsDesk/ps-typescript-template

GitHub script: https://github.com/actions/github-script
CLI pattern: https://github.com/ActionsDesk/admin-support-issueops-actions

GitHub Docs - Secrets: https://docs.github.com/en/actions/reference/encrypted-secrets
Environment docs - https://docs.github.com/en/actions/reference/environments
Workflow syntax - https://docs.github.com/en/actions/reference/workflow-syntax-for-github-actions#jobsjob_idenvironment
GitHub Docs - Deployment API: https://developer.github.com/v3/repos/deployments/