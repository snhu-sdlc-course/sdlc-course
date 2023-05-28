# Required Software

## Required Software, Links, and Instructions

This class is designed around an Angular software project. You will use this project as the focus of most of your activities.

If you are using your personal computer (not the SNHU Java Virtual Lab --aka Apporto), you must install the software below.

{% hint style="warning" %}
The steps below are **only required** if you are using your own computer.
{% endhint %}

<table><thead><tr><th width="150">Software</th><th width="150">Version</th><th width="150">Download Location</th><th>Instructions</th></tr></thead><tbody><tr><td>Node/NPM</td><td>latest</td><td><a href="https://nodejs.org/en">https://nodejs.org/en</a></td><td>Install the one that matches your architecture.</td></tr><tr><td>Visual Studio Code IDE</td><td>latest</td><td><a href="https://code.visualstudio.com/">https://code.visualstudio.com/</a></td><td>Install the one that matches your architecture.</td></tr><tr><td>Git</td><td>latest</td><td><a href="https://git-scm.com/downloads">https://git-scm.com/downloads</a></td><td>Download and install the version that matches your Operating System.</td></tr><tr><td>Angular CLI</td><td>15.0.0</td><td><a href="https://angular.io/cli">https://angular.io/cli</a></td><td>Install using NPM. Instructions can be found at the link to the left.</td></tr><tr><td>Podman Desktop</td><td>latest</td><td><a href="https://podman.io/">https://podman.io/</a></td><td>Install the one that matches your architecture.</td></tr><tr><td>MongoDB</td><td>latest</td><td>N/A</td><td><a href="required-software.md#starting-a-mongodb-pod">Create a podman container</a></td></tr></tbody></table>

## Starting the MongoDB Pod

{% hint style="warning" %}
You must **ensure Podman is running** before continuing.
{% endhint %}

{% hint style="warning" %}
You should ensure Podman **auto-starts at login**. If you do not, you must manually launch it to provide access to MongoDB.
{% endhint %}

For simplicity, you will run MongoDB as a Podman container. After you install and start Podman, execute the code below in either a Bash/Zsh terminal or Windows PowerShell.

```bash
podman run mongo --name mongo -d --restart=unless-stopped mongo
```
