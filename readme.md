# Workflows de Automatización con IA para n8n

Este repositorio contiene una colección de flujos de trabajo (workflows) en formato JSON, diseñados para ser importados en la plataforma de automatización n8n. Cada archivo implementa un agente de Inteligencia Artificial para realizar tareas específicas y resolver distintos casos de uso.

## Descripción de los Proyectos

A continuación se detallan los proyectos y los archivos que los componen:

* ### 00. Asistente de Portafolio (Cris-Bot)
    Acceder desde tuprofeanalitica.com/chatbot un asistente conversacional completo que he desarrollado y desplegado en un entorno de **producción**, accesible públicamente. El chatbot, llamado **Cris-Bot**, integra frontend, backend y un robusto flujo de automatización que permite a los visitantes de mi web solicitar mi portafolio directamente por correo electrónico. La solución gestiona la conversación de forma autónoma, utiliza **memoria** para mantener el contexto y ejecuta **tools** específicas para el envío de la información, demostrando mi capacidad para llevar un proyecto de IA de la concepción al despliegue.
    * `intenziaprueba00.json`
  Se usa la api de gemini y la configuracion de STM de google para el gmail  


* ### 02. Asistente de Belleza
    Un asistente inteligente que ofrece recomendaciones personalizadas de productos y estilos, consultando el perfil del usuario y una base de datos de productos.
    * `AssistantBeauty02.json`
    * `AssistantBeautytool02.json`

* ### 03. Asistente de Recetas Saludables
    Un asistente de cocina que sugiere recetas a partir de una lista de ingredientes proporcionada por el usuario, buscando coincidencias en una base de datos.
    * `Recetas_Saludables003.json`
    * `Receta_Tools_03.json`

* ### 04. Entrenador Personal
    Una solución que genera rutinas de ejercicios personalizadas. El agente de IA procesa la solicitud del usuario y consulta una base de datos de ejercicios para crear un plan.
    * `Personal_trainer04.json`
    * `db_004.json`

* ### 05. Resumen de Opiniones con IA
    Una herramienta que recopila y analiza grandes volúmenes de reseñas de usuarios para generar un resumen conciso y balanceado, facilitando la rápida comprensión del feedback.
    * `Smart05.json`
    * `Smart05tool05.json`

* ### 06. Planificador de Recetas
    Un agente diseñado para ayudar a los usuarios a planificar sus comidas semanales. El sistema puede sugerir recetas, organizarlas en un calendario y generar listas de compras.
    * `planificadorReceta06.json`
    * `planificadorRecetatool06.json`

* ### 07. Análisis de Sentimiento
    Un módulo que procesa y analiza el feedback de texto libre (ej. encuestas de empleados) para determinar el sentimiento general y generar informes con los hallazgos clave.
    * `Sentiment-analysis07.json`

* ### 08. Herramienta de Brainstorming
    Una herramienta creativa que asiste en la generación de ideas. La IA crea conceptos detallados y "prompts" para ser utilizados en otras plataformas (ej. generadores de imágenes).
    * `brainstorming08.json`
