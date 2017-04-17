# Hello React JS

## Explained for Cloud9 IDE

Tutorials Used:

1. https://facebook.github.io/react/tutorial/tutorial.html (designed for CodePen)

Steps Followed:

* Run Clickable [command](https://gist.github.com/BenjaminHaos/ca4cc854aa946b95dde2235d1679d617) to setup react.js from root.
* [Step 3](https://github.com/BenjaminHaos/hello_react_js/commit/965e47f52bf86b5da6308e3366d5b8cfbb9955ec "view commit with this step.") In VM's workspace directory:  
    * Run command: ```create-react-app tic_tac_toe_hello```.
* Remove file not needed.
    * Notice README.md file created by create command contains useful info.
* [Step 4]() Remove code from these files remaining.
    * src/index.js
    * src/App.js
* [Step 5]() Copy Start here code into file. (There will be a warning for unused definition.)
    * This step would essentially mirror tuturial one's [setup](https://facebook.github.io/react/tutorial/tutorial.html#getting-started) step.
    * There will be a three by three matrix displayed.
* [Step 6]() Modify Board's renderSquare method and Square's render method to demonstrate passing data through props.
    * You should see a number in each square in the rendered output.
* [Step 7]() Modify the button tag returned in the render() function of the Square class so that when you click on a square, you should get an alert in your browser.
* [Step 7.1]() Add constuctor to Square class, change Square's render method, and change Square's event handler. This causes an 'X' to appear when a square is clicked. Previous clicks stored in the Square components state.
* [Step 8]() Add constructor to Board class that stores state of the entire board.
* [Step 8.1]() Change Board's renderSquare method return.
* [Step 8.2]() Change Square's render method.
* [Step 8.3]() Add handleClick method to Board class.
* [Step 9]() Simplify square class. 
* [Step 10]() Add xIsNext value to state in Board's constructor.
* [Step 10.1]() Change Board's handleClick method.
    * Clicks now display alternating 'X' and 'Y'
* [Step 10.2]() Modify status variable in Board's render method.
* Message above board now changes to show who goes next.
* [Step 11]() In Board's render method, create variable 'winner' equal to return of calculateWinner method when passed `this.state.squares`. 
    * Message at top now shows when there is a winner.
* [Step 11.1]() Modify handleClick to return early and ignore the click if;
    * the square is already filled.
    * someone has already won the game.
* [Step 12.1]() Add constructor to Game. The constructor create a state object with two atributes. The first atribute is the history array. The history array contains an object that represents the initial empty board with an array of nine null values. The second state atribute is the xIsNext variable set to true.
    * App should still function correctly.
* [Step ]() 
* [Step ]() 
* [Step ]() 



