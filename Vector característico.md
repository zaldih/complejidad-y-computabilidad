---
tags:
  - máquina-de-turing
Aprendido: true
---

El **vector característico** es un concepto crucial en la teoría de la computación, especialmente al estudiar máquinas de Turing y la clasificación de lenguajes.

## Definición
El vector característico de una MT es una representación binaria que codifica la estructura y el comportamiento de la máquina. Cada componente del vector está asociado a un aspecto específico de la MT, como sus estados, transiciones, y símbolos de cinta.

## Uso en la Clasificación de Lenguajes

El vector característico se utiliza para clasificar lenguajes en diversas categorías, como **decidibles**, **indecidibles**, y **recursivamente enumerables**.

- Si dos MT tienen el mismo vector característico, entonces reconocen el mismo lenguaje.
- La comparación de vectores característicos también se utiliza para demostrar propiedades como la equivalencia de lenguajes y la indecidibilidad de ciertos problemas.

## Ejemplo

Consideremos una MT $M$ con tres estados $(q_0, q_1, q_{\text{aceptar}})$, un conjunto de símbolos de entrada $(0, 1)$, y un conjunto de símbolos de cinta $(0, 1, \sqcup)$. El vector característico de $M$ podría ser: 
$$\text{110010001}$$
Donde cada posición del vector representa un aspecto específico de $M$.
Este ejemplo ilustra cómo el vector característico codifica la estructura y el comportamiento de la máquina de Turing, facilitando su clasificación y comparación con otras máquinas.