---
layout: default
title: MonoGame / Tools
nav_order: 5
---

# MonoGame and Other Tools
{: .no_toc }

## Table of Contents
{: .no_toc .text-delta }

1. TOC
{:toc}

## Basic Information

We are using MonoGame 3.8.1 build 303 with Microsoft Visual Studio Community 2022.

## Links and Official Samples

* [MonoGame Homepage](https://www.monogame.net/)
* [Getting Started with MonoGame](https://docs.monogame.net/articles/getting_started/0_getting_started.html)
* [Official MonoGame Example Projects](https://github.com/MonoGame/MonoGame.Samples)

## Game Design Guides

* ["Let's Talk Games" - Game Design Primer](/assets/materials/GameDesignPrimer.pdf) by Timur Anvar

## MonoGame Labs and Tutorials

* [MonoGame Lab 1 - BoxBattle](https://docs.google.com/document/d/1_FJr9w4_pNbO0EDbcuHplrzEjYAJ59EA1NznisrcDIM/edit?usp=sharing)
* [Using the MGCB Editor](https://www.cs4730.org/modules/monogame/mgcb-tutorial/)
* [Tiled Tutorial](https://www.cs4730.org/modules/monogame/tiled/)

## MonoGame Tutorials (External)

* [Spritesheet Animation](https://www.industrian.net/tutorials/using-sprite-sheets/)
* [MonoGame Content Builder Information](https://docs.monogame.net/articles/tools/mgcb_editor.html)
* [http://rbwhitaker.wikidot.com/monogame-2d-tutorials](http://rbwhitaker.wikidot.com/monogame-2d-tutorials)
## Installing MonoGame

__Windows__ 

[Official Instructions @ https://docs.monogame.net/articles/getting_started/1_setting_up_your_development_environment_windows.html](https://docs.monogame.net/articles/getting_started/1_setting_up_your_development_environment_windows.html)

We will want to download the Community 2022 version of VS from the drop-down, but otherwise these instructions from MonoGame are accurate.

__Mac__

_NOTE: Tested on Intel chip_

Follow the same link as above to download Visual Studio 2022

When the installer asks what you’d like to install:

* .NET 
* .NET Multi-platform App UI 
* macOS (Cocoa)

This will take a while.

From the MonoGame github release channel [https://github.com/MonoGame/MonoGame/releases](https://github.com/MonoGame/MonoGame/releases), download `MonoGame.Templates.VSMacExtension_3.8.1.303.mpack`

Once Visual Studio is installed:

* Launch VS
* Go to Visual Studio -> Extensions…
* Click Install from file…
* Select the .mpack downloaded above. 

Clicking through the Oks, it will advise you that there was an error but installed it anyway. This is a known issue [https://github.com/MonoGame/MonoGame/issues/7960](https://github.com/MonoGame/MonoGame/issues/7960).

From the above issue report, the recommended course of action is to enter in the Terminal:

`dotnet new --install MonoGame.Templates.CSharp`

When you open VS and select New, a MonoGame Cross-Platform project template may appear as a Recent option. If not, go to the bottom under Other, then Custom, and select MonoGame Cross-Platform Desktop Application.

Note, after around 30 days, VS will warn you that your license has expired and require you to sign in to your Microsoft account to proceed. Logging in to the SSO for UVA was sufficient for continued access. 

## Git Resources
![Git Cheat Sheet](/assets/images/git-cheat-sheet.png?raw=true "Git Cheat Sheet")

### Tutorials
{: .no_toc }
There are several tutorials you should go through if you are not familiar with GitHub. 

* [https://try.github.io/](https://try.github.io/)
* [https://learngitbranching.js.org/](https://learngitbranching.js.org/)
* [https://rogerdudler.github.io/git-guide/](https://rogerdudler.github.io/git-guide/)
* [https://guides.github.com/introduction/flow/](https://guides.github.com/introduction/flow/)
* [https://guides.github.com/activities/hello-world/](https://guides.github.com/activities/hello-world/)
* [https://kbroman.org/github_tutorial/](https://kbroman.org/github_tutorial/)

### Authenticating to GitHub
{: .no_toc }

In many cases, such as using third-party services like we will be using, GitHub requires you to authenticate using an SSH key or GitHub token.  

* [Information on how to setup an SSH key and add it to your GitHub account for logging in](https://docs.github.com/en/github/authenticating-to-github/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent)

In practice, using an SSH key is a better solution than using a password.  However, it does take some time and effort to set up.  If you’ve never used an SSH key before, it’s very similar to using your NetBadge certificate to login to Collab.  There are two files that are generated - one is your private key (which you keep on your computer) and one is your public key (that you give to GitHub and other places you want to login to).  It’s kind of like generating your own key/lock combination, where you can give anyone the lock!

### Recommended Tools
{: .no_toc }

* [GitKraken](https://www.gitkraken.com/)
* [Tower](https://www.git-tower.com)
* [GitHub Desktop](https://desktop.github.com/)
