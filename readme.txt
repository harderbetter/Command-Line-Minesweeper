Command for makefile:
1:gcc minesweeper.c
2: ./a.out
Command-Line Minesweeper Project Description:
Enter two digits which are width and height number_of_mines then generates a Minesweeper board internally. The board is a rectangle with a cover over each square. It will display this board to the user and prompt for a coordinate where they predict that no mine exists (format: x-coord y-coord 0-indexed). If they struck a mine then they lose (let them know). Otherwise uncover the selected square. If there are no adjacent mines then it should be blank and you uncover all adjacent squares too (chain-react this for every blank square). Otherwise show the number of mines in the surrounding 8 squares. If at somepoint only mines are covered then the user wins and the game ends.
