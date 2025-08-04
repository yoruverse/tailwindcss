# @yoruverse-js/tailwindcss

Sistema de utilidades CSS para Tailwind, creado por Yoruverse.

Incluye variables y utilidades para colores, espaciados, radios, tamaños y más, organizados en archivos CSS modulares. Este paquete está pensado para ser importado fácilmente en proyectos que usen TailwindCSS, permitiendo extender o personalizar el diseño de manera sencilla.

## Instalación

```sh
npm install @yoruverse-js/tailwindcss
```

## Uso

Importa el CSS principal en tu archivo de estilos:

```css
@import '@yoruverse-js/tailwindcss/index.css';
```

O importa solo los módulos que necesites:

```css
@import '@yoruverse-js/tailwindcss/src/primitives/colors.css';
@import '@yoruverse-js/tailwindcss/src/color/background-color.css';
```

## Estructura

- `index.css`: Importa todos los módulos principales.
- `src/primitives/`: Variables base (colores, tamaños, espaciados).
- `src/color/`: Utilidades de color.
- `src/radius/`: Radios de borde.
- `src/spacing-and-widths/`: Espaciados y anchos.

## Autor

[Yoruverse](https://github.com/yoruverse-dev)

## Licencia

MIT
