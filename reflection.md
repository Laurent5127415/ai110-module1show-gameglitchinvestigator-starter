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
|    4  | Go LOWER!         | Go HIGHER!      | None                   |
|    1  | Go HIGHER!        | Go LOWER!       | None                   |
| Hard  | Range: 1 to 100   | Range: 1 to 50  | None                   |

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

  I played the game again to review if the corrections worked. 

- Describe at least one test you ran (manual or using pytest)  
  and what it showed you about your code.

  I opened the developer debug infor to see the secret number and played the game and reviewed the results. 

- Did AI help you design or understand any tests? How?

  Yes, I used claude to try and understand why when I was running the game, at some point, when I input 8, it said it was to high and when I inpute 9, it said it was to go lower. Claude told me about the even/odd bug.

---

## 4. What did you learn about Streamlit and state?

- How would you explain Streamlit "reruns" and session state to a friend who has never used Streamlit?
  I still do not understand it myself. I am working on it understanding it. 

## 5. Looking ahead: your developer habits

- What is one habit or strategy from this project that you want to reuse in future labs or projects?
  - This could be a testing habit, a prompting strategy, or a way you used Git.

  One habit I will reuse in the future is making multiple small Git commits. This make life easier that way if a mistake is made, it is easier correct them.

- What is one thing you would do differently next time you work with AI on a coding task?

I left VS studio open for about 4 days and tried to use co-pilot to pick up where I left off and fix the errors I had found previously. 

- In one or two sentences, describe how this project changed the way you think about AI generated code.

I still think AI generated code is great and sometimes hard to understand. However, now I do have some doubts that no matter how good a thing is, mistakes can always happen. Trust but verify alwasy. 
