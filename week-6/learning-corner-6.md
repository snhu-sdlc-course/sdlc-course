---
description: Project Management Tools and Communications Tools
---

# Learning Corner 6

## Project Management Tools

Any non-trivial Agile projects involve multiple people working on multiple tasks. To be effective, they need a way to coordinate and track their efforts. In the past (before the explosion of SaaS products and distributed teams), it was common to have physical Kanban boards in offices (see Figure 1).

<figure><img src="../.gitbook/assets/image (4).png" alt=""><figcaption><p>Fig. 1: Pysical Kanban Board in Office</p></figcaption></figure>

Tools that facilitate the flow of information and promote _openness and transparency_ are called **information radiators**. Information radiators ensure that:

* Everyone on the team is aware of the work of all other team members;
* The Product Owner and other stakeholders are aware of the team's progress and any issues;
* Customers and stakeholders are involved and participate in a partnership between themselves and the Scrum team; and,
* Management does not have to control all aspects of the operation (Cobb, 2015, pg. 140).

Agile project management tools should support the values outlined in the Agile Manifesto. To that end, Madhuri (2023) lists these essential features of an Agile Project Management tool:

* **Performance Tracking.** The tool should track each team member's tasks and make that information apparent to the entire team. It should also track the team's velocity, which is necessary for the team's estimation efforts. Finally, the tool should provide a clear measure of both the current Sprint's and the project's completion measures. Implementations include:
  * Burn-down/Burn-up charts
  * Gantt charts
  * Story point metrics
  * Dashboards
  * Kanban charts
* **Obstacle Identification.** Obstacles might include bugs, dependencies, and limited team member availability. This feature often comes in the form of:
  * Task linking to show inter-task dependencies and bugs that may be blocking tasks
  * Alerts and reports showing tasks that are in danger of not being completed in the current Sprint
  * Gantt charts showing dependencies among tasks.&#x20;
* **Teamwork.** The tool should encourage team members to tackle the project collectively. Modern tools usually achieve this through knowledge-sharing and collaboration features. Examples include:&#x20;
  * Commenting on user stories
  * Tagging co-workers in comments and documentation
  * "Sharing" user stories, files, and other media with team members
  * Wikis
* **Customer Portal.** One of the most important Agile values is "Customer collaboration over contract negotiation." To that end, the customers must be able to participate in the process, which includes using the Agile Project Management tool. This often looks like:
  * Customer-accessible forms to submit feature requests and bug reports
  * Limited-privilege customer roles that can access most of the system
  * Feedback forms that can be integrated into the end product and, when submitted, generate new feature requests or bug reports
* **Time Estimation.** While user stories are not estimated in days, Sprints are still time-boxed. Modern tools should use the time-box duration to project a project schedule. It is common for tools to allow Sprints:
  * To be added Epics,
  * Assigned to "milestones,"
  * And grouped in other ways.

With the popularization of Continuous Integration/Continuous Deployment, modern Agile Project Management tools have added features that blur the lines between _change management_, _project management_, _environment management, quality assurance_, and _release management_. A discussion of these features is outside the scope of this module, but you can read about how several popular Agile Project Management tool offerings integrate with CI/CD tools here:

