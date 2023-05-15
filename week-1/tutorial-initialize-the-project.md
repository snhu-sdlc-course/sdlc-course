# Tutorial: Initialize the Project

## Overview

You will be using a JavaFX application as the subject of your assignments throughout this course. Now, at the beginning of the course, is the time to get your IDE configured and ensure you can build and execute the project.

You are welcome to perform assignments related to this application on either your own computer or SNHU's Java Virtual Lab (also called Apporto).

This course uses the freely available [Eclipse IDE](https://eclipseide.org) software.

{% hint style="info" %}
**Using your own computer?** Ensure you have installed all required software by visiting the [Required Software](../introduction/required-software.md) page.
{% endhint %}

<details>

<summary>Video Walkthrough</summary>



</details>

## Clone the Git Project

1. Open a terminal (e.g., Git Bash for Windows, macOS Terminal, etc.)
2. I suggest cloning the project to your user directory. Run the script below in your terminal.

```bash
cd ~
git clone https://github.com/snhu-sdlc-course/snhu-library-catalog.git
```

{% hint style="info" %}
**Finding your project on Windows.** Your project is now located at `C:\Users\<your name>\snhu-sdlc-course`.

**Finding your project on macOS.** Your project is now located at `/Users/<your name>/snhu-sdlc-course`.
{% endhint %}

## Opening the Project in Eclipse

1. Open **Eclipse IDE for Java Developers**
2. Choose **File** > **Import...**
3. Expand the **Gradle** folder, choose **Existing Gradle Project**, click **Next**
4. Click **Next** again
5. Select the project directory for the **Project root directory** field
6. Click **Finish**

## Running the Project in Eclipse

Because the project is a **Gradle Project**, you can simply run a single Gradle task to download dependencies, compile the source code, and run the project.&#x20;

1. Choose **Window** > **Show View** > **Other**
2. Expand the **Gradle** folder
3. Choose **Gradle Tasks**
4. Expand the **Application** folder
5. Double-click **run**

{% hint style="info" %}
**What is Gradle?** Gradle is a build automation tool that developers use to define how their software projects should be compiled, tested, executed, and deployed.&#x20;

It also functions as a dependency management tool meaning it downloads external libraries required by a project.

For more information, visit their website: [https://docs.gradle.org/current/userguide/what\_is\_gradle.html](https://docs.gradle.org/current/userguide/what\_is\_gradle.html)
{% endhint %}
