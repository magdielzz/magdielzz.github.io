# Página personal — Magdiel Joshua Angel Galván

Sitio web personal: investigación en redes neuronales informadas por la física (PINNs),
tesis de licenciatura, artículos en proceso de publicación, repositorios de código,
trayectoria profesional y constancias de congresos.

Una sola página en HTML, CSS y JavaScript sin dependencias: no hay build, no hay
framework, no hay paso de compilación. Se abre con doble clic en `index.html`.

## Contenido

```
index.html                 La página completa (estructura, estilos y scripts)
assets/magdiel-angel.jpg   Retrato del encabezado
docs/cv-magdiel-angel-galvan.pdf        CV en PDF
docs/cv-fuente.tex                      Fuente LaTeX del CV
docs/constancia-dgfm-xxxiv-2026.pdf     XXXIV Reunión Anual DGFM–SMF (póster galardonado)
docs/constancia-xvi-taller-dgfm-2026.pdf  XVI Taller de la DGFM, Chiapas
docs/constancia-congreso-salud-2026.pdf   2° Congreso Innovación para la Salud, HGM
docs/credencial-orion-evenplan.pdf        Credencial Orion Innovation (Acreditta)
```

## Características

- Tema claro y oscuro, con botón y detección automática de la preferencia del sistema.
- Versión en español e inglés con un interruptor ES / EN.
- Índice lateral que resalta la sección en pantalla.
- Animación del encabezado: partículas arrastradas por un campo de velocidad
  incompresible derivado de una función de corriente con cuatro modos de Fourier
  (guiño al solucionador pseudo-espectral de Navier–Stokes). Se desactiva sola
  si el sistema pide movimiento reducido.
- Diseño adaptable a teléfono, tableta y escritorio.

## Publicar en GitHub Pages

```bash
# 1. Crear el repositorio vacío en github.com (por ejemplo: magdielzz/magdielzz.github.io)
# 2. Desde esta carpeta:
git remote add origin https://github.com/magdielzz/magdielzz.github.io.git
git branch -M main
git push -u origin main
```

Si el repositorio se llama `magdielzz.github.io`, el sitio queda en
`https://magdielzz.github.io`. Con cualquier otro nombre, hay que activar
**Settings → Pages → Source: Deploy from a branch → main / (root)** y el sitio
queda en `https://magdielzz.github.io/<nombre-del-repositorio>`.

## Cómo actualizarlo

Todo el contenido vive dentro de `index.html`. Para traducir un texto nuevo, se
escribe en español dentro del elemento y la versión en inglés en su atributo
`data-en`; el interruptor de idioma hace el resto.

---

© 2026 Magdiel Joshua Angel Galván
