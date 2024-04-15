# Pixel-Derby

## Horse Betting Video Demo
https://youtu.be/j1opMk3vBWw

## Description
PixelDerby has brought to life a simple and fun horse-betting system with a completely custom user interface, made to give enjoyment to its users. This is the main intent of the project, to come up with a very easily navigable, user-friendly, interactive game of horse betting, which can provide one with the essence of both strategies coupled with entertainment. We aimed to create a distinctive UI that enhances the gaming experience and a robust betting system that allows players to make informed decisions. The project was driven by our shared passion to create a product we would enjoy using ourselves and to develop our skills in UI development and game design. Qt Framework and C++ programming language were used in developing the game.

The game features include bankroll management, where players start with $1000 and must strategically manage their funds to continue participating in races; detailed horse statistics to aid players in making educated bets; a bet history section for users to view their previous bets and analyze their performance; and a visually engaging representation of horse races, adding excitement to the betting experience. 

PixelDerby was a project filled with challenges, from creating user-friendly and appealing UI to implementing proper, fair, and engaging betting algorithms. Also, due justice needed to be done to the game mechanics associated with the very dynamics of horse racing.

## Execution
LINUX COMMANDS:
"qmake startRace.pro"
"make"
"./startRace"

If ./startRace doesn't work: delete all executables, compile, find the target in the makeFile
If using WSL: run command: "export DISPLAY=$(cat /etc/resolv.conf | grep nameserver | awk '{print $2}'):0"
