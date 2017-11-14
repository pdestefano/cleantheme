---
layout: guidelines
title: Git and Branches
heading: Git and Branches
permalink: /guidelines/contrib-code/
---

Git and Branches information...

In short, the master branch is always the head of latest development. Anything
merged into master should be of such good quality that at any time a snapshot
from master passes all tests, and can be deployed. That is not to say that it
will be free of bugs; we are not superhuman.

All real work should be done in feature branches. It is still OK to make a
small trivial change directly in the master. Stuff like editing the README.
