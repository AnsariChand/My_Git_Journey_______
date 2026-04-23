Welcome to git & Github
An Ultimate Guide to Git and Github
Git is the most widely used version control System, helping developers track changes, collaborate, and manage code effectively. Github builds on Git by providing a cloud platform to host, review, and share project with ease.

1. Git enables version tracking, branching, and seamless teamwork.

2. Github Adds cloud hosting, pull requests, issues, and collaboration tools.

3. Together, they power open-source development and large-scale project management.

Introduction to Git
A Version Control System (VCS) is a Tool tracks and manages all changes made to your project, whether you work alone or in a team. As Your Project Grows and new Features are added, It Stores every version safely. This Allows you to access or restore any version without manually creating separate copies.

--> Eliminates the need for folders like MyProject, My ProjectWithFeature1, etc.

--> Makes rolling back or comparing versions quick, safe, and effortless.

Distrubuted Version Control System means every collaborator (any developer working on a team project) has a local repository of the project in his/her local machine unlike central where team members should have an internet connection to every time update their work to the main central repository.

So, by distributed we mean: the project is Distributed. A repository is an area that keeps all your project files, Images, etc. In therms of Github: different version of project correspond to commits.

Git Concepts

-> Repository - A Directory where git monitors your project files and records their revision history.

-> Clone - It Created a local copy of a remote repository on your machine.

-> Stage - It Selects specific changes that you want Git to include in the next snapshot.

-> Commit - It records the stages changes as a permanent version in the project history.

-> Branch - Lets you develop new features or experiment without affecting the main project.

-> Merge - Integrates changes from one branch into another.

-> Pull - It fetches and applies updates from a remote reposistory to your local one.

-> Push - It Uploads your locsl commits to a remote repository

Git Repository Structure
it Consists of Four Parts:

1. Working Directory: This is your local directory where you make the project (write code) and make changes to it.

2. Staging Area (or index): this is an area where you first need to put your project before committing. this is used for code review by other team members.

3. Local repository: this is your local repository where you commit changes to the project pushing them to the central repository on github. this is what is provided by the distributed version control system. this corresponds to the .Git folder in our directory.

4. Central Repository: This is the main project on the central server, a copy of which is with every team member as a local repository.

All the repository structure is internal to Git and is Transparent to the developer.

Some Commands which relate to repository structure:

// transfer your project form working directory
// to staging area.
Git add .

// transfer your project from staging area to
// Local Reposistory.
git commit -m "Your message here"

//transfer project from local to central repository.
//(requires internet)
git push

Working with existing repos (Git Clone) and new repos (git init)

Git allows you to manage existing repository as well as new one. You can clone remote repository to work on a project that already exist, or initialize a new repository to begin tracking changes in an fresh project.

-> Working
