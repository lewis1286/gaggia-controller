# Gaggia Classic Controller

## Purpose:
The Gaggia Classic is a great entry level espresso machine, but has an
unacceptable amount of variance around the temperature control.  A few others
have helped solve this issue with PID control (see sources).  I aim to do the
same, and hopefully add some logging and a web UI on the local network to see
how things are going.


## Goals:

### Primary
1. Raspberry Pi PID control of temperature
2. Feedback in simple web UI.

### Secondary
2. PID pressure control
3. Web app logging stats and giving user control to set temp/pressure.
4. IFTTT?


## Sources:

This project is motivated by similar projects using microcontrollers.

- [Arduino based controller][http://www.cyberelectronics.org/?p=458]
- [Raspberry Pi based controller][http://int03.co.uk/blog/project-coffee-espiresso-machine/]


