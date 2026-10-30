# **SdA 2 Final: Proyecto Integrador "Lanzamiento y Gestión Digital de una Startup"**

---

## **1. DESCRIPCIÓN GENERAL Y MISIÓN DEL PROYECTO**

En este proyecto integrador final de la **Unidad Didáctica 2 (Comunicación y Colaboración Digital - CC)**, asumirás el rol de emprendedor/a digital y simularás el lanzamiento completo de tu propia empresa o proyecto de estudio (**Startup**).

A lo largo de esta actividad, aplicarás de forma práctica e integrada todas las competencias entrenadas en el tema (**SdA 2.1 a SdA 2.6**), utilizando el diseño en píxeles con **PiskelApp**, la generación web con la Inteligencia Artificial **Gemini** y el ecosistema colaborativo de **Google Workspace**.

### **Metodología y Sistema de Entrega (Sin capturas de pantalla):**
* **Trabajo real con archivos:** En lugar de rellenar un informe con capturas de pantalla, crearás y gestionarás **los archivos digitales reales** que genera una empresa en su día a día.
* **Estructura previa en la nube:** Lo primero que harás será entrar en tu carpeta de la asignatura (**CAGM**) en **Google Drive** y crear la estructura de carpetas de tu empresa para ir guardando cada fichero en su lugar correspondiente a medida que lo generas.
* **Entrega final en Moodle Centros:** Al terminar la actividad, descargarás tu carpeta de la Startup de Google Drive en un único archivo comprimido **`.zip`** que contendrá todas tus carpetas y ficheros originales de trabajo.

---

## **2. GUÍA DE TRABAJO PASO A PASO POR FASES**

---

### **FASE 1: Creación de la Estructura en Google Drive (Dentro de tu Carpeta CAGM)**

*Objetivo: Preparar el espacio de almacenamiento corporativo ("Mochila Digital") dentro de la carpeta general de la asignatura para organizar ordenadamente todos los documentos y recursos del proyecto.*

1. **Ubicación en Google Drive:**  
   Entra en tu **Google Drive** (`drive.google.com`) y accede a tu carpeta habitual del curso:  
   📁 **`CAGM`** (o el nombre que tengas asignado para la materia de *Competencia Digital Básica*).

2. **Creación de la Carpeta del Proyecto:**  
   Dentro de tu carpeta **`CAGM`**, haz clic en **`+ Nuevo` ➔ `Nueva carpeta`** y crea la carpeta principal de tu empresa con el siguiente formato exacto:  
   **`SDA_2_PROYECTO_STARTUP`**

3. **Creación de las 3 Subcarpetas de Trabajo:**  
   Entra dentro de la carpeta **`SDA_2_PROYECTO_STARTUP`** y genera estas tres subcarpetas:
   * **`01_Documentos_Oficiales`** (para guardar los textos, propuestas, la agenda `.csv` y el código web `index.html`).
   * **`02_Recursos_Multimedia`** (para guardar los archivos de imagen y logotipos `.gif` y `.png`).
   * **`03_Otros`** (para guardar información útil o relevante en caso de ser necesario).

4. **Configuración de Permisos Seguros:**  
   Haz clic derecho sobre tu carpeta **`SDA_2_PROYECTO_STARTUP`** ➔ **Compartir** ➔ **Obtener enlace**.  
   Configura el acceso general en modo **Cualquier persona con el enlace** pero con el rol estricto de **Lector** o **Comentador** *(¡Atención! Nunca selecciones Editor para evitar que personas externas puedan modificar o borrar tus archivos corporativos)*. Copia el enlace para incluirlo más adelante en la memoria.

---

### **FASE 2: Identidad Gráfica, Prototipo Web con IA y Documentación (SdA 2.1, 2.2 y 2.5)**

*Objetivo: Diseñar la identidad de marca de tu Startup, generar el prototipo web funcional y redactar la ficha técnica del proyecto.*

