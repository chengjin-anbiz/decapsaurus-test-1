---
title: Introduction
sidebar_position: 1
---
This is an introduction to the Docs part of the website.

## 1. Editing Documents

To edit documents, start by going to <a href="/admin/index.html">the CMS panel</a> and log in with a writer's GitHub account.

You will see a list of links that mirror the structure of the Docs part of the live website. Each "folder" represents a file in the website.

Click on the entry on the right to begin editing.

## 2. Saving Documents

Once your changes are made, click **Save** on the top navbar. This will create a pull request on the website's Github repository.

You can access the repository [here](https://github.com/chengjin-anbiz/decapsaurus-test-1) and log in with the same writer account as provided. Once logged in and on the repository's page, click on the **Pull Requests** tab to find the change you made.

You should be able to see a deploy preview provided by Netlify containing a copy of the website that includes the changes you just made.

![Github PR Image](/img/githubpr.png)

## 3. Publishing Documents

This setup is meant to leave the publishing of the new changes into the production branch to the developers. 

The **Publish** button is originally meant to trigger a merge on GitHub, but I have set up rules that prevent non-admin users from performing that action, so an error message will pop-up if you click that button.

## 4. Other Actions

The **Status** dropdown will update the tag attached to the pull request on Github.

The **Delete unpublished changes** button will close the pull request.

Further changes can be made to the file, and a new commit will be added to the PR when the **Save** button is clicked again.
