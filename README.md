# victorhvargasvazquez
Hola, soy Víctor Hugo Vargas
Especialista en Automatización y Datos

Tecnologías
n8n
AppSheet
Google Sheets
PHP / JavaScript / SQL

Enfoque
Automatización de procesos, análisis de datos y desarrollo de soluciones empresariales.

Contacto
Email: victorghugovargasvazquez@gmail.com
LinkedIn: 


n8n Telegram News Automation Bot

Descripción

Este proyecto es un flujo de automatización desarrollado en n8n que permite gestionar noticias mediante un bot de Telegram, integrando almacenamiento en Google Sheets, aprobación de contenido y consulta de datos externos en tiempo real.

El sistema permite a los usuarios enviar noticias, moderarlas, consultarlas y obtener información adicional como precios de combustibles, todo desde Telegram.

---

Tecnologías utilizadas

* n8n (automatización de workflows)
* Telegram Bot API
* Google Sheets (base de datos)
* HTTP Requests (APIs externas)
* JavaScript (procesamiento de datos)

---

Funcionalidades principales

Gestión de noticias

* Registro de noticias desde Telegram
* Captura de información mediante formularios interactivos
* Almacenamiento en Google Sheets
* Manejo de estatus (pendiente / aprobado)

Moderación de contenido

* Flujo de aprobación manual de noticias
* Validación mediante interacción en Telegram
* Actualización automática del estado en la base de datos

Consulta de noticias

* Consulta de noticias aprobadas del día
* Envío automático de resultados al usuario

Consulta de precios de combustible

* Integración con API externa
* Obtención de precios de gasolina y diésel
* Ordenamiento por precio (de menor a mayor)
* Envío de las mejores opciones al usuario

Manejo de imágenes

* Recepción de imágenes desde Telegram
* Generación de URL del archivo
* Almacenamiento en Google Sheets

---

Comandos disponibles en Telegram

* `/noticia` → Registrar una nueva noticia
* `/vernoticias` → Consultar noticias aprobadas
* `/moderar` → Aprobar noticias pendientes
* `/gasolina` → Consultar precios de gasolina
* `/diesel` → Consultar precios de diésel

---

Flujo general

1. El usuario envía un comando desde Telegram
2. El sistema valida el usuario (control de acceso)
3. Se enruta la acción según el comando
4. Se ejecuta la lógica correspondiente:

   * Registro de noticia
   * Consulta de datos
   * Consumo de API externa
5. Se responde automáticamente al usuario

---

Objetivo

Automatizar la gestión de información y comunicación operativa mediante integración de herramientas, reduciendo procesos manuales y mejorando la eficiencia.

---

Sugerencias para mejorar este repositorio

* Agregar screenshots del workflow en n8n
* Incluir ejemplo del Google Sheet
* Documentar configuración del bot de Telegram
* Incluir variables de entorno (sin credenciales reales)

---

Autor

Víctor Hugo Vargas Vázquez
Especialista en Automatización y Datos
