<h1>Git Tutorial</h1>

Hi everyone,

This toy project serves as a tutorial for setting up Git in RStudio and practicing with common git commands.

Find and download the file Git-Installation-Guide.pdf. Follow each step in the guide.

If you encounter errors at any step, try copying the error message to ChatGPT and follow its advice. If you need more help with troubleshooting, please contact May Liu by emailing her at Yinuo.Liu\@nationwidechildrens.org or messaging her on Teams.

If you'd like to learn about the general ideas of Git and GitHub, please keep reading. If you already have a good knowledge of Git, skip the following introduction and go to Issues or YouTube playlist to start setting up.

<h2>Introduction of Git and GitHub</h2>

Let's get started by answering the first question: What is Git?

<h3>What is Git?</h3>

In short, Git is the most popular version control system. People use it to control and track different versions of a given project.

Version control allows team members to work collaboratively on a project. You can view changes made by other members, copy the newest code to your local file, and push any updates made by you to the cloud so other members can find it.

<h3>What is GitHub?</h3>

Git and GitHub are complementary technologies. GitHub is a cloud-based hosting service that helps teams conveniently manage their project. With GitHub, we can more easily use Git and code collaboratively.

<h3>How does Git work?</h3>

Here is an (incomplete) breakdown of how Git works. Don't worry about memorizing the functionalities. You will get a better idea of Git features after playing with them.

1.  Repository (Repo). A Git repository is a directory where all the files for a particular project are stored.
2.  Commits. Every change or set of changes that you finalize in Git is called a commit.
3.  Branches. Git allows you to create multiple lines of development using branches. The default branch is called master (where we are now). When you want to develop a feature or fix a bug, you can create a new branch.
4.  Merging. Once you're done with your changes on a branch, you can merge those changes back into the master branch.
5.  Remote Repositories. While you work locally on your machine, Git also allows you to connect to remote repositories. The most common remote repository is GitHub.
6.  Push and pull. Once connected to a remote repository, you can push your changes to it, allowing others to see and collaborate on your code. Similarly, you can pull changes from a remote repository to update your local version with the latest updates.
7.  Clone. If you want to have a copy of an existing Git repository, you use clone it. This creates a new directory on your machine with all the repository's files and history.

<h3>Something more on R and RStudio</h3>

Our task is to set up Git in RStudio, so we can more conveniently disucss code and synchronize updates. Before approaching Git, make sure you installed R and RStudio on your device.

R is the programming language, and RStudio is a user-friendly interface for R code.

You can download them in following websites:

R: https://cran.rstudio.com/

RStudio: https://posit.co/download/rstudio-desktop/

Be ready for your R trip with Git!
