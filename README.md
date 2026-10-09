# Mis Cuentas

Aplicación de finanzas personales en español: gastos e ingresos, categorías y subcategorías, presupuestos, comparativas, exportación Excel/PDF y simulación de préstamos.

## Abrir la aplicación

**https://marco-prieto.github.io/mis-cuentas/**

Los datos se guardan en `localStorage` del navegador y dispositivo que uses. No se envían a GitHub y no se sincronizan entre dispositivos. El almacenamiento de esta dirección es independiente del de la demo anterior. Haz respaldos periódicos desde la aplicación.

## Código fuente

El archivo **mis-cuentas-codigo-fuente.zip** contiene el proyecto completo editable (React, TypeScript y Vite), sin dependencias instaladas ni credenciales. Descomprímelo, instala Node.js 22.13 o posterior y ejecuta:

```sh
npm ci
npm run dev:pages
```

Para generar una nueva versión web:

```sh
npm run build:pages
```

La carpeta `dist-pages` contiene la aplicación estática lista para publicar. Este repositorio publica esos archivos mediante GitHub Pages, desde la raíz de la rama `main`.

La aplicación incluye datos de demostración. Los cálculos de préstamos son estimaciones, no cronogramas oficiales de un banco.
