# Study Quiz Game


> A customizable command-line quiz game for learners who want to test themselves using self-created questions.


## Description

This project is a Python-based study quiz game that allows users to input their own multiple-choice questions, play through the quiz, and receive a final score. It's designed to help learners reinforce knowledge in any subject by creating and answering their own questions.


## Installation & Setup

```bash
git clone https://github.com/YOUR_USERNAME/study-quiz-game.git
cd study-quiz-game
# Ensure Python 3 is installed
python final_project.py
```

Make sure to run this in the same directory as your `quiz-questions.txt` file (or let the program create one during setup).

## Usage

Follow the prompts in the terminal:
- Enter questions using the format: `Question|A. Option1|B. Option2|C. Option3|D. Option4|C`
- Start the game, choose your answers, and receive your score.

### Example

```
Welcome to the study quiz game!

Enter your question (format: Question|A. Option|B. Option|C. Option|D. Option|CorrectLetter):  
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
Would you like to play again? (Y/N): N  
Quiting the game! Goodbye!
```



## Tech Stack

- Backend: Python (Standard Library)
- Tools: Terminal / Command-Line

No external libraries or frameworks required.


## Future Improvements

- [ ] Add question randomization  
- [ ] Save scores and stats to a file  
- [ ] Create a GUI version using Tkinter or web frontend  


## Contributing

1. Fork the project  
2. Create a feature branch (`git checkout -b feature/my-feature`)  
3. Commit your changes (`git commit -m 'Add feature'`)  
4. Push to your branch (`git push origin feature/my-feature`)  
5. Open a Pull Request


## Credits

Created by [David Griffin](https://github.com/DavidTJGriffin)


## License

MIT License © 2025 David Griffin  

Permission is hereby granted, free of charge, to any person obtaining a copy  
of this software and associated documentation files (the "Software"), to deal  
in the Software without restriction, including without limitation the rights  
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell  
copies of the Software, and to permit persons to whom the Software is  
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included  
in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED.
