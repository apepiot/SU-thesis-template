# Additionnal informations

Here is an **adaptation in LaTex of the Sorbonne Université PhD manuscript template**. The original template in Word can be found [here](https://www.sorbonne-universite.fr/le-doctorat/demarches-administratives/soutenance). 

It contains 
* a cover page including the logos, the title of the thesis, the doctoral school name, the jury, etc. (see the example in [document.pdf](https://github.com/apepiot/SU-thesis-template/blob/main/document.pdf)).
* a dedication page
* an acknowledgments page
* the table of contents (TOC)
* introduction
* chapters 
* the list of figures
* the list of tables
* the bibliography
* appendices
* a back page with the résumé/abstract

## About the template

Right and left margins are different by default: inside margins are bigger than outside margins to ensure that text isn't obscured by the binding, when the manuscript is printed.
The cover page contains the title page with all the necessary informations concerning your PhD.
The back page contains the résumé (fr) and the abstract (en).

## How to start
1. Download all the files. Keep the structure as it is in this repository. In particular, do not change the name of the **logos** folder.
2. Upload the logo of your lab in the logos folder. Accepted formats: png, pdf, jpg.
3. Open **document.tex** with your favourite LaTeX editor and compile.


## How to format this manuscript for your need 
In the **document.tex** file
* by default this template is set up in french, i.e. the names of the TOC, bibliography,... are in french. You can change that easily by commenting the line **\usepackage[francais]{babel}** to use the english version
* to adapt the title page: fill the 

