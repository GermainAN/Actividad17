# Actividad17: Gestión ágil de proyectos con GitHub Projects, configuración de Kanban Board y creación de historias de usuario
#### Integrantes:
- Frank Oliver Hinojosa Zamora
- Germain Ronald Choquechambi Quispe
- Guido Anthony Chipana Calderon
- Edy Saul Serrano Arostegui

### Parte 1:
En este ejercicio aprenderemos como configurar un Kanban board usando GitHub Projects para el repositorio del curso. 

1. Navega al repositorio del curso donde has estado trabajando en GitHub.

2. Una vez que estés en la página del repositorio, haz clic en la pestaña Projects.

3. Al lado del botón Link project, haz clic en el menú desplegable y selecciona New Project.

4. Después de hacer clic en el botón New Project, aparecerá una ventana emergente para crear un proyecto. Selecciona Kanban, como se muestra en la captura de pantalla.

5. Nombra tu proyecto como Devops-agile y procede haciendo clic en el botón Create project.

    ![alt text](Img17/05.jpg)

6. En el Kanban board del proyecto, tendrás columnas para representar diferentes etapas de tu flujo de trabajo, como Backlog, Ready, In Progress, In review, y Done. Puedes agregar columnas personalizadas según los requisitos de tu flujo de trabajo.

    ![alt text](Img17/06.jpg)

7. Para personalizar o modificar el nombre de una columna, haz clic en los tres puntos y luego selecciona Edit details.

    ![alt text](Img17/07.jpg)

8. Cuando hagas clic en Edit details, aparecerá una ventana emergente, como se muestra en la captura de pantalla a continuación. Introduce el nombre de la columna requerido en el cuadro de texto resaltado. Puedes agregar una descripción apropiada o elegir eliminarla, luego haz clic en Save para confirmar los cambios.

9. De manera similar, renombra las columnas restantes de la siguiente manera:

    * Renombra la columna Ready a Icebox.
    * Deja la columna In Progress tal como está.
    

        ![alt text](Img17/08.jpg)

    * Renombra la columna In review a Review/QA.   
    * Deja la columna Done tal como está.

        ![alt text](Img17/09.jpg)

10. Después de realizar los cambios mencionados, presenta tu Kanban board.

11. Para agregar una nueva columna, navega al final de las columnas existentes y haz clic en el botón +. Luego, selecciona New column de las opciones. Introduce el nombre de la columna como Product Backlog en el campo de texto Label, y finalmente, haz clic en Save para aplicar los cambios.

    ![alt text](Img17/10.jpg)

    ![alt text](Img17/11.jpg)

12. Para establecer la secuencia correcta en el Kanban board, arrastra la columna Product Backlog y colócala antes de la columna In Progress. La flecha en la captura de pantalla a continuación indica desde dónde necesitas arrastrar y soltar la columna.

    ![alt text](Img17/12.jpg)

13. De manera similar, crea la columna Sprint Backlogs, y luego reorganízala para que se asemeje al Kanban board mostrado a continuación. Ejemplo de tablero kanban

    ![alt text](Img17/13.jpg)

### Parte 2:

En este ejercicio, crearemos una issue template en GitHub que nos ayudara a escribir historias de usuario bien formateadas en el Kanban board.

**Crear una issue template en GitHub**


1. En la página del repositorio que usaste en el ejercicio anterior, selecciona Settings.

2. Desplázate hacia abajo hasta la sección Features y selecciona Set up templates.

    ![alt text](Img17/21.jpg)

3. En la lista desplegable etiquetada Add template, selecciona Custom template.

    ![alt text](Img17/22.jpg)

4. Al lado de la entrada Custom issue template, presiona el botón Preview and edit.

    ![alt text](Img17/23.jpg)

5. Selecciona el icono del lápiz para editar la template.

6. Copia el siguiente markdown para el contenido de la plantilla de historia:

    ![alt text](Img17/24.jpg)

