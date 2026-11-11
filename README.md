# FORM-TL-01 — Taller de modelado de comunicación entre procesos distribuidos

Taller académico sobre el modelado de comunicación entre procesos distribuidos, considerando mecanismos como sockets TCP, RPC y mensajería.

## Integrantes

- APUNTE PAZMIÑO WASHINGTON GERMAN
- LOOR SUAREZ JORDAN JOSUE
- MACIAS VASQUEZ CESAR ABRAHAN

## Estructura del repositorio

```text
├── README.md
├── diagrama/
│   ├── comunicacion.drawio
│   └── comunicacion.pdf
└── notas/
    ├── notas.tex
    └── notas.pdf
```

## Contenido

- **diagrama/**: contiene el diagrama editable de comunicación entre procesos y su exportación en PDF.
- **notas/**: contiene las notas de la presentación, las preguntas recibidas y las respuestas del equipo.

## Instrucciones de compilación

Para generar el PDF de las notas, se necesita una distribución de LaTeX, como MiKTeX o TeX Live.

Desde la carpeta `notas/`, ejecutar:

```bash
pdflatex notas.tex
```

El archivo generado será `notas.pdf`.

## Herramientas utilizadas

- Git y GitHub para el control de versiones.
- draw.io para elaborar el diagrama.
- LaTeX para documentar las notas de presentación.
