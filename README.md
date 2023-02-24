# Git Playground

This repo is a place to play around with Git commands—e.g. rebase and merge.

## Setup

Clone this repo:

```
git clone https://github.com/benchristel/git-playground
```

If you want to use commands that interact with remotes, like `fetch`, `pull`,
`push`, and `remote`, make one or two more clones of your local copy of the repo.

```
git clone /path/to/git-playground /tmp/git-playground-1
git clone /path/to/git-playground /tmp/git-playground-2
```

This works because `git clone`ing a directory on your machine works just like
cloning a repo from a service like GitHub or GitLab. Git is a _decentralized_
version control system, so any copy of a repo can clone, fetch, or push to any
other copy (if the user has the necessary permissions, of course).

## Make and commit changes

To make and commit a one-line change to the `scratch.txt` file, run `./commit`.
