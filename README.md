# my_answer
This repository contains a TeX file, which contains the answers to some math problems, that is automatically compiled to PDF using GitHub Actions.

## Github Action
1. On every git push, the spelling of files (including *.tex, *.md and *.yaml) will be checked. 
If there are unexpected mistakes in misspelled wordlist, you can add them to wordlist.txt after confirming that they are correct.

2. On every git push, the TeX file is compiled using 'latexmk'.

3. Compiled PDF is available as a Github Action artifact.

## Local Compiling
If you want to compile the TeX file locally, enter the following command in Git Bash:

latexmk -pdf ZhuHuatao.tex