**Ejemplo de plantilla de historia**

7. Cambia el Template name a User Story, dale una descripción apropiada, y pega el contenido del markdown anterior en el Template content.

    ![alt text](Img17/25.jpg)

8. Desplázate hacia la parte superior de la página y presiona el botón Propose changes.

    ![alt text](Img17/26.jpg)

9. Presiona el botón Commit changes para confirmar el cambio en tu repositorio.

Commit change:
    ![alt text](Img17/27.1.jpg)

Ahora deberías tener una nueva carpeta en tu repositorio llamada .github/ISSUE_TEMPLATES, que contendrá tu nueva issue template de historia de usuario.

Mostramos el `GitHub/ISSUES_TEMPLATE`:
    ![alt text](Img17/27.2.jpg)

Visualizamos el `user-story.md`:
    ![alt text](Img17/27.3.jpg)

Entramos a `user-story`:
    ![alt text](Img17/27.4.jpg)


Ahora tenemos una issue template que podemos usar para todos los repositorios de GitHub en los que necesitemos escribir historias para usar en el Kanban board.

### Parte 3:

En este ejercicio crearemos siete historias de usuario basadas en los requisitos dados. Las primeras cuatro se nos proporcionaran. Solo tendremos que copiarlas y pegarlas para familiarnos con la creación de historias de usuario en GitHub. Tenemos que crear las últimas tres historias de usuario. Luego priorizaremos estas historias y las moveremos a las columnas apropiadas en tu Kanban board.

**Objetivos**

Después de completar esta actividad podremos:

* Crear nuevas historias de usuario usando GitHub issues.
* Priorizar el product backlog.

**1: Crear nuevas historias de usuario usando GitHub issues**

En este ejercicio, crearás las siguientes historias de usuario usando GitHub issues:

1. Ve a la pestaña Issues del repositorio del curso o donde estés trabajando la actividad.

2. Haz clic en el botón New issue.

3. Verás tu template listada aquí. Haz clic en el botón Get Started.

4. Introduce el título para la primera historia como Need a service that has a counter y actualiza la sección de historia de usuario (es decir, As a, I need, So that) por ahora. Una vez hecho, haz clic en el botón Submit new issue.

**Historias de la lección:**

1. Título: Need a service that has a counter
Como un usuario, necesito un servicio que tenga un contador para que pueda hacer un seguimiento de cuántas veces se ha hecho algo.
Puedes usar esta versión en inglés si deseas: As a user, I need a service that has a counter so that I can keep track of how many times something has been done.

<img src="Img17/31.png" alt="alt text" width="600"/>

2. Título: Must allow multiple counters
Como un usuario, necesito tener múltiples contadores para que pueda hacer un seguimiento de varios conteos a la vez.
Puedes usar esta versión en inglés si deseas: As a user, I need to have multiple counters so that I can keep track of several counts at once.

<img src="Img17/32.png" alt="alt text" width="600"/>

3. Título: Must persist counter across restarts
Como proveedor de servicios, necesito que el servicio persista el último conteo conocido para que los usuarios no pierdan el seguimiento de sus conteos después de que el servicio se reinicie.
Puedes usar esta versión en inglés si deseas: As a service provider, I need the service to persist the last known count so that users don't lose track of their counts after the service is restarted.

<img src="Img17/33.png" alt="alt text" width="600"/>

4. Título: Counters can be reset
Como administrador del sistema, necesito la capacidad de reiniciar el contador para que pueda rehacer el conteo desde el principio.
Puedes usar esta versión en inglés si deseas: As a system administrator, I need the ability to reset the counter so that I can redo counting from the start.

<img src="Img17/34.png" alt="alt text" width="600"/>

**Nuevos requisitos:**

* Deploy service to the cloud
* Need the ability to remove a counter
* Need the ability to update a counter to a new value

Respecto a estos nuevos requisitos crearemos las nuevas historias de usuario basadas en los requisitos dados.


