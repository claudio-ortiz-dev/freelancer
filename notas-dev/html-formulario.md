# 📌 Notas HTML - Formulario de Contacto (4 ene 2026)

Conceptos clave aprendidos hoy

<form> → Envuelve todo el formulario
<fieldset> → Agrupa campos relacionados (dibuja un borde por defecto)
<legend> → Título del grupo (aparece arriba del borde)
<label> → Texto explicativo de cada campo
<input> → Campo para escribir
type="text" → texto normal
type="tel" → teléfono (mejor teclado en móvil)
type="email" → correo (valida formato básico)
type="submit" → botón de enviar

<textarea> → Para texto largo (mensaje)
placeholder → Texto gris de ejemplo dentro del campo
<div> → Agrupa cada label + input (el instructor lo usó al final para organización)

Mejoras profesionales que aplicamos juntos (recomendadas)

Conectar label con input (accesibilidad):

<label for="nombre">Nombre</label>
<input type="text" id="nombre" name="nombre" placeholder="Tu nombre">

→ Al hacer clic en "Nombre" el cursor va directo al campo
Agregar name="" en cada input:
→ Necesario para que PHP reciba los datos después
Agregar required en campos obligatorios:

<input type="text" id="nombre" name="nombre" placeholder="Tu nombre" required>

→ El navegador no deja enviar si está vacío
Código recomendado final (lo que tienes en tu proyecto):
Usa la versión básica del curso por ahora, pero cuando lleguemos a PHP agrega id, name y required.

✅ Buenas prácticas aplicadas hoy

Todo el HTML del proyecto ya está completo
Formulario semántico y organizado con divs
Listo para estilizar con CSS mañana

¡HTML 100% terminado! Mañana empieza CSS y el sitio va a cambiar completamente 🔥


Guarda este archivo en tu carpeta de notas, haz commit y push:

```bash
git add notas/html-formulario.md
git add index.html
git commit -m "feat: add contact form + docs: practical notes on forms"
git push