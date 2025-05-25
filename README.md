============================================================
                    LANGUAGE TRANSLATOR
============================================================

Developer    : Ghulam Ishaque  
Degree       : BS Software Engineering (Semester IV)  
Project Title: Language Translator (GUI-based Application)  
Technologies : Python, Tkinter, googletrans

------------------------------------------------------------




# Language Translator App

A simple desktop application built using **Tkinter** and **Googletrans** that allows users to translate text into various languages.

## Features

- User-friendly GUI
- Translate text from English to over 100 different languages
- Dropdown menu to select target language
- Error handling for empty inputs and invalid selections
- Clear input and output fields easily

## Requirements

- Python 3.x
- `tkinter` (comes pre-installed with Python)
- `googletrans` (Install using the command below)

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/language-translator.git
   cd language-translator
   ```

2. Install the required Python package:
   ```bash
   pip install googletrans==4.0.0-rc1
   ```

3. Run the app:
   ```bash
   python translator.py
   ```

## Usage

1. Enter the text you want to translate in the input box.
2. Select the language you want to translate to from the dropdown.
3. Click on the **Translate** button to view the result.
4. Click on **Clear** to reset both input and output fields.

## Notes

- The app uses the unofficial `googletrans` API which might occasionally break if Google changes its translation backend.
- If you encounter issues, try reinstalling the library or using an alternative translation package.

## License

This project is open-source and free to use under the MIT License.

## Acknowledgements

- [Simplilearn](https://www.simplilearn.com/) for the inspiration
- [googletrans](https://pypi.org/project/googletrans/) Python library
