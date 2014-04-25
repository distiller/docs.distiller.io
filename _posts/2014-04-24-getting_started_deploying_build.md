---
layout: article
title: "Deploying a Build"
category: start
order: 3
---

#Getting Started - Deploying a Build
---

In this guide, we’ll get your Distiller builds deployed to users via Testflight (more OTA providers coming soon).

<div class="bs-callout bs-callout-warning">
    <h4>Configure your project first</h4>
You need to first configure your project for deployment. We outline that process in a separate guide here - <a href="/articles/getting_started_ota_deployment_setup.html">Setup for OTA Deployment</a>
</div>

###Step 1. Go to the Build Details Page

Click on the build number of the build you want to deploy from either the dashboard or build history for the project.  On the build details page, click “Deploy Now” in the upper right hand corner.

<div class="bs-callout bs-callout-info">
        <h4>Configured?</h4>
If you have not configured your project for deployment, that button on the Build Details page will read “Configure for OTA Deployment”. You have to set up your project first.
</div>

###Step 2. Enter the Deploy Details

For deploy details, you can optionally enter the following values:

- <code>Distribution Lists</code>:  You can enter one or more Testflight distribution lists. If this field is blank, it will go to all users who are part of the project.

- <code>Notify Users via Email</code>: If you select yes, users who have access to the build will receive a new build email from Testflight. (this defaults to no)

- <code>Release Notes</code>: These are the notes that will be included in both the Testflight email and Testflight download page.

###Step 3. Deploy the Build

Once deployed, Distiller sends the app file to Testflight. There is usually a slight delay before Testflight notifies you via email of a new build. So, be patient.
