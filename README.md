# PhD-thesis
This is the older version before the oral examination. The final version after the oral examination is at [https://github.com/Gardner-BinfLab/thesis-bikash](https://github.com/Gardner-BinfLab/thesis-bikash).


### Compilation
I used TeXstudio on Ubuntu 18.04.5/Debian GNU/Linux 10 to compile this. TeXstudio and LaTeX distribution can be installed using `sudo apt install texlive-full texstudio`.
These are the configurations that work.
 - Configure > Build > Build & View
     `txs:///pdflatex | txs:///biber | txs:///pdflatex | txs:///pdflatex`
 - Configure > Build > Default Bibliography Tool
     `Biber`
 - Bibliography > Type 
     `BibLaTeX`
 - `sudo apt-get install texlive-fonts-extra` for extra fonts. Else comment out these lines in `preamble/packages.tex`:
      ```sh
      \usepackage{gfsartemisia-euler}
      \usepackage[T1]{fontenc}
      ```
