---
layout: article
title: "Managing Shared Schemes"
category: project
order: 1
---

#Project - Managing Shared Schemes
---

In order to build and run your tests on Distiller (or any other continuous integration service), you must create Shared Schemes for your application target.

To create a Shared Scheme:

- Open up your project in Xcode.


- Open up the Manage Schemes sheet by selecting **Product > Scheme > Manage Schemes**.


- Locate the application target in the list. Make sure the “Shared” checkbox on the far right is checked.


![Manage Schemes Sheet](/img/14-manage-schemes-sheet.png)


</br>

- Check this file into your repository and use this Shared Scheme in your Distiller project configuration.


![Project Settings](/img/15-schemes-settings.png)


</br>

Your scheme should now be configured correctly.
