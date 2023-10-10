# Part II Dissertation Template

Recommended Setup
- VSCode 
- [LaTeX Workshop Plugin](https://github.com/James-Yu/LaTeX-Workshop) (Using TeX Live)

Compilation 
- To compile the main disseration, open `./Dissertation/dissertation.tex` and save the file.
- This should update the PDF file (and spawn many intermediary compilation files, you can ignore these).
- Similarly, the proposal files can be compiled by opening `./Proposal/Phase_2/Phase_2.tex` and `./Proposal/Phase_3/Phase_3.tex`, and saving the files.

Viewing PDFs 
- Viewing PDFs is easiest in VSCode, open a new VSCode window containing the PDF (which live updates when the LaTeX is changed). 
- Alternatively, the Okular PDF viewer has dark-mode settings for late-night writing sessions (also supports live updating).

Extra files (in `./Dissertation`) 
- The `prooftree.sty` and `tombstone.sty` files are custom LaTeX packages I used. These can be removed once you remove the LaTeX code dependent on them. 
- My `preamble.sty` contains lots of extra packages. If you remove the contents of all chapter and appendices files, this file can be replaced with `minimal_preamble.sty`.

Feel free to reuse any LaTeX code in this project, although be warned that it is a little hacky at times. 

Enjoy,\
Dylan :P 

