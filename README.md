# Aula Digital — versión HTML/CSS/JS

Proyecto Base para migración posterior a React + TypeScript.

## Ejecutar

Usar un servidor local (por ejemplo Live Server en VS Code). Al utilizar ES Modules no se recomienda abrir los HTML directamente con `file://`.

## Organización

- `assets/css`: estilos separados por base, layout y componentes.
- `assets/js/components`: piezas reutilizables de interfaz.
- `assets/js/data`: datos del catálogo.
- `assets/js/services`: acceso a localStorage.
- `assets/js/pages`: lógica específica de cada página.
- `assets/js/main.js`: inicialización compartida.

## Nota pedagógica

`localStorage` se usa solo como simulación frontend. Las contraseñas quedan visibles en el navegador y esto NO es autenticación segura para producción.
# catalogo_cursos_base
