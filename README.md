# git-practice

![](https://img.shields.io/badge/git-version%202.36.0.windows.1-red)

This repository is used as a playground to practice `GIT` commands.

## Prerequisites

1. Download `git` https://git-scm.com/
2. Recommended Editor: `vscode` https://code.visualstudio.com/

## Getting Started

1. Download this Github repository
2. Reimagine `_recipe.git` as the local remote repository
3. Extract `practice-package.zip` (See content explained [here](#practice-package-content))
4. **IMPORTANT** inside of each of the following folders:

- `/contributors/alpha/recipe`
- `/contributors/bravo/recipe`
- `/contributors/charlie/recipe`

Run the following command in CLI: `git restore .`

> **NOTE**: You are going to `push` and `pull` only on that local remote repository and not on this **Github** repository

# Practice Package Content

| folder         | description                                                           |
| -------------- | --------------------------------------------------------------------- |
| `_recipe.git`  | a local remote repository                                             |
| `contributors` | contains folders of developers working on the local remote repository |

## Scenario

The local remote repository contains `main` and `dev` branch.

- There are 3 developers/contributors having the names `alpha`, `bravo` and `charlie` are working on the same local remote repository.

- Each devs created their own folder to clone the repository
- All devs are branching out from `dev` branch
- ⚫ `alpha` is working on `feature/a` branch
- 🔵 `bravo` is working on `feature/b` branch
- ⚪ `charlie` is working on `feature/c` branch
- ⚫ `alpha` focuses on `chocolate` feature
- 🔵 `bravo` is focusing on the `creme` feature
- ⚪ `charlie` working on `caramel` feature

## _Other references_

https://github.com/lightzane/git-setup

[comment]: <> (https://www.sourcetreeapp.com/)
[comment]: <> (This app can visualize the branches of your GIT history)
