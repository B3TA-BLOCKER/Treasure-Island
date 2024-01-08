# Treasure Island 🏴‍☠️💎

Welcome to the interactive text-based game, "Treasure Island"! Embark on a thrilling adventure, making choices that lead to different scenarios and outcomes in your quest to find the hidden treasure.

## Code Overview 🚀💻

- **Console Clearing:**
  - The `system('cls')` command clears the console, providing a polished introduction to the game.

- **ASCII Art:**
  - ASCII art at the beginning adds a decorative touch to the game's introduction.

- **Game Introduction:**
  - The game begins with a warm welcome to Treasure Island, outlining your mission: discovering the treasure.

- **First Choice:**
  - The first choice prompts you to decide between going 'left' or 'right,' with the input stored in `choice_1`.
  - `choice_1` is converted to lowercase using the `lower()` method and stored in `choice_1_lower`.
  - Conditional statements based on `choice_1` dictate the next steps:
    - Choosing 'left' leads to a decision at a serene lake.
    - Choosing 'right' results in an immediate "Game Over" message as you fall into a hole.

- **Second Choice:**
  - If you chose 'left,' brace yourself for the second choice involving the lake, with a prompt like "You've come to a lake...". The input is stored in `choice_2`.
  - `choice_2` is converted to lowercase and stored in `choice_2_lower`.
  - Opting to 'wait' progresses you to the third choice involving vibrant colored doors on an island.

- **Third Choice:**
  - In the third choice, select a door color ('red,' 'yellow,' or 'blue'), with the input stored in `choice_3`.
  - `choice_3` is converted to lowercase and stored in `choice_3_lower`.
  - Based on `choice_3`, conditional statements unveil different outcomes:
    - Choosing 'red' leads to a fiery room, resulting in a "Game Over" message.
    - Opting for 'blue' takes you to a room of intimidating beasts, triggering a "Game Over" message.
    - Choosing 'yellow' rewards you with discovering the treasure and winning the game.
    - Any other door choice leads to a "Game Over" message.

- **Unexpected Encounters:**
  - Opting to 'swim' at any point brings an unexpected encounter with an angry trout and a "Game Over" message.

- **Right Choice at the Beginning:**
  - Choosing 'right' at the beginning results in a perilous fall into a hole and another "Game Over" message.

## Conclusion 🏆

This code demonstrates the use of nested conditional statements to create a captivating, tech-savvy story-based game where your choices influence the ultimate outcome.
