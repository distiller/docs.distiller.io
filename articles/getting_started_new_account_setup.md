---
layout: article
title: "Setting Up a New Account"
---

#Getting Started - Setting up a New Account 
-------

Distiller is integrated with GitHub to make new account creation easy. GitHub has some wrinkles to their OAuth process that you’ll need to be aware of during the set up process.
</br>

###Connecting to GitHub

Go to the Distiller homepage and click "Sign up with GitHub." You will be redirected to GitHub (and asked to sign in if necessary). Click the "Authorize Application" button on the GitHub authorize page. 

Distiller asks for two separate scopes from Github:

- <code>user:email</code>  : We use this permission to email you build notifications if you choose to have them sent to you.

- <code>repo</code> : We use this to check out your repository when building.

GitHub does not have fine-grained repository access controls as part of their OAuth process. So, to give Distiller access, it’s all or none. Read AND Write. This is a known issue with the GitHub API. Feels like a pretty big issue to address. It does to us as well. You can go here and make your voice heard so GitHub changes their policy.

[Connecting with third party applications with GitHub] (https://help.github.com/articles/connecting-with-third-party-applications)

[Contact Github] (https://github.com/contact)

We understand this is a big ask. The nice thing about GitHub Oauth is that you can revoke access at any time without any intervention from us. 

Recognize it’s our business keeping your code safe and acting responsibly. Here are some resources to make you feel comfortable.

[Distiller Code Security Policy](https://www.distiller.io/security/)

[Utah Street Labs GitHub Organization Page] (https://github.com/utahstreetlabs)

[Rob Zuber's GitHub Profile] (https://github.com/z00b)

[Travis Vachon's GitHub Profile] (https://github.com/travis)

[Jim Rose's GitHub Profile] (https://github.com/jimdotrose) 


###Hacking around GitHub 

Not there? Well, we came up with a hack around the GitHub repository all or none scope. It’s not perfect, but can give limited access with some hiccups.

1. Create a new user account on GitHub (e.g. distiller-admin@yourcompany.com).
2. Give this new user admin access to the repository you want to build and deploy on Distiller.
3. Create a new account on Distiller with this new account. 

This will allow you to start building with Distiller. You just have to make sure that you log in with this account to the Distiller system.