5. Título: Deploy service to the cloud
Como desarrollador, necesito desplegar el servicio en la nube para que los usuarios puedan acceder a él desde cualquier lugar.
As a developer, I need to deploy the service to the cloud so that users can access it from anywhere.

<img src="Img17/35.png" alt="alt text" width="600"/>

6. Título: Need the ability to remove a counter
Como usuario, necesito la capacidad de eliminar un contador para poder gestionar solo los contadores que realmente necesito.
As a user, I need the ability to remove a counter so that I can manage only the counters I need.

<img src="Img17/36.png" alt="alt text" width="600"/>

7. Título: Need the ability to update a counter to a new value
Como usuario, necesito la capacidad de actualizar el valor de un contador a un nuevo número para poder corregir errores o ajustar el conteo manualmente.
As a user, I need the ability to update a counter to a new value so that I can correct errors or manually adjust the count.

<img src="Img17/37.png" alt="alt text" width="600"/>

Despues de crear las historias:

<img src="Img17/40.png" alt="alt text" width="600"/>

5. Agregar la historia de usuario creada al Kanban board, haz clic en el botón de configuración al lado de la opción Projects, y luego elige el proyecto Devops-agile del menú desplegable que creaste en el ejercicio anterior.

<img src="Img17/41.png" alt="alt text" width="600"/>

6. A continuación, selecciona el menú desplegable Status y elige New Issues. Esta acción moverá la historia de usuario creada a la columna 'New Issues' en el Kanban board.

<img src="Img17/42.png" alt="alt text" width="600"/>

7. Para ver la historia de usuario recién creada en el Kanban board, navega a la pestaña Projects y selecciona el proyecto titulado Devops-agile.

8. Notarás que la historia de usuario recién creada ahora está listada bajo la columna New Issues.

9. Dado que debemos crear un total de siete historias de usuario, ajustemos el límite predeterminado a 7. Para lograr esto, haz clic en los tres puntos de la columna New Issues, luego selecciona la opción Set limit.

10. Introduce el límite como 7 en el campo de texto Column limit y haz clic en Save. Ten en cuenta que, similar a esto, puedes optar por modificar los límites de otras columnas o mantener los límites predeterminados.

<img src="Img17/43.png" alt="alt text" width="600"/>

11. Para regresar a la pestaña Issues para crear nuevas historias de usuario, simplemente haz clic en el botón de retroceso del navegador.

12. Continúa agregando historias hasta que las siete estén creadas y completa tu Kanban. Las primeras cuatro historias se proporcionan en la lección Deberás crear tu propio rol, función y beneficio para las últimas tres historias.

<img src="Img17/45.png" alt="alt text" width="600"/>


**Ejercicio: Priorizar el product backlog**

En este ejercicio, moverás issues entre columnas para recrear el Kanban board del video de la lección Building the Product Backlog. Esto simulará un punto de partida inicial para nuestro próximo laboratorio sobre la refinación del backlog. Ten en cuenta que puedes mover los issues entre columnas simplemente arrastrándolos y soltándolos de una columna a otra.

1. Mueve la historia Need a service that has a counter al inicio de la columna Product Backlog.

<img src="Img17/46.jpg" alt="alt text" width="600"/>

2. Mueve la historia Must allow multiple counters a la columna Icebox.

<img src="Img17/47.jpg" alt="alt text" width="600"/>

3. Mueve la historia Must persist counter across restarts al final de la columna Product Backlog.

<img src="Img17/48.jpg" alt="alt text" width="600"/>

4. Mueve la historia Counters can be reset al final de la columna Product Backlog.

<img src="Img17/49.jpg" alt="alt text" width="600"/>

5. Deja las historias restantes en la columna New Issues por ahora. Las moveremos en un laboratorio posterior.

<img src="Img17/50.jpg" alt="alt text" width="600"/>

### Parte 4:

