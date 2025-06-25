Automatización de Mantenimiento
Este proyecto es una automatización desarrollada en n8n diseñada para gestionar y mantener datos provenientes de sitios web mediante webhooks, integraciones y herramientas de inteligencia artificial.
🎯 Objetivo
Simplificar y automatizar el proceso de consulta, clasificación y almacenamiento de información recibida desde distintos servicios web, optimizando tareas repetitivas y centralizando resultados.
⚙️ Flujo del workflow
El flujo completo se compone de los siguientes pasos:
- Inicio (Test Workflow): Punto de activación del proceso.
- Dominio Personalizado: Se valida o introduce un dominio como entrada.
- Consulta a BD (SELECT): Extrae datos clave de la base de datos.
- HTTP POST: Envía datos a un endpoint externo.
- HTTP GET: Recupera información de un servicio externo.
- Código Personalizado: Se ejecuta una función para procesar o transformar datos.
- Inserción en BD (INSERT): Guarda información nueva procesada.
- Clasificador: Evalúa los datos y los categoriza según criterios definidos.
- Condicional: Permite bifurcar el flujo si se cumplen ciertas condiciones.
- Organizador: Reordena o estructura los datos para el siguiente paso.
- Agente de IA: Utiliza modelos con capacidades de memoria y análisis para procesar lenguaje natural.
- DeepSeek Chat: Motor LLM que permite generar respuestas o análisis más ricos.
- HTML Generator: Construye una plantilla HTML con los resultados finales.
🧠 Tecnologías utilizadas
- n8n para la orquestación y automatización del workflow.
- Bases de datos SQL para manejo estructurado de datos.
- HTTP APIs para conexión con servicios externos.
- Código personalizado (JavaScript) para lógica avanzada.
- Modelos de lenguaje (LLMs) como agentes de IA para procesamiento de texto.
- HTML/CSS para generar plantillas visuales.
🧪 Estado del proyecto
Actualmente en fase de pruebas, este workflow está en constante mejora para ofrecer resultados precisos, rápidos y confiables
