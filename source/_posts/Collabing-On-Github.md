---
title: Collaboration on Github
---

In order to Collab on Github, one user must create a repo, and then their partner(s) must then fork the main repo.

The collaboration process goes something like this:

When changes are made to the main repo, in order for the forked repo to be updated locally the **git fetch upstream** command is needed. From there, **git pull --rebase origin** will sync the changes locally.
When changes are made to the forked repo, the owner of the forked repo must open up a pull request to reflect the changes.