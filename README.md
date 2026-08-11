# Invitación XV de Emily

Invitación digital autocontenida (un solo archivo HTML) para los XV años:

**Sitio en vivo:** https://darioatencio21.github.io/emilyalvaradobirthday15/

## Qué incluye
- Pantalla de apertura con sobre interactivo + sonido/música.
- Conteo regresivo en vivo hasta el 14 de noviembre de 2026.
- Secciones: bienvenida, fecha/hora/lugar, programa (timeline), galería, código de vestimenta, RSVP y bloque de host (con contraseña).
- Cambio de idioma ES/EN.
- Animaciones: fuegos artificiales, luciérnagas, mariposas, pétalos, shimmer dorado, contador, etc.
- Prefill del invitado por link: `?nombre=María` (o `?name=`) rellena automáticamente el campo del RSVP.

## Cómo se publica
GitHub Pages sirve el archivo `index.html` desde la rama `main`. Con cada cambio se publica automáticamente.

### Actualizar los cambios
1. **Edita** el archivo local `quinceanera-invitation.html` (o `index.html`).
2. Copia la versión al `index.html` (que es lo que sirve el sitio): `Copy-Item quinceanera-invitation.html index.html -Force`
3. Sube ambos:
   ```
   git add index.html quinceanera-invitation.html
   git commit -m "descripción del cambio"
   git push origin main
   ```
4. Espera ~1–2 min y refresca https://darioatencio21.github.io/emilyalvaradobirthday15/

### Invitaciones personalizadas
Envía a cada invitado un link con su nombre:
```
https://darioatencio21.github.io/emilyalvaradobirthday15/?nombre=María
```

## Cosas pendientes de contenido
- **RSVP:** conectarlo (p. ej. Formspree) cuando definas el nº de invitados — el envio hoy solo es simulado.
- **Dirección del salón de la recepción:** reemplazar el placeholder "Terra Bella, CA" (línea del bloque *Reception*).
- Poner la foto real de la quinceañera en `CONFIG.heroPhoto` si no quieres el marco decorativo.

## Archivos
- `quinceanera-invitation.html` — fuente editable.
- `index.html` — copia que sirve GitHub Pages.
- `README.md` — este documento.