# 🧠 Aprendiendo Git – Informática I (UTN FRBA)

Este repositorio forma parte de la práctica de **control de versiones** de la materia **Informática I**.

El objetivo es que experimentes con los comandos básicos de **Git** y las herramientas de **GitHub**, entendiendo cómo se registran los cambios y cómo se trabaja en equipo usando ramas y pull requests.

---

## 🧩 Objetivos de la actividad

- Comprender qué es un repositorio y cómo se crea.  
- Realizar commits y analizar el historial de cambios.  
- Crear y trabajar en ramas de desarrollo.  
- Subir los cambios a GitHub.  
- Generar un Pull Request para integrarlos en el proyecto principal.

---

## 🪜 Pasos a seguir

### 1. Hacer un **fork** de este repositorio

Esto crea una copia del proyecto en tu cuenta.  
Usá el botón **Fork** arriba a la derecha.

### 2. **Clonar** tu fork en tu computadora

Abrí la terminal y ejecutá:

```bash
git clone https://github.com/matnalopez2/aprendiendo-git.git
cd aprendiendo-git
```

### 3. Crear una rama nueva

Creamos una rama con tu legajo para trabajar:

```bash
git checkout -b 1234567
```

### 4. Realizar la nueva funcionalidad

Para este trabajo debemos crear un archivo que imprima en pantalla "Hola mundo, soy [NOMBRE_ALUMNO]" y tenga de nombre [APELLIDO_ALUMNO]_Informatica1.c. En mi caso, sería:


```bash
 "Hola mundo, soy Matías.
```

Y el archivo se llamaría: 

```bash
LOPEZ_Informatica1.c
```

### 5. Subir tu rama a GitHub

```bash
git add [ARCHIVOS]
git commit -m "MENSAJE"
git push origin [RAMA]
```

### 6. Crear un Pull Request
1. Entrá al proyecto de GitHub
2. Vas a ver un cartel que dice "Compare & Pull Request"
3. Abrilo, revisá que el cambio sea correcto y hacé click en "Create Pull Request".

El PR o Pull request es la forma profesional de proponer un cambio en un proyecto compartido.



## 🧠 Bonus: explorá más comandos

| Comando | Descripción |
|----------|--------------|
| `git status` | Muestra el estado de los archivos (nuevos, modificados o listos para commit). |
| `git log` | Lista los commits con autor, fecha y mensaje. |
| `git diff` | Muestra las diferencias entre versiones o commits. |
| `git branch` | Lista las ramas locales y marca la activa. |
| `git merge` | Une los cambios de una rama con otra. |
| `git pull` | Trae los últimos cambios del repositorio remoto. |
| `git push` | Sube tus commits locales al repositorio remoto. |
| `git checkout -b nombre_rama` | Crea una nueva rama y se mueve a ella. |
| `git clone URL` | Descarga un repositorio remoto a tu máquina local. |

---


## 🗂️ Archivos que **no** deberían subirse

En los proyectos reales no todo se guarda en el repositorio.  
Algunos archivos son temporales, muy pesados o se generan automáticamente (por ejemplo: `.exe`, `.o`, `.DS_Store`, etc.).

Para eso existe un archivo especial llamado **`.gitignore`** 👀  
Sirve para decirle a Git: *“no sigas estos archivos”*.

> 💭 Te dejamos la curiosidad:  
> ¿Cómo se crea un `.gitignore` y qué tipo de archivos conviene excluir?

--- 

## 🎯 Resultado esperado

Al finalizar la actividad deberías tener:

- Una **rama** creada con tu nombre.  
- Un **commit** con tus cambios.  
- Un **Pull Request** abierto en GitHub para revisión.

---

## 💬 Recomendaciones

- Usá mensajes de commit claros y en presente (“Agrego función de saludo”).  
- No subas archivos compilados (`.exe`, `.o`, etc.).  
- Si algo sale mal, podés volver a una versión anterior con `git log` y `git checkout`.

---

## 👨‍🏫 Información docente

**Docente:** Matías N. López  
**Materia:** Informática I – UTN FRBA  

