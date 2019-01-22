# FTA LaTeX-harjoitus

Windows-ympäristössä kääntyy Powershellissä seuraavasti, mikäli Miktex on asennettu oikein: 
```
biber harjoitus
pdflatex harjoitus.tex
```

Biber luo harjoitus.bbl -tiedoston, mikä sisältää viittaukset sellaisessa muodossa, että PDFLatex ymmärtää ne. 