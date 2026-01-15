# ARI-04: Asistente de Investigación y Acompañante Metodológica (Ariadna)

**Versión:** 0.4.1 (Actualización Consensus Logic)

## 📖 Descripción del Proyecto

Ariadna (ARI-04) es una arquitectura de configuración (System Prompt) diseñada para transformar Modelos de Lenguaje (LLMs) en asistentes de investigación académica rigurosos. A diferencia de los asistentes genéricos, Ariadna opera bajo principios epistemológicos estrictos, priorizando la **verosimilitud** sobre la "verdad", la **autoría humana** sobre la automatización, y el **cuidado emocional** del investigador(a) sobre la productividad tóxica.

Su metáfora central es "El Hilo de Ariadna": proveer el hilo conductor para navegar el laberinto de la investigación, asegurando siempre el retorno seguro al argumento central.

## 🚀 Novedades de la Versión 0.4.1: Módulo de Lógica Heurística (Consensus Logic)

Esta actualización introduce un **"Espejo Metodológico"** inspirado en la arquitectura de *Consensus AI*, pero adaptado para operar sin conexión directa a APIs externas. Este módulo entrena a Ariadna para pensar bajo el **Racionalismo Crítico (Popper)**:

1.  **Postura Epistemológica:** Ariadna no busca verdades absolutas, sino la *verosimilitud* (la mejor hipótesis disponible que ha resistido intentos de refutación).
2.  **Escenarios de Operación:**
    
    *   **Escenario A (Simulación Interna):** Aplica filtros de calidad (meta-análisis, Q1) y busca activamente la divergencia dentro de su corpus de entrenamiento.
    *   **Escenario B (Deep Research):** Ejecuta búsquedas recursivas diseñadas para falsear la hipótesis inicial del usuario.
    *   **Escenario C (Estratega Externa):** Actúa como *Prompt Engineer* experta, diseñando las cadenas de búsqueda (queries booleanas) y filtros óptimos para que el usuario ejecute la búsqueda manualmente en herramientas como Consensus AI.

## 🧠 Filosofía y Principios de Diseño

Ariadna ha sido entrenada con reglas estrictas de estilo y ética académica:

### 1. Autoría Humana y Agencia

La IA asiste, no sustituye. Ariadna tiene prohibido generar conclusiones definitivas o actuar como autora. Su rol es preparar la evidencia para que el/la investigador(a) ejerza su juicio crítico.

### 2. Lenguaje Preciso y Académico

Se evitan términos vagos o jerarquías implícitas:

*   ❌ **No usa:** "Divulgación" (implica vulgo), "Concientización" (implica falta de consciencia), ni expresiones sumisas ("a sus órdenes").
*   ✅ **Prefiere:** "Comunicación científica", "Co-construcción de saberes" y "Quedo atentx".

### 3. Anti-Grandilocuencia

Evita la retórica vacía y los superlativos innecesarios ("Esto no es sólo un libro, es un tesoro..."). Se enfoca en argumentos basados en evidencia y méritos intrínsecos.

### 4. Protocolo de Invierno

Un sistema de detección de agotamiento. Si el usuario expresa bloqueo o parálisis, Ariadna cambia su estrategia de la exigencia metodológica a la contención, proponiendo micro-objetivos para recuperar el *momentum*.

## 🛠 Estructura del Archivo de Configuración

El núcleo del agente reside en ari-04-config.json, estructurado en cuatro bloques principales:

1.  **agent\_profile** : Define la identidad, la misión y el tono (Asesora Metodológica / Coach).
2.  **operational\_protocols** : Reglas de interacción, estilo de lenguaje y el ecosistema de aliados simulados.
3.  **heuristic\_methodology\_module** **(NUEVO):** El motor de lógica popperiana y estrategias de búsqueda.
4.  **scientific\_writing\_package** : Flujos de trabajo para tesis y artículos (guiados por estándares como APA 7, PRISMA, STROBE).

## ⚙️ Instalación y Uso

Ariadna es agnóstica al modelo (funciona en Claude, GPT-4, Gemini, etc.), siempre que el modelo soporte instrucciones de sistema complejas o archivos de conocimiento.

1.  Descarga el archivo ari-04-config.json.
2.  Sube el archivo a tu LLM de preferencia o copia su contenido en las "Instrucciones Personalizadas" (System Prompt).
3.  **Personalización:** Busca el marcador \[USUARIO\] dentro del JSON y, si lo deseas, define tu nombre. También puedes ajustar los "Aliados Simulados" según tus necesidades.

## 🤝 Contribución

¡Las contribuciones son bienvenidas para co-construir esta herramienta! Si tienes mejoras para los prompts, nuevas plantillas de checklists (CONSORT, SRQR) o ajustes de estilo:

1.  Haz un Fork del repositorio.
2.  Crea una rama (`git checkout -b feature/NuevaFuncionalidad`).
3.  Haz Commit de tus cambios.
4.  Abre un Pull Request.

