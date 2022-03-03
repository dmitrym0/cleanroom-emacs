cleanroom-emacs stores all emacs settigns in current directory; without impacting "main" emacs instance. Could be used to run multiple Emacs instances.

Instructions adapted from [here](https://emacs.stackexchange.com/questions/4253/how-to-start-emacs-with-a-custom-user-emacs-directory).

1. start emacs from here (`pwd`) using `./cleanroom-emacs.sh`. 
2. Use as you would normally.

For configuration, see it is loaded on startup [init.el](init.el).

Emacs modules, local settings, etc will be stored in `pwd`. 

This can be useful to test Emacs setup.

