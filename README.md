# Proyecto — Landing Mundial 2026

Pequeña landing informativa sobre la Copa Mundial 2026. HTML + SCSS modular con Parcel y Sass.

## Estado
- Trabajo en progreso: layout principal, componentes y sistema de estilos modular.

## Características
- Arquitectura Sass modular: `abstracts/`, `components/`, `layout/`, `base/`.
- Mixins y funciones reutilizables (`grid-flexible`, `layout_basico`, `card-style`).
- Componente de clasificación con banderas y rejilla responsive.

## Tech stack
- HTML5
- SCSS (Dart Sass, módulos `@use`/`@forward`)
- Parcel (dev server / build)

## Estructura importante

- `src/index.html` — Punto de entrada HTML.
- `src/scss/styles.scss` — Archivo raíz que importa los partials.
- `src/scss/abstracts/` — Variables, mixins, funciones.
- `src/scss/components/` — Componentes reutilizables (`_group-cards.scss`, `_cards.scss`, etc.).
- `src/scss/layout/` — Reglas de layout y zonas (header, main, footer).

## Instalación y desarrollo

1. Instala dependencias:

```bash
npm install
```

2. Ejecuta el servidor de desarrollo:

```bash
npm start
```

3. Compilar para producción:

```bash
npm run build
```

4. Generar documentación SassDoc (si está configurado):

```bash
npm run docs
```

## DEMO
- **EN PRODUCCION:** https://alex1245re.github.io/SassParcel/dist/

- **SASSDOC:** https://alex1245re.github.io/SassParcel/sassdoc/