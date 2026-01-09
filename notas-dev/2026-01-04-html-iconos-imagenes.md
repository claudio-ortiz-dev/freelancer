# 📌 Notas HTML - Imágenes e Iconos (4 ene 2026)

## 🖼 Imágenes con <img>
- Etiqueta autónoma (no tiene cierre): `<img src="" alt="">`
- Ruta relativa recomendada: `img/nombre-archivo.jpg`
- Carpeta estándar: `/img/` o `/images/`
- Siempre usar `alt`:
  - Descriptivo si la imagen aporta info: `alt="Foto de perfil Claudio Mata"`
  - Vacío si es decorativa: `alt=""`

Ejemplo:
```html
<img src="img/hero.jpg" alt="Claudio Mata trabajando como freelancer">

🎨 Iconos modernos (RECOMENDADO 2026)
Font Awesome 6 (mi elección para este proyecto)

Carga con CDN (una sola línea en <head>):

 <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css"
      integrity="sha512-DTOQO9RWCH3ppGqcWaEA1BIZOC6xxalwEsw9c2QQeAIftl+Vegovlnee1c9QX4TctnWMn13TZye+giMm8e2LwA==" 
      crossorigin="anonymous" referrerpolicy="no-referrer" />   


Ventajas:
Código limpio (sin SVG largos)
Cambiar tamaño/color solo con CSS
Miles de iconos gratuitos
Estándar profesional actual


Iconos usados en Freelancer

Ubicación: <i class="fas fa-map-marker-alt"></i>
Diseño Web: <i class="fas fa-palette"></i>
Android: <i class="fab fa-android"></i>
Apple: <i class="fab fa-apple"></i>
E-Commerce: <i class="fas fa-credit-card"></i>
Accesibilidad: agregar aria-hidden="true" si son decorativos

❌ Lo que EVITAR

Pegar SVG inline uno por uno → ensucia el HTML
Usar PNG/JPG para iconos simples → pesan más y se pixelan

Buenas prácticas aplicadas hoy

Font Awesome en vez de SVG inline
Carpeta /img/ organizada
Iconos con aria-hidden
Código semántico y limpio


### Commit rápido
```bash
git add notas/html-iconos-imagenes.md
git commit -m "docs: add practical notes on images and Font Awesome icons"
git push
```