En este ejercicio, seguiremos los pasos para llevar a cabo una reunión de refinamiento del backlog. Seremos el product owner preparando el product backlog para tu próxima reunión de planificación del sprint. Esto implica preparar las historias que creamos en el último ejercicio para hacerlas listas para el sprint.

**Objetivos**
Después de completar este ejercicio, podrás:

* Triage de nuevos issues
*  Hacer que las historias estén listas para el sprint
* Crear nuevas labels
* Añadir labels a las historias

**Estado inicial**
New Issues:
* Deploy service to the cloud
* Need the ability to remove a counter
* Need ability to update a counter to a new value

Icebox:
* Must allow multiple counters

Product Backlog:
* Need a service that has a counter
* Must persist counter across restarts
* Counters can be reset

**1: Triage de nuevos issues**
En este ejercicio, tomarás todas las historias en la columna New Issues y las moverás a una columna apropiada o las rechazarás.

1. Ve a github.com e inicia sesión con tu cuenta de GitHub y abre tu Kanban board.

2. El primer nuevo issue es Deploy service to the cloud. Queremos hacer eso después de agregar persistencia, así que muévelo a la columna Product Backlog bajo Must persist counter across restarts.

3. El siguiente nuevo issue es Need the ability to remove a counter. Solo tenemos un contador y no quisiéramos eliminarlo, así que muévelo al Icebox después de Must allow multiple counters.

4. El último nuevo issue es Need ability to update a counter to a new value. Podríamos querer hacerlo como una mejora después de poder reiniciar el contador, así que muévelo al Product Backlog después de Counters can be reset.

<img src="Img17/51.jpg" alt="alt text" width="600"/>

**2: Hacer que las historias estén listas para el sprint**

En esta parte, agregarás más detalles a las historias en el Product Backlog que creas que podrían entrar en el próximo sprint. Se te proporcionarán los detalles para dos de las historias. Debes proporcionar los detalles para las otras tres.

1. Selecciona la primera historia en la parte superior de la columna Product Backlog para abrirla. Haz clic en los tres puntos y luego selecciona el botón Edit para editar el issue.

2. Edita los Details y Assumptions para que los desarrolladores sepan lo que sabemos, y edita los Acceptance Criteria para asegurar que todos entiendan cuál es la definición de "hecho(done)".

3. Cuando termines de editar, presiona el botón Save para guardar las ediciones.

4. Cierra la ventana presionando el icono de X.

5. Edita la historia Must persist counter across restarts de la misma manera.

6. Edita las siguientes historias con tus propios detalles, suposiciones y criterios de aceptación:

    * Deploy service to the cloud
    * Counters can be reset
    * Need ability to update a counter to a new value
    
    <img src="Img17/52.jpg" alt="alt text" width="600"/>

**3: Crear nuevas labels en GitHub**
En este ejercicio, crearemos una nueva label en GitHub llamada technical debt para marcar aquellas historias que no aportan valor visible al cliente pero deben completarse para continuar con el desarrollo.

1. Desde la página de tu repositorio, selecciona la pestaña Issues.

2. Desde la página de issues, selecciona el botón Labels.

3. Desde la página de labels, selecciona el botón New label.

    <img src="Img17/53.jpg" alt="alt text" width="600"/>

