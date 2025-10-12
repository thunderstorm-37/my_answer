# my_answer
This repository contains a TeX file, which contains the answers to some math problems, that is automatically compiled to PDF using GitHub Actions.

## Github Action
1. On every git push, the spelling of files (including *.tex, *.md and *.yaml) will be checked. 

2. On every git push, the Tex file is compiled using 'latexmk'.

3. Compiled PDF is available as a Github Action artifact.

## Local Compiling
If you want to compile the TeX file locally, enter the following command in Git Bash:

latexmk -pdf ZhuHuatao.tex



