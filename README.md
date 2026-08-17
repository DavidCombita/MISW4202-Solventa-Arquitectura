# MISW4202 — Solventa: Arquitectura de Software

Backlog de Historias de Arquitectura (ASR) del caso **Solventa** para la asignatura **MISW4202 – Arquitecturas Ágiles de Software**.

## Contexto

Solventa es una insurtech *greenfield*, nativa en la nube y orientada a Open Finance y Open Data. Debe soportar clientes web, móviles y socios externos que distribuyen seguros embebidos mediante APIs.

El alcance incluye cotización, suscripción, pólizas, siniestros, pagos, identidad, consentimiento, perfilamiento de riesgo, integraciones, analítica, fraude y cumplimiento.

## Restricciones de arquitectura

- Estilo arquitectónico basado en microservicios.
- Experimentos de arquitectura implementados con Python y Flask.
- Persistencia y mensajería basadas preferentemente en componentes open source estándar.
- Diseño y validación en ocho semanas, con equipo reducido y presupuesto operativo limitado.

## Backlog de arquitectura

Las ASR se gestionan como [Issues del repositorio](https://github.com/DavidCombita/MISW4202-Solventa-Arquitectura/issues) y en el Project público [Solventa - Backlog de Arquitectura](https://github.com/users/DavidCombita/projects/2).

El backlog cubre seis atributos de calidad:

1. Latencia
2. Escalabilidad
3. Disponibilidad
4. Seguridad
5. Facilidad de modificación
6. Facilidad de integración

Cada ASR incluye fuente, estímulo, ambiente, artefacto, respuesta, medida verificable y prioridad.

## Flujo de trabajo

El Project utiliza los estados:

- Backlog
- Ready
- In Progress
- Done

También registra atributo de calidad, prioridad, responsable, iteración e identificador ASR.

## Criterios de validación

Una historia se acepta cuando:

- identifica claramente fuente, estímulo y ambiente;
- define la respuesta esperada y una medida verificable;
- afecta una decisión arquitectónica;
- se relaciona con uno de los seis atributos de calidad;
- está sustentada por el caso Solventa;
- expresa una necesidad, no una tecnología o táctica específica.

Las tecnologías y tácticas —por ejemplo, colas, caché, réplicas o circuit breakers— se evalúan posteriormente como posibles decisiones para satisfacer las ASR.
