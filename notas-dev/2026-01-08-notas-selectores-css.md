# Notas CSS - Día 8 de enero de 2026  
Tema: Selectores CSS

## Selectores principales

| Tipo         | Sintaxis          | Selecciona                               | Reutilizable | Recomendado      |
|--------------|-------------------|------------------------------------------|--------------|------------------|
| Elemento     | `h1 { }`          | Todos los <h1>                           | Sí           | Solo globales    |
| Clase        | `.titulo { }`     | Elementos con class="titulo"             | Sí (infinitas) | **SIEMPRE**      |
| ID           | `#titulo { }`     | Solo elemento con id="titulo"            | No           | Evitar           |
| Atributo     | `[href] { }`      | Elementos con ese atributo               | Sí           | Casos específicos|

## Descendentes
- `h1 span { }` → <span> dentro de <h1>
- `.titulo span { }` → <span> dentro de cualquier .titulo

## Aplicado en Freelancer
```html
<h1 class="titulo">Claudio Mata <span>Freelancer</span></h1>

.titulo { text-align: center; font-size: 3.8rem; }
.titulo span { font-size: 2rem; }

→ Clase reutilizable en cualquier heading.


Inline, sin semántica.
Para estilizar parte de texto dentro de otro elemento.

Buenas prácticas

Usar clases → reutilizables y seguras.
Evitar IDs → aumentan especificidad.
Nombres descriptivos, minúsculas, sin empezar con número.

Recordatorio

Selector genérico (span) → aplica a todos.
Selector específico (.titulo span) → solo dentro del elemento indicado.