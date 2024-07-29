# applescript-folder-commands

AppleScript to run based on folder information

# TOC

- [applescript-folder-commands](#applescript-folder-commands)
- [TOC](#toc)
- [Scripts](#scripts)
  - [For Git commands](#for-git-commands)
    - [ghRepoClone.workflow](#ghrepocloneworkflow)
    - [ghRepoCloneBranch.workflow](#ghrepoclonebranchworkflow)
    - [gitPull.workflow](#gitpullworkflow)
    - [ghRepoCloneBranchBy.workflow](#ghrepoclonebranchbyworkflow)
  - [For VSCode](#for-vscode)
    - [actVSCode.workflow](#actvscodeworkflow)
  - [For QuickTime](#for-quicktime)
    - [show\_grid\_qt.workflow](#show_grid_qtworkflow)

# Scripts

## For Git commands

### [ghRepoClone.workflow](./scripts/Git/README.md#ghrepocloneworkflow)

AppleScript to clone the specified repository based on the list of repositories obtained by the "gh" command

### [ghRepoCloneBranch.workflow](./scripts/Git/README.md#ghrepoclonebranchworkflow)

AppleScript to clone the specified repository and branch based on the list of repositories obtained by the "gh" command and "jq" command

### [gitPull.workflow](./scripts/Git/README.md#gitpullworkflow)

AppleScript to execute "git pull" commands based on folder path information

### [ghRepoCloneBranchBy.workflow](./scripts/Git/README.md#ghRepoCloneBranchByworkflow)

Create a list of repositories registered on GitHub by executing curl/jq command with topic and number of items specified. In addition, based on the list, an applescript to clone the specified repository and branch.

## For VSCode

### [actVSCode.workflow](./scripts/VSCode/README.md#actvscodeworkflow)

AppleScript to execute "code" commands based on folder path information

## For QuickTime

### [show_grid_qt.workflow](./scripts/QuickTime/README.md#show_grid_qtworkflow)

AppleScript for arranging video files stored in specified folders in a grid format.
