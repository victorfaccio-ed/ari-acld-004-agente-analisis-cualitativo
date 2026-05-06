# Ariadna (ARI-AClD-004) - Agente para el Análisis Cualitativo de Datos (AClD)

Ariadna es un agente de inteligencia artificial especializada en el Análisis Cualitativo de Datos (AClD), diseñada específicamente para investigadores en Ciencias Sociales, Humanidades y de la Conducta. A diferencia de las herramientas de procesamiento automático, Ariadna actúa como un "espejo hermenéutico", promoviendo la reflexividad y el pensamiento crítico del investigador a través del diálogo socrático y la codificación iterativa.

## 🎯 ¿Para qué sirve?

El propósito central de este proyecto es liberar al investigador de la carga cognitiva de la organización documental, permitiéndole enfocarse en la interpretación profunda. Ariadna asiste en:

1. Codificación Dialógica: Propuesta de códigos (inductivos, deductivos o híbridos) línea por línea.
2. Curaduría Digital: Establecimiento de protocolos de nomenclatura y logbooks para asegurar la trazabilidad.
3. Ética de Datos: Gestión de seudónimos en contextos latinoamericanos para proteger el anonimato.
4. Saturación Teórica: Identificación de patrones y construcción de categorías mediante memos analíticos.

## ⚙️ Configuración e Instalación

Ariadna no es una aplicación ejecutable independiente, sino un perfil de sistema (System Prompt) diseñado para funcionar en modelos de lenguaje avanzados (como GPT-4, Claude 3.5 o Gemini 2.0).

### Requisitos previos

Acceso a una interfaz de IA que permita instrucciones de sistema (Playground, Custom Instructions o API).

El archivo json contenido en este repositorio (que contiene la configuración de la versión ARI-AClD-004).

Pasos para la configuración

1. Copia el contenido del archivo json.
2. Pégalo en la sección de "Instrucciones de Sistema" o "System Prompt" de tu entorno de IA preferido.
3. Inicia una nueva sesión. Ariadna se presentará automáticamente y activará su protocolo de Onboarding.

## 🚀 Instrucciones de Uso

Para interactuar con Ariadna, se recomienda seguir el flujo de trabajo predefinido:

1. Inicio (Onboarding)

Al comenzar, Ariadna te preguntará sobre tu diseño metodológico (Nivel A y B) y tus materiales.

Ejemplo de entrada: "Hola Ariadna, quiero iniciar el análisis de 5 entrevistas sobre deserción escolar. Mi enfoque es fenomenológico."

2. Codificación (AClD)

Envía fragmentos de texto (máximo 3 párrafos por vez).

Ejemplo de entrada: "Aquí tienes el primer fragmento de la entrevista ENT-01: 'Siento que el papeleo me quita tiempo para enseñar'..."

3. Salida de Datos (Pseudónimos)

Cuando solicites un reporte, Ariadna verificará la ética de los datos.

Ejemplo de interacción:

Ariadna: "¿Deseas que aplique el protocolo de seudonimización para este Memo Analítico?"

Usuario: "Sí, por favor."

Resultado: "En el fragmento [ENT-01], Mateo (Docente, 45 años) expresa una tensión entre..."

## 🔬 Rigor y Reproducibilidad

Este proyecto integra las siguientes bases teóricas y guías de reporte:

Análisis Temático Reflexivo: Braun & Clarke (2022).

Thematic Analysis (Enfoques Híbridos): Xu & Zammit (2020), Lochmiller (2021).

Manual de Codificación: Saldaña (2020).

Sistematización de Experiencias: Oscar Jara.

Para asegurar la reproducibilidad de tu análisis, se recomienda guardar el Logbook generado por Ariadna y los Memos Analíticos en una carpeta de materiales empíricos junto con la versión del JSON utilizada.

## 🤝 Comunidad y Contribución

Si encuentras un error metodológico, deseas sugerir una nueva técnica de análisis o quieres contribuir con un módulo especializado:

Reporte de Errores: Abre un Issue detallando el problema.

Mejoras: Realiza un Fork del proyecto y envía un Pull Request.

Consultas Académicas: Contacta a la persona autora para colaboraciones en investigación.

## 👤 Autoría y Atribución

Este proyecto ha sido conceptualizado y desarrollado por J. Víctor Faccio Lucero

Cómo citar este trabajo:

Faccio Lucero, J. V. (2024). Ariadna (ARI-AClD-004): Agente para el Análisis Cualitativo de Datos (AClD) [Agente de IA]. Versión 2.0. Disponible en: [Enlace al repositorio].

## 📄 Licencia

Este proyecto está bajo la licencia GNU General Public License v3.0.

Eres libre de copiar, modificar y distribuir el software, siempre y cuando los trabajos derivados se distribuyan bajo esta misma licencia y se mantenga la atribución a la persona autora original. Consulta el archivo LICENSE para más detalles.

Este README fue generado con un enfoque en la integridad científica y la eficiencia técnica.
