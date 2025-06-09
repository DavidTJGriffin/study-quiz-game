# Study Quiz CLI

[![PyPI version](https://badge.fury.io/py/study-quiz-cli.svg)](https://pypi.org/project/study-quiz-cli/)

> A command-line quiz tool for self-testing with your own multiple-choice questions.

## Description

This Python CLI app allows users to input and answer their own quiz questions, track their score, and replay the game. It's designed for learners who want a lightweight, customizable quiz experience directly in the terminal.

---

## Installation

### Recommended (via `pipx`)

```bash
pipx install study-quiz-cli
```

> ⚠️ If `quizcli` isn’t recognized after install, run:

```bash
pipx ensurepath
exec $SHELL  # or restart your terminal
```

### Or Manual (for development)

```bash
git clone https://github.com/YOUR_USERNAME/study-quiz-cli.git
cd study-quiz-cli
python src/study_quiz_cli/__main__.py
```

Make sure to run it in the same directory as your `quiz-questions.txt`, or let the program create one during setup.

---

## Usage

```bash
quizcli
```

Follow the prompts:
- Input questions using this format:
  ```
  What is the capital of France?|A. Berlin|B. Madrid|C. Paris|D. Rome|C
  ```
- Type `D` to start the game
- Type `Q` to quit anytime

### Example:

```
Enter your question (format: ...):  
What is the capital of France?|A. Berlin|B. Madrid|C. Paris|D. Rome|C  
Enter another question or "D" to start the game: D

The game is now starting! Enter "Q" to quit!

What is the capital of France?  
A. Berlin  
B. Madrid  
C. Paris  
D. Rome  
Answer (A, B, C, D): C

Your final score is : 5!
```

---

## 🛠 Tech Stack

- Python 3.12+
- Poetry for packaging
- No external dependencies

---

## Future Improvements

- [ ] Add question randomization  
- [ ] Save scores and stats to a file  
- [ ] Create a GUI version using Tkinter or web frontend

---

## Contributing

1. Fork the project  
2. Create a feature branch (`git checkout -b feature/my-feature`)  
3. Commit your changes (`git commit -m 'Add feature'`)  
4. Push to your branch (`git push origin feature/my-feature`)  
5. Open a Pull Request

---

## Credits

Created by [David Griffin](https://github.com/DavidTJGriffin)

---

## License

This project is licensed under the MIT License.
