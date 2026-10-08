# Deslopping the OpenAI 372
On the 6th October 2026, OpenAI announced 372 proofs completed with an internal model. Virtually all of these proofs are not to a publishable standard, and many are deemed unreadable by the community. I'm creating this repository as an effort to get the proofs up to standard. The original repository can be found here: https://github.com/openai/math.

Note that some of the initial 372 have been withdrawn due to technical errors. These are still included in the number. 

## My process

I don't intend to do many myself, but my process is the following:
* I do not spend significant amounts of time understanding ambiguities or possible errors. I feel like this is a waste of time. Something that is overly verbose can be cut down later.
* I do at least one pass of the paper to iron out ambiguities and notational errors with an LLM. I would suggest GPT-6.1 Sol for this purpose, or perhaps Opus 5.5 if you prefer Claude. The result of this is hopefully a human-readable paper. I will then upload this to readable/.
* I will then go manually and rewrite the paper. This will may involve asking an LLM questions about the proof, but LLMs should not touch this tex file at all.
* I will then go back to the LLM to test this human-written paper, then get into a feedback-implementation loop.

I disagree with "one-shotting" papers. I think realistically AI-assisted workflows should be generating one definition/lemma at a time and "humanising" as you go, possibly following an AI-suggested program. I feel problems that this won't work for are not ready to be solved.

## Guidelines for submissions
* Absolutely no LLM-touched content in preprints/. LLMs are encouraged for feedback, but no detectable "AI polish", nothing, nada.
* readable/ is expected to be full slop. You're welcome to write it yourself, though.

## Progress on problems
| Number | Name | Progress
|---|---|---
| 369 | "Strict hot spots and the absence of interior critical points on smooth simply connected planar domains" | "Readable" 