#### **Paso 1: Diseño del Logotipo en PiskelApp (SdA 2.1)**
1. Entra en **PiskelApp** (`piskelapp.com`) y haz clic en **Create Sprite** sobre el lienzo de 32x32 píxeles.
2. Dibuja el logotipo de tu Startup en el primer fotograma (*Frame 1*).
3. Añade un segundo fotograma (*Frame 2*) duplicando el primero y variando algún elemento (color, brillo o movimiento) para crear una animación continua. Ajusta la velocidad (**FPS**) en la ventana de previsualización.
4. Anota los valores numéricos **RGB (Rojo, Verde y Azul)** del color corporativo principal de tu diseño.
5. **Exportación de los ficheros de imagen:**
   * En el menú derecho, ve a **Export** ➔ pestaña **GIF** y descarga tu archivo animado: **`logo_startup.gif`**.
   * En la pestaña **PNG**, descarga una copia fija: **`logo_startup.png`**.
6. **Guardado en Drive:** Sube inmediatamente ambos archivos (`logo_startup.gif` y `logo_startup.png`) a la subcarpeta **`02_Recursos_Multimedia`** de tu carpeta del proyecto.

#### **Paso 2: Generación de una web (fichero `index.html`) utilizando IA (Gemini, ChatGPT, etc) (SdA 2.1 + IA)**
1. Abre **Gemini** (`gemini.google.com`) o cualquier IA que uses.
2. Adjunta en el chat el fichero con el **`logo_startup.png`** (o `.gif`).
3. Adjunta un documento (por ejemplo .pdf) con al menos 3 servicios que ofrecerá tu empresa.
4. Escribe el siguiente prompt a la IA:  
   `"Actúa como un diseñador web experto. Te adjunto el logotipo de nuestra empresa. Genera directamente el archivo index.html completo y descargable para la landing page promocional de mi Startup. La empresa se llama [Nombre de tu Startup], nos dedicamos a [Actividad] y nuestro color corporativo principal es RGB: R: ___, G: ___, B: ___. Incluye un encabezado con el logo, presentación, los servicios más destacados (extraídos del documento adjunto) y botón de contacto."`
5. **Descarga y comprobación del archivo:**
   * Descarga el archivo **`index.html`** generado por la IA directamente a tu ordenador.
   * Haz doble clic sobre **`index.html`** para abrirlo en **Google Chrome** y comprobar que tu web funciona correctamente en el navegador.
   * Para observar realmente como es el código (idioma) de una web, haz clic derecho sobre **`index.html`** ➔ **Abrir con** ➔ **Bloc de Notas** e inspecciona el código HTML y CSS generado.
6. **Guardado en Drive:** Sube el archivo **`index.html`** a la subcarpeta **`01_Documentos_Oficiales`** de tu carpeta del proyecto.

#### **Paso 3: Ficha Técnica y Documento Fundacional en Google Docs**
1. En Google Drive, entra en la subcarpeta **`01_Documentos_Oficiales`** y crea un nuevo **Documento de Google Docs** titulado:  
   **`Memoria_Fundacional_[Nombre de tu Startup]`**
2. Redacta en este documento los siguientes apartados:
   * **Datos de la Startup:** Nombre comercial, sector de actividad y descripción de los 3 servicios o productos que ofrece.
   * **Manual de Marca:** Inserta la imagen del logotipo y registra la paleta de color con sus valores numéricos exactos **RGB** (R: ___, G: ___, B: ___).
   * **Enlace Público de Drive:** Pega el enlace compartido (modo Lector) configurado en la Fase 1.
   * **Análisis de Privacidad y LOPD (6-8 líneas):** Explica por qué es fundamental proteger datos sensibles (DNI, contraseñas, teléfonos personales, datos bancarios) en la nube y por qué es obligatorio usar el campo **CCO** al enviar correos corporativos masivos.

---

