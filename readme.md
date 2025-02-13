# CSS Grid Cheatsheet 🎨

Este repositorio contiene un resumen rápido de las propiedades más útiles de CSS Grid, junto con enlaces a herramientas y recursos interesantes para dominar el diseño con Grid.

---

## **Cheatsheet de CSS Grid**

### **Propiedades del Contenedor**
| Propiedad                  | Descripción                                                                 |
|----------------------------|-----------------------------------------------------------------------------|
| `display: grid;`           | Define un contenedor como grid.                                             |
| `grid-template-columns`    | Define el número y tamaño de las columnas (ej: `repeat(3, 1fr)`).           |
| `grid-template-rows`       | Define el número y tamaño de las filas (ej: `100px 200px auto`).            |
| `gap`                      | Define el espacio entre celdas (ej: `10px` o `10px 20px` para filas/columnas).|
| `justify-items`            | Alinea los elementos horizontalmente dentro de sus celdas (ej: `center`).   |
| `align-items`              | Alinea los elementos verticalmente dentro de sus celdas (ej: `end`).        |
| `justify-content`          | Alinea todo el contenido horizontalmente (ej: `space-between`).             |
| `align-content`            | Alinea todo el contenido verticalmente (ej: `center`).                      |
| `grid-auto-flow`           | Controla cómo se colocan los elementos automáticamente (ej: `row`, `column`).|

---

### **Propiedades de los Elementos**
| Propiedad                  | Descripción                                                                 |
|----------------------------|-----------------------------------------------------------------------------|
| `grid-column`              | Define en qué columnas se colocará el elemento (ej: `1 / 3`).               |
| `grid-row`                 | Define en qué filas se colocará el elemento (ej: `2 / span 2`).             |
| `justify-self`             | Alinea un elemento horizontalmente dentro de su celda (ej: `start`).        |
| `align-self`               | Alinea un elemento verticalmente dentro de su celda (ej: `center`).         |
| `grid-area`                | Define un área para el elemento (ej: `header` o `1 / 1 / 3 / 3`).           |

---

### **Funciones Útiles**
| Función                    | Descripción                                                                 |
|----------------------------|-----------------------------------------------------------------------------|
| `repeat()`                 | Repite un patrón (ej: `repeat(3, 1fr)`).                                    |
| `minmax()`                 | Define un tamaño mínimo y máximo (ej: `minmax(100px, 1fr)`).                |
| `fit-content()`            | Ajusta el tamaño al contenido (ej: `fit-content(200px)`).                   |

---

## **Ejemplo Básico**
```css
.grid-container {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 10px;
    justify-items: center;
    align-items: center;
}

.item {
    grid-column: 1 / 3;
    justify-self: start;
    align-self: end;
}
```

---

## **Webs de Interés**
Aquí tienes algunas herramientas y recursos útiles para trabajar con CSS Grid:

1. **[CSS Grid Generator](https://cssgridgenerator.io/)**  
   Genera código CSS Grid de forma visual.

2. **[Flexbox Labs - Grid](https://flexboxlabs.netlify.app/grid)**  
   Prueba y experimenta con CSS Grid en tiempo real.

3. **[Cheatsheet Visual de CSS Grid](https://pbs.twimg.com/media/GXH6p70WYAAv_Dh?format=jpg&name=4096x4096)**  
   Una imagen con un resumen visual de CSS Grid.

4. **[Layout Playground](https://layout.bradwoods.io/)**  
   Explora diferentes diseños con CSS Grid y Flexbox.

5. **[CSS Grid Generator](https://cssgrid-generator.netlify.app/)**  
   Otra herramienta para generar código CSS Grid.

6. **[Interactive Guide to Grid](https://www.joshwcomeau.com/css/interactive-guide-to-grid/)**  
   Una guía interactiva para aprender CSS Grid.
