# Part II Dissertation Template

Contents 
- `Dissertation-Full`: My full dissertation
- `Dissertation-Template`: An empty dissertation template
- `Progress-Report`: My mid-project progress report
- `Proposal`: All stages of my initial project proposal

**Important:** Please make sure to check the department page for the up-to-date dissertation standards.  Rules regarding dissertation formats and declarations may vary year on year.

Recommended Latex Setup
- VSCode 
- [LaTeX Workshop Plugin](https://github.com/James-Yu/LaTeX-Workshop) (Using TeX Live)

Compilation
- To compile any Latex document, open the relevant `document.tex` file and save it.
- For example, to compile the main dissertation, open `./Dissertation-Full/dissertation.tex` and save the file. This automatically compiles all Latex sub-files (such as `./Dissertation-Full/chapters/introduction.tex`).  
- Compiling updates the PDF file (and spawns many intermediary compilation files, which you can ignore).

Viewing PDFs 
- Viewing PDFs is easiest in VSCode, open a new VSCode window containing the PDF (which live updates as the LaTeX is changed). 
- Alternatively, the Okular PDF viewer has dark-mode settings for late-night writing sessions (also supports live updating).

Extra files (in `./Dissertation-Full`) 
- The `prooftree.sty` and `tombstone.sty` files are custom LaTeX packages I used. These can be removed if you remove the LaTeX code dependent on them.
- The `preamble.sty` in this directory contains lots of extra packages. If you remove the contents of all chapter and appendices files, this file can be replaced with `minimal_preamble.sty`.

Feel free to reuse any LaTeX code in this project, although be warned that it is a little hacky at times. 

If there are any issues (large or small), feel free to reach out to me. Pull requests for fixes are very welcome :) 

Enjoy,\
Dylan :P 

