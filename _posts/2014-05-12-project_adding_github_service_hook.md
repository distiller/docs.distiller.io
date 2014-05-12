---
layout: article
title: "Adding the Distiller Service Hook to your GitHub Repo"
category: project
order: 2
---

#Project - Adding the Distiller Service Hook to your GitHub Repo
---

In order to automatically trigger builds on each push for your GitHub repository, we need to add our Distiller service hook to your repo. If you added a repository that you have admin access to, Distiller does this for you automatically. If you added a repository that you do not have admin access to, an admin will have to add it manually.

To add the Distiller service hook to your GitHub repository:

###Step #1. Go to the settings section of your GitHub repository.

github.com/org_name/repo_name/settings


Click Webhooks & Services in the left navigation.


###Step #2: Find the Distiller service hook.

Click the “Add Services” button and select Distiller from the dropdown list or enter it into the search field.

![GitHub repo settings](/img/16-github-repo-settings.png)

</br>

###Step #3: Add the Distiller service hook.

On the service hook page, ensure that the checkbox for “Active” is selected.

![Add GitHub Service Hook](/img/17-github-add-service-hook.png)

</br>

Save by clicking "Add Service" You're done. Now your repository will automatically build when you push.