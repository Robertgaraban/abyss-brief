# Evolución de plataforma — estado público

## Propósito

Este documento explica cómo ABYSS STCW evoluciona desde un sistema operativo amplio hacia una base más configurable y reutilizable, sin presentar como terminadas capacidades que todavía están en desarrollo.

La plataforma fue puesta **en producción durante mi etapa, finalizada en abril de 2026**. La generalización de configuración se documentó de forma incremental sobre ese núcleo. Esta ficha no informa sobre el estado actual del sistema.

## Capacidades verificables

### Configuración separada del núcleo

Existe una base de resolución de configuración para separar identidad, comportamiento por contexto y valores de compatibilidad del código común. Este trabajo permite reducir dependencias rígidas sin alterar el funcionamiento actual.

### Ciclo de vida unificado

El modelo conecta eventos y estados de distintas áreas, entre ellas:

- captación;
- comunicaciones;
- matrícula;
- pagos;
- certificaciones.

Esto permite revisar el proceso como una secuencia coherente y no como módulos desconectados.

### Analítica de calidad persistente

La capa de calidad incorpora persistencia de indicadores, materialización programada y consultas orientadas a evolución histórica. El objetivo es convertir evidencia operativa en información analizable y trazable.

### Planificación técnica estructurada

La evolución se documenta por dominios, fases, riesgos, límites de publicación y criterios de salida. El [prompt maestro sanitizado](../prompts/00_prompt_maestro_expansion_abyss.md) muestra este método sin exponer información sensible.

## Lo que este brief no afirma

- no afirma que toda la plataforma esté generalizada para cualquier contexto;
- no afirma que exista aislamiento lógico completo dentro de un único runtime;
- no afirma que todas las reglas locales o regulatorias estén abstraídas;
- no presenta planes futuros como capacidades operativas actuales;
- no identifica nombres propios, URL, infraestructura ni detalles comerciales.

## Lectura correcta del estado

La afirmación pública defendible es:

> ABYSS STCW fue puesta en producción durante mi etapa, finalizada en abril de 2026, y documentó una evolución hacia mayor configuración, reutilización y analítica. Esta ficha no afirma cuál es su estado actual.

## Criterios que gobiernan la evolución

- preservar el comportamiento existente mientras se extrae configuración;
- evitar copias permanentes del núcleo;
- aislar datos, secretos, almacenamiento y procesos cuando corresponda;
- distinguir siempre entre hecho operativo, hardening pendiente y expansión futura;
- mantener los detalles operativos fuera de la documentación pública.

## Ruta de revisión

1. [Brief principal](../README.md)
2. [Arquitectura pública](./architecture.md)
3. [Prompt maestro sanitizado](../prompts/00_prompt_maestro_expansion_abyss.md)
