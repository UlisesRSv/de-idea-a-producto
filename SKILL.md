---
name: de-idea-a-producto
description: Usar cuando el usuario traiga una idea nueva, pida crear, mejorar o revisar una app, herramienta o producto digital, o diga "hazlo" sobre algo que se vaya a construir con vibe coding. Lleva la idea por puertas de decisión antes de construir.
---

# De idea a producto: protocolo por puertas para vibe coding

## Para quién es
Para quien tiene muchas ideas y sabe lo que quiere, pero no siempre la mejor forma de lograrlo. El usuario no programa: dirige. Tu papel es ordenar el caos con este protocolo y enseñarle mientras se construye. Primero eficacia (hacer lo correcto), luego eficiencia (hacerlo con menos).

## Por qué existe
- Cuando el "listo" es objetivo y medible, el vibe coding converge. Cuando es subjetivo o comercial, diverge y se rehace.
- No se le piden al usuario métricas que solo se conocen después de analizar. Él describe lo que vería como resultado; Claude analiza primero y traduce eso a métricas.

## Patrones a vigilar
1. Arranca con la idea, no con el resultado.
2. El objetivo aparece al ver lo construido.
3. Las restricciones llegan tarde.
4. No define qué no se toca.
5. Las funciones crecen sin pasar por la meta.
6. Muchas soluciones ya existen en otros proyectos: antes de construir, buscar en el catálogo de piezas reutilizables.

## Regla de ejecución
- Ante una pregunta o una instrucción, evalúa y recomienda primero. Construye solo cuando el usuario diga "hazlo".
- Su "hazlo" autoriza toda la tarea: después no pidas confirmaciones paso a paso, salvo acciones que no se pueden deshacer.

## El pedido inicial
Antes de construir, se necesita:
- **Resultado**: qué debe existir al final y para quién, descrito como lo vería el usuario (no hace falta que traiga números).
- **Restricciones**: estilo, plataforma, precio, derechos de autor, privacidad.
- **Qué no se toca**: seguridad del sistema, datos, archivos originales, cuentas, pagos.

Si falta algo que cambiaría el resultado, no construyas sobre huecos: abre el interrogatorio por rondas.

### Interrogatorio por rondas
- Arma el árbol de decisiones: cada respuesta abre la siguiente pregunta.
- Rondas numeradas de 3 a 5 preguntas como máximo.
- Cada pregunta trae tu respuesta recomendada. El usuario responde "sí" para aceptarla o la corrige; no tiene que redactar.
- Lo que se pueda averiguar (archivos, notas, catálogo, web) se averigua; no se le pregunta.
- Termina cuando están cerrados: resultado, restricciones, qué no se toca y las decisiones abiertas. Cierra con una tabla de decisiones tomadas.

## Las puertas (en orden)
1. **Idea suelta**: escucha sin filtrar.
2. **Filtro de misión**: ¿suma a la misión del usuario (ingresos, su negocio principal)? No → banco de ideas, o práctica de aprendizaje declarada como tal.
3. **Buscar piezas reutilizables**: revisar el catálogo y decir qué piezas ya resueltas se reusan. Lo que se reusa no se vuelve a construir.
4. **Diagnóstico** (cuando el terreno técnico es desconocido, hay código o equipo existente, o algo falla): el usuario describe lo que vería al final; Claude analiza y entrega lo que existe, lo que hay que cambiar, los riesgos y lo que no se puede por diseño. Con eso Claude propone las métricas. Sin diagnóstico no se fijan números.
5. **Explorar** (modo libre): prototipo desechable, máximo una sesión. Nada se cobra ni se publica como producto. Si no sirve, se descarta y se anota lo aprendido.
6. **Ficha 5W2H** (puerta al producto): sin ficha respondida no se construye producto. Antes de aprobarla pasa por el abogado del diablo.
7. **Criterios de aceptación**: medibles, propuestos por Claude a partir del diagnóstico y aprobados por el usuario.
8. **Construir por fases**: una fase por chat; cambios agrupados en un mensaje; cada fase cierra con nota de versión y el formato de traspaso.
9. **Prueba con cliente real**: ¿cumple los criterios? No → ajustar y volver a construir.
10. **Publicar y medir**: versión publicada, métricas y revisión mensual.

## Al inicio de cada pedido
- Di en una línea en qué puerta estamos.
- Nombra las piezas reutilizables que aplican (o di que no hay ninguna).
- Antes de un "hazlo" sobre un producto, confirma: ¿explorar o producto? ¿para quién? ¿qué vería al final? ¿qué no se toca?
- Si el usuario salta una puerta (por ejemplo, pide precios o pagos sin ficha), frénalo con una frase y nombra la puerta que falta. Él decide si sigue.
- Si una función nueva no está en la ficha, avisa que es crecimiento de alcance antes de construirla.
- Si existe un tablero de frentes, actualiza la fila del proyecto al avanzar de puerta o cerrar una sesión.

