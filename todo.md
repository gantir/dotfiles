* Fish
** ~~install omf~~ (done - using Fisher instead)
** ~~omf install nvm~~ (done - nvm v22.16.0 configured in config.fish)
* Python
** ~~Add pyenv version to path~~ (switched to uv/virtualenv)
** ~~install python 3.7.10 and set it as default version~~ (managed via uv now)
* Node
** ~~nvm~~
*** ~~install nvm v10.15.3 and set it as default version~~ (now using v22.16.0)
*** ~~create .nvm directory~~ (done)
*** ~~need to figureout .nodeversion file and how to exactly set it depending on nvm~~ (resolved)
* Git
** ~~add p4v for diff and merge~~ (using vscode as diff/merge tool)
* Cleanup
** Replace bundled apps/misc/linux/eza-linux-x86_64 with actual eza binary when next using Linux
** Deprecated tmux syntax: tmux.conf uses -t vi-copy (deprecated in tmux 2.4+, should be -T copy-mode-vi)
** deploy/misc.fish uses sudo easy_install pip which is removed in modern Python -- update to use pip directly
** linux.arch profile references configs not present in meta/configs/ (arch_dependencies, i3, xmonad, etc.)
