# WebSudoku
A website where a user can play a new random unique Sudoku.

User authentication is implemented using Passport.js authentication middleware.

The user can decide whether to play an easy, medium or a hard Sudoku.

Based on the difficulty, a new unique Sudoku is generated with the help of backtracking.

A countdown timer starts once the Sudoku is generated.

The user gets an alert for every wrong input.

Once the Sudoku gets solved within the timeframe, it gets auto-submitted and the result is saved in
MongoDB database using Mongoose ODM library, and the result is displayed.