### **FASE 3: Comunicación Oficial, Contactos y Colaboración en Equipo (SdA 2.1, 2.2, 2.3 y 2.4)**

*Objetivo: Configurar tu identidad en Gmail, enviar la comunicación formal del proyecto, organizar tu agenda y gestionar tareas colaborativas en tiempo real.*

#### **Paso 4: Configuración de Gmail y Firma Corporativa (SdA 2.1)**
1. En la configuración de Gmail (*General*), ajusta la opción **"Deshacer el envío"** a **30 segundos**.
2. Configura tu **Firma Corporativa** oficial con esta estructura:  
   `[Tu Nombre y Apellidos] | CEO / Fundador/a de [Nombre de tu Startup] | IES La Marisma (Huelva)`

#### **Paso 5: Envío Formal de Presentación con Adjunto (SdA 2.2)**
1. Redacta un correo en Gmail para presentar oficialmente la Startup:
   * **Para:** Dirección de tu profesor/a.
   * **CCO (Copia Oculta):** Añade al menos 2 direcciones reales de compañeros/as de clase para probar el envío protegiendo sus direcciones.
   * **Asunto:** `Presentación Oficial de la Startup - [Nombre de tu Startup]`
   * **Cuerpo:** Saludo formal, resumen ejecutivo de la empresa, tono profesional y despedida.
   * **Archivo adjunto:** Adjunta el archivo **`logo_startup.gif`** usando el icono del clip 📎.
2. Envía el correo formal.

#### **Paso 6: Agenda del Equipo en Google Contactos (SdA 2.3)**
1. Abre **Google Contactos** y añade a 3 compañeros/as de clase con sus nombres, apellidos, correo institucional y cargo dentro de la empresa.
2. Agrupa a estos contactos bajo la etiqueta de grupo: **`Equipo_Startup_UD2`**.
3. **Exportación de la Agenda:** En Google Contactos, selecciona la etiqueta `Equipo_Startup_UD2`, haz clic en **Exportar** y descarga el archivo en formato **CSV de Google** con el nombre: **`contactos_equipo.csv`**.
4. **Guardado en Drive:** Sube el archivo **`contactos_equipo.csv`** a la subcarpeta **`01_Documentos_Oficiales`** de tu carpeta del proyecto.

#### **Paso 7: Espacio en Google Chat y Google Tareas (SdA 2.4)**
1. Abre **Google Chat** y crea un **Espacio de Trabajo** titulado **`Startup_[Nombre de tu Proyecto]`**. Invita a tus compañeros/as de equipo para probar el canal.
2. **Mensaje Fijado en el Tablón (*Pin*):** Escribe el mensaje de bienvenida con las normas del equipo, haz clic en los tres puntos (`...`) y selecciona **Fijar (*Pin*)** para anclarlo en el tablón superior.
3. **Asignación de Tareas (Tasks):** En la pestaña *Tareas* del espacio, crea **3 tareas concretas** asignando responsable y fecha/hora límite:
   * *Tarea 1:* Revisión del diseño del logotipo y archivo `index.html`.
   * *Tarea 2:* Redacción de la propuesta de servicios en la memoria oficial.
   * *Tarea 3:* Asistencia a la reunión virtual de lanzamiento.

---

### **FASE 4: Coordinación Virtual, Netiqueta y Cierre Documental (SdA 2.6)**

*Objetivo: Planificar la reunión síncrona de lanzamiento en Google Calendar/Meet, redactar el protocolo de videollamadas y exportar los informes finales.*

#### **Paso 8: Convocatoria en Google Calendar y Google Meet**
1. Abre **Google Calendar** y programa la reunión: **`Reunión de Lanzamiento - [Nombre de tu Startup]`**.
2. Añade en la descripción el **orden del día** detallado de la sesión.
3. Haz clic en **Añadir videollamada de Google Meet**.
4. En el campo de invitados, añade a tus compañeros/as utilizando la etiqueta **`Equipo_Startup_UD2`**.

