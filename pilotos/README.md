# Criterios de éxito para pilotos

Este documento establece cómo definir, evaluar y cerrar pilotos. Las
metas deben acordarse antes de iniciar y deben respaldarse con evidencia
reproducible. Ningún valor numérico se debe inventar ni reutilizar como
resultado real sin una fuente verificable.

## Principios

- Proponer criterios observables y límites definidos antes de la ejecución.
- Registrar fuentes, fecha y responsable de cada evidencia.
- Separar hechos comprobados, supuestos y pendientes.
- No publicar datos personales, secretos, credenciales o información confidencial.
- Evitar afirmaciones absolutas o comparaciones sin criterio y muestra documentada.
- Mantener trazabilidad entre los objetivos del piloto y la decisión final.

## Antes de iniciar

Cada piloto debe tener como mínimo:

1. Problema que pretende resolver y población o caso de uso incluido.
2. Alcance, exclusiones y responsables.
3. Estado inicial o línea base acordada, si corresponde.
4. Criterios de éxito y criterios de parada.
5. Método de recopilación y resguardo de la evidencia.
6. Riesgos conocidos, restricciones y responsables de mitigación.
7. Umbrales de decisión acordados por el responsable del piloto.

Cuando no exista una línea base o un umbral verificable, el campo debe
continuar como “pendiente” y no convertirse en una métrica inventada.

## Evidencia aceptable

La evidencia puede ser, según el caso:

- Resultado de una prueba reproducible.
- Registro de ejecución almacenado en un entorno autorizado.
- Captura o exportación anonimizada cuando su origen pueda verificarse.
- Lista de criterios revisados por un responsable identificado.
- Revisión documental de riesgos, seguridad y operación.

El documento debe indicar qué no pudo verificarse. Una ausencia de
evidencia no constituye aprobación.

## Matriz mínima de decisión

| Dimensión | Pregunta | Evidencia requerida | Estado |
| --- | --- | --- | --- |
| Objetivo | ¿El alcance resolvió el problema acordado? | Evidencia vinculada al caso de uso | Pendiente |
| Calidad | ¿Los criterios técnicos acordados se cumplen? | Resultados reproducibles | Pendiente |
| Seguridad | ¿Se identificaron y mitigaron los riesgos aplicables? | Revisión registrada | Pendiente |
| Operación | ¿La solución puede mantenerse por los responsables definidos? | Evidencia operativa acordada | Pendiente |
| Privacidad | ¿Se excluyeron datos sensibles o se aplicaron controles aprobados? | Revisión de datos y controles | Pendiente |
| Reproducibilidad | ¿Otra persona puede repetir las pruebas con la información publicada? | Instrucciones y artefactos disponibles | Pendiente |

## Resultado posible

Las tres conclusiones deben basarse en evidencia y quedar registradas:

- **Aprobar:** todos los criterios obligatorios acordados están respaldados.
- **Continuar con condiciones:** existe un plan verificable para resolver
  límites específicos y responsables determinados.
- **Detener o replantear:** faltan criterios obligatorios, existen riesgos no
  aceptados o no hay evidencia suficiente.

## Contenido relacionado

- [Ficha de piloto](plantilla-ficha-piloto.md)
- [Matriz de madurez](matriz-madurez.md)
- [Repositorio My-Portfolio](https://github.com/NicoLucian/My-Portfolio)
