---
layout: default
title: "V. Why Technical Docs Fail"
nav_exclude: true
---

# V. Why Technical Documentation Fails

![Iceberg](../img/05-iceberg.webp)

[Alistair Cockburn](https://en.wikipedia.org/wiki/Alistair_Cockburn), commenting on Naur, suggests that technical documentation fails because it addresses the wrong target.

---

## The Wrong Target

> "Using Naur's ideas, the designer's job is not to pass along 'the design' but to pass along 'the theories' driving the design. The latter goal is more useful and more appropriate."

Technical documentation describes artifacts. But artifacts are *products* of theory, not theory itself. Reading a program text tells you what decisions were made; it does not tell you:

- What considerations led to those decisions
- What alternatives were rejected and why
- What similarities the programmer perceived between this problem and others

The iceberg metaphor applies: documentation shows the tip (the artifact); the theory is the submerged mass that supports it.

---

## A Reframed Goal

Cockburn further notes:

> "Documentation cannot—and so need not—say everything. Its purpose is to help the next programmer build an accurate theory about the system."

This reframes the goal. Documentation need not (and cannot) *contain* theory explicitly. It should provide sufficient material for a reader to *reconstruct* theory—to build their own understanding that, while not identical to the original programmer's, is close enough to guide correct modifications.

---

## What Experienced Designers Document

Experienced designers, Cockburn observes, often start documentation with:

- The metaphors
- Text describing the purpose of each major component
- Drawings of the major interactions between components

These are theory-transmission devices, not artifact descriptions. They help the reader build mental models, not just record facts.

---

[← Previous](04-cultural-transmission.md) | [Index](index.md) | [Next →](06-forced-articulation.md)

---

🏠 [Solo Dev Musings](../../README.md)
