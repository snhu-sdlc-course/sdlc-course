---
description: Initialize the Project
---

# Assignment 2-2

## Overview

You will use an Angular application as the subject of your assignments throughout this course. Now, at the beginning of the course, is the time to get your IDE configured and ensure you can build and execute the project.

You are welcome to perform assignments related to this application on either your own computer or SNHU's Java Virtual Lab (also called Apporto).

This course uses the freely available [Visual Studio Code IDE](https://code.visualstudio.com/download) software.

{% hint style="info" %}
**Using your own computer?** Ensure you have installed all required software by visiting the [Required Software](../introduction/required-software.md) page.
{% endhint %}

{% hint style="success" %}
**Do you have a GitHub account?** You will need a GitHub account for this class. If you do not already have one, please create one here: [https://github.com/signup](https://github.com/signup)
{% endhint %}

<details>

<summary>Video Walkthrough</summary>



</details>

## Fork and Clone the Git Project

1. Navigate to the SNHU SDLC Course project in GitHub:
2. Click the "Fork" button in the top right-hand corner of the web browser\
   ![](<../.gitbook/assets/image (3).png>)
3.  Ensure your **repository name** is `snhu-library` and click <mark style="color:blue;">**Create Fork**</mark>

    <figure><img src="../.gitbook/assets/image (1).png" alt=""><figcaption></figcaption></figure>
4. Once the fork is complete, open a terminal (e.g., Git Bash for Windows, macOS Terminal, etc.)
5. Clone the project to your user directory. Run the script below in your terminal. **Be sure to replace** `<your username>` **with your GitHub username.**

```bash
cd ~
git clone https://github.com/<your username>/snhu-library.git
```

{% hint style="info" %}
**Finding your project on Windows.** Your project is now located at `C:\Users\<your name>\snhu-library`.

**Finding your project on macOS.** Your project is now located at `/Users/<your name>/snhu-library`.
{% endhint %}

## Opening the Project in VS Code

1. Open **Visual Studio Code**
2. Choose **File** > **Open Folder...**
3. Select the cloned project folder (see the hint above if you aren't sure where to find it)
4. Click **Open**

## Project Structure

{% hint style="success" %}
**Helpful!** The diagram below will tell you where to find files you must change as part of your assignments later.
{% endhint %}

The application is a traditional 3-tier, mid-tier application. It consists of three main parts:

* **Front-end:** a client-side _Angular_ JavaScript application
* **Back-end:** a server-side _SailsJS_ JavaScript application
* **MongoDB:** the server-side MongoDB NoSQL, document database

<figure><img src="../.gitbook/assets/image (2).png" alt=""><figcaption><p>Fig. 1: App Structure</p></figcaption></figure>

## Preparing to Run the Project (i.e., Installing Dependencies)

{% hint style="warning" %}
You only need to install the dependencies **once.**
{% endhint %}

{% hint style="info" %}
**What is NPM?** Node Package Manager is a **dependency management tool** used for JavaScript projects. It comprises two parts: a command line client and an online database of all the available packages.
{% endhint %}

Before [#running-the-project-in-vs-code](assignment-2-2.md#running-the-project-in-vs-code "mention"), you must install all the requisite dependencies.

1. After [#opening-the-project-in-vs-code](assignment-2-2.md#opening-the-project-in-vs-code "mention")
2.  Expand **Explorer** panel on the left

    <img src="../.gitbook/assets/image (2) (1).png" alt="" data-size="original">
3.  Expand **NPM Scripts** at the bottom of the _Explorer_ panel

    ![](<../.gitbook/assets/image (1) (1).png>)
4. Run the `install` script of the `backend` project by clicking the ▶️ button next to `install`
5. Run the `install` script of the `frontend` project by clicking the ▶️ button next to `install`

## Running the Project in VS Code

Because the project (i.e., its two subprojects) uses NPM, we will use NPM scripts to automate the build and run processes.

{% hint style="info" %}
**NPM is also a simple build automation tool.** It has a feature called _scripts_ that allows you to run scripted command-line tasks.
{% endhint %}

{% hint style="warning" %}
**Start the database.** Ensure the Podman MongoDB container is running. The backend project will not run properly without the database being available. If you aren't sure it is running, see [#starting-the-mongodb-pod](../introduction/required-software.md#starting-the-mongodb-pod "mention").
{% endhint %}

1. After [#opening-the-project-in-vs-code](assignment-2-2.md#opening-the-project-in-vs-code "mention")
2.  Expand the **Explorer** panel on the left

    <img src="../.gitbook/assets/image (2) (1).png" alt="" data-size="original">
3.  Expand **NPM Scripts** at the bottom of the _Explorer_ panel

    ![](<../.gitbook/assets/image (1) (1).png>)
4. Run the `start` script of the `backend` project by clicking the ▶️ button next to `start`
5. Run the `start` script of the `frontend` project by clicking the ▶️ button next to `start`

{% hint style="success" %}
**You should always start both the front-end and back-end projects.** The front-end project makes API requests to the back-end project. The back-end project communicates with the database.
{% endhint %}

{% hint style="success" %}
**Both projects will **_**hot reload**_. This means the projects will rebuild and redeploy automatically as you make code changes.
{% endhint %}

## Rubric

