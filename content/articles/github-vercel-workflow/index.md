---
title: "Github and Vercel workflow."
description: "Set up github and vercel flow for the pull requests"
date: "2023-02-22"
categories:
  - "Git"
  - "Github"
keywords:
  - "Github"
  - "Vercel"
---

# Github and Vercel workflow

Create a GitHub repo, clone it and follow these steps:

```
echo "#  task description here " >> README.md
git add README.md
git commit -m "Initial commit"
git push -u origin master
```

Go to Settings tab of your repo -> Manage Access -> click on Invite a collaborator and type in knlju

Create new project on Vercel by importing your GitHub repo

Create a branch called develop or dev and do all the work on that branch, commit and push

Create pull request and add Ljubisa as reviewers