* GitLab links code merge requests (and their CI/CD information) to issues (user stories): [https://docs.gitlab.com/ee/user/project/issues/crosslinking\_issues.html#from-linked-issues](https://docs.gitlab.com/ee/user/project/issues/crosslinking\_issues.html#from-linked-issues)
* Jira links tickets (user stories) to merge requests and displays the CI/CD status and release status on the tickets: [https://www.atlassian.com/devops/imagelabeller-intro/jira-cicd-integration](https://www.atlassian.com/devops/imagelabeller-intro/jira-cicd-integration)
* Azure Boards provides similar capabilities: [https://learn.microsoft.com/en-us/azure/devops/boards/work-items/work-item-deployments-control?view=azure-devops](https://learn.microsoft.com/en-us/azure/devops/boards/work-items/work-item-deployments-control?view=azure-devops)

Finally, your textbook gives a thorough examination of the VersionOne enterprise, Agile project management system starting on page 145.

## Communication Tools

### Synchronicity

While Agile Project Management tools offer several ways to communicate (e.g., assigning tickets, tagging people, and comments), and e-mail is always an option, both of these lack a key ingredient of Agile communication: _**synchronicity**_. Agile communications _should_ be **synchronous**.&#x20;

The Agile Manifesto's twelve underlying principles include this:

> The most efficient and effective method of conveying information to and within a development team is face-to-face conversation (Beck et al.)

The bottom line is you should always prefer face-to-face communication when and where possible. In the past, the co-location of teams made this a moot point. However, it is increasingly common for teams to be distributed across multiple time zones, requiring communication tools.

{% hint style="info" %}
You should choose communication tools that provide at least two forms of _synchronous_ communication: _**instant messaging**_ and _**video conferencing**_.&#x20;
{% endhint %}

### Permanence and Searchability

Your communications can (and probably will) serve as forms of requirements documentation. This means _they should be preserved!_ The tools you choose should permanently capture written communications (instant messaging) by default and optionally capture video communications.

You want to be able to find your discussions and decisions about product features easily. This means you want a tool that offers a high-quality and easy-to-use search engine for your written communications.

{% hint style="success" %}
Choose a tool that **permanently stores** instant messaging conversations by default and that makes them **easily searchable**.
{% endhint %}

### Screen Sharing and Recording

<figure><img src="../.gitbook/assets/image (11).png" alt="" width="375"><figcaption><p>Fig. 2: MS Teams Screen Sharing</p></figcaption></figure>

Pair programming and Swarming are pivotal to successful Agile software projects. For distributed/remote teams, these practices are impossible without the ability to screen share. Commonly, the information gained while solving a problem needs to be shared with the rest of the team; hence, it is important that your tool offer the ability to record sessions.

There are many other times when screen sharing and recording are important. Examples include:

* Recording product demos to share with clients
* Recording brainstorming sessions with clients to document requirements and decisions
* Recording design sessions with the development team and Product Owner to capture the team's plans

### Grouping and Categorizing Communications

<figure><img src="../.gitbook/assets/image (2).png" alt="" width="375"><figcaption><p>Fig. 3: MS Teams Channel</p></figcaption></figure>

Whatever tool you choose should allow the team to categorize (i.e., label) and group communications. It is common for two or three members of an Agile team to work together on user stories (e.g., a tester and a developer, two developers working on the same part of a system, a developer and the product owner, etc.) Communication tools should support creating a "thread" of communication for this group of people.

Similarly, it is common for varying numbers of people to collaborate on the same user story or bug over time. For these cases, the tool should support creating a "thread" of communication for a specific feature or issue.

Examples of this feature include "Channels" in Slack and "Conversations" or "Channels" in Microsoft Teams.

### File Sharing

<div align="center">

<figure><img src="../.gitbook/assets/image (9).png" alt="" width="375"><figcaption><p>Fig. 4: Slack File Sharing</p></figcaption></figure>

</div>

Your tool should support sharing files with other members. You should also be able to share files to groups (see the paragraph above).

### Integrations

<figure><img src="../.gitbook/assets/image.png" alt="" width="375"><figcaption><p>Fig. 5: GitLab for Slack App</p></figcaption></figure>

Finally, your tool should support integrating with the various components of your Project Management tool and CI/CD pipeline. This includes connecting to:

* The _project management_ tool so you can link conversations to specific issues
* Your _source code repository_ so you can mention specific changes in code or branches created for implementing fixes/features in your conversations
* Your _continuous integration tool_ so you can mention or reference specific builds, automated test results, or code scans in your conversations

## References

* Beck, K., Beedle, M., van Bennekum, A., Cockburn, A., Cunningham, W., Fowler, M., Grenning, J., Highsmith, J., Hunt, A., Jeffries, R., Kern, J., Marick, B., Martin, R. C., Mellor, S., Schwaber, K., Sutherland, J., & Thomas, D. (n.d.). _Principles behind the Agile Manifesto_. Retrieved July 1, 2023, from https://agilemanifesto.org/principles.html&#x20;
* Cobb, C. G. (2015). _The Project Manager’s Guide to Mastering Agile_. Wiley.
* Madhuri, T. (2023, May 29). _Agile Project Management Tools | Key Features and Various Types of Agile_. EDUCBA. https://www.educba.com/agile-project-management-tools/
