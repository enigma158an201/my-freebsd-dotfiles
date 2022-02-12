# my-freebsd-dotfiles
https://avignu.wiki.tuxfamily.org/doku.php?id=documentation:bsd:freebsd:clavier-fr
fichiers à mettre en respectant ces chemins
$HOME/.Xmodmap
/usr/local/etc/X11/xorg.conf.d/10-{keyboard,mouse,touchpad}.conf

penser a modifier dans /etc/sysctl.conf 
kern.evdev.rcpt_mask=3
par
kern.evdev.rcpt_mask=12
