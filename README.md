# koalatex 🐨

Esta é unha plantilla que inclúe exemplos de LaTeX e estilos predefindos.

## como usar

Hai dúas maneiras de uso: crea un novo repositorio utilizando esta plantilla (recomendado) ou descarga os arquivos directamente.
Unha vez feito isto, colócao todo nunha carpeta e ábrea co teu editor de LaTeX favorito.
Eu recomendo [VS Code](https://code.visualstudio.com) coa extensión LaTeX Workshop, é increíble e moi fácil de configurar.

## estructura

- **main.tex:** É o arquivo principal e o que tes que compilar para obter o pdf.
- **main.pdf:** O pdf resultante.
- **koalatex.sty:** A extensión de LaTeX principal que inclúe moitas outras extensións útiles e os estilos definidos.
- **koalatex-graficas.sty:** Extensión opcional con soporte para gráficas pgf exportadas dende matplotlib.
- **koalatex-tablas.sty:** Extensión opcional con soporte para cadros importados de csv ou tablegenerator.
- **koalatex-extra.sty:** Extensión opcional con algunhas funcións máis avanzadas.
- **bibliografia.bib:** Arquivo de BibTeX que carga a bibliografía do proxecto.
- **carpetas:** Organización para imaxes, cadros e gráficas.

## funcións

**Teoremas e outros espazos**

Podes utilizar diferentes recadros para resaltar información. Hai predefinidos: theorem, definition, example e proof.
Úsanse escribindo o contido entre \begin{theorem} e \end{theorem}.

**Gráficas**

Carga gráficas exportadas de matplotlib con pgf usando \plt{ruta/ao/arquivo.pgf}{lenda da gráfica}. Require usar koalatex-graficas.

**Cadros**

Hai dúas maneiras de poñer cadros, ou ben cargando dende un arquivo csv, co comando \csv (as instruccións exactas están dentro de main.tex). Tamén podes utilizar unha táboa de tablegenerator no mesmo formato.

Ademáis, inclué soporte para código de python, debuxar circuitos, apéndices e engadir imaxes, con explacións en cada liña.
