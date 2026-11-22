# Portfolio UGC · María Gómez Belenguer

Portfolio editorial en React + Vite para UGC, moda, belleza y lifestyle.

## Desarrollo

```bash
npm install
npm run dev
```

## Build

```bash
npm run build
npm run preview
```

Para GitHub Pages, configura `VITE_BASE_PATH` con el nombre del repositorio, por ejemplo `VITE_BASE_PATH=/portfolio-ugc/ npm run build`. La propiedad `base` de Vite ya está preparada para ello.

## Editar contenidos

Los trabajos, filtros, servicios, colaboraciones y enlaces se encuentran centralizados al inicio de `src/main.jsx`. Para añadir un vídeo, añade un objeto a `media` con `src`, `image`, `title`, `tag` y `type: 'video'`. Las imágenes y vídeos públicos seleccionados se encuentran en `public/media/`.

Las estadísticas no verificadas se mantienen fuera de la interfaz como pendientes en `ESTADISTICAS_PENDIENTES.md`.

## Privacidad

Las exportaciones privadas no forman parte del proyecto publicado. Los originales de `fotos/` y `videos/` se conservan sin modificar.
