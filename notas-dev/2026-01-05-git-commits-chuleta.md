# 📌 Chuleta Git - Mensajes de Commit Profesionales (Conventional Commits)

Fecha: 5 ene 2026  
Usa este formato siempre:  
**tipo: descripción corta en presente (minúsculas)**

Ejemplo:  
`feat: add contact form`

## Tipos más comunes (los que usarás el 90% del tiempo)

| Tipo         | Cuándo usarlo                                          | Ejemplo en proyecto Freelancer                              |
|--------------|--------------------------------------------------------|-------------------------------------------------------------|
| **feat**     | Nueva funcionalidad o sección que el usuario ve/usa    | `feat: add services section with icons`  <br> `feat: add contact form` |
| **fix**      | Corriges un error o problema                           | `fix: rename reídme.md to README.md` <br> `fix: correct alt text in images` |
| **docs**     | Cambios solo en documentación (README, notas, etc.)    | `docs: update progress table` <br> `docs: add notes on HTML forms` |
| **style**    | Cambios de estilos visuales (CSS)                      | `style: add reset and container styles` <br> `style: style contact form` |
| **refactor** | Mejoras de código sin cambiar cómo se ve o funciona    | `refactor: improve HTML semantics in header` <br> `refactor: organize CSS classes` |
| **chore**    | Tareas menores de mantenimiento (config, limpieza)     | `chore: add .gitignore for macOS files` <br> `chore: update dependencies` |
| **test**     | Agregas o modificas pruebas (cuando lleguemos a JS)    | `test: add form validation tests`                           |
| **build**    | Cambios en configuración de build o herramientas       | `build: update VS Code settings`                            |

## Cómo elegir el tipo correcto (pregúntate esto)

1. ¿Agregué algo nuevo que se ve o usa? → **feat**  
2. ¿Arreglé algo que estaba mal o roto? → **fix**  
3. ¿Solo cambié documentación o notas? → **docs**  
4. ¿Solo toqué CSS/estilos? → **style**  
5. ¿Mejoré el código pero todo funciona igual? → **refactor**  
6. ¿Es una tarea técnica menor? → **chore**

## Reglas rápidas para mensajes pro

- Siempre **minúsculas**
- Verbo en **presente**: add, update, fix, remove (NO added, updated)
- Máximo 50 caracteres en la primera línea
- Sé claro y breve
- Si es complejo, agrega cuerpo:
  ```bash
  git commit -m "feat: add contact form
  
  - Includes fieldset, legend and grouped inputs
  - Prepared for CSS styling with divs"


## Por qué usar Conventional Commits

Tu historial de GitHub se ve profesional
Reclutadores lo notan rápido
Herramientas automáticas generan changelogs bonitos
Estándar usado en casi todas las empresas en 2026

¡Guarda esta chuleta y úsala en cada commit!
Con esto tu repo Freelancer ya se ve como el de un dev junior serio 💼

# Git Commit Guide (Concisa)

## Regla básica

* Inglés
* Presente
* Mensaje corto y claro
* Un cambio por commit

**Formato**

```
type: verb + change
```

---

## Types esenciales

* **feat** → nueva funcionalidad
* **fix** → corrección de bugs
* **style** → CSS, fuentes, UI
* **refactor** → mejora interna sin cambiar comportamiento
* **docs** → documentación
* **chore** → configuración / tareas menores

---

## Verbos más usados

`add` · `update` · `fix` · `remove` · `improve` · `refactor` · `implement`

---

## Commits más comunes

```
feat: add contact form
fix: prevent empty form submission
style: add Google Font
style: improve responsive layout
refactor: simplify form validation
docs: update README
chore: configure ESLint
```

---

## Comando

```
git commit -m "style: add Google Font"
```

---

## Regla final

> Menos palabras, más claridad

Simple > creativo
Claro > elegante
