# Aula del Repaso · Módulo 2 · v5

Aula de estudio de 360Educa (GMC360). Armada el 04/10/2026 con la plantilla del mapa interactivo (modo aula).
Un portal (`index.html`), una carpeta por herramienta y el simulacro mixto en `m2-simulacro/`
(604 reactivos de las herramientas integradas). Cada herramienta lleva arriba la franja negra para saltar a otra o al simulacro.

## Herramientas

| | Carpeta | Temas | Estado |
|---|---|---|---|
| H1 | `m2-h1-objetivo-kyc/` | 2.1.1–2.1.2 · Objetivo y política de identificación y conocimiento | integrada |
| H2 | `m2-h2-reportes-dolares-sistemas/` | 2.1.3–2.1.5 · Reportes, dólares en efectivo y sistemas automatizados | integrada |
| H3 | `m2-h3-otras-obligaciones-lpb/` | 2.1.6–2.1.8 · Otras obligaciones, intercambio de información y LPB | integrada |
| H4 | `m2-h4-ccc-oficial/` | 2.1.9–2.1.10 · Comité de Comunicación y Control y oficial de cumplimiento | integrada |
| H5 | `m2-h5-novedosos-cambios-itf/` | 2.1.11–2.1.14 · Modelos novedosos, centros cambiarios, transmisores e ITF | integrada |
| H6 | `m2-h6-sanciones-pr-plazos/` | 2.1.15–2.1.17 · Sanciones, propietario real y plazos | integrada |
| H7 | `m2-h7-tipologias/` | 2.1 · Tipologías UIF y de organismos internacionales | integrada |
| H8 | `m2-h8-lfpiorpi/` | 2.2.1–2.2.2 · LFPIORPI: actividades vulnerables y uso de efectivo | integrada |

## Cómo publicarla
- **Netlify sin GitHub:** app.netlify.com/drop y arrastra la carpeta descomprimida (la que tiene `index.html` y las carpetas `m2-…`).
- **GitHub + Netlify:** sube todo a la raíz del repositorio `modulo2-cnbv`; en Netlify, Import from GitHub, sin build command ni publish directory.
- Las ligas son relativas: funcionan igual en la vista del artifact de Claude, en Netlify y abriendo `index.html` desde el disco.

## Cómo cerrar o abrir una herramienta para alumnos
En los datos del aula (`M2 · datos Aula`, en el proyecto de Claude) cada herramienta tiene `"abierta": true|false`.
Con `false` no se sube, el portal la muestra como «Próximamente» y la franja la apaga. Para abrirla: cambiar a `true` y volver a armar con `construir_aula.py`.
`aula.json` es sólo la copia de referencia de cómo se armó esta versión; cambiarlo aquí no abre ni cierra nada.

## Cómo se corrige
No se edita ningún `index.html` a mano. Se corrige el `datos.json` de la herramienta (o los datos del aula) y se vuelve a armar con la plantilla «Plantilla Mapa Interactivo 360Educa» (skill mapa-norma-360educa).

## Aviso
Material didáctico: los textos están resumidos y no sustituyen la publicación oficial ni son asesoría para un caso concreto.
El avance de cada simulador se guarda sólo en el navegador de quien estudia; no se envía a ningún servidor.
