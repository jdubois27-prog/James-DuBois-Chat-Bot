# My Chatbot: Reflection & Submission

**Name:** ______________________  **Period:** ________  **Bot name:** ______________________

> Write in your own words. Short, specific answers beat long, vague ones. Refer to what **your** bot actually did.

---

## How to turn this in

1. Fill in this file (replace the blanks and the `[...]` prompts). Save it.
2. Make sure your best work is saved in `persona.py`, `corpus.txt`, and your stage files.
3. **Commit and push** your work:
   - Click the **Source Control** icon (left sidebar) → type a message like `Finished chatbot lab` → **Commit** → **Sync Changes**.
   - Or in the Terminal: `git add .` then `git commit -m "Finished chatbot lab"` then `git push`
4. Submit the **link to your repository** (the web address of your repo on GitHub) to your teacher, in the place they tell you.
   - Your repo must be one your teacher can open: either add your teacher as a collaborator, or ask which they prefer.
   - Don't put personal information (full name, address, phone, school ID) in your bot or your corpus.

**Stage checkpoints your teacher saw (teacher initials):**
Stage 1 ____  Stage 2 ____  Stage 3 ____  Stage 4 ____  Stage 5 ____

---

## Part 1: Meet my bot

**Personality in one sentence:** [...]

**Something I'm proud of in `persona.py` or `corpus.txt`:** [...]

**A real conversation.** Paste at least 8 lines of chat with your finished bot (copy from the Terminal):

```
[paste here]
```

---

## Part 2: What I learned (answer all)

1. **The "hi in this" bug (Stage 1).** In your own words, why did the bot say "Hello!" to "this is hard", and how did splitting the sentence into a list of words fix it?

   [...]

2. **Important word (Stage 3).** Which method does your bot use to pick the important word (first word, longest word, or your own scoring)? Give one example sentence where it picked a **good** word and one where it picked a **bad** word. Why?

   [...]

3. **Reflection and rule order (Stage 4).** What does `reflect()` do? Why did `I hate my homework` get a different kind of reply from `I am nervous about the dance`?

   [...]

4. **N-grams (Stage 5).** In your own words, what does the bot store in its model, and how does it use that to write a sentence? What changed when you used `N = 3` instead of `N = 2`, or when you added lines to `corpus.txt`?

   [...]

---

## Part 3: Thinking like an engineer

5. **Where my bot fails.** Describe one thing it gets wrong or one reply that makes no sense. What would you need to change to fix it?

   [...]

6. **Does it understand?** Your bot can keep a conversation going. Does it *understand* what you say? Explain what you think is different between what your bot does and what a person does.

   [...]

7. **Hand-made vs. learned.** In Stage 4 you typed lists of related words by hand (`mom`, `dad`, `sister` → family). Our class discussed how word2vec could learn those groups automatically. What is the advantage of learning them from lots of text? What could go wrong?

   [...]

8. **If I had more time**, the next feature I would add is: [...] and I would start by: [...]

---

## Part 4: Honest process notes

- **Help I used** (classmates, teacher, websites, or AI tools), and what it helped with: [...]
- **The hardest bug I fixed** and how I found it: [...]
- **Which stage was hardest, and why:** [...]
