# my-bspwm-config
this is my bspwm config feel free to copy it

----------------------------------------------
requirements:
bspwm

sxhkd

feh

a bar of your choice

a terminal of your choice

linux

----------------------------------------------
how to use:
first install bspwm, sxhkd, a terminal of your choice [for me it's xfce4-terminal], and a bar of your choice [for me it's xfce4-panel]

use your package manager for example I use pacman so I put in: pacman -S 

bspwm sxhkd, xfce4-terminal, and xfce4-panel

now after that make 2 directorys in .config: 

mkdir .config/bspwm/

mkdir .config/sxhkd/

now put in:

git clone https://github.com/smerte42/my-bspwm-config.git

now put in these commands

cd my-bspwm-config/

cp ./bspwmrc .config/bspwm/

cp ./sxhkdrc .config/sxhkd/

edit both files your text editor of choice and put in:

bspwmrc:

a web browser of your choice

a panel of your choice

sxhkdrc:

a terminal of your choice

---------------------------------------------
note: you might need sudo to install stuff and copy stuff

---------------------------------------------

if you are using minnium you need to startx it:

first get xinit, xsetroot, and xorg

example:

pacman -S xinit xorg-xsetroot xorg

now put in

cp /etc/X11/xinit/xinitrc ~/.xinitrc

now edit it and get rid of the stuff related to TWM you don't need that out dated shit

put in:

exec bspwm

xsetroot -cursor_name left_ptr

--------------------------------------------

if you have a log in manager just change the session to bspwm

-----------------------------------------------

and this is how to get the worse bspwm configurations in the world
