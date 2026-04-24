---
title: Introduction
sidebar_position: 1
---
This is an introduction to the Docs part of the website.

# 1. Editing documents

To edit documents, start by going to [the CMS panel](/admin/index.html) and log in with a writer's GitHub account.

You will see a list of links that mirror the structure of the Docs part of the live website. Each "folder" represents a file in the website.

Click on the entry on the right to begin editing.

# 2. Saving documents
Once your changes are made, click **Save** on the top navbar. This will create a pull request on the website's Github repository.

You can access the repository [here](https://github.com/chengjin-anbiz/decapsaurus-test-1) and log in with the same writer account as provided. Once logged in and on the repository's page, click on the **Pull Requests** tab to find the change you made.

You should be able to see a deploy preview provided by Netlify containing a copy of the website that includes the changes you just made.

# 3. Publishing documents
This setup is meant to leave the publishing of the new changes into the production branch to the developers. 

The **Publish** button is originally meant to trigger a merge on GitHub, but I have set up rules that prevent non-admin users from performing that action, so an error message will pop-up if you click that button.
