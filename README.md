# De idea a producto

Una skill de Claude para quienes tienen muchas ideas y quieren convertirlas en apps o productos digitales con *vibe coding*, sin construir sobre huecos.

Está pensada para personas que **no programan, pero dirigen**: saben lo que quieren lograr, aunque no siempre la mejor forma de llegar. La skill hace que Claude ordene la idea, la cuestione y la lleve por puertas de decisión antes de construir.

## Qué hace

- **Interrogatorio por rondas:** antes de construir, Claude pregunta en rondas cortas. Cada pregunta trae su respuesta recomendada, y tú solo dices "sí" o la corriges.
- **10 puertas de decisión:** de la idea suelta al producto publicado, con un diagnóstico antes de fijar métricas.
- **Abogado del diablo:** antes de aprobar el producto, Claude intenta demostrar que va a fracasar desde 8 ángulos y da un veredicto: PASA, PASA CON CONDICIONES o NO PASA.
- **Ficha 5W2H y criterios medibles:** sin ficha no se construye producto.
- **Formato de traspaso:** un resumen fijo para continuar en un chat nuevo o en otra IA sin perder decisiones.
- **Límites de seguridad:** Claude no desactiva protecciones del sistema, no toca originales sin respaldo y pide confirmación para acciones que no se pueden deshacer.
- **Modo aprendizaje:** al cerrar cada sesión, una retroalimentación corta sobre tus competencias de vibe coding.
- **Regla "hazlo":** Claude evalúa y recomienda primero; construye solo cuando dices "hazlo".

## Las puertas

```
1 Idea → 2 Filtro de misión → 3 Buscar piezas reutilizables → 4 Diagnóstico
→ 5 Explorar (prototipo desechable) → 6 Ficha 5W2H + abogado del diablo
→ 7 Criterios de aceptación → 8 Construir por fases → 9 Prueba con cliente real
→ 10 Publicar y medir
```

## Instalación

**En la app de Claude (web o escritorio)**
1. En Configuración, activa la ejecución de código y creación de archivos.
2. Descarga el archivo `de-idea-a-producto.zip`.
3. Ve a Skills, elige subir una skill y selecciona el ZIP.

**En Claude Code**
Copia la carpeta `de-idea-a-producto` en `~/.claude/skills/` (para todos tus proyectos) o en `.claude/skills/` dentro de un proyecto.

## Cómo usarla

Escribe `/de-idea-a-producto` o simplemente cuéntale a Claude una idea. Ejemplos:

- "Tengo una idea: una app para que los talleres reserven turnos de mantenimiento."
- "Quiero mejorar mi calculadora de precios; ¿en qué puerta estamos?"
- "Pasa esta ficha por el abogado del diablo."
- "Dame el traspaso para seguir mañana en otro chat."

## Complemento opcional: tablero de frentes

Si llevas varios proyectos a la vez, usa una hoja con estas columnas: Frente, Prioridad (máximo 3 en Alta), Estado, Puerta, Siguiente acción, Bloqueo, Tipo y Revisado. Pídele a Claude que la lea al inicio de cada sesión y la actualice al cierre.

## Personalízala

La skill es genérica. Te rinde más si le agregas tu contexto: tu misión, tu catálogo de piezas reutilizables, tus casos de estudio y las IAs que usas para investigar.

## Seguridad

Revisa siempre el contenido de una skill antes de instalarla. Esta contiene solo instrucciones en texto: no tiene scripts y no se conecta a internet.

## Licencia

MIT. Puedes usarla, modificarla y compartirla.
