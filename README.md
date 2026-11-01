# Software de detección de amenazas de seguridad – Mercado Libre

Trabajo Práctico Integrador (TPI) de la asignatura **Organización Empresarial**.
Tecnicatura Universitaria en Programación a Distancia – Universidad Tecnológica Nacional.

## Descripción del sistema

Software que detecta intentos de intrusión externos y accesos internos no autorizados a las bases de datos de usuarios de Mercado Libre. Registra cada evento de seguridad, lo evalúa con reglas de detección, emite una alerta en menos de 5 segundos y bloquea automáticamente las amenazas de severidad alta o crítica.

## Autora

- Celentano Eliana – Comisión 04 (trabajo individual)

## Contenido del repositorio

- `docs/Entregas/`: PDF de las cuatro entregas del TPI.
- `docs/bpmn/`: diagrama BPMN del proceso de detección y respuesta.

## Tablero de gestión

https://github.com/users/gokuheine/projects/5

## Indicadores de control

| Indicador | Estándar | Datos de origen |
| --- | --- | --- |
| Tasa de detección | ≥ 95 % de ataques simulados detectados | ALERTA y pruebas de penetración |
| Tasa de falsos positivos | ≤ 2 % de las alertas | ALERTA (campo falso_positivo) |
| Tiempo de alerta (percentil 95) | < 5 segundos | ALERTA (campo tiempo_respuesta_seg) |
| Capacidad de procesamiento | ≥ 10.000 eventos por segundo, sin pérdidas | EVENTO_SEGURIDAD |
| Cobertura | 100 % de los activos monitoreados | ACTIVO_PROTEGIDO (campo monitoreado) |
| Cumplimiento del plazo | 0 semanas de atraso en el camino crítico | Gantt y tablero |
| Integración controlada | 100 % de los PR con comentario de revisión | Historial de GitHub |

## Declaración de Uso de IA

Se utilizó un asistente de IA generativa (Claude, de Anthropic) para proponer la estructura del trabajo, un borrador del diagrama BPMN, las Historias de Usuario y los indicadores, y para guiar la configuración de GitHub. La veracidad y la coherencia del contenido son responsabilidad de la autora. El detalle de los prompts utilizados y de las correcciones humanas está en la sección 5 del PDF de la Entrega 4.

