
# Private dotfiles sample

This is a sample meant to be used with my [dotfiles repository]().

I store local and private dotfiles in separate folder and repository for easy 
maintenance. When installing a new machine I only have to change the 
~/.dotfiles-\* repositories:

- .dotfiles-private: private settings (accounts, personal URL…)
- .dotfiles-local:   local settings (monitor, DPI, themes, performances …)

Note that, when possible, the configuration use *Unix pass*, for safety reasons.
You can fork this repository and push it to a private one, then clone it in 
~/.dotfiles-private (by default):

    git clone <your-private-repository-url> ~/.dotfiles-private
    cd ~/.dotfiles-private
    # edit files with your settings, stage, commit and push

Be aware that pushing this to a public repository would expose your personal 
data. You can for example add an alert message every time you commit to the 
repository using a git hook.