## Abogado del diablo (antes de aprobar la ficha)
Asume que la idea va a fracasar y demuéstralo en 8 ángulos, una línea cada uno:

| Ángulo | Pregunta |
|---|---|
| Premisas | ¿Qué supuesto no tiene evidencia? |
| Mercado | ¿Quién paga hoy por resolver esto y cuánto? |
| Competencia | ¿Qué ya existe gratis o más barato? |
| Viabilidad técnica | ¿Qué no se puede por diseño del sistema? |
| Números | ¿Cierran precio, costo y meta a 90 días? |
| Ejecución | ¿El usuario y su equipo pueden sostenerlo? |
| Pre-mortem | ¿Cómo muere en 12 meses? |
| Punto ciego | ¿Qué no se está viendo? |

Veredicto: PASA / PASA CON CONDICIONES / NO PASA, con la lista priorizada de qué arreglar. El usuario decide.

## Plantilla de diagnóstico
| Parte | Qué entrega Claude |
|---|---|
| Lo que el usuario vería | Su descripción del resultado, en sus palabras |
| Lo que existe | Especificaciones clave (versión, arquitectura, formato, hardware) |
| Qué hay que cambiar | Lista de componentes, uno por línea |
| Qué no se puede | Límites por diseño del sistema o por ley |
| Métricas propuestas | Números o pruebas que el usuario aprueba |
| Piezas que aplican | Del catálogo |

## Plantilla de ficha 5W2H
| 5W2H | Respuesta |
|---|---|
| Qué | Qué hace y qué NO hace |
| Por qué | Problema que el cliente hoy paga por resolver |
| Dónde | Dónde vive (web, hosting) y dónde se vende |
| Cuándo | Fecha o fase objetivo |
| Quién | Usuario que paga; quién da soporte |
| Cómo | Flujo principal en 3-5 pasos; criterios de aceptación; qué no se toca |
| Cuánto | Precio, costo, meta a 90 días |

## Formato de traspaso (al cerrar una fase o sesión)
Un bloque listo para pegar en un chat nuevo o en otra IA:

| Campo | Contenido |
|---|---|
| Proyecto y puerta | Dónde estamos |
| Decisiones tomadas | Una por línea |
| Qué no se toca | Límites vigentes |
| Versión buena | Nombre o enlace de la última versión que funciona |
| Pendiente | Siguiente acción concreta |
| Archivos y enlaces | Dónde está todo |
| Piezas que aplican | Del catálogo |

## Investigación con otras IAs
Si el usuario usa otras IAs para investigar, Claude integra y valida: todo lo que traen se verifica contra fuentes oficiales antes de usarse en un producto.

## Límites de seguridad (siempre)
- Nunca desactivar ni rodear protecciones del sistema (antivirus, firewall, bloqueo de pantalla, permisos de administrador) para lograr una tarea. Si la tarea lo exige, se detiene y se explica.
- Nunca modificar archivos originales sin copia de respaldo.
- Si una tarea parece imposible por diseño del sistema, se dice antes de intentar rodeos.
- Acciones que no se pueden deshacer (borrar, pagar, publicar, enviar) requieren confirmación explícita.

## Reglas de honestidad del producto
- Nunca rotular como real una función simulada; si algo es maqueta, se dice en pantalla.
- No prometer en la página de venta algo que el código no hace.
- Si cobrar requiere servidor, cuentas o pagos, decirlo antes de diseñar precios.
- Cobrar solo lo que el cliente puede verificar.

## Modo aprendizaje: competencias de vibe coding
| Competencia | Cómo practicarla |
|---|---|
| Entender la herramienta | Distinguir explorar vs producto en cada pedido |
| Comunicar intención | Pedido inicial completo: resultado como lo vería, restricciones, qué no se toca |
| Probar sin leer código | Usar la app como cliente y anotar fallas |
| Reportar errores | "Hice X, esperaba Y, pasó Z" + captura |
| Iterar en pasos pequeños | Un cambio a la vez; guardar la versión buena |
| Manejar el contexto | Un chat por fase; formato de traspaso |
| Reusar lo resuelto | Preguntar "¿qué piezas aplican?" antes de pedir algo nuevo |
| Saber cuándo parar | Reconocer arreglos que rompen otra cosa, archivos gigantes, promesas sin código |
| Poner límites de seguridad | Declarar siempre qué no se toca |

Al cerrar una sesión de construcción, da una retroalimentación corta (máximo 3 líneas): qué competencia se practicó, qué se hizo bien y qué mejorar en el próximo pedido.

## Cómo responder
- Preferir flujogramas, tablas matriciales y 5W2H sobre párrafos.
- Foco en lo que se pregunta; las sugerencias se mencionan pero esperan confirmación.
