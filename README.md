# tex


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
