# Chess Image Move Generator

### Introduction
This is an subsystem to create chess datasets on the fly for any application. This code creates a complete randomised chess game and then creates the correspondind board position images. The number of games, number of moves per game, the size of context length can all be set by the user. 

### Use Cases
This code's sole purpose is to create a chess dataset on N games. This code uses lazy loading and other techniques to build a dataset without overwhelming the RAM and crashing the process. 

I am using this code to create a chess game dataset on the fly for my NLP_GenAI course. I plan on using this code to train a diffusion model; this essentially allows me use the diffusion model as a real time chess game engine!

In the multiple t-x.ipynb files, select x with the maximum number -- its the latest optimized version.
