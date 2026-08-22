---
publish: true
created: 2026-08-14T08:01:16.000+02:00
modified: 2026-08-19T14:43:36.164+02:00
tags:
  - concept
---

# Simple Generic Prompt Structure

**What it is**

1. ****Instruction**** — What exactly should the system do?
2. ****Context**** — Who is this for, and what situation should the system understand?
3. ****Input data**** — What information does the system need from you?
4. ****Output format**** — What should the answer look like?

You can define this also by approaching with a similar set of questions, if you still lack the clarity:

1. _What do you give the AI?_ This defines the input.
2. _What should it give back?_ This defines the output.
3. _How do you know it's good?_ Here the TDD thought comes in, you find out by testing with a valid input, one that tests the boundary (see question #4), one that doesn't have the valid input)
4. _What must it **never** do?_ Here you define constraints, or where the human takes over.

**When to use it**
This is a great clear prompt structure for clear topics. It forces you to have clarity about what you want to do and helps you define it. It's not great if the topic is unclear or very complex, then you'll need other prompts or techniques to first clarify the Job to be done.

**Example**

- [[Example Prompt]]

**Common mistake**
(the one thing people get wrong with this)

**Related**

- [[Constraints-vs-Instructions]]
