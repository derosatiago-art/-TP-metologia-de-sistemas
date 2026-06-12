
# Estadísticas del Repositorio

* **Integrante con mayor cantidad de commits:** [derosatiago-art] realizo ([15] commits).
  * *Comando usado:* `git shortlog -s -n`

* **Cantidad total de merges realizados:** [5] merges.
  * *Comando usado:* `git rev-list --merges --count HEAD`

* **Cantidad de conflictos producidos:** [1] conflictos. 

* **Cantidad de ramas existentes en el repositorio:** [6] ramas.
  * *Comando usado:* `git branch -a `

* **Commit con la mayor cantidad de archivos modificados:**
  * *Hash del commit:* `[5dbe405]`
  * *Cantidad de archivos involucrados:* `[1 Archivo]`
  * *Comando usado para encontrarlo:* `git log --stat --oneline`
  * *Captura del conflicto y diff:* ![Captura del conflicto](conflicto.png) ```
  * *resolucion del conflicto:*El choque de versiones en el archivo `indice.md` se solucionó desde la interfaz de Visual Studio Code seleccionando el cambio correcto. Luego, se guardó el archivo y se ejecutaron los comandos `git add indice.md` y `git commit` en la terminal para finalizar la fusión.
---

### 5. Archivo: `IA.md`
```markdown
# Documentación sobre el uso de IA

 Usamos un Modelo de Lenguaje Grande (LLM) como herramienta de asistencia para poder hacer este repositorio.

**Uso específico:**
* Ayudo en la resolución de errores de los comandos git.
* Ayudo en la estructura de los archivos.