#### **Paso 9: Protocolo de Netiqueta Síncrona y Valoración de Herramientas**
Abre de nuevo tu documento **`Memoria_Fundacional_[Nombre de tu Startup]`** en Google Docs y añade al final estos dos apartados:
1. **Decálogo de Netiqueta en Google Meet (5 reglas):**
   * *Micrófono:* Silenciado al entrar a la sala.
   * *Turno de palabra:* Uso obligatorio de **Levantar la mano (✋)**.
   * *Cámara:* Encendida con encuadre correcto y actitud respetuosa.
   * *Chat:* Uso exclusivo para aportaciones o enlaces del proyecto.
   * *Puntualidad:* Conexión a la hora fijada y escucha activa.
2. **Valoración Competencial de la Suite Digital:** Redacta un párrafo (6-8 líneas) evaluando cómo la combinación de **PiskelApp + Gemini + Google Workspace** permite coordinar y lanzar una empresa sin costes de software y facilitando el trabajo colaborativo en la nube.

#### **Paso 10: Exportación de Documentos Finales**
1. En tu documento de Google Docs (**`Memoria_Fundacional_[Nombre de tu Startup]`**), ve a **`Archivo` ➔ `Descargar` ➔ `Documento PDF (.pdf)`**.
2. Guarda el archivo descargado (**`Memoria_Fundacional_[Nombre de tu Startup].pdf`**) dentro de la subcarpeta **`03_Entregables_Finales`** de tu Google Drive.

---

### **FASE 5: Empaquetado y Entrega Final en Moodle Centros (Archivo .ZIP)**

*Objetivo: Comprimir toda la estructura de archivos generada dentro de la carpeta CAGM y realizar la entrega oficial.*

1. **Comprobación de la estructura en Google Drive:**  
   Antes de descargar, accede a tu carpeta **`CAGM`** y entra en **`SDA_2_PROYECTO_STARTUP`**. Verifica que contiene exactamente estos archivos ordenados en sus 3 subcarpetas:
   * 📁 **`01_Documentos_Oficiales`**:
     * 📄 Documento de Google Docs: `Memoria_Fundacional_[Nombre de tu Startup]`
     * 🌐 Archivo web: `index.html` (generado por Gemini)
     * 📇 Archivo de agenda: `contactos_equipo.csv` (exportado de Contactos)
   * 📁 **`02_Recursos_Multimedia`**:
     * 🖼️ Logotipo animado: `logo_startup.gif` (exportado de PiskelApp)
     * 🖼️ Logotipo estático: `logo_startup.png` (exportado de PiskelApp)
   * 📁 **`03_Entregables_Finales`**:
     * 📕 Informe completo exportado: `Memoria_Fundacional_[Nombre de tu Startup].pdf`

2. **Descarga en archivo comprimido (.ZIP):**
   * En Google Drive, dentro de tu carpeta **`CAGM`**, haz clic derecho sobre la carpeta **`SDA_2_PROYECTO_STARTUP`**.
   * Selecciona la opción **Descargar**.
   * Google Drive comprimirá automáticamente toda la carpeta con sus 3 subcarpetas y todos los archivos en un único archivo comprimido:  
     **`SDA_2_PROYECTO_STARTUP.zip`**

3. **Subida a Moodle Centros:**
   * Accede a la plataforma **Moodle Centros**.
   * Entra en la tarea **`SdA 2 Final: Proyecto Integrador Startup`**.
   * Sube el archivo comprimido **`.zip`** descargado.

---

## **3. RÚBRICA DE EVALUACIÓN COMPETENCIAL (CE3 - CC)**

La calificación final de este proyecto integrador se calcula mediante la **media aritmética (escala 1 a 10)** de los 6 criterios oficiales de la Competencia Específica 3 (CC):

