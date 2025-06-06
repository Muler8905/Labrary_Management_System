                            MEMBERS OF THE GROUP                       ID N0.
                         1, MULUKEN UGAMO ...........................  1501491
                         2, NEBIYU   TSEGAYE ..........................1501532
                         3, MAHLET   FEKADEWLD .........................1501381
                         4, HABTAMU  INKA     ..........................1501198
.Library Management System

This project demonstrates the conversion of a UML design to Java code using ArgoUML and manages project versions using Git and GitHub.

## Question 1: UML to Java Code Conversion

The UML diagram for the Library Management System was designed in ArgoUML, including classes for Book, Author, Member, Librarian, and Loan, along with their attributes, methods, and relationships. Java source code was then generated from this UML model.

## Question 2: Project Version Control

This section details the use of Git and GitHub for version control.

### Git Command Usage:

* `git init`: Used to initialize a new local Git repository in the project directory.
* `git add .`: Used to stage all changes (new and modified files) in the working directory to the staging area before committing.
* `git commit -m "Your message"`: Used to record staged changes to the repository with a descriptive message. Our initial commit was "Initial commit - Java code generated from UML".
* `git branch <branch-name>`: Used to create a new branch. We created the `LoanManagement` branch.
* `git checkout <branch-name>`: Used to switch to a different branch. We switched to `LoanManagement` to work on its features. (Alternatively, `git checkout -b <branch-name>` creates and switches).
* `git push -u origin <branch-name>`: Used to push local commits to a remote repository. The `-u` flag sets the upstream branch. We pushed `LoanManagement` to GitHub.
* `git pull origin <branch-name>`: Used to fetch and integrate changes from a remote repository into the current local branch. We pulled changes into our `main` branch after merging the PR.
* `git merge <branch-name>`: (Implicitly used during PR merge on GitHub) Integrates changes from one branch into another.

### Branching and Merging Flow:

1.  An `Initial commit` was made on the `main` branch with the generated Java code.
2.  A new feature branch, `LoanManagement`, was created from `main` to develop the `Loan` class functionality.
3.  Work was done and committed on the `LoanManagement` branch (e.g., implementing `borrowBook` and `returnBook` methods with validations).
4.  The `LoanManagement` branch was pushed to GitHub.
5.  A Pull Request (PR) was created on GitHub from `LoanManagement` to `main`. This allowed for review of the new features.
6.  After approval, the `LoanManagement` branch was merged into the `main` branch on GitHub, integrating the new functionality.
7.  Finally, the `main` branch on the local machine was updated by pulling the latest changes from the remote `main` branch on GitHub.
