# Actividad-branching-jueves-2
aprender a usar branching

- Alumno 1 Monserrat Miranda
- Alumno 2 Diego Peña
- Alumno 3 Victor Erazo

# Actividad-branching-jueves-2

## Tema investigado
- Diego Peña

### Que es branching
Branching es la creación de diferentes ramas en un repositorio

### Que es fork
- Es una copia de un repositorio de otra persona, en nuestro repositorios propios

### Cuando se usa cada uno
- Se usan cuando uno quiere trabajar, o hacer aportes a proyectos públicos

### Por que github usa forks para contribuir a proyectos ajenos
Para que el dueño del proyectos pueda revisar aportes sin interferir con la información almacenada del repositorio, sin causar problemas, de que otra persona cambio algo sin previo aviso.

### Conclusión personal

El branching y los forks, son muy utiles porque permiten a varias personas trabajar al mismo tiempo sin irrumpir el codigo base, teniendo en cuenta de que necesitan aprobacion para incluir su codigo dentro de la rama principal.

###  ¿Que es un main y por que se protege?
- main es la rama principal (branch principal) de un repositorio en Git.ç
- Se protege para evitar errores y mantener la calidad del código.

### ¿Qué representa `main` en un proyecto?

La rama `main` es la rama principal de un repositorio. Representa la versión oficial del proyecto, es decir, el código más completo, funcional y listo para ser utilizado o entregado.

### ¿Por qué no debería usarse para cambios directos?

No se recomienda trabajar directamente en `main` porque:
- Puede introducir errores o bugs en el proyecto
- No hay revisión previa de los cambios
- Puede afectar a otras personas que usan el código

Lo correcto es crear una nueva rama, realizar los cambios ahí y luego integrarlos mediante una revisión.

###  ¿Por qué es importante mantenerla estable?

Es importante mantener `main` estable porque:
- Es la versión que otros utilizarán
- Sirve como base confiable del proyecto
- Permite un trabajo en equipo más organizado
- Evita errores en producción

Si `main` no es estable, todo el proyecto puede verse afectado.

## ¿Qué es un commit y por qué es importante?

### ✨ ¿Qué es un commit?
Un **commit** es un punto de guardado que captura los cambios realizados en un proyecto en un momento específico.

---

### 🔹 ¿Por qué es importante?
- Permite guardar el progreso del proyecto  
- Mantiene un historial de cambios  
- Facilita el trabajo en equipo  
- Permite volver a versiones anteriores si hay errores  

---

### 🔸 ¿Por qué se deben hacer commits pequeños?
Porque:
- Son más fáciles de revisar  
- Permiten entender mejor los cambios realizados  
- Mantienen el historial del proyecto ordenado y claro  
- Facilitan la colaboración entre desarrolladores  

---

### 🧠 ¿Cómo ayudan los commits a entender la historia del trabajo?
Los commits permiten:
- Ver qué cambios se realizaron en el proyecto  
- Identificar quién hizo cada cambio  
- Entender la evolución del código  
- Corregir errores regresando a versiones anteriores  

---


## 1. ¿Qué es un merge?
Un **merge** es el proceso de **unir los cambios de una rama con otra**.  
Generalmente se usa para integrar el trabajo de una rama (por ejemplo, `feature`) en la rama principal (`main`).

---

## 2. ¿Qué es un conflicto?
Un **conflicto** ocurre cuando Git no puede unir automáticamente los cambios, porque **dos personas modificaron la misma parte del código** de manera diferente.

---

## 3. ¿Cómo puede evitarse o reducirse?
- Hacer **commits frecuentes y pequeños**  
- Mantener tu rama actualizada con `main`  
- Comunicarte con tu equipo sobre qué está trabajando cada uno  
- Trabajar en partes distintas del código cuando sea posible  
- Revisar los cambios antes de hacer merge  

---







Alumno 7
### Debe investigar:

- Qué significa merge
Merge es la fusión de varias ramas en el repositorio principal 'main'

- Qué es un conflicto de merge
Es un conflicto que ocurre cuando hay modificacion de un mismo archivo en dos ramas diferentes, donde git intenta unir dos ramas, y el sistema no sabe que cambios mantener o cual tiene mayor peso o importancia.

- Por qué ocurre cuando dos personas editan lo mismo
Porque no puede combinar cambios automáticamente que se hicieron en el mismo sector o linea de código de un archivo, o una persona edito un archivo que se eliminó. hay contradiccion en las diferentes ramas.

- Como evitar un merge o reducirse
Trabajando solo caracteristicas espeficicas en ramas que describan el espacio de donde se está trabajando, como ejemplo: 
Voy a editar el login,
- aviso que esa va ser mi tarea dentro del grupo de trabajo
- creo una rama con un nombre pertinente que defina mi acción (editar login)
- creo y edito archivos pertinentes (.gitignore, y archivos de proyecto)
- agrego, confirmo, y envio los datos al repositorio
- dentro del repositorio, hago una solicitud de revision, espero confirmacion o rechazo.
- vuelvo a editar en caso de rechazo, procedo a realizar otra tarea en caso de confirmación

## 👨‍🎓 Alumno 8 — Buenas prácticas al trabajar con ramas

- nombrar ramas
Las ramas deben nombrarse segun la caracteristicas que se vayan a trabajar, por ejemplo
* style/PagInicio -> lleva un style evidenciando que trabajara estilos, o visualizacion, pueden aplicarse definiciones mejores, y luego lo que va a trabajar.
* feature/regEx-Run-Usuario -> esto indica que se va trabajar una nueva caracteristicas o funcion del programa, donde se implementa el como son reconocidos los RUN de los usuarios dentro del programa
bugfix/error-formulario -> indica que es para solucionar problemas de insectos, como cuando vegeta invade la tierra.

- frecuencia de commits
Definir frecuencia de commints con trabajo de equipo, al final jornada, o cuando una se termina una tarea.
Para los commits y buenas practicas tener presente.
- mensajes claros
- no trabajar todo en una sola rama eterna
- revisar antes de mergear
- definir resumidamente siempre las tareas elaboradas
