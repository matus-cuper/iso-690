# **ISO 690 pre BibTeX**
BibTeXový štýl prebratý z http://www.fit.vutbr.cz/~martinek/latex/czechiso.html, preložený do  slovenčiny, bez žiadnych ďalších úprav.

# Použitie
Je potrebné stiahnuť repozitár a odkázať sa na súbor slovakiso.bst pri použití príkazu `\bibliographystyle`
```
cd $MY_LATEX_PROJECT
git clone git@github.com:matus-cuper/iso-690.git
```
a pridať do súboru `.tex` bibliografický štýl
```
\bibliographystyle{iso-690/slovakiso}
\bibliography{bibliography}
```

# Upozornenie
Tento bibliografický štýl úplne nezodpovedá norme.

# Úprava
Pri chybnom preklade alebo zmene textu je potrebné upraviť súbor `slovak.mbs` a vygenerovať nový súbor `slovakiso.bst` príkazom
```
latex slovakiso.dbj
```
