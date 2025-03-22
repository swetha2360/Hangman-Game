# Hangman Game 🎭🔠

## Overview
This is a **classic Hangman game** built using Python. The player must guess the secret word one letter at a time while avoiding running out of lives. The game includes ASCII art to represent the hangman stages for a fun experience.

## Features
✅ Random word selection from a predefined list  
✅ Tracks guessed letters and prevents duplicate guesses  
✅ ASCII art to visualize the hangman’s progress  
✅ Dynamic word display that updates as letters are guessed  
✅ Win or lose messages based on remaining lives  

## How to Play 🕹️
1. Run the Python script.
2. A random word is selected, and you’ll see underscores representing each letter.
3. Guess one letter at a time.
4. If the letter is in the word, it replaces the underscore.
5. If the letter is incorrect, you lose a life.
6. The game ends when you guess the word correctly or run out of lives.

## Code Highlights 📝
- **Random module** for word selection.
- **Lists** for tracking guessed letters.
- **Conditional logic** to determine game progress.
- **ASCII art** for a fun visual experience.

## Installation & Setup 🚀
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/hangman-game.git
   ```
2. Navigate to the project folder:
   ```bash
   cd hangman-game
   ```
3. Run the script:
   ```bash
   python hangman.py
   ```

## Example Gameplay 🎮
```
 _ _ _ _
Guess a letter: a
Word to guess: _ a _ _
Guess a letter: b
You guessed 'b', which is not in the word. You lose a life.
Lives left: 5
```

## Contributing 🤝
Feel free to fork this repository, improve the game, and submit a pull request! 

## License 📜
This project is open-source and available under the [MIT License](LICENSE).

---
⭐ If you like this project, please consider giving it a **star** on GitHub! ⭐
