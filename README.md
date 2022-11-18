# Stanford LaTeX Poster Template

![](poster_pic.png)

There are four color demos under `demos`: Palo Alto Green, Cardinal Red, White and Cool Gray. To change the color, go to `beamerthemestanford.sty` and change the `headline` color:

- White Text, Palo Alto Green Banner: `\setbeamercolor{headline}{bg=paloaltogreen,fg=white}`
- Cardinal Red Text, White Banner: `\setbeamercolor{headline}{bg=white,fg=cardinalred}`
- White Text, Cardinal Red Banner: `\setbeamercolor{headline}{bg=cardinalred,fg=white}`
- White Text, Cool Gray Banner: `\setbeamercolor{headline}{bg=coolgray,fg=white}`

# Tips

## Fontspec & xelatex error

If you get the `fontspec` error:
```
(fontspec)                      LuaTeX.
(fontspec)                      
(fontspec)                      You must change your typesetting engine to,
(fontspec)                      e.g., "xelatex" or "lualatex" instead of
(fontspec)                      "latex" or "pdflatex".

Type <return> to continue.
 ...                                              
                                                  
l.45 \msg_fatal:nn {fontspec} {cannot-use-pdftex}
```
Go to overleaf's: 
> menu > compiler > select xelatex then recompule.

ref: https://www.overleaf.com/learn/how-to/Changing_compiler
