# AI Use Log

I used different AI tools during this assignment to help me learn faster and write cleaner code. 
Here’s where and how I used each one:

## ChatGPT (OpenAI)
- **Where I used it:** When I was working on the GC content problem (Rosalind #9). I wasn’t sure how to track which FASTA record had the highest GC percentage. 
- **What I asked:** I asked ChatGPT to give me pseudocode for finding the record with the maximum GC%. 
- **How it helped:** It suggested keeping track of `best_id` and `best_gc` while looping through the records. 
- **What I changed:** I rewrote the code to use my own variable names, added rounding to six decimals, and added print statements so I could double-check my results. 
- **How I verified:** I created a small FASTA file with 3 sequences, manually calculated GC%, and confirmed the code picked the right one.

## Gemini (Google)
- **Where I used it:** While writing the base-count code (counting A, C, G, T). I had a basic loop but it looked messy. 
- **What I asked:** I asked Gemini to suggest a simpler or more Pythonic approach. 
- **How it helped:** It suggested using a dictionary with a loop instead of writing multiple `if` statements. 
- **What I changed:** I kept the dictionary approach but limited it to only A, C, G, T so it wouldn’t count other characters. 
- **How I verified:** I compared the dictionary results with Python’s built-in `str.count()` for the same DNA string and both matched.

## DeepSeek (note only)
- **Where I used it:** I didn’t actually commit any DeepSeek code, but I used it to think about performance. 
- **What I asked:** I asked whether using `collections.Counter` would be faster than my dictionary counting on large sequences. 
- **What I decided:** For this assignment, readability was more important than tiny performance gains, so I stayed with the dictionary method. 
- **How I verified:** I generated a long random DNA sequence (~100k bases) and tested both methods. The runtime was similar, so my simpler code was fine.

---
Overall, AI tools gave me starting points and helped me refactor, but I always tested the outputs myself before committing them.
