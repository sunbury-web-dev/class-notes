# 📝 Week 2 Lab - Class Notes

A repository that can be used to take class notes and also practicing git. This repository will be used for working through Week 2's lab.

## Instructions

We'll start by forking this `class-notes` repository, opening up a Codespace on your forked version and then follow the below instructions.

##### Managing files with the commandline
* Open a terminal window and create a new directory called `test`
* Navigate to the `test` directory
* Create a new file called `test.txt`
* Open the file in VS Code and make a few changes, save the file and close it.
* Navigate back out of the `test` directory
* Delete the `test` directory

##### Adding a new file to the repository
* Create a new branch for the changes you are about to make.
* Create a new file in the `notes` directory with the name of the topic you want to take notes on. For example, if you want to take notes on git, create a file called `git.md`.
* Add some notes to the file. You can use [markdown](https://www.markdownguide.org/) to format your notes.
* Use `git add` to stage your changes for a commit, then use `git status` to view the current state of your project (you should see the file you just created).
* Commit your changes and push your new branch to [GitHub](https://github.com).
* Create a pull request to merge your branch into the `main` branch.
* Have someone else review your pull request and resolve any feedback.
* Merge your pull request into the `main` branch and delete your branch.
* Pull the latest changes from `origin` to your local machine and confirm your changes are there.
* Celebrate! 🎉

##### Practice using git to revert changes
* Try making another change to your notes
  * Create a new branch
  * Make a change (like adding a new file or changing an existing one)
  * Commit it
  * `push` it to `origin` and merge it into `main`
* Switch back to the `main` branch on your repository and `pull` your latest change.
* Use `git log` to see a list of your changes.
* Revert your changes by creating a new branch and reverting the commit that you made.
* Commit your changes and push your new branch to [GitHub](https://github.com).
* Create a pull request to merge your branch into the `main` branch.
* Have someone else review your pull request and resolve any feedback.
* Merge your pull request into the `main` branch and delete your branch.
* Pull the latest changes from `origin` to your local machine and confirm your changes are there.
* Celebrate! 🎉

An overview of these basic git commands can be found on the [Odin Project](https://www.theodinproject.com/lessons/foundations-git-basics).
