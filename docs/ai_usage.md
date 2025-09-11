## ChatGPT (OpenAI)  
- **Where I used it:** For the GC-content problem.  
- **What I asked:** How to find which FASTA record has the highest GC%.  
- **How it helped:** Gave me code with a `parse_fasta` function and a loop to track the best ID.  
- **What I changed:** Added Colab file upload and formatted the GC% to six decimals.  
- **How I verified:** Tested with the Rosalind sample and got the correct output.  

## Gemini (Google)  
- **Where I used it:** For the DNA to RNA transcription task.  
- **What I asked:** A cleaner way to replace `T` with `U`.  
- **How it helped:** Suggested using `str.replace()`.  
- **What I changed:** Added `.strip()` to clean file input.  
- **How I verified:** Ran the sample dataset and checked the output matched Rosalind’s.  

## DeepSeek (note only)  
- **Where I used it:** Thought about RNA → protein translation performance.  
- **What I asked:** If `dict.get()` lookups were faster than other methods.  
- **What I decided:** Kept the dictionary table for readability since performance was fine.  
- **How I verified:** Tried longer test strings; runtime was still fast.  
