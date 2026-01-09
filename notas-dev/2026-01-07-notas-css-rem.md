# Notas CSS - Día 7 de enero de 2026  
Curso: Juan Pablo De la torre Valdez (Udemy)  
Tema del día: Unidades de medida y uso de <span>

## Lo esencial aprendido hoy

### Problema con unidades antiguas
- **px** → Tamaño fijo en píxeles  
  No se adapta bien a diferentes densidades de pantalla (móviles, retina, TVs).  
  Ya no recomendado para fuentes ni tamaños generales.
- **em** → Relativo al tamaño del elemento padre  
  Efecto cascada confuso (se duplica/multiplica inesperadamente).  
  Evitar para fuentes.

### Solución actual (2026): **rem**
- **rem** = relativo al tamaño de fuente del **<html>** (root)  
- Ventajas clave:
  - Consistente en todo el sitio
  - Se adapta perfectamente a cualquier dispositivo/pantalla
  - Fácil de mantener y calcular

### Configuración base OBLIGATORIA (poner siempre al inicio de style.css)
```css
html {
    font-size: 62.5%;    /* Hace que 1rem = 10px → cálculos súper fáciles */
}

body {
    font-size: 16px;     /* Tamaño base estándar */
}


→ Con esto:

1rem   = 10px
1.6rem = 16px
2rem   = 20px
3.8rem = 38px

Aplicado en el proyecto Freelancer

Título principal:

h1 {
    text-align: center;
    font-size: 3.8rem;   /* ≈ 38px */
}
- Freelancer" más pequeño usando :

<h1>Claudio Mata <span>Freelancer</span></h1>
h1 span {
    font-size: 2rem;     /* ≈ 20px */
}

Etiqueta 

Inline, no hace nada por sí sola ("etiqueta de nada").
Útil para aplicar estilos a una parte específica de texto dentro de otro elemento (sin romper semántica).

Recordatorio rápido

Siempre usar rem para font-size, margin, padding, etc.
Esta configuración base → copiar en todos los proyectos futuros.