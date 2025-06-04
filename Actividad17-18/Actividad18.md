# Actividad 18

## **Gestión ágil de sprints con GitHub, planificación, ejecución y cierre de Sprints**

### **Parte 1**

1. **Configuración de Sprints**
    - Ve a GitHub, inicia sesión con tu cuenta de GitHub, y abre tu Kanban board.
        
        ![imagen.png](imagenes/imagen.png)
        
    - Aparecerá una ventana emergente. Introduce **Sprint** como el nombre del campo, elige **Iteration** como el tipo de campo, y deja la fecha de inicio en la fecha actual. Mantén la duración en dos semanas. Finalmente, haz clic en el botón **Save and create**.
    - Ahora tienes un sprint que se puede usar para la planificación del sprint en el próximo ejercicio.
        
        ![imagen.png](imagenes/imagen%201.png)
        
2. **Crear un Sprint plan**
    - Selecciona la historia superior **Need a service that has a counter** del Product Backlog para abrirla.
    - Discutiste la historia con el equipo, y tus desarrolladores están de acuerdo en que esta es una historia grande que vale 8 puntos de historia, así que establece el **Estimate** en 8.
        
        ![imagen.png](imagenes/imagen%202.png)
        
    - El equipo de desarrollo ha determinado que agregar una historia de 8 puntos al sprint es aceptable. Arrastra la historia del Product Backlog al **Sprint Backlog**.
    
    **Nota**: Puedes ver las fechas de inicio y fin de la historia de usuario pasando el ratón sobre el Sprint que se muestra en la tarjeta.
    
    - Observa que la estimación de puntos de historia y las fechas del sprint son anotaciones en la historia.
        
        ![imagen.png](imagenes/imagen%203.png)
        
    - La reunión de planificación del sprint ha avanzado bien. En las discusiones con el equipo de desarrollo, han estimado las siguientes dos historias en el Product Backlog y han determinado que ambas pueden caber en el sprint actual.
        
        
        | **Título de la Historia** | **Puntos de Historia** |
        | --- | --- |
        | Must persist counter across restarts | 5 |
        | Deploy service to the cloud | 5 |
    

![imagen.png](imagenes/imagen%204.png)

![imagen.png](imagenes/imagen%205.png)

- Sprint plan
    
    ![imagen.png](imagenes/imagen%206.png)
    
- Basado en la velocidad del equipo, el equipo de desarrollo ha decidido que hay suficientes historias en el sprint, pero queda algo de tiempo en la reunión de planificación del sprint para estimar más historias. Añade las siguientes estimaciones a las historias en el Product Backlog.
    - [ ]  Counters can be reset -> 3
    - [ ]  Need ability to update a counter to new value -> 5

![imagen.png](imagenes/imagen%207.png)

- Kanban board.
    
    ![imagen.png](imagenes/imagen%208.png)
    

### Parte 2

- [ ]  **Flujo de trabajo diario**

En este ejercicio, simularás el flujo de trabajo diario de un desarrollador en un equipo Agile. Comenzarás moviendo una historia desde la parte superior del Sprint Backlog a la columna In Progress y la asignarás a ti mismo. Luego, simularás completar la historia, solicitar una revisión y finalmente moverla a Done.

1. Ve a GitHub, inicia sesión con tu cuenta de GitHub y abre tu Kanban board.
2. El sprint ha comenzado y estás listo para trabajar en tu primera historia. Selecciona la historia en la parte superior del Sprint Backlog para abrirla y leerla.
3. Después de leerla, decides que esta es una tarea para la que tienes las habilidades necesarias, así que te la asignas haciendo clic en la opción **Assign yourself**.
    
    ![imagen.png](imagenes/imagen%209.png)
    
4. Una vez asignada, haz clic en el botón **X** para cerrar la ventana.
5. De vuelta en el Kanban board, mueve la historia que acabas de asignarte del Sprint Backlog arrastrándola a la columna **In Progress**.
    
    ![imagen.png](imagenes/imagen%2010.png)
    
6. Ahora, todos saben que estás trabajando en esta historia. Normalmente, crearías una rama en GitHub para comenzar a trabajar en tu código. Para esta actividad, solo asegúrate de que tu Kanban board se vea como el siguiente
7. Una vez que termines de trabajar en la historia, es momento de solicitar una revisión. Siempre es buena idea que al menos otra persona revise todos los productos de trabajo. Si registraste código en GitHub, este es el paso donde harías un pull request para fusionar tu código en la rama main. Mueve tu historia de In Progress a **Review/QA**.
    
    ![imagen.png](imagenes/imagen%2011.png)
    

1. Mientras esperas una revisión, decides comenzar a trabajar en otra historia. Toma la siguiente historia de la parte superior del Sprint Backlog, léela para asegurarte de que tienes las habilidades para implementarla (Pista: Las tienes), asígnatela y muévela a In Progress.

