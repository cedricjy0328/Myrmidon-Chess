# Myrmidon-Chess
A GUI-based Java application of a chess game.


Myrmidon Chess is a two-human chess game played on a 6X7 board.
There are several types of chess pieces, such as Plus, Triangle, Chevron and Sun, each of them with different movements and transformations.

Rules:
1. The Plus can move vertically or horizontally, up to 2 steps in any direction in a straight line.
2. The Triangle can move diagonally, both up and down, up to 2 steps in any direction in a straight line.
3. The Chevron must move in an L shape, exactly two steps then 1 step right or left. (This is the only piece that can jump over other pieces.)
4. The Sun can move only 1 step in any direction. The game ends when the sun is captured by the other side.
5. After 3 turns, a Plus will turn into a Triangle, a Triangle will turn into a Chevron, and a Chevron will turn into a Plus.


Design Pattern used:
1. Singleton
2. Prototype
3. Model-View-Controller (MVC)
4. Strategy


Setup instructions using command prompt:
1. Compile all the .java files
2. Run the GameController.class file


Date completed: 24 September 2018
