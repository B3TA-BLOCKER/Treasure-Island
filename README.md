# Treasure-Island

This code is an interactive text-based game called "Treasure Island." It presents the player with a series of choices, leading them through different scenarios and outcomes to find or lose the treasure.

Here's a breakdown of how the code works:

The system('cls') command clears the console, providing a cleaner presentation for the game's introduction.

The ASCII art at the beginning is a decorative visual element for the game's introduction.

The game begins by printing "Welcome to Treasure Island" and explaining the player's mission: to find the treasure.

The player is prompted with the first choice: "You're at a crossroad. Where do you want to go? Type 'left' or 'right'". The player's input is stored in the variable choice_1.

The input is then converted to lowercase using the lower() method and stored in choice_1_lower.

The code enters a nested series of conditional statements based on the player's first choice:

If the player chooses "left," they are prompted for the next choice involving a lake.
If the player chooses "right," they immediately receive a "Game Over" message indicating they fell into a hole.
If the player chose "left," they are prompted for the second choice: "You've come to a lake...". The player's input is stored in choice_2.

Like before, the input is converted to lowercase and stored in choice_2_lower.

If the player chooses "wait," they proceed to the next choice involving doors on an island.

In the third choice scenario, the player is presented with three colored doors (red, yellow, blue) and is asked to choose a door color. The player's input is stored in choice_3.

Similar to previous inputs, the choice is converted to lowercase and stored in choice_3_lower.

Based on the third choice, the code uses conditional statements to provide different outcomes:

If the player chooses "red," they encounter a room full of fire and receive a "Game Over" message.
If the player chooses "blue," they enter a room of beasts and receive a "Game Over" message.
If the player chooses "yellow," they find the treasure and win the game.
If the player chooses anything else, they chose a door that doesn't exist and receive a "Game Over" message.
If the player chose "swim" at any point, they get attacked by an angry trout and receive a "Game Over" message.

If the player chose "right" at the beginning, they fall into a hole and receive a "Game Over" message.

This code demonstrates the use of nested conditional statements to create an interactive story-based game where the player's choices impact the outcome of the game.
