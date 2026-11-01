# **SdA 2 Final: Proyecto Integrador "Lanzamiento y Gestión Digital de una Startup"**

---

## **1. DESCRIPCIÓN GENERAL Y MISIÓN DEL PROYECTO**

En este proyecto integrador final de la **Unidad Didáctica 2 (Comunicación y Colaboración Digital - CC)**, asumirás el rol de emprendedor/a digital y simularás el lanzamiento completo de tu propia empresa o proyecto de estudio (**Startup**).

A lo largo de esta actividad, aplicarás de forma práctica e integrada todas las competencias entrenadas en el tema (**SdA 2.1 a SdA 2.6**), utilizando el diseño en píxeles con **PiskelApp**, la generación web con la Inteligencia Artificial **(Gemini, ChatGPT, etc)** y el ecosistema colaborativo de **Google Workspace**.

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
   **`PROYECTO_STARTUP_[Nombre de tu Startup]`**

3. **Creación de las 3 Subcarpetas de Trabajo:**  
   Entra dentro de la carpeta **`PROYECTO_STARTUP_[Nombre de tu Startup]`** y genera estas tres subcarpetas:
   * **`01_Documentos_Oficiales`** (para guardar los textos, propuestas, la agenda `.csv` y el código web `index.html`).
   * **`02_Recursos_Multimedia`** (para guardar los archivos de imagen y logotipos `.gif` y `.png`).
   * **`03_Entregables_Finales`** (para guardar los informes y exportaciones finales en `.pdf`).

4. **Configuración de Permisos Seguros:**  
   Haz clic derecho sobre tu carpeta **`PROYECTO_STARTUP_[Nombre de tu Startup]`** ➔ **Compartir** ➔ **Obtener enlace**.  
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

#### **Paso 2: Generación Directa del Fichero `index.html` con IA (SdA 2.1 + IA)**
1. Abre **(Gemini, ChatGPT, etc)** (`gemini.google.com`).
2. Haz clic en el botón de adjuntar archivos (`+` o clip) y sube tu **`logo_startup.png`** (o `.gif`).
3. Escribe el siguiente prompt a la IA:  
   `"Actúa como un diseñador web experto. Te adjunto el logotipo de nuestra empresa. Genera directamente el archivo index.html completo y descargable para la landing page promocional de mi Startup. La empresa se llama [Nombre de tu Startup], nos dedicamos a [Actividad] y nuestro color corporativo principal es RGB: R: ___, G: ___, B: ___. Incluye un encabezado con el logo, presentación, 3 servicios destacados y botón de contacto."`
4. **Descarga y comprobación del archivo:**
   * Descarga el archivo **`index.html`** generado por Gemini directamente a tu ordenador.
   * Haz doble clic sobre **`index.html`** para abrirlo en **Google Chrome** y comprobar que tu web funciona correctamente en el navegador.
   * *(Visualiza):* Haz clic derecho sobre **`index.html`** ➔ **Abrir con** ➔ **Bloc de Notas** si quieres inspeccionar el código HTML y CSS generado.
5. **Guardado en Drive:** Sube el archivo **`index.html`** a la subcarpeta **`01_Documentos_Oficiales`** de tu carpeta del proyecto.

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
   Antes de descargar, accede a tu carpeta **`CAGM`** y entra en **`01_PROYECTO_STARTUP_[Tu Nombre y Apellidos]`**. Verifica que contiene exactamente estos archivos ordenados en sus 3 subcarpetas:
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
   * En Google Drive, dentro de tu carpeta **`CAGM`**, haz clic derecho sobre la carpeta **`01_PROYECTO_STARTUP_[Tu Nombre y Apellidos]`**.
   * Selecciona la opción **Descargar**.
   * Google Drive comprimirá automáticamente toda la carpeta con sus 3 subcarpetas y todos los archivos en un único archivo comprimido:  
     **`01_PROYECTO_STARTUP_[Tu Nombre y Apellidos].zip`**

