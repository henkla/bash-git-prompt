# bash-git-prompt
### version 0.1

[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)
[![Maintenance](https://img.shields.io/badge/Maintained-yes-green.svg)](https://GitHub.com/Naereen/StrapDown.js/graphs/commit-activity)
[![made-with-bash](https://img.shields.io/badge/Made%20with-Bash-1f425f.svg)](https://www.gnu.org/software/bash/)

This script will try and parse information about a git repository (if you are currently standing in one). It will display branch name, upstream name, porcelaine (dirty or not), how many untracked files there are (if any) and more.

## Example output
This is a sketch of how the ouput could end up looking:

> [master] [origin/master] [dirty] [4 untracked files]

> ~/../bash-git-prompt/ $

## Installation and how to use
1) Download the script file (git_prompt.sh)
2) Put it in your desired location (i.e. $HOME/.local/bin)
3) Make it executable (chmod +x /location/of/script/git_prompt.sh)
4) Make sure your .bashrc configuration knows the location of the script
5) Assign your PS1 (or prompt of choice) to the script: 
   > export PS1=$(git_prompt)\n$PS1 

## Resources
- https://gist.github.com/eliotsykes/47516b877f5a4f7cd52f
- https://emojipedia.org/slightly-smiling-face/
- https://gist.github.com/justintv/168835
- https://github.com/Naereen/badges
