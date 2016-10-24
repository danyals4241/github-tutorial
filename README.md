# GitHub Tutorial

by **Danyal Sarfraz**
- **All important terms will be bolded**
---
## Git vs. GitHub

##### What is Git?
Git is a software that runs in the command line which lets you **save and control your files**. In more technological terms you can call it a **DVCS** (_**Distributed Version Control System**_).

##### What is GitHub?
GitHub utilizes Git to **push ones changes to the cloud** to make sure they are **somewhere safe and accessible anywhere in the world**. This allows for **filesharing** across the globe. Making doing your projects easier if you are on the move constantly. You can call it a **"hub"** for **"git"**. It's a **server for multimedia sharing**.

##### So what is the difference?
Git is the software that **provides bases and mechanisms to share content and save it**, however GitHub is what utilizes that software to make it work. An easy way to know the difference is that GitHub is a "hub" for "git" to work on. Basically meaning GitHub is a server.

---
## Initial Setup
##### How do I start working on Git?
Before we create an account on [GitHub](github.com) we need to first setup our **IDE** or Integrated Development Environment.
- **Make sure your IDE is acceptable to be used and provides a SSH key. This will be helpful further on in the tutorial. A good IDE to use would be Cloud9. For further information visit their [website](c9.io). Here is a helpful [link](https://docs.c9.io/docs/setting-up-github-workspace) if you are interested.**

Once you have made sure you have an IDE that is compatible with GitHub proceed with these following steps:
* Go to [GitHub](github.com).
* Click the Sign Up button.
* Enter all required information in Step 1. 
* Once you are at Step 2 make sure you choose the free plan. You can choose the paid plan but for now for the sake of this tutorial we will keep with the free one.
* In Step 3 it is up to you to do the survey, you can skip it if you want.
* Now verify your email and we can continue with your IDE.
* **Make sure you research how to use GitHub. There are many resources online!**

Now it's time to link our GitHub to our IDE.
* Retrieve your SSH key, normally you would find it in a SSH keys tab. Google if you are having problems finding it!
* Copy the key and go to GitHub. **github > top-right > profile icon > settings
left sidebar > SSH keys**
* Paste it and add SSH key, before you add it make sure it starts with ssh-rsa. _Make sure you copy it correctly_.
* Return to your IDE, paste `ssh -T git@github.com` and press enter. You will be greeted by something like this 
```
Hi <your username>! You've successfully authenticated, but GitHub does not provide shell access._
```
* Now you're _done!_


---
## Repository Setup



---
## Workflow & Commands