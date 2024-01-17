# Spell-Checker_January

## Project Statement

The Spell Checker Project is a simple command-line tool that allows users to input text, and it corrects misspelled words using the `spellchecker` library in Python. The project provides a basic interface for users to interact with the spell checker.

## Libraries Imported

The following libraries are imported and used in this project:

- `re`: Regular expression library for text processing.
- `spellchecker`: A Python library for spell checking.
- `nltk`: Natural Language Toolkit for tokenization.

## Project Description

- **Initialization (`__init__`):** Initializes the SpellChecker instance.

- **Tokenize and Spell Check (`tokenize_and_spell_check`):** Tokenizes the input text, finds and corrects misspelled words using the SpellChecker instance.

- **Process Input Text (`process_input_text`):** Removes special characters and numbers using regular expressions, and converts the text to lowercase.

- **Run Spell Checker (`run_spell_checker`):** Main method that runs the spell checker. It prompts the user to enter text, processes it, performs spell checking, and displays the original and corrected texts.

## How to Run

1. Ensure you have Python installed on your machine.
2. Install required dependencies using: `pip install spellchecker nltk`.
3. Run the script: `python spell_checker.py`.
4. Enter text when prompted and observe the spell checker in action.

