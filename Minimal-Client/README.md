Elizabeth Bergshoeff

December 28, 2022

Minimal C++ OpenGL Utility Toolkit Client

The parts of a game program are the game client and game
server. This project provides a minimal game client which
logs mouse and keyboard input. This client is written in
C++ and uses the OpenGL Utility Toolkit.

The client is central to gameplay. This project contains
a minimal client, which only logs all input. Input is
provided to the client via a keyboard and mouse. The
client will use glut to create a window. The window will
capture clicks, drags, and keystrokes. Game clients
interpret user input and provide an interface to the
game state.

The client will be complied from C++ and will use the
"OpenGL Utility Toolkit," or 'glut.' 'glut' was chosen
because it is one of the course libraries of 'CSCI 172:
Advanced Graphics Programming' at Fresno State
University. I used glut in completing CSCI 172 at Fresno
State, and expect to use glut and C++ for CSCI 173 this
upcoming spring.

The design of this client is not complete. For example,
glut passes input to a function. Should the function
forward the input to another object? This project is the
natural start to game programming as there is no single
generalized server. There are as many server models as
there are models of computation and programming
paradigms.