![imagen.png](imagenes/imagen%2012.png)

1. Tu pull request para la historia inicial ha sido aprobado, y el proceso de revisión se ha completado. Por favor, mueve la historia **Need a service that has a counter** de la columna Review/QA a la columna **Done**.
    
    **Nota**: Cuando los issues se mueven a la columna Done, se marcarán automáticamente como cerrados, gracias a la funcionalidad incorporada de GitHub.
    
    ![imagen.png](imagenes/imagen%2013.png)
    
    1. Has completado el trabajo en tu segunda historia y has hecho otro pull request. Mueve la historia **Must persist counter across restarts** de la columna In Progress a la columna **Review/QA** para solicitar una revisión.
    2. Toma la última historia, **Deploy service to the cloud**, de la parte superior del Sprint Backlog, asígnatela y muévela a In Progress.
        
        ![imagen.png](imagenes/imagen%2014.png)
        
        ![imagen.png](imagenes/imagen%2015.png)
        
        1. La revisión de tu segunda historia se ha completado. Mueve la historia **Must persist counter across restarts** de Review/QA a **Done**
            
            ![imagen.png](imagenes/imagen%2016.png)
            
        2. El sprint ha terminado y no hemos tenido tiempo para completar nuestra última historia, **Deploy service to the cloud**, que aún está en progreso. Veremos cómo lidiar con esto. Déjala donde está por ahora.
            
            ![imagen.png](imagenes/imagen%2017.png)
            
        3. Presenta tu Kanban board terminado.

![imagen.png](imagenes/imagen%2018.png)

# Parte 3

En este ejercicio, configurarás un burndown chart para tu sprint plan usando GitHub. Un burndown chart es una herramienta visual utilizada en la gestión ágil de proyectos para rastrear el progreso de un proyecto a lo largo del tiempo. Muestra la cantidad de trabajo restante frente al tiempo. El eje x en un burndown chart normalmente representa la línea de tiempo (días, sprints, etc.), mientras que el eje y muestra la cantidad de trabajo restante (a menudo medido en story points, tareas u horas). El gráfico ayuda a los equipos a monitorear su progreso y predecir si completarán su trabajo antes de la fecha límite del proyecto.

**Objetivos**

Después de completar esta actividad, podrás:

- Entender cómo configurar tu burndown chart
- Ver los datos que contiene un burndown chart
- Evaluar tu progreso en el sprint

### **1: Configurar tu Burndown Chart**

En este ejercicio, configurarás tu burndown chart para mostrar el estado de las historias en la columna Done.

1. Ve a GitHub, inicia sesión con tu cuenta y abre tu Kanban board.
2. Para crear un burndown chart para tu sprint en GitHub Projects, haz clic en el menú desplegable junto a Backlog y selecciona **Generate chart**.
3. Esta acción abrirá la sección **Insights** de tu proyecto. Aquí, verás el gráfico de **Status** predeterminado generado para tu proyecto
    
    ![imagen.png](imagenes/imagen%2019.png)
    
4. Para configurar un burndown chart que solo muestre el estado de las historias en la columna Done en lugar del gráfico predeterminado, aplica un filtro. Haz clic en **Filter by keyword or field**, escribe **Status** y selecciona **status:** del menú desplegable. Esto mostrará otro menú desplegable con todas las columnas de tu Kanban board. Selecciona **Done**.
5. Al pasar el cursor sobre el gráfico, puedes ver el número de historias de usuario en la columna Done. Estas incluyen las dos historias, **Need a service that has a counter,** **Must persist counter across restart,** que movimos a Done en el ejercicio anterior.
A continuación, para crear un nuevo gráfico que muestre el número de story points completados y restantes en el sprint, comienza limpiando el filtro haciendo clic en el botón **clear filter**. Luego, haz clic en el botón **Configure**. Esto proporcionará un indicador visual de tu progreso.

![imagen.png](imagenes/imagen%2020.png)

1. A continuación, para crear un nuevo gráfico que muestre el número de story points completados y restantes en el sprint, comienza limpiando el filtro haciendo clic en el botón **clear filter**. Luego, haz clic en el botón **Configure**. Esto proporcionará un indicador visual de tu progreso.
    
    ![imagen.png](imagenes/imagen%2021.png)
    
2. Para configurar el gráfico, añade los siguientes detalles:
    - **Layout**: Selecciona **Column** de las opciones de layout.
    - **X-axis**: Configura el eje X en **Sprint**.
    - **Group by**: Elige **Status** para agrupar los datos por estado.
    - **Y-axis**: Configura el eje Y en **Sum of a field**.
    - **Y-axis field**: Elige **Estimate** como el campo a sumar.
    
    Después de configurar estas opciones, haz clic en el botón **Save to new chart**.
    

