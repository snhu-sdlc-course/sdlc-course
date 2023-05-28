---
description: Scrum Developers
---

# Learning Corner 4

## Preface

Whereas previous _Learning Corners_ have covered the primary material for those weeks, this _Learning Corner_ seeks to provide you with practical knowledge beyond what your textbook and other required resources cover.

## What is a Scrum Developer?

Scrum only lists three roles:

* Scrum Master
* Product Owner
* Developer

However, anyone who has participated in software development knows many other roles are required to bring a product to completion. Most of those other roles fall under the "developer" role.

Scott Richards (2021) provides an excellent definition of _Scrum Developer_:

> Anyone that is important to create increments of value for a Product. Coder, Tester, UX, BA, Operations, Marketing, Sales Expert, Juggler...

The bottom line is this: if a worker directly contributes to the creation, quality assurance, or deployment of a product, they are a developer. As Richards demonstrates with his list of job titles that might be included under the Scrum Developer role can vary greatly depending on the industry and product.

## Scrum Developers on a Software Team

### Job Titles of Scrum Developers

On a software development team, the _Scrum Developer_ role will often include:

* Developers (programmers, engineers, coders, etc.)
* Testers
* Configuration Managers
* User Interface/User Experience Designers
* Graphics Artists
* Technical Writers
* DevSecOps engineers
* System Administrators
* Cyber Security Engineers and Analysts
* Software Architects
* Cloud Architects and Engineers
* Database Administrators

### Importance of Acceptance Criteria

The _Acceptance Criteria_ are the bread and butter of Scrum Developers. On a software project, the software developers build features to satisfy the _acceptance criteria,_ and _testers_ write and execute test scripts that verify the _acceptance criteria_.&#x20;

### Updating Your User Stories

As a developer, you should update the comments/notes of your user story in the ticketing system your team uses. Your comments should cover the design and implementation decisions you make that impact what and how the testers should do their jobs. You should also include information that could be helpful to you or other developers who perform maintenance on the system at some point in the future.

### Definition of Done (DoD)

A team will have several Definitions of Done. Examples include:

* Project-level DoD;
* Development DoD;
* Testing DoD; and,
* Deployment DoD.

The development DoD typically includes activities developers must complete and quality gates their changes (i.e., code) must pass.&#x20;

A development DoD can be effectively represented in the form of a checklist. Common items in a development DoD include:

* Code maintains 85% coverage or more by unit tests;
* All changes are committed to the code repository;
* At least one developer has reviewed and passed your changes;
* The changes have passed all quality gates of the static code analysis tool;
* Release notes have been updated;
* User manuals have been updated;
* The status of the user story ticket has been updated;
* Dependency scans for vulnerabilities and licensing issues have passed; and,
* All pre-existing unit and integration tests pass.

### Relationship to Testers

Developers and Testers must work closely together to be successful. Historically (e.g., using _Linear Sequential_ models), developers would toss their work over the proverbial "wall" to testers and forget about it.

In Agile frameworks, developers and testers collaborate on user stories to get them across the finish line to deployment. Developers and testers must have a shared vision for what satisfied acceptance criteria look like. The developers must be building a product that looks and behaves the way testers' test scripts expect them to.

If there is enough time left in the sprint and the scope of a discovered issue is small enough, there will be a back-and-forth between testers and developers to quickly resolve the issue. Otherwise, the issue will be logged as a new user story (or bug ticket) to be worked in a future sprint.

On Agile teams, quality assurance is typically performed in phases, as depicted in the graphic below:

![Fig. 1: Phases of Quality Assurance on an Agile Team](<../.gitbook/assets/image (2) (1).png>)

## Estimating with Story Points

Your textbook and other readings cover this topic well. Therefore, I will only provide some advice based on my experiences.

When you join a Scrum team, you will have to determine what _Story Points_ mean to that team.&#x20;

If the team is well-established, they will already have assigned values to _Story Points_. In that case, you make a deliberate effort to learn what those values are. My suggestions:

* Study their user stories in the ticketing system to determine their complexities and scale; then, compare the complexity and scale of each user story to their assigned points
* Set your pride aside and defer to their estimations for a sprint or two until you have a good feel for what Story Points mean to the team
* If available, use the team's Story Point Matrix
* Learn what sequence the team uses for its Story Points (most use the Fibonacci Sequence because the growing difference between one number and the next makes comparison far easier and the differences in user story sizes starker)

If the team is newly formed, they will not have reached _their own_ value for _Story Points_ and will need starting values. My suggestions:

* Determine an initial meaning for 1 Story Point (e.g., an Ideal Day's worth of work) and adjust the meaning of Story Points as you all gain experience
* Work with the team to build a Story Point Matrix

Here's a great [article on Story Point Matrices](https://www.linkedin.com/pulse/cheat-sheet-story-point-sizing-neeraj-bachani/) and the image below is a good example of one you could use.

![Fig. 2: Story Point Matrix](<../.gitbook/assets/image (5) (1).png>)

## Swarming

_Swarming_ is a practice Scrum teams use to complete high-priority work or help a team member get past a tricky problem. Swarming is said to occur when "as many team members as possible work simultaneously on the same priority item. And they work on just that one item until it is done" (Sutherland, 2020).

I worked with an amazing company called Analyst1 for just over a year. Analyst1 had the best Agile culture I've experienced, and one of the team's greatest strengths was _swarming_ on problems anytime a member hit a roadblock. If someone encountered a problem I didn't know how to solve, everyone else would stop what they were doing and jump on that one problem until it was resolved.&#x20;

This practice had several benefits beyond the face value of solving the problem. I will leave those for you to brainstorm in [discussion-4.md](discussion-4.md "mention").

I encourage you to read this great article about Agile Swarming:

{% embed url="https://www.teamly.com/blog/agile-swarming/" %}

## References

* Richards, S. (2021, September 3). _What is a Developer in Scrum?_ Serious Scrum | Medium.Com. https://medium.com/serious-scrum/what-is-a-developer-in-scrum-e9234aa0501e
* Sutherland, J. (2020, January 22). _Swarming: Instantly Boost Scrum Team Productivity, Here’s How..._ Scrum Inc. https://www.scruminc.com/swarming-instantly-boost-scrum-team-productivity/
* Vige, W. (2022, April 25). _Story Points: Your Guide to Estimating User Stories in Agile • Asana_. Asana Resources. https://asana.com/resources/story-points
