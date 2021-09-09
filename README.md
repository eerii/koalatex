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

<img width="601" alt="Teoremas" src="https://user-images.githubusercontent.com/22449369/132727886-21e57096-1cc6-46d4-b334-4d82b7798e7d.png">

**Gráficas**

Carga gráficas exportadas de matplotlib con pgf usando \plt{ruta/ao/arquivo.pgf}{lenda da gráfica}. Require usar koalatex-graficas.

<img width="594" alt="Graficas" src="https://user-images.githubusercontent.com/22449369/132727943-820bf9a1-da4a-4f9e-9c44-d3d2c5c154ef.png">

**Cadros**

Hai dúas maneiras de poñer cadros, ou ben cargando dende un arquivo csv, co comando \csv (as instruccións exactas están dentro de main.tex). Tamén podes utilizar unha táboa de tablegenerator no mesmo formato.

<img width="593" alt="Cadros" src="https://user-images.githubusercontent.com/22449369/132727973-f6ef14b4-9bdd-4fa5-8ddb-aa1a40545a30.png">

Ademáis, inclué soporte para código de python, debuxar circuitos, apéndices e engadir imaxes, con explacións en cada liña.

<img width="602" alt="Gato" src="https://user-images.githubusercontent.com/22449369/132728009-bcb0503e-a867-4007-a0e8-a444535aca35.png">