3. **Subida a Moodle Centros:**
   * Accede a la plataforma **Moodle Centros**.
   * Entra en la tarea **`SdA 2 Final: Proyecto Integrador Startup`**.
   * Sube el archivo comprimido **`.zip`** descargado.

---

## **3. RÚBRICA DE EVALUACIÓN COMPETENCIAL DETALLADA**

La evaluación de este proyecto integrador se realiza mediante una rúbrica formativa y competencial que valora tanto los criterios oficiales de la **Competencia Específica 3 (Comunicación y Colaboración Digital - CC)** como las evidencias curriculares asociadas a la **Creación de Contenidos Digitales (CCD)** y la **Organización de la Información (IAD)**.

La calificación final se obtiene mediante la **media aritmética (escala de 1 a 10)** de los siguientes indicadores de logro:

| Ámbito / Criterio de Evaluación | Insuficiente (1 - 4) | Suficiente (5 - 6) | Notable (7 - 8) | Sobresaliente (9 - 10) |
| :--- | :--- | :--- | :--- | :--- |
| **1. Prototipado Web y Generación de `index.html` con IA**<br>*(CCD3.1.2 / CC3.1.1)*<br>Generación directa del archivo `index.html` con Gemini, integración de la identidad corporativa y visualización en el navegador. | No genera el archivo `index.html` o no utiliza la IA; el archivo web no abre en Chrome o no guarda relación con la temática de la Startup. | Genera el código HTML con Gemini pero requiere ayuda docente para descargar el archivo `index.html`; la página abre en Chrome con diseño básico o textos genéricos. | Genera y descarga correctamente el archivo `index.html` mediante Gemini, integrando el nombre de la empresa, servicios y abriéndolo en Chrome con visualización funcional. | Domina la interacción con Gemini adjuntando logo y borrador; obtiene directamente el archivo `index.html`, que funciona a la perfección en Chrome reflejando con exactitud la identidad, servicios y colores de la Startup. |
| **2. Identidad Gráfica, Animación y Codificación RGB**<br>*(CCD3.1.1 / CC3.1.1)*<br>Diseño de logotipo en PiskelApp (32x32 px), animación en 2 fotogramas, registro de paleta RGB y exportación dual (`.gif` y `.png`). | No diseña el logotipo en PiskelApp o no logra crear la animación; no exporta los formatos requeridos ni identifica la paleta RGB de su marca. | Dibuja un icono estático básico con ayuda; genera el segundo fotograma tras indicaciones y exporta al menos uno de los dos formatos (`.gif` o `.png`). | Diseña un logotipo original en 32x32 px con animación fluida en 2 fotogramas; identifica sus valores RGB y exporta correctamente `logo_startup.gif` y `logo_startup.png`. | Crea una identidad gráfica excelente en PiskelApp con animación expresiva en 2 fotogramas; exporta con rigor técnico ambos formatos y documenta con precisión su paleta de color RGB para uso web. |
| **3. Estructura de la Nube en Drive y Empaquetado `.zip`**<br>*(IAD3.3.2 / CC3.1.1)*<br>Organización jerárquica dentro de la carpeta `CAGM`, distribución limpia de archivos y compresión final en `.zip`. | No ubica el proyecto dentro de `CAGM`, desorganiza las 3 subcarpetas, faltan archivos clave o no entrega el paquete comprimido `.zip` en Moodle. | Crea la carpeta dentro de `CAGM` con ayuda; distribuye los archivos con pequeños errores de ubicación y descarga el paquete `.zip` con dificultad. | Organiza con orden la carpeta principal dentro de `CAGM` con sus 3 subcarpetas (`01_Documentos`, `02_Multimedia`, `03_Entregables`), clasifica sus ficheros y entrega el `.zip` correctamente. | Demuestra una gestión documental impecable: estructura rigurosa en Drive dentro de `CAGM`, todos los formatos en su subcarpeta exacta y entrega pulcra del archivo `.zip` en Moodle Centros. |
| **4. Seguridad Digital, Permisos de Drive y Privacidad (LOPD)**<br>*(CC3.1.2)*<br>Configuración de permisos en modo Lector (evitando riesgos de edición) y aplicación estricta del campo CCO en envíos masivos. | Expone correos de terceros al no utilizar el campo CCO, deja la carpeta de Drive en modo Editor abierto o incluye datos confidenciales no protegidos. | Aplica el campo CCO tras indicaciones del profesor; configura el enlace de Drive en modo Lector y redacta una justificación elemental sobre protección de datos. | Protege adecuadamente las direcciones mediante CCO, ajusta los accesos de Drive en modo Lector y redacta con claridad el análisis sobre riesgos y datos sensibles. | Actitud y dominio ejemplar en seguridad y privacidad: protección rigurosa con CCO, configuración estricta de permisos en Drive y justificación brillante de la LOPD en la memoria fundacional. |
| **5. Comunicación Formal en Gmail y Exportación de Agenda**<br>*(CC3.3.1 / IAD3.3.2)*<br>Redacción de correo corporativo con firma institucional, margen de 30s antierrores, adjunto `.gif` y exportación de contactos a `.csv`. | Redacta el correo sin tono formal ni estructura, carece de firma corporativa, no configura el margen de 30s o no exporta la agenda `contactos_equipo.csv`. | Envía el correo con estructura básica y firma sencilla; exporta la etiqueta de contactos de Google a formato CSV con apoyo del profesorado. | Redacta una comunicación corporativa formal con asunto, saludo, cuerpo, despedida, firma de CEO/Fundador y adjunto; exporta con éxito el archivo `contactos_equipo.csv`. | Comunicación profesional sobresaliente: redacción formal impecable sin faltas, salvavidas de 30s activo, adjunto funcional y exportación rigurosa de la agenda corporativa a `.csv`. |
| **6. Colaboración en Equipo: Google Chat y Asignación de Tareas**<br>*(CC3.4.1)*<br>Creación de canal interno en Chat, fijado de mensaje en el tablón (*pin*) y asignación de 3 tareas con plazos y responsables. | No crea el Espacio de trabajo en Chat, no invita a compañeros de equipo o no asigna tareas operativas con plazos. | Configura el Espacio en Chat e invita a compañeros; publica el mensaje de bienvenida y asigna tareas básicas con fechas aproximadas. | Organiza el canal de Chat con miembros del aula, fija el mensaje de normas en el tablón (*pin*) y asigna 3 tareas con responsables y fechas límite bien definidas. | Liderazgo colaborativo excelente: dinamización real del canal de Chat con mensaje anclado en el tablón de anuncios y asignación estructurada de tareas y recursos con fechas y horas límite. |
| **7. Videollamada en Google Meet, Netiqueta y Evaluación de la Suite**<br>*(CC3.4.2 / CC3.2.1)*<br>Convocatoria de reunión en Google Calendar con enlace a Meet, redacción del decálogo de netiqueta síncrona y valoración crítica de herramientas. | No programa la videollamada en Calendar, no incluye invitados por etiqueta, omite el decálogo de netiqueta o no valora el ecosistema de herramientas. | Programa el evento con enlace de Meet con ayuda; redacta pautas básicas de netiqueta y aporta una reflexión breve sobre el uso de Google Workspace. | Convoca la reunión en Calendar invitando a la etiqueta del equipo, redacta un decálogo de 5 normas de netiqueta síncrona y analiza con coherencia las ventajas de la suite. | Planificación impecable en Calendar/Meet con orden del día e invitados corporativos; decálogo de netiqueta de alto nivel y valoración crítica sobresaliente de la suite Google Workspace + Gemini + PiskelApp. |
