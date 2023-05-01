# my-bspwm-config
this is my bspwm config feel free to copy it

----------------------------------------------
requirements:
bspwm

sxhkd

feh

xfce4-panel

xfce4-terminal

linux

picom

xorg

xsetroot

xinit

use your package manager for example I use pacman so I put in: pacman -S bspwm sxhkd, xfce4-terminal, and xfce4-panel

now after that make 2 directorys in .config: 

mkdir .config/bspwm/

mkdir .config/sxhkd/

now put in:

git clone https://github.com/smerte42/my-bspwm-config.git

now put in these commands

cd my-bspwm-config/

cp ./bspwmrc .config/bspwm/

cp ./sxhkdrc .config/sxhkd/

edit bspwmrc to put in this:

a web browser of your choice

---------------------------------------------
note: you might need sudo to install stuff and copy stuff

---------------------------------------------

you don't need a DM so let's get rid of it we are going to use xinit.

first get xinit, xsetroot, and xorg

example:

sudo pacman -S xinit xorg-xsetroot xorg picom

now put in
cp my-bspwm-config/.xintrc /

just put in:

startx
-----------------------------------------------

and this is how to get the worse bspwm configurations in the world

------------------------------------------------
bspwm: https://github.com/baskerville/bspwm
sxhkd: https://github.com/baskerville/sxhkd
