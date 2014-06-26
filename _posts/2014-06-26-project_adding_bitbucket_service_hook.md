---
layout: article
title: "Adding the Distiller Service Hook to your Bitbucket Repo"
category: project
order: 3
---

#Project - Adding the Distiller Service Hook to your Bitbucket Repo
---

In order to automatically trigger builds on each push for your Bitbucket repository, we need to add our Distiller service hook to your repo. If you added a repository that you have admin access to, you can do this yourself. If you added a repository that you do not have admin access to, an admin will have to add it for you.

To add the Distiller service hook to your Bitbucket repository:

###Step #1. Go to the settings section of your Bitbucket repository.

bitbucket.org/org_name/repo_name/admin


Click Hooks in the left navigation.


###Step #2: Create a New "POST" hook for Distiller.

Click the “Select a Hook” dropdown and select POST from the dropdown list and click the "Add Hook" button.


</br>

###Step #3: Add the Distiller service hook url.

In the POST hook modal, enter the Distiller URL:  https://distiller.io/hooks/bitbucket

Save by clicking "Save" You're done. Now your repository will automatically build when you push.
