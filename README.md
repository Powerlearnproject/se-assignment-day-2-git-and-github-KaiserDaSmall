[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/8wgCKhpZ)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=18482510&assignment_repo_type=AssignmentRepo)
# se-day-2-git-and-github
## Explain the fundamental concepts of version control and why GitHub is a popular tool for managing versions of code. How does version control help in maintaining project integrity?
  Version control is a computer system that records the changes made to a project. This allows the user to access those previous versions called repositories incase they wish to make changes. The most popular of these repositories is a cloud based repository called github. Github is extremely popular amoungst developers due to how user friendly it is, featuring features such as forking which allow for easy collaboration and building of large communities as well as it's integration with Git, which itself is a powerful version control system. 
  Version control's importance cannot be understated in maintaining project integrity. Version control allows for better collaboration by allowing multiple developers to make changes without inerfering with changes made by other developers, creation of backup for code by storing it in a remote repository and keeps a record of all changes made incase each change needs to be tracked or undone.

## Describe the process of setting up a new repository on GitHub. What are the key steps involved, and what are some of the important decisions you need to make during this process?
  You start by signing into your Github account.
  You then move your cursor to the top right side of the screen, click 'create new' drop down menu and then select "new repository".
  Then you setup your repository to your liking. This involoves naming your repository, choosing whether to make it public or private, choosing whether or not to add a read 
  me file or choosing whether or not to make your reopsitry open source. 
  Once all that is done you click create repository. Doing so should open 
  The next step is to clone your repository locally. You do this by typing in the command line/powershell.
  Then that's it, all that's left to do is start working on it.
  
## Discuss the importance of the README file in a GitHub repository. What should be included in a well-written README, and how does it contribute to effective collaboration?
  A README file is important because it explains exactly what the project is about to anyone who comes across your repository helping them understand the project and how       they may wish to contribute. 
  Thus a well written README should include:
    A project title to convey the main goal of the project
    Description to let other developers know what the appliction does, why it was made and any challenges it may be facing
    How to use the project so they don't get stuck or incase you added anything like a password
    How to install it incase there are any special dependencies or ways of setting it up
    How the project is to be used 
    Mentions of anyone else who has made contributions to it
    A license so other developers know what they can and cannot do to your project
    
## Compare and contrast the differences between a public repository and a private repository on GitHub. What are the advantages and disadvantages of each, particularly in the context of collaborative projects?
  The key difference between the two is public repositories are accessible to anyone whilst private repositories are visible to one person and the few others they allow to     have access to them. These differences create distinct advantages and disadvantages for each. For instance:
  Security risks: Public - there is a greater risk of leaking sensitive information on a public repository
                  Private - the risk of exposing sensitive information is virtualy none existent due to the ability to choose who gets to see it
  Visibility: Public - public visiblities allows for the attraction of many more collaborators with a greater wealth of experience than your own.
              Private - limited exposure leaves fewer opportunities to collaborate with people 
  Feedback: Public - feedback is more frequent and problems can be solved much more quickly
            Private - feedback could be infrequent with problems taking a greater amount of time to resolve
  
## Detail the steps involved in making your first commit to a GitHub repository. What are commits, and how do they help in tracking changes and managing different versions of your project?
  A commit is a snapshot of the changes one makes to the entire project at a specific point in time. Commits track data by recording additions and subtractions made to the     script, edits made, who made those edits, when they did it and it also gives a description of the changes. Commits also help in managing previous versions by allowing for    code reviews, let's you see different versions of said project.
  
## How does branching work in Git, and why is it an important feature for collaborative development on GitHub? Discuss the process of creating, using, and merging branches in a typical workflow.
  Branching is creating a parrallel version of the repository so you can add features, expirement or fix bugs without making changes to the main one. 
  Branching is exteremely important for collaborative development because it allows for multiple developers to do different repositories at once without affecting the main     one. 
  Branching allows the developers to also experiment with no ideas
  Branching also reduces the likely hood of conflict arising due to changes
  Branching can also be used to manage different versions of the project for release
  To create a new branch you simply type "git_branch"
  To switch to a new branch you simply type "git checkout"
  To merge a branch you simply type "git merge"
  
## Explore the role of pull requests in the GitHub workflow. How do they facilitate code review and collaboration, and what are the typical steps involved in creating and merging a pull request?
  The role of a pull is a formal channale used to propose changes to the main repository by submitting their code to be reviewed by the rest of the team allowing for       
  feedback and discussion as to whether or not to go through with the changes. 
  To create a formal pull request you click "new pull request" in your repository, select the main repository and the branch repository, add a description decribing what the   changes are for along with a title and after that create the pull request. Assuming the pull request gets approved along with all the checks being passed the only thing left to do is get on to GitHub and click the "merge commit" button

## Discuss the concept of "forking" a repository on GitHub. How does forking differ from cloning, and what are some scenarios where forking would be particularly useful?
  Forking is making a copy of someone else's repository on your Github account specifically whilst clonig creates tha same copy on your local machine. Forking is useful for when you wish to co operate on open source projects, making a personalized copy for yourself, learning and practicing for yourself and creating back ups.

## Examine the importance of issues and project boards on GitHub. How can they be used to track bugs, manage tasks, and improve project organization? Provide examples of how these tools can enhance collaborative efforts.

## Reflect on common challenges and best practices associated with using GitHub for version control. What are some common pitfalls new users might encounter, and what strategies can be employed to overcome them and ensure smooth collaboration?
