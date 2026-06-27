# Triple-Ten - Sprint7 - Proyecto Final - Telecom Analysis
## Análisis ConnectaTel
Proyecto de análisis sobre el comportamiento de los clientes de la empresa de telecomunicaciones ConnectaTel LATAM. Se trabaja con información registrada hasta el año 2024, lo cual permite analizar el comportamiento del negocio dentro de ese periodo.

**Para ello se trabaja con tres datasets:**
- `plans.csv` → información de los planes actuales (precio, minutos incluidos, GB incluidos, costo por extra)
- `users.csv` → información de los clientes (edad, ciudad, fecha de registro, plan, churn)
- `usage.csv` → detalle del uso real de los servicios (llamadas y mensajes)

Se explora, limpia y analiza estos datos para construir un perfil estadístico de los clientes, detectar comportamientos atípicos y crear segmentos de clientes.
Este análisis permite identificar patrones de consumo, diseñar estrategias de retención y sugerir mejoras en los planes ofrecidos por la empresa.

**Se busca responder las siguientes preguntas del negocio:**
- ¿Qué segmentos de clientes muestran mayor o menor uso de llamadas y mensajes?
- ¿Qué usuarios presentan valores atípicos que puedan indicar comportamientos inusuales, fraude o errores de registro?
- ¿Cómo varía el uso según la edad y el tipo de plan contratado?
- ¿Qué patrones pueden ayudar a diseñar mejores planes, optimizar la oferta y mejorar la satisfacción del cliente?

**Etapas realizadas:**
- Paso 1: Cargar y explorar
- Paso 2: Identificación de problemas de calidad de datos
- Paso 3: Limpieza de datos
- Paso 4: Summary statistics de uso por usuario
- Paso 5: Visualización de distribuciones (uso y clientes) y outliers
- Paso 6: Segmentación de Clientes
- Paso 7: Análisis Ejecutivo para Stakeholders
- Paso 8: Carga en GitHub

**Cómo ejecutar el notebook**
- 1.- Abrirlo en Google Colab o Jupyter NoteBook Web desde Github.
- 2.- Clonarlo a Local y luego cargarlo en Google Colab o Jupyter NoteBook Web.
- Nota importante: si se realiza la clonación y carga desde su PC o laptop en Google Colab o Jupyter NoteBook Web, puede darse el siguiente error:
  
      ModuleNotFoundError: No module named 'modulo o líbrería'

Para corregirlo se requiere ejecutar en una celda de código la instalación de las librerías antes de importarlas con la siguiente instrucción:

        %pip install nombre_librería

>>`Ejemplo con la librería de Pandas:`
- Error que se presentaría al intentar importar pandas:
  
       ModuleNotFoundError: No module named 'pandas'
- Corrección del error al intentar importar pandas, ejecutar en una celda de código antes de importar la librería pandas:
  
      %pip install pandas

**Guía de reproducción:**
- 1.- Coloquese dentro de la celda de código de importación de librerías y presione `Ctrl + enter` para ejecutarla.
- 2.- Coloquese dentro de la siguiente celda de código consecutiva y presione `Ctrl + enter` para ejecutarla.
- 3.- Continúe realizando la acción del paso anterior celda por celda de código hasta terminar de ejecutar todas las celdas de código.
- Nota: Ejecute las celdas de forma descendente a partir de la celda de código de importación de librerías para evitar errores. Si realiza la ejecución en un orden diferente los resultados no serán los esperados.
