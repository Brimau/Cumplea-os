# Cumpleaños

Web de cumpleaños para **Benja**, de parte de **Brian**.

Un detalle interactivo en un solo archivo `index.html`: se abre con doble clic,
sin instalar nada y sin conexión a servidor.

## Qué contiene

- **Flores azules 3D en tiempo real** generadas con Three.js al estilo
  *turtle graphics*: los tallos crecen solos, los pétalos se abren y puedes
  girar el ramo con el ratón o con el dedo.
- **Pantalla de bienvenida** que hay que abrir para empezar (también sirve para
  desbloquear la música en los navegadores).
- **Reproductor flotante** con estética de vinilo, apuntando a `musica.mp3`.
- **Cuatro tarjetas de canciones de Westlife** (*Flying Without Wings*,
  *You Raise Me Up*, *My Love*, *Swear It Again*), cada una con su flor, su
  sello y un mensaje.
- **Vela de los deseos**: escribes un deseo, la apagas y sale con confeti. El
  deseo aparece después en la carta final.
- **Carta final** con efecto de máquina de escribir.

## Cómo usarlo

1. Abre `index.html` en el navegador.
2. Sustituye `musica.mp3` por la canción que quieras (mismo nombre y en la
   misma carpeta).
3. Listo.

## Lo que puedes editar

Todo el contenido editable está al principio del bloque de código, dentro de
`<script id="cumpleanos-src">`:

| Constante | Qué es |
|---|---|
| `DESTINATARIO` | El nombre de quien cumple años |
| `REMITENTE` | Tu nombre |
| `MUSICA_TITULO` | El texto del reproductor |
| `ARCHIVO_MUSICA` | La ruta del MP3 (`./musica.mp3`) |
| `CARTA` | La dedicatoria final |

Los textos de las tarjetas Westlife están en el array `CANCIONES` y las frases
de la vela en `CandleSection`.

## Stack

React 18 · Tailwind CSS · Framer Motion · Three.js · Lucide Icons ·
canvas-confetti. Todo vía CDN, sin build ni `npm install`.

## Nota

`musica.mp3` es un archivo de silencio de 10 segundos que hace de marcador de
posición para que la consola no muestre errores. Sustitúyelo por la canción
real.

---

Flores azules, Westlife de fondo. Nada más.