4. En la sección de nueva label:
    (1) establece el nombre de la label como technical debt
    (2) establece el Color como amarillo (#FBCA04)
    (3) presiona el botón Create label.

    <img src="Img17/54.jpg" alt="alt text" width="600"/>

Ahora podemos ver una label amarilla technical **debt** que podemos usar para anotar nuestras historias.


**4: Añadir labels a las historias**
En este ejercicio, añadirás labels a las historias en el Product Backlog para hacerlas aún más listas para el sprint. También usarás nuestra nueva label llamada technical debt para marcar aquellas historias que no aportan valor visible al cliente pero deben completarse para continuar con el desarrollo.

1. Selecciona la primera historia en la parte superior de la columna Product Backlog para abrirla. Luego, presiona el icono de engranaje al lado de Labels para asignar una label.

2. Nuestra primera historia es una mejora a nuestro producto. Desde el menú de labels, selecciona enhancement para reflejar eso.

    <img src="Img17/55.jpg" alt="alt text" width="600"/>

3. Haz clic en cualquier parte fuera del menú de labels para cerrarlo. Ahora deberías ver que la label enhancement ha sido asignada a esta historia.

    <img src="Img17/56.jpg" alt="alt text" width="600"/>

4. Selecciona cada una de las siguientes historias en la columna Product Backlog y asígnales las labels correspondientes:

    * **Story Title:** Must persist counter across restarts

      **Label:** enhancement

    <img src="Img17/57.jpg" alt="alt text" width="600"/>

    * **Story Title:** Deploy service to the cloud
    
      **Label:** technical debt

    <img src="Img17/58.jpg" alt="alt text" width="600"/>

    * **Story Title:** Counters can be reset

      **Label:** enhancement
    
    <img src="Img17/59.jpg" alt="alt text" width="600"/>

    * **Story Title:** Need ability to update a counter to new value

      **Label:** enhancement

    <img src="Img17/60.jpg" alt="alt text" width="600"/>

*  Abre el menú desplegable al lado de Backlog (resaltado como 1 en la captura de pantalla a continuación).
*  Haz clic en la flecha al lado de la opción Fields (resaltado como 2).
*  Arrastra y suelta Labels de la lista de campos ocultos a la lista de campos visibles (resaltado como 3).
*  Haz clic en el botón Save (resaltado como 4) para guardar los cambios.

    <img src="Img17/61.jpg" alt="alt text" width="600"/>

### Ejercicios:

#### **Ejercicio 1:**  Crear un Epic y vincular historias de usuario

**Objetivo:** Aprender a organizar historias de usuario más grandes en Epics y vincular múltiples historias de usuario a un Epic.

**Instrucciones:**

1. Crea un nuevo Epic en tu Kanban board llamado "Gestión de Contadores".

<img src="Img17/62.jpg" alt="alt text" width="600"/>

2. Vincula las historias de usuario existentes, como "Need a service that has a counter", "Must allow multiple counters", y "Counters can be reset" a este Epic.
3. Añade una nueva historia de usuario bajo este Epic que abarque una funcionalidad adicional (por ejemplo, "Generar reportes de uso de contadores").

<img src="Img17/63.jpg" alt="alt text" width="600"/>

**Resultadoesperado:** El Epic "Gestión de Contadores" debe contener las historias de usuario relacionadas, proporcionando una visión global de esta funcionalidad.

<img src="Img17/64.jpg" alt="alt text" width="600"/>

#### **Ejercicio 2:** Uso avanzado de etiquetas (labels) para priorización y estado

**Objetivo:** Aprender a usar etiquetas de manera más detallada para indicar la prioridad y el estado de las historias.

**Instrucciones:**

1. Crea nuevas etiquetas como high priority, medium priority, y low priority.

    <img src="Img17/65.jpg" alt="alt text" width="600"/>

2. Asigna una de estas etiquetas a cada historia de usuario en el Product Backlog para indicar su prioridad.

    <img src="Img17/66.jpg" alt="alt text" width="600"/>

3. Crea etiquetas adicionales como in review, blocked, y ready for testing.
4. Usa estas etiquetas para actualizar el estado de las historias según su progreso en el Kanban board.

    <img src="Img17/67.jpg" alt="alt text" width="600"/>

**Resultado esperado:** Las historias de usuario tendrán etiquetas que indiquen tanto su prioridad como su estado actual, facilitando la gestión del flujo de trabajo.


#### **Ejercicio 3:** Automatización de Kanban board con GitHub Actions

**Objetivo:** Aprender a automatizar tareas en el Kanban board usando GitHub Actions.

**Instrucciones:**

1. Configura un flujo de trabajo de GitHub Actions que automáticamente mueva las historias de usuario entre columnas del Kanban board basado en eventos. Por ejemplo, mover automáticamente una historia a "In Progress" cuando se asocia un pull request.
2. Crea un archivo de configuración de GitHub Actions en la carpeta .github/workflows que defina estas reglas de automatización.

    <img src="Img17/68.jpg" alt="alt text" width="600"/>

**Resultado esperado:** Las historias de usuario se mueven automáticamente en el Kanban board según las reglas definidas, como cambiar de columna al asociar un pull request o al cerrar un issue.
    <img src="Img17/69.jpg" alt="alt text" width="600"/>

#### **Ejercicio 4:** Seguimiento de tiempo y esfuerzo usando GitHub Projects

**Objetivo:** Aprender a usar el seguimiento de tiempo y esfuerzo para las historias de usuario en GitHub Projects.
1. Añade un campo personalizado en tu Kanban board para registrar el esfuerzo estimado de cada historia de usuario (en horas).

**Instrucciones:**

2. Establece una estimación de esfuerzo para cada historia en el Product Backlog.

3. Durante el sprint, actualiza el campo para reflejar el tiempo real invertido en cada historia.

<img src="Img17/70.jpg" alt="alt text" width="600"/>

**Resultado esperado:** Cada historia de usuario tendrá una estimación de tiempo y un registro del tiempo real invertido, permitiendo un análisis del esfuerzo requerido.

#### Ejercicio 5: Refinamiento de backlog basado en comentarios de los stakeholders

**Objetivo:** Aprender a refinar las historias de usuario del Product Backlog basado en comentarios de los stakeholders.

**Instrucciones:**

1. Imagina que has recibido comentarios de stakeholders indicando que necesitan una funcionalidad adicional, como "Exportar datos del contador a CSV".

2. Crea una nueva historia de usuario basada en estos comentarios.

<img src="Img17/71.jpg" alt="alt text" width="600"/>

3. Realiza una sesión de refinamiento del backlog y prioriza esta nueva historia en el Product Backlog.

4. Añade los detalles necesarios para que esta historia esté lista para el sprint, incluyendo criterios de aceptación.

<img src="Img17/72.jpg" alt="alt text" width="600"/>

**Resultado esperado:** La nueva historia de usuario basada en los comentarios de los stakeholders está correctamente integrada y priorizada en el Product Backlog.


#### Ejercicio 6: Análisis del flujo de trabajo usando el Kanban board

**Objetivo:** Analizar el flujo de trabajo usando las métricas proporcionadas por el Kanban board.

**Instrucciones:**

1. Activa las métricas en GitHub Projects para tu Kanban board.

2. Observa y analiza las métricas generadas, como el tiempo promedio en cada columna y el número de historias completadas.

3. Identifica cuellos de botella en tu flujo de trabajo e identifica posibles mejoras.

<img src="Img17/73.jpg" alt="alt text" width="600"/>

**Resumen del gráfico:**

* Icebox: 2 elementos
* Product Backlog: 6 elementos
* Done: 1 elemento

1. Cantidad de historias completadas:

    * Solo 1 historia ha sido completada (Done), lo que indica un avance bajo en el ciclo actual o sprint.

2. Acumulación en el Product Backlog:
    * 6 historias están en el Product Backlog, lo cual representa el 66% del total visible en el gráfico. Esto sugiere que la planificación o el refinamiento puede no estar siendo lo suficientemente agil o que las historias aun no están listas para moverse a ejecucion.

3. Cuello de botella:
    * El mayor cuello de botella está en la fase de Product Backlog. Si estas historias no avanzan, puede ser por dependencias sin resolver o falta de asignación.

**Mejoras:**
* Reunirse como equipo para analizar por que las tareas no están pasando a desarrollo.
* Revisar prioridades y actualizar estimaciones de esfuerzo si es necesario.
