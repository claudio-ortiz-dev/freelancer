# 📘 Bitácora Git & GitHub — Primer setup real (Mac + VS Code)

## 🧭 Contexto
Proyecto: Freelancer  
Objetivo: aprender Git y GitHub desde cero y subir avances reales de mi aprendizaje en desarrollo web.

Este documento registra mi proceso real, incluyendo errores comunes y cómo los solucioné.

## ⚙️ Entorno
- macOS  
- VS Code  
- Git (Xcode Command Line Tools)  
- GitHub  

## 🚀 Inicio
Quería subir mi proyecto a GitHub, pero aún no dominaba Git.  
Decidí subir avances aunque el proyecto no estuviera terminado.

## 🧪 Problema 1: Licencia de Xcode
Error encontrado:
You have not agreed to the Xcode and Apple SDKs license

Solución aplicada:
sudo xcodebuild -license

Acciones:
- Leer la licencia (scroll)
- Escribir `agree`
- Presionar Enter

## 🔐 Problema 2: permisos de administrador
El sistema indicó que aceptar la licencia requería privilegios de administrador.  
Solución: usar `sudo` y aceptar como root.

## 🧰 Verificación de Git
Comando usado:
git --version

Resultado: Git ya estaba instalado vía Xcode Command Line Tools.

## 📁 Problema 3: not a git repository
Error:
not a git repository (or any of the parent directories): .git

Causa:
Ejecuté comandos de Git fuera de la carpeta raíz del proyecto.

Solución:
Abrir la carpeta correcta del proyecto en VS Code y ejecutar:
git init

## 🌐 Creación del repositorio en GitHub
Decisiones tomadas:
- Un repositorio por proyecto
- Repositorio público
- Sin README inicial (el proyecto ya existía localmente)

Conexión del repositorio local con GitHub:
git remote add origin https://github.com/USUARIO/freelancer.git  
git branch -M main  
git push -u origin main  

## 🔐 Login de GitHub en VS Code
Mensaje mostrado:
The extension 'GitHub' wants to sign in using GitHub

Acciones:
- Aceptar
- Autorizar en el navegador
- VS Code queda vinculado a GitHub

## 🧼 Problema 4: archivo .DS_Store
Observación:
- Apareció en GitHub
- No se veía en VS Code
- Archivo automático creado por macOS
- No es código ni debe subirse

## ✅ Solución profesional: .gitignore
Crear archivo en la raíz del proyecto llamado:
.gitignore

Contenido del archivo:
.DS_Store

Eliminar el archivo del control de Git:
git rm --cached .DS_Store

Confirmar cambios:
git add .gitignore  
git commit -m "remove DS_Store and add gitignore"  
git push  

Resultado:
- .DS_Store eliminado del repositorio
- No volverá a subirse
- Repositorio limpio y profesional

## 🧠 Aprendizajes clave
- Git se aprende usándolo
- Los errores son parte normal del proceso
- .gitignore es obligatorio en macOS
- Subir avances demuestra disciplina y constancia
- GitHub es parte del perfil profesional

## 📌 Reglas para el futuro
- Un repositorio por proyecto importante
- Commits pequeños y claros
- Ignorar archivos del sistema
- No esperar a “saber más” para usar Git

## 🎯 Objetivo final
Usar GitHub como:
- Historial real de aprendizaje
- Evidencia para reclutadores
- Base de mi portafolio profesional
