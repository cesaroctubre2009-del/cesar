# DOCUMENTACIÓN GIT

## 1. ¿Qué es Git?

Git es un sistema de control de versiones que permite guardar cambios en proyectos y trabajar de forma organizada.  
Se utiliza para controlar modificaciones en archivos y colaborar con otros desarrolladores.

---

## 2. ¿Cuál es el flujo de trabajo de Git?

El flujo básico de Git es:

1. Modificar archivos del proyecto.
2. Añadir cambios al área de preparación con `git add`.
3. Guardar los cambios con `git commit`.
4. Subir los cambios al repositorio remoto con `git push`.
5. Descargar cambios del repositorio con `git pull` o `git fetch`.
6. Unir ramas usando `git merge`.

---

## 3. Comandos realizados durante la práctica

### Git add

El comando `git add` añade archivos al área de preparación antes de hacer un commit.

```bash
git add .

---

## 4. ¿Qué es un conflicto de Git, qué lo causa y cómo solucionarlo?

Un conflicto de Git ocurre cuando dos personas modifican la misma parte de un archivo y Git no sabe qué cambio conservar.

Causas:

Dos usuarios editan la misma línea.
Se hacen cambios diferentes en ramas distintas.
Solución
Abrir el archivo en conflicto.
Elegir qué cambios conservar.
Guardar el archivo.
Añadir cambios:

/Images/conflicto.jpg.

