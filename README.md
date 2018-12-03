# murder-mystery
A murder mystery game!


The purpose of this is to build a clue-like game to engage in a murder mystery event.
Goals of this project:
    Have users create a login
    Users can create a new game of clue which creates a join game link
    Users can then share the link with others to their game
    The game will log the players
    The creator of the game can setup:
        #rooms and names of said rooms
        #weapons and which weapons
    Allows for conclusion and a winner.
    The preferred method of play to be on mobile but desktop/laptop is allowed as well

However the gamemaster (dungeon master) will all be handled server side so everyone can enjoy the fun.

The server should now have a lobby address, name, and also use the creators parameters and the joined users to assign a weapon, room, and murderer!

The server will also give each player a room, weapon, and user that is not of the murder.

The game will be split into rounds, the order of play randomly determined at beginning of game.

Each round every player will have the opportunity to guess the terms of the murder.
The server will check in order to find a reason for the guess being wrong and display the first error it encounters.

The user will be able to update a chart that contains their conclusions.
Setup like so:

            Weapons         Room

Murderer

room

This will help them deduce the solution to the murder.  However the server will not check for correct inputs but instead just store their deductions.


