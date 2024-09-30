# tex
TeX is a typesetting system designed and developed by Donald Knuth in 1978, primarily used for the production of high-quality documents, especially those containing complex mathematical expressions. 

## Installing IEEEtran

If the command `sudo tlmgr install IEEEtran` does not work, try this alternative approach:

Download the package from the following site:
https://ctan.org/pkg/ieeetran?lang=en

Then, unzip the folder and copy everything to the target directory.

```
sudo mkdir /usr/local/texlive/2024basic/texmf-dist/tex/latex/ieeeconf/
sudo cp -r IEEEtran/* /usr/local/texlive/2024basic/texmf-dist/tex/latex/ieeeconf
sudo texhash
````
