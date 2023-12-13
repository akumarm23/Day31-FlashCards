# Flash Cards GUI Python

[![License: MIT](https://img.shields.io/badge/License-MIT-purple.svg)](https://opensource.org/licenses/MIT)
[![Python Version](https://img.shields.io/badge/python-3.8-lightblue.svg)](https://www.python.org/downloads/release/python-380/)
![Version](https://img.shields.io/badge/version-v0.1-lime)

## Flash Cards GUI Python v0.1

The Flash Cards GUI Python (`main.py`) is a simple graphical user interface (GUI) application built with Tkinter in Python. It allows users to learn French words by presenting flashcards with English translations. Users can mark words as known or unknown, and the application saves the progress.

## Features

- Display flashcards with French words and their English translations.
- Allow users to mark words as known or unknown.
- Progress is saved to a CSV file for future sessions.
- Randomly select flashcards for an interactive learning experience.

## Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/akumarm23/Day31-FlashCards.git
   cd Day31-FlashCards
   ```

2. Run the script:

   ```bash
   python main.py
   ```

3. Use the application to learn and practice French words.

## Data Files

- The script reads words from `data/french_words.csv`.
- Progress is saved to `data/words_to_learn.csv`.

## Flash Cards

- Flashcards are presented with French words and their English translations.
- After a brief interval, the card flips to reveal the translation.

## Buttons

- "✓" Button: Marks the word as known and proceeds to the next flashcard.
- "✗" Button: Marks the word as unknown and proceeds to the next flashcard.

## Background Color

- The background color is set to "#B1DDC6" for a visually pleasing experience.

## Requirements

- Python 3.8
- Tkinter library

## Acknowledgments

Feel free to contribute and enhance the functionality of this Flash Cards GUI Python application! Happy learning!