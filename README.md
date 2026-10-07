# rrivkanya · Welcome to the Villains’ world

*A fanmade project by rrivkanya.*

Página fan no oficial y sin fines de lucro para presentar personajes originales (OCs) creados dentro del universo de *Disney Twisted-Wonderland*.

> **Aviso:** *Disney Twisted-Wonderland*, sus personajes, música, emblemas y arte oficial son propiedad de © Disney y Aniplex. Este proyecto no está afiliado ni respaldado por ellos. Los personajes originales y el diseño de la página son de rrivkanya.

## Qué incluye esta versión

- Portada con el castillo, estrellas titilantes y el botón **“Entra al espejo de la oscuridad”**.
- Acercamiento a la puerta del castillo con el scroll y estallido de luz blanca con sonido de brillos.
- Galería de retratos con marcos dorados, columna de luz por personaje y sonidos al cambiar.
- Ficha del personaje: emblema de dormitorio, descripción, botón de acción, sección de relaciones y frase.
- Música ambiental que inicia al terminar el destello, con botón para silenciarla.

## Estructura

```
index.html                 página completa (HTML, CSS y JS)
assets/
  img/
    castillo.jpg           fondo de la portada
    fondo-personaje-uno.jpg
    emblema-diasomnia.png
    relacion-leona.jpg
  audio/
    musica-ambiental.mp3
```

## Verla en tu computadora

Abre una terminal en esta carpeta y ejecuta:

```bash
python3 -m http.server 8000
```

Luego entra a <http://localhost:8000>. (Abrir `index.html` con doble clic también funciona, pero algunos navegadores bloquean la música si no se sirve así.)

## Publicarla con GitHub Pages

1. Sube el contenido de esta carpeta a la raíz de tu repositorio.
2. En GitHub ve a **Settings → Pages**.
3. En **Source** elige **Deploy from a branch**, rama `main` y carpeta `/ (root)`.
4. Guarda; en un par de minutos la página estará en `https://TU-USUARIO.github.io/NOMBRE-DEL-REPO/`.
