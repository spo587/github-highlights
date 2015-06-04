# Sight reading page
This [website](https://dl.dropboxusercontent.com/u/95890750/vexflow_sightreading/home.html) is an ongoing project that generates and displays music (in the form of sight reading exercises for piano) in a web browser using the Vexflow Javascript library, developed in part with a faculty grant from Levine Music.

Different levels use different algorithms for generating music. Level three uses a variable neighborhood search (VNS) which adapts a few simple counterpoint rules to generate melodic sequences that minimize an objective function after coming up with initially random sequences.

Other algorithms in progress include hierarchical structures, a VNS for rhythms, and other combinations of different techniques.

[https://github.com/spo587/sightreading-vexflow](https://github.com/spo587/sightreading-vexflow)

# Connect Four AI
A minimax-with-heuristics algorithm for connect four strategy. The basic strategy involves a six-moves deep minimax algorithm (with alpha-beta pruning). If a terminal state (victory or defeat) is reached by the algorithm at this depth, then the final utility of +1 or -1 is returned, but if no final state is returned by minimax, then the algorithm evaluates the board state and assigns it a heuristic value based on a number of parameters. The project contained many variant strategies, all easily manipulated, that use different values for these board-evaluating parameters. The basic variants in the strategies have to do with even and odd "threats" (based on which player moves first, threats are more valuable if they are in an even or odd space), control of the center of the board, and some planning behavior for building threats that stack on top of each other.

[https://github.com/spo587/connect_four](https://github.com/spo587/connect_four)

# Set Game Website
This [website](https://fierce-headland-9954.herokuapp.com) allows you to play the best game ever, set, and superset, its neglected cousin, live on the Internet either by yourself or with opponents on opposite ends of the planet. 

[https://github.com/spo587/set-sockets](https://github.com/spo587/set-sockets)

# Python Synthesizer
A python library for synthesizing digital instruments by building waveforms from scratch. 

This program builds sine waves as strings of integer bits in python, and uses the Sox program to convert them to sound waves. By combining different partials, one can create different tones, and using different onset and decay functions, one can create any number of different "instruments" with their own characteristic timbres, and write out tunes using the different instruments.

[https://github.com/spo587/music/](https://github.com/spo587/music/)




