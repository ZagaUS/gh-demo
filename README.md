# gh-demo

[What is git?](https://git-scm.com/about/branching-and-merging)
  - VCS: version control system
  - DVCS: distributed version control system
    - what does that mean?

[Install the git cli](https://chatgpt.com/share/1548dfdd-a9d1-4875-a466-ff02b55d9efd)

How do we get helpful instructions on how to use the git cli?
  - `git --help`

How do we initialize a new local repository?
  - `git init`

Let's make some changes:
  - create a gh action workflow
    - see this [chatgpt inquiry](https://chatgpt.com/share/8be1ddb9-891a-4af8-9acb-80c5fa96ddf1)

Let's discuss status
  - `git status`
  - status tells us what is:
    - untracked
    - staged
    - other things we'll learn about later

What are commits?
  - how do we stage commits?
    - `git add`
  - how do we commit staged updates?
    - `git commit -m '<commit message>'`

Now that we've made a commit, what do we do with it?

Creating a remote repository
  - What is a remote repository?

What is cloning?
  - `git clone <url of remote repository>`
  - What is the origin?

Branching strategies:
  - trunk
  - GitFlow
