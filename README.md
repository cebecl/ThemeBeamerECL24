# ThemeBeamerECL24
Thème Beamer Latex cherchant à respecter la charte graphique de l'école centrale de Lyon 2024 disponible sur l'Intranet de l'école [ici](https://campus.ec-lyon.fr/modeles-bureautique-et-divers-39174.kjsp).

## Utilisation du thème *ecl24*
Le fichier [beamerthemeecl24.sty](https://github.com/cebecl/ThemeBeamerECL24/blob/main/beamerthemeecl24.sty) contient le code du thème Beamer *ecl24*, il doit être ajouté dans le même repertoire que votre fichier Latex.
Pour utiliser le thème Beamer *ecl24*, il vous faut appeler les modules *tikz*, *ifthen* et *etoolbox*.
Pensez à vérifier que les images utilisée par le thème Beamer *ecl24* sont accessibles en indiquant par exemple le chemin vers ces images.
 
Ainsi, ces commandes sont à insérer dans l'en-tête de votre fichier latex (*ie* avant `\begin{document}`) :
```latex
\usepackage{tikz}     
\usepackage{ifthen,etoolbox}
\graphicspath{{IMAGES/}}
\usetheme{ecl24}
```

### Option licence creative commons BY-NC-ND
Pour utiliser la licence creative commons BY-NC-ND, activez l'option *ccbyncnd* en appelant le thème *ecl24* :
```latex
\usetheme[ccbyncnd]{ecl24}
```

## Exemple de présentation
Vous pouvez tester le thème *ecl24* avec le fichier [presentation.tex](https://github.com/cebecl/ThemeBeamerECL24/blob/main/presentation.tex).

Cet exemple utilise [*lualetex*](https://www.luatex.org/), mais vous pouvez utiliser simplement *latex* ou *pdflatex* en commentant la ligne `\usepackage{luatextra}`
