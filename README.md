# Martin Body Piercing — sitio web

Sitio estático (una sola página) para **Martin Body Piercing**.
Listo para subir a GitHub y desplegar en Vercel.

## Contenido

```
index.html                  → toda la página (HTML + CSS + JS en un archivo)
assets/
  logo.svg                  → logo vectorial (alta resolución, escalable)
  logo-white.svg            → versión blanca (para fondos oscuros)
  videos/                   → videos de la sección PQRS
  img/                      → fotos: proceso, resultados, joyería, posters
```

## Características

- **Dos temas** con interruptor: Blanco/Negro (白) ↔ Rojo japonés/Beige (赤).
- **Fondo animado (three.js):** destellos plateados (piercings) + máscaras hannya y katanas en movimiento.
- **Música japonesa instrumental** generada en el navegador (Web Audio), con botón de activar/silenciar. Baja de volumen al alejarse del header. *No usa archivo de audio (sin problemas de derechos).* Si quieres tu propio MP3, colócalo en `assets/audio/` y avísame para conectarlo.
- **Secciones:** Precios · Tipos · Joyería · Proceso · Bioseguridad · Resultados · PQRS · Contacto.
- **Contacto:** WhatsApp (313 210 9098), llamada, Instagram y mini-mapa que abre Google Maps (Carrera 64A #11A-30).

## Cómo desplegar en Vercel

1. Crea un repositorio en GitHub y sube estos archivos (`index.html` en la raíz).
2. En [vercel.com](https://vercel.com) → **Add New → Project** → importa el repo.
3. Framework preset: **Other** (es un sitio estático, no necesita build).
   - Build Command: *(vacío)*
   - Output Directory: `.` (la raíz)
4. **Deploy**. Listo.

## Notas para editar

- **Número de WhatsApp:** busca `573132109098` en `index.html` para cambiarlo.
- **Dirección / mapa:** busca `Carrera` en `index.html`.
- **Agregar fotos de resultados:** pon los `.jpg` en `assets/img/resultados/` y duplica un `<figure>` dentro de la sección `#resultados`.
- **Agregar más joyería:** pon las fotos en `assets/img/joyeria/` y duplica una `.joya-card`.
- **Video de esterilización (Bioseguridad):** hay un espacio listo con el texto "Próximamente". Cuando tengas el video, colócalo en `assets/videos/` y avísame para insertarlo.

Hecho con cariño para un parcero. 🎌
