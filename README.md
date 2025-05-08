# Proyecto: Aprendiendo React Hooks

Este proyecto contiene tres ejemplos prácticos que ilustran el uso de diferentes hooks de React. Cada ejemplo está diseñado para enfocarse en un hook específico y demostrar cómo se puede utilizar en una aplicación React. Los ejemplos están organizados en carpetas separadas y se pueden ejecutar directamente en el navegador.

## Ejemplos incluidos

### 1. `ReactUseCallback` - Uso de `useCallback`
Este ejemplo muestra cómo optimizar componentes React utilizando el hook `useCallback`. Incluye un botón optimizado con `React.memo` que evita renders innecesarios al memorizar funciones.

- **Archivo principal:** [ReactUseCallback/index.html](ReactUseCallback/index.html)
- **Características:**
  - Generación de números aleatorios con un botón optimizado.
  - Incremento de un contador con un botón normal.
  - Uso de `useCallback` para evitar la recreación de funciones.

### 2. `ReactUseMemo` - Uso de `useMemo`
Este ejemplo demuestra cómo usar `useMemo` para optimizar cálculos costosos, como filtrar una lista de usuarios. También incluye la funcionalidad para agregar nuevos usuarios y realizar búsquedas con o sin sensibilidad a mayúsculas.

- **Archivo principal:** [ReactUseMemo/index.html](ReactUseMemo/index.html)
- **Características:**
  - Búsqueda de usuarios por nombre o descripción.
  - Agregar nuevos usuarios a la lista.
  - Uso de `useMemo` para memorizar los resultados de la búsqueda.

### 3. `ReactUseRef` - Uso de `useRef`
Este ejemplo implementa un cronómetro funcional que utiliza `useRef` para manejar referencias al intervalo de tiempo. También incluye la funcionalidad para guardar sesiones y reiniciar el cronómetro.

- **Archivo principal:** [ReactUseRef/index.html](ReactUseRef/index.html)
- **Características:**
  - Iniciar, pausar y reiniciar el cronómetro.
  - Guardar sesiones de tiempo.
  - Uso de `useRef` para manejar el intervalo de tiempo.

## Cómo usar los ejemplos

1. Abre cada archivo `index.html` en tu navegador.
2. Explora la funcionalidad de cada ejemplo interactuando con los botones y entradas.
3. Revisa el código fuente para entender cómo se implementaron los hooks.

## Objetivo del proyecto

El objetivo de este proyecto es aprender y practicar el uso de los hooks de React (`useCallback`, `useMemo` y `useRef`) en aplicaciones prácticas. Cada ejemplo está diseñado para ser simple y fácil de entender, proporcionando una base sólida para el uso de estos hooks en proyectos más complejos.

