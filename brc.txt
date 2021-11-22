# .bachrc
[[ $- != *i* ]] && return

alias ls='ls --color=auto'
PS1='\h \W $ '



#
alias t='aria2c'
alias h='htop'

alias a='alsamixer'
alias m='mpd'
alias n='ncmpcpp'
alias l='ls -a'
alias i='sudo pacman -S'
alias u='sudo pacman -Syyu'
alias v='nvim'
alias vim='nvim'
alias g='ranger'
alias y='youtube-dl'
alias yl='youtube-dl -F'
alias yv='youtube-dl -f 22'
alias ya='youtube-dl -f 140'
alias p='poweroff'
alias pp='reboot'
alias mi='sudo make clean install'
alias b='newsboat'
alias yy="youtube-dl -ct --batch-file=/home/sh/Documents/y.txt"





alias fa="ffmpeg -framerate 20 -f x11grab -s 1366x768 -i :0.0+0,0 -f alsa -i hw:0 out.mkv"
alias f="ffmpeg -framerate 20 -f x11grab -s 1366x768 -i :0.0+0,0 out.mkv"
alias ff="ffmpeg -framerate 20 -f x11grab -s 1920x1080 -i :0.0+0,0 out.mkv"
