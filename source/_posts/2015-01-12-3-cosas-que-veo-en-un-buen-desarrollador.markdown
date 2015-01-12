---
layout: post
title: "3 cosas que veo en un buen desarrollador"
date: 2015-01-12 00:31:37 -0600
comments: true
categories: 
---

Un desarrollador de software suele saber a lo largo de su carrera profesional
distintos lenguajes, editores, versionadores, entre otras herramientas. Sin
embargo, suelo encontrarme con "expertos en ruby" con 10 años de experiencia
haciendo exactamente el mismo código deficiente de alguien con poco tiempo en
el gremio.

Esta conversación la he tenido con otros desarrolladores y he concluído que es
más importante saber las variables que se perciben de un problema que las
herramientas que se han de utilizar para cumplir el objetivo.

<!-- more -->

Aquí están los 3 puntos más importantes en los que me enfoco para saber qué
tanta experiencia tiene un developer.

## 1. Cómo nombra objetos

No hay otra cosa que dure más en el código que los nombres de objetos. Una vez
que se ha nombrado la clase `` User `` es difícil que sea modificado a
`` Employee `` o a otro nombre no solo en el código, sino también en la
documentación, pruebas, etc.

Por otro lado, nombres que solo se comprenden bajo ciertas circunstancias,
significan muy a menudo pérdida de tiempo para otros que por primera vez ven
esa pieza de software, además de perder el contexto de lo que se está
reslviendo únicamente por no seguir un cierto estándar o tener cuidado al darle
una etiqueta a cada tipo de pieza del rompecabezas.

## 2. Cómo administra objetos

Una vez que se ha determinado el nombre del objeto, la siguiente interrogante
es el comportamiento que se le va a otorgar (aunque honestamente el punto 1 y 2
es casi como preguntarse si fue primero el huevo o la gallina).

Si te has topado con una clase que además de guardar en la base de datos,
convierte algunos datos a JSON, calcula la edad, manda un correo, crea un
proceso en la cola, valida datos de guardado, procesa archivos grandes, etc.,
sabes perfecto de qué hablo.

Es necesario saber exactamente el comportamiento del que se encargará cada
clase para:

1. No repetir código
2. Hacer pruebas más simples
3. Hacer código fácil de modificar
4. Hacer código reutilizable

## 3. Cómo razona el problema

Aunque este punto se piense obvio, la manera en que razona un problema tiene
mucho que ver con la complejidad de la implementación final.

Hace años escuché el término KISS (Keep it simple, stupid) que se refería a
determinar el código más sencillo para resolver un problema. Cabe señalar que
simple no implica corto, sino menos complejo. Así pues, para mostrar un texto
en un sitio web, puede hacerse por medio de un parámetro en la URL, por medio
de una variable de sesión, o un texto estático controlado por el navegador.
Todo depende de que se necesite, que tanto debe considerarse el rendimiento,
etc.

Comúnmente aplico problemas matemáticos de razonamiento para descubrir qué tipo
de respuestas piensa el candidato: descrubrir la moneda falsa, determinar la
cantidad de impares en una sucesión, la validez de una fórmula, etc.

¿Qué otras cosas ves en un buen desarrollador?

Saludos!
