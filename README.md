# Geometría fractal

Trabajo colaborativo del curso **Computación Visual** (8.º ciclo, Ingeniería de Sistemas). Grupo 8.
Exposición: **02/12/2026** · 20 minutos.

Aplicación web interactiva (HTML + JavaScript + WebGL) que muestra los algoritmos de geometría fractal en tiempo real. No requiere instalación.

## Módulos

| # | Módulo | Técnica y demostración | Responsable | Estado |
|---|--------|------------------------|-------------|--------|
| 1 | [Conjuntos de escape](modulos/01-conjuntos-escape) | Mandelbrot y Julia con zoom interactivo | _por asignar_ | Prototipo listo |
| 2 | [IFS y Chaos Game](modulos/02-ifs-chaos-game) | Helecho de Barnsley, triángulo de Sierpinski | _por asignar_ | Pendiente |
| 3 | [L-systems](modulos/03-l-systems) | Plantas y curva de Koch por reglas de reescritura | _por asignar_ | Pendiente |
| 4 | [Terreno fractal](modulos/04-terreno-fractal) | Ruido fBm o diamond-square en 3D | _por asignar_ | Pendiente |
| 5 | [Dimensión fractal](modulos/05-dimension-fractal) | Box-counting sobre una imagen cargada por el usuario | _por asignar_ | Pendiente |

## Cómo ejecutarlo

Cada módulo es una página independiente: abre `modulos/<módulo>/index.html` en Chrome, Firefox o Edge.
La portada `index.html` enlaza a todos. Con un servidor local (opcional):

```bash
python3 -m http.server 8000
```

y entra a <http://localhost:8000>.

## Estructura

```
index.html          portada que enlaza a los módulos
modulos/NN-nombre/  un módulo por integrante (index.html autocontenido)
docs/informe/       capítulos del informe (APA)
docs/presentacion/  diapositivas y video de respaldo
docs/bitacora-ia.md registro de uso de IA (exigido por la rúbrica)
```

## Cómo trabajamos

Lee [CONTRIBUTING.md](CONTRIBUTING.md). Resumen: una rama por módulo, commits pequeños y nadie edita la carpeta de otra persona.

## Entregables

- [ ] Informe en formato APA (impreso y PDF), con mínimo 2 artículos científicos
- [ ] Presentación en PDF
- [ ] Aplicación gráfica funcionando
- [ ] Bitácora de uso de IA anexada al informe
