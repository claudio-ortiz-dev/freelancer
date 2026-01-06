# Uso de Hojas de Estilo Externas (CSS)

Usar la etiqueta `<style>` dentro del HTML no es la forma recomendada.  
La práctica correcta es trabajar con archivos CSS externos, ya que permiten centralizar los estilos y evitar cambios repetidos.

¿Por qué usar CSS externo?
Evita repetir cambios en múltiples archivos HTML.
Facilita el mantenimiento del código.
Permite reutilizar estilos en varias páginas.
Mejora el rendimiento del sitio web.

Organización del proyecto
Se recomienda crear una carpeta para los estilos.
Dentro de ella se coloca el archivo CSS.
El nombre de la carpeta y del archivo es libre, por ejemplo css y styles.css.

Ejemplo de estructura:
css
styles.css
index.html
nosotros.html

Mover los estilos a un archivo CSS
Eliminar la etiqueta `<style>` del HTML.
Copiar las reglas CSS.
Pegarlas dentro del archivo styles.css.
Al guardar, el diseño se perderá temporalmente hasta enlazar el CSS.

Enlazar el CSS al HTML
La hoja de estilos se enlaza dentro del `<head>` usando la etiqueta `<link>`.
Se utiliza el atributo href para indicar la ruta del archivo.
El atributo rel se usa para indicar que es una hoja de estilos.

Ejemplo:
<link rel="stylesheet" href="css/styles.css">

Mejora de rendimiento
Se puede usar preload para que el navegador cargue la hoja de estilos lo antes posible.
Esto mejora el performance del sitio web.

Ejemplo:
<link rel="preload" href="css/styles.css" as="style">
<link rel="stylesheet" href="css/styles.css">

Conclusión
Usar CSS externo es una buena práctica.
Reduce trabajo duplicado.
Facilita el mantenimiento.
Mejora el rendimiento y la escalabilidad del sitio.
