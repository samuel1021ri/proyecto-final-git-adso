#proyecto-final-git

📝 INFORME – Práctica con Git y GitHub

📅 Fecha: 24 de noviembre de 2025

📌 1. Objetivo

El objetivo del día fue aprender a usar Git para controlar versiones del proyecto y subirlo correctamente a la plataforma GitHub, entendiendo cómo trabajar de forma profesional y organizada.

📘 2. ¿Qué es Git?

Git es un sistema de control de versiones que permite guardar el historial de cambios de un proyecto, trabajar en equipo, recuperar versiones anteriores y organizar el desarrollo del software de forma segura.

Git NO es GitHub: GitHub es una plataforma en línea donde se pueden subir repositorios Git para compartirlos, trabajar en equipo y almacenarlos en la nube.

⌨️ 3. 10 comandos explicados de Git
Comando	Explicación
git init	Inicializa un repositorio Git en la carpeta actual.
git status	Muestra el estado del proyecto (cambios pendientes, rama actual).
git add .	Añade todos los archivos modificados para guardarlos.
git commit -m "mensaje"	Guarda los cambios con un mensaje.
git log	Muestra el historial de commits.
git branch	Muestra o administra las ramas del proyecto.
git checkout -b nombre_rama	Crea y cambia a una nueva rama.
git checkout rama	Cambiar de rama.
git remote -v	Muestra la URL del repositorio remoto (GitHub).
git push -u origin main	Envía los cambios a GitHub por primera vez.
🔄 4. Flujo de trabajo recomendado (Workflow)
🔄 4. Flujo de trabajo recomendado (Workflow)

Crear carpeta del proyecto

git init

Crear/modificar archivos

git add .

git commit -m "mensaje"

Subir a GitHub → git push -u origin main

Seguir trabajando:

git add .
git commit -m "cambio nuevo"
git push

⚠️ 5. Problemas encontrados

Error: failed to push some refs → la rama no existía.

No había commits todavía → se tuvo que hacer primero el commit.

Escribí mal los comandos (u-, git push main, etc.).

La rama master no existía → usar main correctamente.

Solución: revisar siempre la rama con git branch y escribir bien los comandos.
