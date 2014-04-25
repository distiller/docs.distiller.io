---
layout: article
title: "Creating a New Project"
category: start
order: 1
---

#Getting Started - Creating a New Project
---

In this guide, we’ll walk you through creating a new project on Distiller.

###Step 1. Enter Create Flow

You can enter the add project flow by clicking on the “Add Project” link in the left sidebar.

###Step 2. Select the Repository

You can select the repository that you want to add to the project from the list of your organizations that we pull from GitHub.  Once you locate the repository that you want to build, simply click “Add”

<div class="bs-callout bs-callout-info">
        <h4>Note</h4>
If you are an admin on the GitHub repository that you are adding to the project, Distiller will automatically add a post-commit hook to the repository that will automatically trigger a build on every new commit. If you are not an admin on the repository, we will poll your repository for changes and trigger builds when we see new commits. This will mean a delay between commit and build. You can have an admin add the Distiller hook to the project on Github.

</div>

###Step 3. Configure the Project

Now, we need to set the Xcode settings for your project to build. We try to make this process easier for you by autodetecting your settings and preloading the options for you. This autodetection isn’t flawless, so there will be times that you’ll have to find these settings manually.

####a. Project or Workspace.

You need to define the app path for Distiller to build. Distiller can build either independent .xcodeproj projects or shared .xcworkspace workspaces. Identify the target of the build, and select it from the autodetected list or enter it manually. If you enter it manually, it should be the repo-relative path to the <code>.xcodeproj</code> or <code>.xcworkspace</code> file. Example would be <code>Distiller/Distiller.xcworkspace</code>.

####b. Scheme and Test Scheme

These are the schemes that Distiller will use to build and test your app.  Identify the scheme from the autodetected list or enter it manually. Entering a test scheme is optional. If no test scheme is identified, no tests will be run during the build.

<div class="bs-callout bs-callout-warning">
        <h4>Scheme must be shared</h4>
The scheme must be a shared scheme. You’ll receive an alert on the settings page if we are not able to detect a shared scheme. To create a shared scheme, you’ll have to open your project in Xcode and and look under Project > Scheme > Manage Schemes. Select the scheme you want to use and make it shared.
</div>

You should now be able to trigger your first build.
