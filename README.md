# 🎮 Game Glitch Investigator: The Impossible Guesser

## 🚨 The Situation

You asked an AI to build a simple "Number Guessing Game" using Streamlit.
It wrote the code, ran away, and now the game is unplayable. 

- You can't win.
- The hints lie to you.
- The secret number seems to have commitment issues.

## 🛠️ Setup

1. Install dependencies: `pip install -r requirements.txt`
2. Run the broken app: `python -m streamlit run app.py`

## 🕵️‍♂️ Your Mission

1. **Play the game.** Open the "Developer Debug Info" tab in the app to see the secret number. Try to win.
2. **Find the State Bug.** Why does the secret number change every time you click "Submit"? Ask ChatGPT: *"How do I keep a variable from resetting in Streamlit when I click a button?"*
3. **Fix the Logic.** The hints ("Higher/Lower") are wrong. Fix them.
4. **Refactor & Test.** - Move the logic into `logic_utils.py`.
   - Run `pytest` in your terminal.
   - Keep fixing until all tests pass!

## 📝 Document Your Experience

- [x] **Describe the game's purpose.**
  This is a Streamlit-based number guessing game where players seek a secret number within dynamic ranges (e.g., 1-200 for Hard) using limited attempts and logic-driven hints.
- [x] **Detail which bugs you found.**
  The game featured reversed hints, incorrect difficulty scaling, a state lag requiring double-clicks to refresh progress, and scores that didn't reset between sessions or could drop below zero.
- [x] **Explain what fixes you applied.**
  I refactored the core logic into a modular utility file, corrected all mathematical and string errors, and integrated `st.rerun()` with session-state feedback to ensure an instant, bug-free user experience.

## 📸 Demo

- [x] [Insert a screenshot of your fixed, winning game here]

![Screenshot of fixed game](screenshot.png)

## 🚀 Stretch Features

- [ ] [If you choose to complete Challenge 4, insert a screenshot of your Enhanced Game UI here]
