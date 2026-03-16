# 💭 Reflection: Game Glitch Investigator

Answer each question in 3 to 5 sentences. Be specific and honest about what actually happened while you worked. This is about your process, not trying to sound perfect.

## 1. What was broken when you started?

- What did the game look like the first time you ran it?
-> The UI looked alright but most counters were wrong and feels clunky.
- List at least two concrete bugs you noticed at the start  
  (for example: "the hints were backwards").
-> The attempts counter is wrong. The hint is wrong, the score counter is wrong, and the submit button needs to be clicked twice to register a guess.

---

## 2. How did you use AI as a teammate?

- Which AI tools did you use on this project (for example: ChatGPT, Gemini, Copilot)?
-> I used Antigravity/Gemini.
- Give one example of an AI suggestion that was correct (including what the AI suggested and how you verified the result).
-> The hint was wrong. I verified it by checking the code and seeing that it was printing the wrong message.
- Give one example of an AI suggestion that was incorrect or misleading (including what the AI suggested and how you verified the result).
-> It wanted to test directly in main, but I wanted to test in a separate file. I verified by checking that we have logic_utils.py and that it has the functions we need for separate testing.

---

## 3. Debugging and testing your fixes

- How did you decide whether a bug was really fixed?
-> I decided it was fixed when the game worked as expected and the counters were correct, and the code logic was sound.
- Describe at least one test you ran (manual or using pytest)  
  and what it showed you about your code.
-> I ran a manual test by playing the game and checking if the hints, counters, and game logic were correct.
- Did AI help you design or understand any tests? How?
-> Yes, it helped me design the tests by suggesting what to test and how to test it.

---

## 4. What did you learn about Streamlit and state?

- How would you explain Streamlit "reruns" and session state to a friend who has never used Streamlit?
-> Streamlit reruns the entire script every time the user interacts with the app. Session state is a way to store data that persists across reruns.
---

## 5. Looking ahead: your developer habits

- What is one habit or strategy from this project that you want to reuse in future labs or projects?
-> I want to reuse the habit of testing my code as I go.
- This could be a testing habit, a prompting strategy, or a way you used Git.
- What is one thing you would do differently next time you work with AI on a coding task?
-> I would use AI less and try to figure things out on my own more.
- In one or two sentences, describe how this project changed the way you think about AI generated code.
-> I think AI is a useful tool, but it's not a replacement for human creativity and problem-solving.
