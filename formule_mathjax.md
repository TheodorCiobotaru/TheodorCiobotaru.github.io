<script id="MathJax-script" async src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"></script>

![text descriptiv imagine](https://metricop.com/cdn/shop/articles/trimble-total-station.jpg?v=1677673954&width=1100)

[homepage](inedx.md)

# Inserarea  ecuatiilor si formulelor `MathJax

**Sintaxa:**

Formulele `MathJax` sunt inserate in aceeasi linie daca sunt plasare intr-o pereche de simboluri `$` 

Exemplu: Aceasta este o ecuatie: $a=bc$

Formulele `Latex` (prin MathJax) se introduc pe rand nou intre doua perechi de simboluri `$$`

*Exemplu:*

$$a=b^2$$

# Ridicare la putere(`superscript)

Se foloseste meta caracterul `Latex`: `^`

*Exemplu:*

$$a=10^7$$

# `Subscript

Se foloseste meta caracterul `LaTeX`: `_`

*Exemplu:*

$$a_i = b^c$$


# Gruparea elementelor din formule

Elementele din formule se grupeaza prin meta caracterele `{` si `}`.

$$ 10^{10} $$

# Literele grecesti

*Exemplu:*

`\alpha` - alpha litera mica($$\alpha$$)

`\Alpha` - alfa litera mare($$\Alpha$$)

# Parantezele

- Parantezele rotunde se scriu direct (nu au un inteles special `LaTeX`)
- Parantezele drepte se scriu direct (nu au un inteles special `LaTeX`)
- Acoladele, deoarce ele sunt meta caractere de grupare, vor fi renderizate corect daca sunt 'escapate' de intelesul lor special, punand in fata lor `metacaracterul` `\`

*Exemplu:*

$$a = (b+c)^{3x} - [3+6x]$$

# Fractiile

*Exemplu:*

`\frac{numarator}{numitor}`

$$ a = \frac{(a+bc)}{(d-c)} $$

# Semnele de multiplicare si respectiv de diviziune

*Exemple:*

$$ a=c+10 \times x $$

$$ a=c+10 \cdot x $$

$$ a=b \div c$$









