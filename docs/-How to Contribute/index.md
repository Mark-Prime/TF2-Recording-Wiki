---
icon: lucide/hand-helping
---

# How to Contribute

Contributions are more than encouraged and should be easy to do, but they should also be done through a proper review process.

Let's break down what that looks like.

## Clone the Source Code

!!! Prerequisites

    Must have :fontawesome-brands-git: installed.
    Can be installed through the [git website](https://git-scm.com/install/).

The code is visible and accessible within it's :fontawesome-brands-github: [Github Repository](https://github.com/Mark-Prime/TF2-Recording-Wiki).

Find where you would like to place the files and run the following command to clone the repository.

```
gh repo clone Mark-Prime/TF2-Recording-Wiki
```

Next create a branch.
Make the name relavant to the change.

```
git branch NAME
git checkout NAME
```

Alternatively:

```
git checkout -b NAME
```

You can access the files and edit the documentation.

## Option 1: Edit Markdown Alone

The easiest way to get started.
Allows you to edit the files directly without needing to install python or remember any console commands.

## Option 2: Running Locally

This is best for if you'd like to be able to properly interact with the website as you work.
It is nice to have but not strictly nessessary to contribute.

!!! Prerequisites

    This set of documentation uses Zensical which requires Python and a Python Package manager installed.
    Python can be downloaded on the [Python Website](https://www.python.org/downloads/).
    The full [Python Setup and Usage](https://docs.python.org/3/using/) guide is available for further instructions.

### Zensical

The documentation here is built using Zensical. For full documentation visit [zensical.org](https://zensical.org/docs/).

#### Installation

Follow the [installation guide](https://zensical.org/docs/get-started/) on the Zensical website for your operating system.

#### Starting Zensical Locally

While there are more commands within Zensical, there is only one commanded needed to help contribute:

* [`zensical serve`][serve] - Start local web server
  
  [serve]: https://zensical.org/docs/usage/preview/

## Pushing your changes

Once you've finished editing or adding to the documentation, it's time to submit your code.

First create the commit with a commit message. The message should be brief but explain generally what was changed.

```
git add .
git commit -m "Added git comamnds to How To Contribute"
```

Then push to your branch.

```
git push
```

Now you can create a pull request on the [Github Website](https://github.com/Mark-Prime/TF2-Recording-Wiki/compare).
