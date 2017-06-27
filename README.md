# Tema UAM para Beamer

Tema para presentaciones en Beamer con los colores y tipografías institucionales de la Universidad Autónoma de Madrid.

## Uso

Para usar el tema, descarga los ficheros e imágenes a la carpeta de trabajo e invoca el comando de Beamer `\usetheme`:
```latex
\documentclass[pdflatex,compress]{beamer}

\usetheme[darktitle,framenumber]{UAM}

% Tipografía institucional News Gothic
\usepackage{avant}
\renewcommand*\familydefault{\sfdefault}
\usepackage[T1]{fontenc}

\title{Plantilla Beamer Institucional}
\subtitle{Universidad Aut\'{o}noma de Madrid}

\author{Author Uno}

\begin{document}


\maketitle

\begin{frame}{Introducción}
  Texto de ejemplo
\end{frame}
\end{document}
```
También puedes usar la [plantilla](main.tex) que se incluye.


## Licencia

This software is published under the [MIT license](https://en.wikipedia.org/wiki/MIT_License).
