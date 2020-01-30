# Getting started with Git

## Git: the version control system

Open source software, developed by Linus Torvald, created to manage large open source project code.

## Prerequisites

Your laptop, Git installed \(installation instructions here : [https://git-scm.com/book/en/v2/Getting-Started-Installing-Git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git) - contains info for all platforms\)

If you got lost during the workshop, here is an extended version of the Git Tutorial you can use later: [https://swcarpentry.github.io/git-novice/reference](https://swcarpentry.github.io/git-novice/reference) 

## Finishing Git setup

Git relies on your name and email address to identify who did what on the code. Let's set that up

```text
(in command line interface - GitBash for windows, Terminal for others)
$ git config --global user.name "the name that will be displayed"
$ git config --global user.email "email you used for your GitLab/GitHub account"

```

This name and email address will be associated to all "commits" \(bundle of changes\) applied to the code.

You may also be aware that different system encore characters differently. Let's adjust Git behavior to sort it out.

```text
(in command line interface - GitBash for windows, Terminal for others)
git config --global core.autocrlf input #for MACOS/Linux users
git config --global core.autocrlf true #for Windows users
```

 