![imagen.png](imagenes/imagen%2022.png)

1. Para centrar el gráfico en un sprint específico, usa la opción de filtro. Escribe **sprint:** en el cuadro de filtro y selecciona el sprint como **Sprint 1**. Nota: **Sprint 1** se refiere a la primera iteración del sprint que asignaste a las historias.
2. Al pasar el ratón sobre la columna Done, se mostrará el número de story points completados en el sprint, mientras que al pasar el ratón sobre la columna Progress se mostrará el número de story points restantes en el sprint. Esto proporciona un indicador visual útil de tu progreso. El burndown chart te permite evaluar rápidamente qué historias se han completado y cuáles aún requieren trabajo.

![imagen.png](imagenes/imagen%2023.png)

**Nota**: Para obtener información más detallada sobre tu proyecto, puedes personalizar las opciones del eje x, el eje y y la agrupación según tus requisitos específicos. Además, tienes la flexibilidad de modificar el layout del gráfico para visualizar mejor los datos. Al ajustar estas configuraciones, puedes crear representaciones más significativas e informativas que se alineen con tus objetivos de análisis.

# Parte 4

En este ejercicio práctico, aprenderás las actividades esenciales de cierre de sprint utilizando GitHub para gestionar historias no terminadas y preparar el backlog para el próximo sprint. Ajustarás los story points para las tareas incompletas, moverás las historias completadas a la columna **Done** y crearás nuevos issues para documentar el trabajo pendiente, asegurando una transición y continuidad fluidas entre sprints.

**Objetivos**

Después de completar este ejercicio, podrás:

- Ajustar los story points para reflejar con precisión el esfuerzo realizado.
- Gestionar issues y columnas en GitHub para rastrear el progreso del sprint.
- Crear nuevos issues para documentar deuda técnica y trabajo no terminado.
- Organizar el product backlog para priorizar y planificar de manera efectiva el próximo sprint.

**Nota**: En el Kanban board, no tenemos una columna **Closed** porque, en GitHub, cuando movemos issues a la columna **Done**, se cierran automáticamente gracias a la funcionalidad incorporada de GitHub.

### **Ejercicio: Gestionar el trabajo incompleto**

En este ejercicio, gestionarás las historias no terminadas en el sprint. Estas son historias que el equipo ha comenzado, pero no ha completado. Queremos ajustar la estimación para contabilizar los story points gastados, de modo que se refleje en la velocidad del equipo, y crear una nueva historia para finalizar el trabajo en el próximo sprint.

1. Selecciona la historia **Deploy service to the cloud** en la columna In Progress para abrirla.
2. Haz clic en la opción **Estimate**.
3. El desarrollador ha determinado que no se gastaron 5 story points de esfuerzo en esta historia y simplemente se quedaron sin tiempo. Estiman que se gastaron 2 story points. Introduce **2** en el campo de texto para cambiar los story points. Ahora podemos ver que los story points están configurados en 2. Luego, haz clic en la **X** para cerrar la ventana.

![imagen.png](imagenes/imagen%2024.png)

1. Ahora los story points se han ajustado para reflejar el esfuerzo que se hizo en este sprint. Mueve esta historia a la columna **Done**.

![imagen.png](imagenes/imagen%2025.png)

1. Presenta tu Kanban board avanzado.

![imagen.png](imagenes/imagen%2026.png)

1. Queremos crear una nueva historia para documentar el trabajo restante. Regresa a tu repositorio de GitHub de la actividad. Navega a la pestaña **Issues** y haz clic en el botón **New Issue**.
    
    **Nota**: Elige la **User Story Template** y haz clic en el botón **Get Started**.
    
2. Completa el nuevo issue llenando el título y la descripción para completar la historia. Asigna la etiqueta **technical debt**, similar a la historia original. Elige el proyecto como **Devops-agile**. Una vez terminado, haz clic en el botón **Submit new issue**.

![imagen.png](imagenes/509bf494-5fd4-4fa4-b122-a910f0dbd022.png)

1. Dado que este nuevo issue se agregará a la columna Product Backlog, abre la lista desplegable junto a la opción **Status** y elige **Product Backlog**. Establece el **Estimate** en **3**, representando los story points restantes de la historia no terminada.
    
    ![imagen.png](imagenes/imagen%2027.png)
    
2. Asegúrate de que la historia esté en la parte superior de la columna Product Backlog para ser seleccionada en el próximo sprint.
    
    ![imagen.png](imagenes/imagen%2028.png)
    
3. Al final nuestro Kanban board se quedaria de la siguiente manera:
imagenes
![imagen.png](imagene/imagen%2029.png)