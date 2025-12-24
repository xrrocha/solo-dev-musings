---
layout: default
title: "El Ensayo de Naur: Un Resumen"
nav_exclude: true
lang: es
---

# La Programación como Construcción de Teoría: Un Resumen

![El Portador de la Teoría](../img/naur.webp)

[Peter Naur](https://es.wikipedia.org/wiki/Peter_Naur) (1928–2016) fue un científico de la computación danés, ganador del Premio Turing y co-creador de la Forma Backus-Naur (BNF). En 1985 publicó "Programming as Theory Building," un ensayo breve pero influyente que replantea qué *es* fundamentalmente la programación.

---

## La Tesis Central

La programación no es primariamente la producción de código y documentación. Es la construcción de una **teoría**—un modelo mental en la mente del programador sobre cómo los asuntos del mundo real se mapean al programa.

El texto del programa y la documentación son artefactos secundarios. La teoría es lo primario.

---

## Qué Significa "Teoría"

Naur se basa en el concepto de teoría del filósofo [Gilbert Ryle](https://es.wikipedia.org/wiki/Gilbert_Ryle): conocimiento que te permite no solo *hacer* cosas sino también *explicarlas*, *justificarlas* y *responder preguntas* sobre lo que haces.

Un programador que posee la teoría de un programa puede:

1. **Explicar** cómo la solución se relaciona con el problema del mundo real que aborda
2. **Justificar** por qué cada parte del programa está estructurada como lo está
3. **Responder constructivamente** a solicitudes de modificación

La tercera capacidad es decisiva. Cualquiera puede leer código y entender *qué* hace. Solo alguien con la teoría sabe *cómo cambiarlo correctamente* cuando los requisitos cambian.

---

## Por Qué Falla la Documentación

La afirmación central de Naur es que la teoría **no puede, en principio, expresarse completamente** en documentación. Esto no es por falta de tiempo o esfuerzo—es un límite epistemológico.

La teoría depende de reconocer *similitudes* entre situaciones del mundo real: qué aspectos importan, cuáles no, cómo los nuevos requisitos se asemejan a los existentes. Estas similitudes resisten la formalización:

> "Las similitudes en cuestión no son, y no pueden ser, expresadas en términos de criterios, no más de lo que las similitudes de muchos otros tipos de objetos, como rostros humanos, melodías o sabores de vino, pueden expresarse así."

No puedes escribir reglas para reconocer rostros. No puedes escribir reglas para reconocer cuándo una nueva funcionalidad encaja naturalmente en una arquitectura existente. Ambas requieren conocimiento tácito construido a través de la experiencia.

---

## Vida, Muerte y Resurrección de un Programa

Naur extiende la visión de construcción de teoría al ciclo de vida de un programa:

- Un programa **vive** mientras los programadores que poseen su teoría continúan manteniéndolo
- Un programa **muere** cuando ese equipo se disuelve—incluso si el código sigue ejecutándose
- La **resurrección** (reconstruir la teoría solo desde la documentación) es extremadamente costosa y frecuentemente produce una teoría *diferente* a la original

Esto explica por qué los programas se degradan bajo el mantenimiento de programadores que carecen de la teoría original. Añaden "parches" que funcionan pero violan la coherencia del diseño. Con el tiempo, la estructura se vuelve "completamente inefectiva por adiciones amorfas de muchos tipos diferentes."

---

## Implicaciones

Si Naur tiene razón:

- **Los programadores no son componentes reemplazables.** Portan conocimiento irreemplazable.
- **La documentación no puede sustituir la continuidad humana.** Transmitir la teoría requiere trabajar cercanamente con quienes la poseen.
- **La modificación de programas es fundamentalmente diferente de la producción de programas.** Requiere teoría, no solo manipulación de texto.
- **Ninguna metodología garantiza buenos programas.** La construcción de teoría es personal, contextual y resiste la procedimentalización.

---

## Dónde Leer Más

El ensayo original fue publicado en *Microprocessing and Microprogramming* (1985) y reimpreso en la colección de Naur *Computing: A Human Activity* (1992). También aparece como apéndice en *Agile Software Development: The Cooperative Game* de [Alistair Cockburn](https://en.wikipedia.org/wiki/Alistair_Cockburn) (2da ed., 2006), con valioso comentario.

---

[← Volver al Índice](index.md)

---

🏠 [Reflexiones de un desarrollador solitario](../../LEEME.md)
