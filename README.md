# Web de Gestión de Preguntas y Respuestas para el CAP Inicial

Esta es una web diseñada para gestionar y crear preguntas y respuestas del CAP Inicial de **Mercancías y Viajeros**, utilizando las preguntas públicas publicadas por el **Ministerio de Transportes**.

## Características

### Preguntas Precargadas
- La web incluye preguntas actualizadas hasta el **08/02/2024**.

### Selección y Carga de Preguntas
- En la sección **"Seleccionar Preguntas"**, puedes:
  - Eliminar las preguntas precargadas.
  - Adjuntar nuevas preguntas en formato `.txt`, siguiendo el formato disponible en la sección "Otros Documentos" del Ministerio.
  - Cargar preguntas por temas en archivos separados, como un conjunto o mediante una carpeta completa.

#### Opciones Configurables:
- Generar un **PDF tipo examen** con las preguntas y las respuestas opcionalmente en la última página.
- Generar archivos **.txt separados** para preguntas y respuestas.
- Habilitar la opción para **desordenar las preguntas**.

### Configuración de Exámenes
- En la sección **"Examen"**, puedes configurar exámenes para **Mercancías**, **Viajeros** o **ambos**.

#### Detalles de los Exámenes:
- **Ambos:** Se generan dos exámenes:
  - 25 preguntas específicas para cada modalidad.
  - 75 preguntas generales comunes.
  - La web mostrará únicamente las 75 preguntas comunes.
- **Solo Mercancías o Viajeros:**
  - La web mostrará 100 preguntas específicas de la modalidad seleccionada.
- Las preguntas del examen se muestran en la parte inferior de la web:
  - Al hacer clic en una pregunta, se muestra su respuesta.
  - Al pulsar nuevamente, la respuesta se oculta.

### Búsqueda de Preguntas (Sección "Test")
- Busca preguntas específicas por:
  - **Código**.
  - **Palabras clave** presentes en las preguntas o respuestas.
- Selecciona el número total de preguntas desde un menú desplegable o escribiéndolo manualmente.

#### Creación de Exámenes Temáticos
- Si solo has cargado preguntas de ciertos temas, las búsquedas y exámenes se limitarán a esos ficheros.
- Es importante eliminar las preguntas precargadas si deseas trabajar únicamente con las nuevas preguntas cargadas.

## Uso
1. Accede a la web e inicia en la sección **"Seleccionar Preguntas"** para configurar tus preguntas.
2. Personaliza tus exámenes o tests en las secciones **"Examen"** y **"Test"** según tus necesidades.
3. Genera los archivos deseados (PDF o `.txt`) o utiliza la visualización interactiva en la web.

## Requisitos
- Las preguntas deben cargarse en formato `.txt` siguiendo el formato especificado por el Ministerio.

## Contribución
Si deseas contribuir a este proyecto o tienes sugerencias, no dudes en abrir un **issue** o enviar un **pull request**.

## Licencia
Este proyecto está bajo la licencia [licencia MIT](LICENSE).
