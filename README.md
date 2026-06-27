[README.md](https://github.com/user-attachments/files/29404682/README.md)
# Leelasgrid# Leela's Grid

Una aplicación web de dibujo pixelado con estética Bauhaus. Pintá, borrá y explorá color directamente en el navegador, sin instalación ni dependencias.

🔗 **[Ver demo en vivo →](https://tu-usuario.github.io/leelasgrid/)**

---

## Qué es

Leela's Grid es un lienzo de píxeles que ocupa toda la pantalla. Cada celda mide 8×8 px. Pintas arrastrando el mouse o el dedo, elegís entre 12 colores y alternas entre modo claro y oscuro.

Funciona como un único archivo `index.html` — sin frameworks, sin dependencias, sin build step.

---

## Features

- Grilla de 8×8 px que llena el 100% del viewport
- Paleta de 12 colores: arcoíris completo + negro + blanco
- Pincel fino (1×1) y pincel grueso (2×2) con la tecla Alt
- Borrador toggle — se activa y queda activo hasta que lo desactivás
- Botón Neu para limpiar el lienzo
- Light mode / Dark mode
- El dibujo sobrevive rotaciones y cambios de tamaño de ventana
- Accesible: navegación por teclado, lectores de pantalla, targets táctiles ≥ 44px
- Estética Bauhaus: tipografía Space Grotesk, formas rectangulares, barra roja constructivista

---

## Cómo usar

| Acción | Resultado |
|---|---|
| Arrastrar mouse o dedo | Pinta con el color activo |
| Tocar el cuadrado de color **1 vez** | Avanza al siguiente color |
| Tocar el cuadrado de color **2 veces rápido** | Salta dos colores |
| **Alt** + arrastrar | Pincel grueso 2×2 |
| Botón **⌫ Löschen** | Activa/desactiva el borrador |
| Botón **Neu** | Limpia todo el lienzo |
| **Flechas** (con foco en el lienzo) | Mueve el cursor celda a celda |
| **Enter / Espacio** (con foco en el lienzo) | Pinta o borra la celda actual |

---

## Instalación

No hay nada que instalar. Descarga `index.html` y ábrelo en cualquier navegador moderno.

Para publicarlo en GitHub Pages:

1. Crea un repositorio en GitHub
2. Sube `index.html` a la rama `main`
3. Anda a **Settings → Pages → Branch: main / root**
4. En un minuto tu página estará en `https://tu-usuario.github.io/nombre-del-repo/`

---

## Estructura del repo

```
leelasgrid/
├── index.html        ← la aplicación completa
├── README.md         ← este archivo
└── docs/
    └── PROMPT.md     ← especificación técnica para replicar o extender el proyecto
```

---

## Replicar o extender el proyecto

Si quieres construir tu propia versión o extender esta con nuevas funciones, la especificación técnica completa está en [`docs/PROMPT.md`](docs/PROMPT.md). Incluye decisiones de arquitectura, lógica de interacción, criterios de accesibilidad y todos los detalles de diseño.

---

## Licencia

MIT — libre para usar, modificar y distribuir.
