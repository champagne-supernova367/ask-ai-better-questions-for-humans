# ask-ai-better-questions-for-humans
A master instruction for your AI to grade and comment the questions humans asked
# Question Grader

Paste this above any question to an AI. Instead of answering, it grades how well
your question is asked (not your language skills) on 7 metrics, scored 0–100.

## How to use
1. Copy the prompt below.
2. Paste it at the top of your message, then add your question underneath.
3. Send.

## The prompt
```
Please write a reusable instruction that people can paste above any question before sending it to an AI. The AI should then [only grade the question / grade it and then answer it]. It grades how well the question is asked, like an IELTS exam for the skill of "asking AI the right question", not for language ability.

Why: [for my own practice / to share with my team / to publish]. Users will range from programmers to everyday shoppers asking for very precise shopping advice. They are [mostly non-technical / mixed] and write in [English / these languages: __].

Background: [what you've tried before and what went wrong].

Requirements:
1. Works in [the tools you mean, e.g. ChatGPT, Claude, Gemini, coding agents].
2. Works for any field or subject.
3. 5–8 metrics, each scored 0–100, with honest comments that explain exactly why a score is 87 and not 88. Strictness: an average everyday question should score about [__].
4. An overall 0–100 score: [weight the metrics as you see fit and show the math].
5. Closing remarks in the spirit of Albert Einstein handing back a student's paper: [tone], [real quotes allowed / no quotes].

Limits: the instruction should be at most [__ words / fit a __-character field]. If precision and brevity conflict, favour [__]. Each report should be about [one screen / __ words].

Deliverable: the instruction in one copyable code block, plus [a short usage note / nothing else].

Test case: "[a real question you've asked]" should score about [__].

If one-point precision isn't realistic for AI graders, or any part of this design is a bad idea, say so and suggest something better.
```

## Example
[Question: can you give me buying advises if I want to buy a "stick pc" for travelling, since I already have my travel dual screen, bluetooth keyboard and mouse in my baggage already? The purpose is to run basic MS Office with another kg less in my checked / cabin bags.]
