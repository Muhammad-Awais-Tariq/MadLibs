# MadLibs
Its a simple madlibs game created in python.

## Features
- Ask the user for the adjectives , verbs , nouns etc
- Speaks the story based on the adjectives and verbs provided by the user
- A simple game that can b modified accordingly

## How the app Works
The app works in the following way:

- **Collecting the data**: It collects the required data (nouns,verbs,adjective) from the user to perform the specific task.
- **Concatenation**: Using the data it has collected concatenate it to form a proper story.
- **Speaking**: Using the pyttsx3 library it converts the simple string into the text that is spoken.

## How to Run the Program
1. Make sure **Python** is installed.
2. Install all required modules using the `requirements.txt` file:
   ```bash
   pip install -r requirements.txt
3. Run the program
    ```bash
    python Main.py
    ```
    
## File Structure
```bash
MadLibs/
│── Main.py
│── README.md
│── requirements.txt
```

## Technologies Used
- Python
- pyttsx3  

## Notes
- Like the game of the madlib the story is fixed and just the words are placed in the spaces accordingly and the story is constant

## Author
Muhammad Awais Tariq

---
If you like this project, consider giving it a star on GitHub!