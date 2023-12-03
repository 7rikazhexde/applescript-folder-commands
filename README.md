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

# Scripts

## For Git commands

### [ghRepoClone.workflow](./scripts/Git/README.md#ghrepocloneworkflow)

AppleScript to clone the specified repository based on the list of repositories obtained by the "gh" command

### [ghRepoCloneBranch.workflow](./scripts/Git/README.md#ghrepoclonebranchworkflow)

AppleScript to clone the specified repository and branch based on the list of repositories obtained by the "gh" command and "jq" command

### [gitPull.workflow](./scripts/Git/README.md#gitpullworkflow)

Applescript to execute "git pull" commands based on folder path information

### [ghRepoCloneBranchBy.workflow](./scripts/Git/README.md#ghRepoCloneBranchByworkflow)

Create a list of repositories registered on GitHub by executing curl/jq command with topic and number of items specified. In addition, based on the list, an applescript to clone the specified repository and branch.

## For VSCode

### [actVSCode.workflow](./scripts/VSCode/README.md#actvscodeworkflow)

Applescript to execute "code" commands based on folder path information
