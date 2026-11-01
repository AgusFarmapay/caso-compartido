---
status: framed
segment: Team Leads y mandos medios que conducen reuniones de trabajo de más de cinco participantes, en cuentas de 100 licencias o más
personas: tomas-ferreyra, mariela-quiroga, lucia-benitez, ricardo-salinas, graciela-ortiz
---

# Opportunity: Trabajo fragmentado en reuniones

En reuniones de más de cinco participantes, cuando hay que trabajar sobre un mismo material, quienes conducen mandan a la gente a herramientas externas, y eso dispersa la atención y alarga la reunión. Por qué ahora: sin disparador identificado; la urgencia todavía no está justificada.

## Segment and personas

- Tomás Ferreyra (primary) — suffers it: salta entre Teams, Jira y Miro, y parte del grupo se desconecta.
- Mariela Quiroga (primary) — suffers it, en una variante: no manda a la gente a otras herramientas, pero 15 personas solo miran una planilla compartida.
- Lucía Benítez (secondary) — suffers it como participante: pierde el hilo, aunque no decide cómo se trabaja en la reunión.
- Ricardo Salinas (tertiary) — does not suffer it; responde la creencia de viabilidad porque decide si se paga.
- Graciela Ortiz (negative) — does not suffer it; sus reuniones son breves y de menos de cinco personas.
- Missing: alguien que conduzca sesiones de trabajo en un área no técnica (marketing, consultoría o recursos humanos) con Google Docs, Notion o Mural.

## Signals

| Signal | Provenance | Source |
|---|---|---|
| A favor: enlace externo compartido en el 29% de las reuniones de más de cinco participantes (no prueba que se use durante la reunión ni que moleste) | unverified | product/overview.md, cifra del brief |
| A favor: 19% de los comentarios negativos es sobre colaboración durante la reunión (tercera queja, detrás de audio/video y de "demasiadas reuniones") | unverified | product/overview.md, cifra del brief |
| Contexto: 41% de las reuniones tiene más de 8 participantes y 23% supera la hora | unverified | product/overview.md, cifra del brief |
| A favor, débil: "el equipo ya usa otras herramientas" entre los motivos de baja (no dice cuáles ni si son para reuniones) | unverified | product/overview.md, dato del brief |
| A favor, solo hipótesis: Tomás y Mariela describen esta fricción | synthetic | product/personas/ |
| En contra o ambiguo: Whiteboard 5%, notas 8%, salas para grupos pequeños 9%; ya hay herramientas integradas y casi no se usan | unverified | product/overview.md, cifra del brief |
| En contra: "pagamos por funciones que no usamos" es el primer motivo de baja; sumar funciones podría agravarlo | unverified | product/overview.md, dato del brief |

## Business outcome

Principal: aumentar las subidas de plan de Premium a Max. Control: que no aumenten las bajas de plan ni las no renovaciones. El 2,4% de subidas de plan incluye todos los planes; falta el dato específico de Premium a Max.

## Constraints

- El despliegue lo controla IT: los empleados reciben la herramienta instalada.
- Licencia por usuario, con renovación anual por cuenta. El salto de Premium a Max cuesta USD 8 por usuario por mes.
- Los archivos compartidos viven en SharePoint.
- Sin restricciones conocidas de presupuesto, fechas o compliance.

## Beliefs

Registradas en product/overview.md.

- [opportunity: trabajo-fragmentado-reuniones] [value] La mayoría de los Team Leads y mandos medios del segmento conduce al menos una reunión por semana en la que trabajar con material en herramientas externas dispersa al grupo o alarga la reunión, y ya intentó hacer algo para evitarlo.
- [opportunity: trabajo-fragmentado-reuniones] [viability] Si este problema se resolviera, IT aprobaría pagar USD 8 por usuario por mes para pasar de Premium a Max en una parte significativa de las cuentas afectadas de 100 licencias o más.
- [product] [value] Los enlaces externos se comparten porque Teams no resuelve la colaboración durante la reunión; quienes conducen preferirían hacerla dentro de Teams antes que seguir usando Miro, Notion o Jira.
- [product] [viability] Las cuentas en Premium no suben a Max porque IT, que decide la compra, no ve valor en capacidades de reuniones que aprovechan sobre todo Team Leads y mandos medios; los USD 8 no son la barrera principal. En tensión con la viabilidad de esta oportunidad: si es cierta, ni una buena solución generaría subidas, salvo que cambie la percepción de IT.

## Research agenda

Sin fechas definidas: los plazos están ordenados por secuencia y falta asignarles fechas.

| Belief | Instrument | Decision it unlocks | By when |
|---|---|---|---|
| [value] de la oportunidad | Datos del producto: enlaces abiertos durante la reunión, duración con y sin enlace, desglose por tamaño de cuenta | Mantener o corregir el segmento, y seguir o descartar la oportunidad si no hay patrón | Paso 1 |
| [viability] de la oportunidad y [product] [viability] | Datos internos: subidas de Premium a Max por tamaño de cuenta | Confirmar si la subida a Max es un resultado realista | Paso 1 |
| [product] [value] sobre enlaces externos | /research-market: cómo resuelve el mercado la colaboración durante reuniones y si se paga por ella | Definir qué queda por preguntar a usuarios reales | Paso 2 |
| [value] de la oportunidad | /design-survey a quienes conducen reuniones del segmento: frecuencia, costo e intentos de evitarlo | Definir si el problema es lo bastante frecuente y grave para seguir | Paso 3 |
| [product] [value] sobre enlaces externos | /design-interview con quienes respondieron la encuesta, priorizando respuestas que contradigan la creencia | Definir si la respuesta pasa por lo integrado o por conectar lo que ya usan | Paso 4 |
| [viability] de la oportunidad y [product] [viability] | /design-interview con responsables de IT de cuentas en Premium | Mantener la subida a Max como resultado, o cambiar el resultado o abandonar la oportunidad | Paso 4, antes de /explore-solutions |

## Candidate ideas (not evaluated)

- Herramientas colaborativas integradas (cómo llegó la oportunidad).
