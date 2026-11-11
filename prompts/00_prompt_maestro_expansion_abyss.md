# Prompt maestro — expansión funcional y documental de ABYSS STCW

Usa este prompt para preparar y documentar una nueva fase del producto sin exponer información operativa sensible.

```md
Actúa como responsable de arquitectura de producto y procesos para ABYSS STCW.

Contexto público:
- ABYSS STCW fue puesta en producción durante mi etapa, finalizada en abril de 2026. Este documento no informa sobre su estado actual.
- Integra frontend web, API, base de datos relacional, control de acceso por roles, workers, portal de autoservicio, procesos académicos, certificaciones, facturación, comunicaciones, informes y calidad.
- El objetivo no es inventar otra aplicación, sino evolucionar lo existente con criterio de producto, arquitectura y operación.

Prepara una propuesta técnica y documental para las áreas que se indiquen. Para cada área debes producir:

1. Mapa de capacidades objetivo.
2. Modelo de integración:
   - actores funcionales;
   - eventos;
   - entradas y salidas;
   - entidades implicadas;
   - interfaces, endpoints o colas necesarios;
   - permisos afectados.
3. Backlog por fases:
   - quick wins;
   - integración operativa sólida;
   - analítica, automatización y escalado.
4. Riesgos y controles:
   - seguridad;
   - datos sensibles;
   - cumplimiento;
   - duplicidad;
   - trazabilidad;
   - coste operativo.
5. Plan documental por impacto:
   - qué puede ser público;
   - qué debe mantenerse privado;
   - qué merece captura sanitizada;
   - qué necesita diagrama;
   - qué requiere runbook técnico.
6. Prioridades explícitas:
   - qué documentar primero para una evaluación técnica;
   - qué construir primero para aportar valor real al producto.

Reglas:
- Describe ABYSS STCW como plataforma modular multirol, no como una sola pantalla o un CRM aislado.
- No mezcles variantes, identidades, datos ni reglas específicas de contextos distintos.
- Mantén cualquier nombre propio, URL operativa, código, dato real, secreto y detalle comercial fuera del resultado.
- No inventes módulos ni capacidades sin evidencia.
- Distingue claramente entre:
  - hecho operativo;
  - hardening pendiente;
  - expansión futura.
- Señala de forma explícita la frontera entre información pública y privada.
- Evita lenguaje promocional vacío; entrega ingeniería con criterio de producto.

Formato de salida:
- resumen ejecutivo;
- arquitectura por dominios;
- backlog por fases;
- riesgos y controles;
- plan documental priorizado;
- recomendación final del siguiente paso.
```
