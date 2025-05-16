# starship-gim-module
[Git identity manager](https://github.com/samrocketman/git-identity-manager) is a handy way to manage multiple git identities. What can be a bit tricky is remembering, which identity is currently used at all times. If you use Starship for your prompt, this module will solve this problem.  

## <b>DISCLAIMER: NEITHER I NOR THE PROJECT ARE AFFILIATED IN ANY WAY WITH GIT IDENTITY MANAGER OR STARSHIP</b>

## Prerequisites
1. Use a Nerd Font in your terminal (as you should anyway, since you use Starship)
2. Install git-identity-manager and set up at least one identity

## Installation
1. Copy `starship.toml` and paste it at the bottom of your starship config (likely located at `~/.config/starship.toml`)
2. Add the module to your prompt format, to have it show up: `format = "$all$git_identity"`
