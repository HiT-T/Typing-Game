# A Typing Game

## Introduction

Typing Game is a web-based application designed to enhance typing skills by challenging players to type displayed quotes as quickly and accurately as possible. Upon clicking the "start" button, a random quote (I'm using [Sherlock Holmes](https://en.wikipedia.org/wiki/Sherlock_Holmes) quotes) appears, and the player types it into the provided input field. The game tracks the time taken to complete the quote, offering an engaging way to practice typing.

![demo](external_resources\demo.gif)

## Technical Implementation

This project is developed using fundamental web technologies: HTML, CSS, and JavaScript. It showcases essential concepts such as event handling, DOM manipulation, and dynamic styling.

### Key Features

- **Random Quote Generation**: Each game session presents a randomly selected quote from a predefined list, ensuring varied practice content.

- **Real-Time Feedback**: As the player types, the application provides immediate visual cues for correct and incorrect inputs, enhancing the learning experience.

- **Timing Mechanism**: The game records the time taken to complete typing the quote, allowing players to track their progress and improvement over time.

- **Responsive Design**: The application is styled to be accessible and visually appealing across different devices and screen sizes.

### Code Structure

- **`index.html`**: Sets up the HTML structure, including the game interface elements such as the quote display, input field, and start button.

- **`index.css`**: Contains styles for the game, including text formatting and visual feedback for user interactions.

- **`index.js`**: Implements the core game logic, including event listeners for user input, game state management, and timing functions.

## How to Play

1. **Start the Game**: Click the "start" button to display a random quote.

2. **Type the Quote**: Enter the displayed quote into the input field as quickly and accurately as possible.

3. **Visual Feedback**:
   - The current word to type is highlighted.
   - Correctly typed words move the highlight to the next word.
   - Typing errors change the input field's background color to light coral.

4. **Completion**: Upon correctly typing the entire quote, a congratulatory message displays the time taken to complete the challenge.

## Installation

To run the Typing Game locally:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your_username/typing-game.git

2. **Navigate to the Project Directory**:
    ```bash
    cd typing-game

3. **Open `index.html` in a Web Browser**: Open the `index.html` with live server in your preferred web browser, or use any other ways you prefer to open it.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements

- Developed following the Web-Dev-For-Beginners curriculum by Microsoft.
- Special thanks to the open-source community for resources and tutorials that aided in the development of this game.