# 💭 Reflection: Game Glitch Investigator

Answer each question in 3 to 5 sentences. Be specific and honest about what actually happened while you worked. This is about your process, not trying to sound perfect.

## 1. What was broken when you started?

- What did the game look like the first time you ran it?
    The first time I ran the game, to me everything looked okay, except on the left it said that I had 8 attempts left and on the right I started the game with only 7 attempts. 
- List at least two concrete bugs you noticed at the start  
  (for example: "the hints were backwards").
    1. The starting attempts left were 7 instead of 8
    2. When I was play the game, a guess of 8, the hint told me to go higher and then when I put in a 9, the hin twould tell me to go lower. 

**Bug Reproduction Log**

Document at least 3 bugs you found. Add rows as needed.

| Input | Expected Behavior | Actual Behavior | Console Output / Error |
|-------|-------------------|-----------------|------------------------|
|    4  | Go LOWER!         | Go HIGHER!      | |
|    1  | Go HIGHER!        | Go LOWER!       |                      |
| Hard  | Range: 1 to 100   | Range: 1 to 50| |

---

## 2. How did you use AI as a teammate?

- Which AI tools did you use on this project (for example: ChatGPT, Gemini, Copilot)?
    I used AI to explain to me the functionality of some of the lines of code and to double check errors I found. 

- Give one example of an AI suggestion that was correct (including what the AI suggested and how you verified the result).
    I  

- Give one example of an AI suggestion that was incorrect or misleading (including what the AI suggested and how you verified the result).
    I was using claude, it told me to create a vertual environment (venv) by using "python -m venv venv" and the terminal returned that "command not found: python" as I was supposed to use python3. 

---

## 3. Debugging and testing your fixes

- How did you decide whether a bug was really fixed?
- Describe at least one test you ran (manual or using pytest)  
  and what it showed you about your code.
- Did AI help you design or understand any tests? How?

---

## 4. What did you learn about Streamlit and state?

- How would you explain Streamlit "reruns" and session state to a friend who has never used Streamlit?

---

## 5. Looking ahead: your developer habits

- What is one habit or strategy from this project that you want to reuse in future labs or projects?
  - This could be a testing habit, a prompting strategy, or a way you used Git.
- What is one thing you would do differently next time you work with AI on a coding task?
- In one or two sentences, describe how this project changed the way you think about AI generated code.
