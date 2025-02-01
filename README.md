# Rock-Paper-Scissors Game

A simple **Rock-Paper-Scissors** game where you play against the computer. Choose between **Rock**, **Paper**, or **Scissors**, and the game will determine the winner based on the traditional rules:

- Rock beats Scissors
- Scissors beats Paper
- Paper beats Rock

---

## Features

- **User Input:** Select between Rock, Paper, or Scissors.
- **Computer Selection:** The computer picks its choice randomly.
- **Game Outcome:** Displays whether you won, lost, or tied with the computer.
- **Scores:** Keeps track of both user and computer scores.
- **Visual Feedback:** Background colors change based on game outcomes (green for a win, red for a loss, gray for a draw).

---

## How to Play

1. Open the game in a web browser.
2. Click on one of the options: **Rock**, **Paper**, or **Scissors**.
3. The computer will automatically pick its choice.
4. The result will display, and the scores will update.
5. Continue playing as long as you want by selecting a new option.

---

## Technologies Used

- **HTML**: Structure of the webpage.
- **CSS**: Styling for the webpage, including buttons, colors, and layout.
- **JavaScript**: Logic for the game, randomizing the computer’s choice, determining the winner, and updating scores.

---

## Installation

To run this game locally:

1. Clone this repository to your local machine.
    ```bash
    git clone https://github.com/space-guy01/rock-paper-scissors.git
    ```

2. Open the project folder and open the `index.html` file in any modern web browser.
    ```bash
    cd rock-paper-scissors
    open index.html
    ```

---

## Game Logic

The game works as follows:

1. The user selects **Rock**, **Paper**, or **Scissors** by clicking a button.
2. The computer selects one of the three options randomly.
3. The game compares the choices:
   - If the choices are the same, it’s a **draw**.
   - If they are different, the game uses the rules of Rock-Paper-Scissors to determine the winner.
4. The scores for both the user and the computer are updated, and the result is displayed with color feedback:
   - **Green** for a win.
   - **Red** for a loss.
   - **Gray** for a draw.

---

## Contributing

Contributions are welcome! If you want to improve the game, feel free to fork the repository, make changes, and create a pull request.

---

## License

This project is open-source and available under the [MIT License](LICENSE).

---

## Acknowledgments

- Thanks to the web development community for inspiring this fun project!
- This game was created as a learning project to practice JavaScript, HTML, and CSS.
