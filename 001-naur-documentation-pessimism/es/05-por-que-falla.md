---
layout: default
title: "V. Por Qué Falla la Documentación Técnica"
nav_order: 6
lang: es
---

# V. Por Qué Falla la Documentación Técnica

![Iceberg](../img/05-iceberg.webp)

Alistair Cockburn, comentando sobre Naur, sugiere que la documentación técnica falla porque apunta al objetivo equivocado.

---

## El Objetivo Equivocado

> "Usando las ideas de Naur, el trabajo del diseñador no es transmitir 'el diseño' sino transmitir 'las teorías' que impulsan el diseño. El segundo objetivo es más útil y más apropiado."

La documentación técnica describe artefactos. Pero los artefactos son *productos* de la teoría, no la teoría misma. Leer un texto de programa te dice qué decisiones se tomaron; no te dice:

- Qué consideraciones llevaron a esas decisiones
- Qué alternativas fueron rechazadas y por qué
- Qué similitudes percibió el programador entre este problema y otros

La metáfora del iceberg aplica: la documentación muestra la punta (el artefacto); la teoría es la masa sumergida que lo sostiene.

---

## Un Objetivo Reformulado

Cockburn además observa:

> "La documentación no puede—y por tanto no necesita—decirlo todo. Su propósito es ayudar al siguiente programador a construir una teoría precisa sobre el sistema."

Esto reformula el objetivo. La documentación no necesita (y no puede) *contener* teoría explícitamente. Debe proporcionar material suficiente para que un lector *reconstruya* la teoría—para construir su propia comprensión que, aunque no sea idéntica a la del programador original, sea lo suficientemente cercana como para guiar modificaciones correctas.

---

## Lo Que Documentan los Diseñadores Experimentados

Los diseñadores experimentados, observa Cockburn, frecuentemente comienzan la documentación con:

- Las metáforas
- Texto describiendo el propósito de cada componente principal
- Dibujos de las interacciones principales entre componentes

Estos son dispositivos de transmisión de teoría, no descripciones de artefactos. Ayudan al lector a construir modelos mentales, no solo a registrar hechos.

---

[← Anterior](04-transmision-cultural.md) | [Índice](index.md) | [Siguiente →](06-articulacion-forzada.md)