| Criterio de Evaluación | Insuficiente (1 - 4) | Suficiente (5 - 6) | Notable (7 - 8) | Sobresaliente (9 - 10) |
| :--- | :--- | :--- | :--- | :--- |
| **CC3.1.1**<br>Utilizar correctamente herramientas digitales comunes para compartir archivos e información en distintos formatos (Pixel Art, HTML, CSV, PDF, ZIP). | No organiza la carpeta en Drive, faltan archivos requeridos o no entrega el paquete comprimido `.zip`. | Crea la estructura básica en Drive, genera los archivos principales con ayuda y descarga el `.zip` con fallos menores. | Organiza la estructura de Drive con sus subcarpetas dentro de CAGM, incluye todos los formatos (`.gif`, `.html`, `.csv`, `.pdf`) y entrega el archivo `.zip` correctamente. | Demuestra un dominio profesional en la gestión de archivos: estructura impecable en Drive dentro de CAGM, integración perfecta de formatos y entrega pulcra en `.zip`. |
| **CC3.1.2**<br>Aplicar criterios de responsabilidad y respeto al compartir información, evitando datos sensibles. | Expone correos al no usar CCO, deja permisos de Drive en edición abierta o incluye datos sensibles no protegidos. | Usa CCO tras indicaciones, configura el enlace de Drive en modo Lector y redacta una justificación elemental sobre privacidad. | Aplica CCO para proteger direcciones, ajusta permisos de Drive en modo Lector y analiza con claridad la protección de datos en la memoria. | Demuestra una actitud ejemplar de seguridad digital, protegiendo comunicaciones con CCO, restringiendo accesos y justificando la LOPD. |
| **CC3.2.1**<br>Seleccionar y emplear diversas tecnologías digitales valorando su finalidad y facilidad de uso. | No justifica la combinación de herramientas empleadas ni reconoce la finalidad práctica de cada una. | Utiliza las herramientas propuestas y redacta una justificación sencilla con apoyo docente en la memoria. | Selecciona y combina PiskelApp, Gemini, Gmail, Contactos, Chat, Tasks, Drive, Calendar y Meet, justificando con coherencia su utilidad. | Evalúa con juicio crítico la integración de herramientas de diseño, IA y colaboración en la nube, destacando su accesibilidad y gratuidad. |
| **CC3.3.1**<br>Transmitir información personal o laboral adaptando el mensaje al canal y destinatario. | Redacta el correo sin tono formal, carece de firma corporativa, omite el asunto o no adjunta el logo corporativo. | Envía el e-mail formal incluyendo asunto, firma básica y archivo adjunto con indicaciones del profesorado. | Envía el e-mail formal con asunto claro, firma corporativa configurada, tono adecuado y el archivo `logo_startup.gif` adjunto. | Redacta una comunicación corporativa impecable, con tono altamente profesional, ortografía perfecta, firma completa y adjunto. |
| **CC3.4.1**<br>Participar activamente en entornos colaborativos gestionando canales, tareas y eventos. | No crea el Espacio en Chat, no asigna tareas en Tasks ni programa la reunión en Calendar con Meet. | Configura el Espacio en Chat, asigna tareas básicas y convoca el evento en Calendar con ayuda docente. | Organiza el Espacio en Chat con mensaje fijado, asigna 3 tareas con fechas/responsables y convoca la reunión en Calendar con Meet e invitados. | Lidera la gestión colaborativa con rigor: canal en Chat con tablón fijado, asignación estructurada de tareas y convocatoria síncrona en Meet. |
| **CC3.4.2**<br>Respetar las normas de comportamiento en entornos digitales síncronos (netiqueta). | No identifica las normas básicas de videollamadas o no incluye el decálogo en la memoria fundacional. | Enumera pautas básicas de comportamiento en Google Meet tras revisar las instrucciones de clase. | Redacta el decálogo de 5 normas de netiqueta síncrona argumentando la importancia del respeto en videollamadas. | Elabora una guía de convivencia y netiqueta síncrona de alto nivel, promoviendo el uso responsable de cámara, micro, mano y chat. |
