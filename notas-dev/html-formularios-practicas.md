# 📌 Notas Completas HTML — Formularios y Prácticas
📅 Fecha: 5 de enero de 2026

---

## 🧑‍💻 Resumen general del día

- Cerré toda la estructura HTML del proyecto Freelancer.
- Integré completamente el formulario de contacto.
- Dediqué el día a práctica extra voluntaria de formularios HTML.
- Creé la carpeta /practicas/formularios/ en el repositorio principal.
- Desarrollé 4 formularios independientes, escritos desde cero y corregidos progresivamente:
  1. formulario-basico.html → Contacto simple
  2. formulario-registro.html → Registro completo
  3. formulario-login.html → Login clásico
  4. formulario-encuesta.html → Encuesta con múltiples opciones

---

## 🧠 Conceptos clave aprendidos y reforzados

### 1️⃣ Estructura general de un formulario

```html
<form>
  <fieldset>
    <legend>Título del formulario</legend>
    <!-- campos -->
  </fieldset>
</form>

# 📌 Notas Completas HTML — Formularios y Prácticas
📅 Fecha: 5 de enero de 2026

---

## 🧑‍💻 Resumen general del día

- Cerré toda la estructura HTML del proyecto Freelancer.
- Integré completamente el formulario de contacto.
- Dediqué el día a práctica extra voluntaria de formularios HTML.
- Creé la carpeta /practicas/formularios/ en el repositorio principal.
- Desarrollé 4 formularios independientes, escritos desde cero y corregidos progresivamente:
  1. formulario-basico.html → Contacto simple
  2. formulario-registro.html → Registro completo
  3. formulario-login.html → Login clásico
  4. formulario-encuesta.html → Encuesta con múltiples opciones

---

## 🧠 Conceptos clave aprendidos y reforzados

### 1️⃣ Estructura general de un formulario

```html
<form>
  <fieldset>
    <legend>Título del formulario</legend>
    <!-- campos -->
  </fieldset>
</form>

2️⃣ Agrupación con <div>
    <div>
  <label for="nombre">Nombre</label>
  <input type="text" id="nombre" name="nombre">
</div>
Cada campo va dentro de un <div>.
Facilita CSS (espaciado, alineación, responsive).
Buena práctica profesional desde el inicio.

3️⃣ <label> + for + id (obligatorio)
    <label for="email">Correo</label>
<input type="email" id="email" name="email">
<label for="email">Correo</label>
<input type="email" id="email" name="email">

4️⃣ placeholder
Texto de ayuda dentro del campo.
Desaparece al escribir.
No reemplaza al label.
5️⃣ Tipos de <input> practicados

| Tipo     | Uso                  |
| -------- | -------------------- |
| text     | Nombre, usuario      |
| email    | Correo electrónico   |
| password | Contraseña           |
| tel      | Teléfono             |
| number   | Edad, calificación   |
| checkbox | Selección múltiple   |
| radio    | Selección única      |
| submit   | Envío del formulario |


Ejemplo:
<input type="submit" value="Iniciar sesión">
6️⃣ <select> (menú desplegable)

    <div>
  <label for="pais">País</label>
  <select id="pais" name="pais">
    <option value="">Selecciona tu país</option>
    <option value="mx">México</option>
    <option value="es">España</option>
    <option value="ar">Argentina</option>
    <option value="co">Colombia</option>
    <option value="otro">Otro</option>
  </select>
</div>

7️⃣ <textarea>
Para mensajes o texto largo.
Admite placeholder.
8️⃣ Checkbox y Radio — reglas críticas
Checkbox
Mismo name.
id único.
value obligatorio.
Radio
Mismo name.
id único + label for.
9️⃣ <form action> y method
    <form action="#" method="post">
action="#": no envía datos (práctica local).
method="post": estándar para login y registro.
Sin name, el campo NO se envía.
🔟 Buenas prácticas aplicadas
IDs únicos.
name en todos los campos.
value en checkbox, radio y option.
lang="es" en todas las páginas.
Código limpio e indentado.
Práctica extra voluntaria → disciplina real.
📚 Recursos
MDN Web Docs — input types
https://developer.mozilla.org/es/docs/Web/HTML/Element/input
✅ Conclusión del día
Base sólida en formularios HTML lograda.
Capacidad real para crear formularios accesibles.
Listo para aplicar CSS profesional.
Progreso consistente hacia perfil junior.
Última actualización: 5 de enero de 2026