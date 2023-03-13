# TicTacToe

## Description:
Tic Tac Toe game built with React and JSX.
## How to Run:
1. Fork the repository in its entirety into your account.
2. clone the repository to your machine.
3. Open the standalone.html file in the browser of your choosing.
4. Play the game!
5. Refresh the page to start over.
## Roadmap of future improvements:
One feature I'd like to implement first is disabling the players from selecting a block that has already been selected. I'd would try to implement this feature by writing a new state that sets the button as disabled. I would then add a function to the onClick effect that toggles the disabled state for the button.

My next feature I'd implement is a "Game Over" page that automatically paginate when a winner is declared that also removes the game board. I would add a function that returns a different <div> than the game Board function and use the useEffect hook updates the DOM. The new <div> will also have a button that allows the user to click and restart the game.
## License information:
This is a free, and open source code available to use for commercial projects, open source projects, and any other projects.

Code — MIT License
