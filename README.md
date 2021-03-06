# Hi There ð
My name is David Alejandro, Iâm preparing myself to be a DevOps engineer and study every day about different topics that could be interesting to youð§. Iâll try to be the clearest possible in each topic and let the bibliography if you want to search.

Test push 3

# Index

1. **[What is DevOps?](https://github.com/SrAlejo44/DevOps#what-is-devops)**
2. **[C.A.L.M.S. Framework](https://github.com/SrAlejo44/DevOps#calms-framework)**
3. **[DevOps Lifecycle](https://github.com/SrAlejo44/DevOps#devops-lifecycle)**
4. **[The three principles](https://github.com/SrAlejo44/DevOps#the-three-principles)**
5. **[Bibliography](https://github.com/SrAlejo44/DevOps#bibliography)**

## What is DevOps?
There are a lot of definitions about what is DevOps, but for me and what I have been researching it is a culture that starts with the objective to break the Wall between Developers and Operators but now DevOps is a methodology of work that we can use in all the product cycle to make faster and complete deployments, where we do guidelines to make a control about how we are progressing and where we can do better.

## C.A.L.M.S. Framework 
The CALMS framework is where we can see the DevOps culture in a more clear form.

### Culture ð
   - Responsability End to End.
   - Colaboration.
   - Continuous improvement.
   - Automation
   - Fault acceptance
   - Unite teams and experiences
### Automation ð¤
   - Eliminate manual processes.
   - Eliminate repetitive processes.
   - Everything as a code.
   - Continuous Delivery.
   - Toil concept.
### Lean ð®
   - Limit the accumulation of waste.
   - Limit the WIP (Work in process)
   - Reduce the size of gaps.
   - Reduce the number of handoffs.
   - Identify the restrictions and concerns.
   - Eliminate all the wast of our value flow.
### Measurement ð
   - LeadTime: When the ticket is created until it ends.
   - Process time: When the ticket started until I finished it.
   - Change Frequency: How frequent are the changes.
   - Change Failure Rate: Failure rate.
   - MTTR: Mean time to repair (How long it takes us to solve the problems).
### Sharing ð£
   - Break down silos to share between different areas.
   - Share knowledge
   - Better practices
   - Processes

## DevOps Lifecycle
The DevOps life cycle is the steps that the source code of software goes through to be deployed in an environment.
![Banner Image](image/devops_lifecycle.png)

### Plan 
  - Define a minimum set of functionalities that add value in each iteration and the acceptance criteria to be met. Communication between the business and the development team is key.
### Code
  - After defining the plan, we proceed to code the application according to the requirements agreed with the client. Here you start to develop the project software. These developments proceed in small processes in the development cycle. At the same time, you begin to define the tests that you must perform on your piece to ensure that it meets the functional requirements. On the part of operations, they begin the construction of the automation necessary for and of the software. The person in charge of the project ensures that the development team is reinforced with the use of security tools and possible attacks that this new piece of software may face.
### Build
  - Build the application with the integration of various codes that were made in the coding phase.
In this phase of the DevOps lifecycle, software development is continuous and iterative, with each part moving forward in the process. This is beneficial for the team as it speeds up the process and ensures delivery. 
### Test
  - Execute the tests to verify the correct operation of all the functionalities of the project. You should consider not only new tests but also those that ensure compliance with the specification of already existing functionalities. The QA team uses tools to identify and correct errors in the new code continuously, if any test is not satisfactory, the correction can be made by returning to the previous phase.
### Release
  - Once the application passed all the functional and integration tests, you can create a version of the software. The objective is to indicate what has happened with all previous validations, these validations can be used by users in the future. This phase integrates with existing code and tests are performed.
### Deploy
  - Then when all the tests were made and passed you could do the deployment in production.
### Operate
  - The operations team takes control of the application in production. They must ensure that there are no unusual or inappropriate behaviors, errors that can be found in production. They must alert other members of the team about the problems that have occurred, make immediate decisions (suspend, rollback, etc.) and plan the necessary improvements before returning to production.
### Monitor
  - In the last phase, you establish which are the parameters to monitor the application. We will collect all the information collected over a period of time to make necessary adjustments in the next planning phase. It is also in this phase that the operation team defines the measures to monitor and control the health status of the applications and their infrastructure.

## The three principles
These three principles are part of the culture of DevOps, they are made to remember how a DevOps Engineer should work and act in the team.

- **Flow:** Optimize the value flow that we are delivering, try to reduce multitasking because one piece flow to deliver value and share the knowledge correctly.

- **Feedback:** Failures are inevitable and inherent and you shuld use it to learn and share the new knowledge, fast bug detection and solve depent of how critical it is, reduce manuals inspections and approvals to make an agile work and quality is everyone's responsibility.

- **Continuos learning:** Failures are inevitable and inherent and you should use them to learn and share the new knowledge, fast bug detection and solve depending on how critical it is, reduce manual inspections and approvals to agile work finally quality is everyone's responsibility.

## Version control systems (VCS)
The version control systems are tools to manage the versions of your project recording changes made to files by keeping a track of modifications done to the code, it works like a database that saves your progress and it allows you to see the changes version to version, it works with repositories and some of them like GIT and GIT HUB works with branches.

### Types of VCS

- **Local Version Control Systems:** 
- **Centralized Version Control Systems:** 
- **Distributed Version Control Systems:** 

### GIT

#### Basic commands Linux

- **ls:** To show me the files in the carpet folder.
   - **ls -al:** To list all the files even the hidden ones.
- **cd:** To move between the folders.
   - **cd:** To move to user folder.
   - **cd /:** To move to home folder.
   - **cd ..:** To go back to the previous folder.
- **pwd:** To know in which folder are you.
- **clear:** To clear the console.
- **mkdir (foldername):** To create a folder.
- **touch (archivename):** To create an empty file.
- **cat:** To show quickly what are in one file.
- **history:** To see some all the history of your commands.
   - **!(number of the command):** To trigget the command in the list of history.
- **rm:** To remove a file or folder.
- **(command) --help:** To see some information about the command.

#### Basic commands GIT

- **git init:** To create a local repository in the folder that you are.
- **git config --global user.name "(name)":** To config your name, it's important because git saves each change and you have to know which person did the change.
- **git config --global user.email "(email)":** To config your email, it's important because git saves each change and you have to know which person did the change.
- **git status:** To show the status of your repository, principally if there are some untracked files and in which branch you are.
- **git add (filename):** Prepare the files to be committed (itÂ´s in the cache).
   - **git add .:** Add all files in the folder.
- **git rm --cached:** Remove the files from the cache.
- **git commit -m (comment):** To send the files in cache to the repository, it is important to send it with a commentary, **it is a good practice**.
- **git log (filename):** Show the history of all commits in this file.


## Bibliography
  - https://www.kranio.io/blog/introduccion-al-ciclo-de-vida-de-devops#:~:text=El%20ciclo%20de%20vida%20de,destino%20y%20ser%20una%20aplicaci%C3%B3n.
  - https://www.simform.com/blog/devops-lifecycle/#section2
  - https://www.geeksforgeeks.org/version-control-systems/
  - https://serengetitech.com/tech/introduction-to-git-and-types-of-version-control-systems/#:~:text=A%20local%20version%20control%20system,file%20since%20its%20last%20version.
