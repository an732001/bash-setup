# bash-setup
My personal bash setup for macOS systems.

### 'subl' alias for Sublime Text
The following command should be added to `.bash_profile`
```alias subl="/Applications/Sublime\ Text.app/Contents/SharedSupport/bin/subl"```

### Make Sublime Text default text editor 

```git config --global core.editor "subl -n -w"```

## Setup git stuff in bash

```git config --global push.default upstream
git config --global merge.conflictstyle diff3```
