# What I Learned in the Git & GitHub Course

In this Git and GitHub course, I learned many new things. Most of the information was new to me because I am a beginner in technology and programming. During this course, I learned how Git works and how to manage and track changes in a project.

## Git Basics

One of the first commands I learned was:

```bash
git init
```

This command creates the Git repository database and starts tracking the project. It is the first step when starting a project with Git, and it must be run in the correct project folder.

## Viewing Project History

I also learned commands that help me see the history of the project:

```bash
git log
git log --oneline
git log --oneline --graph
```

These commands show all commits in the project and help visualize the history, including branches and merges.

Other useful commands include:

```bash
git show
git diff
```

These commands show details about commits and the differences between changes in files.

## How Git Stores Data

One important thing I learned is that nothing in Git is random. Everything is organized and stored carefully.

Git stores data using different objects:

- blob
- tree
- commit
- tag

Each object has a unique **hash ID**, which allows Git to track every change in the project.

To ignore files that should not be tracked by Git, we can use:

```
.gitignore
```

## Branches

Git uses pointers, which means every commit remains in the history and does not disappear.

Branches allow developers to work on different features without affecting the main project.

Some important branch commands are:

```bash
git branch
```

```bash
git checkout
```

```bash
git merge
```

```bash
git branch -D
```

Sometimes a **merge conflict** happens when merging branches, but it can be solved by reviewing the changes and fixing the conflict.

## GitHub

GitHub is the remote version of Git. It allows us to store repositories online and collaborate with other people.

We can create repositories that are public or private and use them to work on projects with a team.

Some important commands when working with GitHub are:

```bash
git push
git pull
git status
```

These commands help synchronize the local Git repository with the remote repository on GitHub.

## Conclusion

This summary does not fully represent everything I learned in this course, but it highlights the most important concepts and commands that helped me understand Git and GitHub.
