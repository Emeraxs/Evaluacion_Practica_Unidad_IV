# Prueba Práctica - Unidad IV
## Ingeniería de Requisitos (ISR-401)

Universidad Técnica Estatal de Quevedo  
Carrera de Ingeniería de Software

### Caso práctico
Sistema de Gestión de Pedidos

## Descripción

Este repositorio contiene el desarrollo en LaTeX de la Prueba Práctica de la Unidad IV de la asignatura Ingeniería de Requisitos (ISR-401).

El documento incluye el desarrollo realizado para P1-P5, con los modelos UML recreados a partir del trabajo manuscrito y almacenados en la carpeta `figuras/`.

## Estructura del repositorio

```text
/
├── main.tex
├── main.pdf
├── README.md
└── figuras/
    ├── p1_diagrama_clases.png
    ├── p2_diagrama_actividades.png
    └── p3_maquina_estados.png
```

### Archivos

- `main.tex`: archivo principal del documento LaTeX.
- `main.pdf`: PDF generado desde `main.tex`.
- `README.md`: instrucciones para reproducir el documento.
- `figuras/`: diagramas utilizados en el documento.

## Compilador

El proyecto utiliza:

```text
pdflatex
```

## Archivo principal

```text
main.tex
```

## Dependencias

Se requiere una distribución de LaTeX que incluya `pdflatex`, por ejemplo:

- MiKTeX
- TeX Live
- MacTeX

El archivo utiliza paquetes estándar de LaTeX, entre ellos:

```text
inputenc
fontenc
babel
graphicx
float
array
tabularx
longtable
booktabs
xcolor
enumitem
hyperref
microtype
setspace
titlesec
fancyhdr
ragged2e
```

No se utiliza BibTeX ni archivo `.bib`, debido a que este desarrollo no contiene una sección de referencias bibliográficas.

## Instrucciones exactas de compilación

Desde la carpeta raíz del repositorio ejecutar:

```bash
pdflatex main.tex
pdflatex main.tex
```

El primer comando genera el documento y sus archivos auxiliares. El segundo actualiza correctamente la tabla de contenido, numeración y referencias internas.

Al finalizar debe generarse:

```text
main.pdf
```

## Reproducción desde un repositorio clonado

```bash
git clone URL_DEL_REPOSITORIO
cd NOMBRE_DEL_REPOSITORIO
pdflatex main.tex
pdflatex main.tex
```

Luego se debe comprobar que `main.pdf` se haya generado correctamente y que las imágenes de la carpeta `figuras/` aparezcan en el documento.

## Contenido desarrollado

- P1. Modelo de datos - Diagrama de clases UML.
- P2. Modelo funcional - Diagrama de actividades UML con dos carriles.
- P3. Modelo de comportamiento - Máquina de estados UML.
- P4. Consistencia entre las tres perspectivas.
- P5. Especificación de requisitos con esquema de atributos.

## Autor

**Estudiante:** Erick Jhair Mera Arias  
**Asignatura:** Ingeniería de Requisitos (ISR-401)  
**Unidad:** IV  
**Fecha:** 11 de agosto de 2026
