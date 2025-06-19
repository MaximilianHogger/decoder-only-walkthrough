# Token-Level Transformers – A Decoder-Only Walkthrough

Ever read a transformer tutorial and thought,  
*"Yeah sure, makes sense..."*  
And then later tried to think it through and ... got stuck?  
Yeah, same.

This notebook dives into the **token-by-token mechanics** of decoder-only transformers (like GPT), walking through every layer: embeddings, attention, masking, residuals, LayerNorm, MLPs — all the fun stuff.

It was supposed to contain *some* code, but honestly, this alone took me a while so it's just text for now 🤷‍♂️.

## What's inside

- Shapes at every step  
- Math with meaning  
- Justifications for scaling, masking, and other dark arts  
- Answers to things I never thought to ask (likely to grow)

## Why?

Because I think matrix multiplications in a wall of formulas aren't as "straightforward" as most walkthroughs pretend they are.

## Run it? Nope, just stuff to read.

Enjoy the text. Or don’t.
But if you find an error, please let me know!

---
