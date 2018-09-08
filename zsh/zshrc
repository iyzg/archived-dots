#
# ~/.zshrc
#

# If not running interactively, don't do anything
[[ $- != *i* ]] && return

# Make Scripts GLOBAL
export PATH="$PATH:$HOME/bin"

# Set VIM as Editor
export VISUAL="vim"

# Aliases
alias ls='ls --color=auto'
alias pcinstall='sudo pacman -S'
alias pcupdate='sudo pacman -Syu'
alias pcclean='sudo pacman -Rs $(pacman -Qqdt)'
alias vim="nvim"

# Oh-My-ZSH
# PATH
export ZSH=/home/plasma/.oh-my-zsh

# Theme
ZSH_THEME="clair"

# Corrections
ENABLE_CORRECTION="true"

# Source
source $ZSH/oh-my-zsh.sh

