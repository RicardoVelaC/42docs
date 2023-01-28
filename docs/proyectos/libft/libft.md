---
layout: default
nav_order: 1
title: Libft
parent: Proyectos
permalink: proyectos/libft
has_children: true
has_toc: false
---

# Libft: Mi primera librería en C

![libft-badge]

> El primer proyecto de **escuela 42** consiste en aprender que hacen las funciones estándar de la programación en `C`, creando desde cero nuestra propia librería a la que llamaremos `Libft`.

| Objectivos  | Habilidades             |
|:------------|:------------------------|
| Lógica Unix | Algoritmos e IA         |
|             | Programación imperativa |
|             | Rigor                   |

## Indice
{: .no_toc .text-delta }

1. TOC
{:toc}
---

## ¿Qué es Libft?

Este proyecto consiste en recrear el comportamiento de muchas de las funciones básicas de propósito general de las librerías de `C` estándar `<libc.a>` y otras que aunque no esten incluidas dentro de la librería estándar nos serán útiles en el futuro. 
El objetivo es apreder que hacen estas funciones programándolas desde cero. 
Al final las agruparemos en nuestra propia librería la cual podremos usar los siguientes proyectos dentro de **escuela 42**.

## Consideraciones previas

| Consideración              | Descripción                            |
|:---------------------------|:---------------------------------------|
| Nombre de programa:        | `libft.a`                              |
| Archivos a entregar:       | `Makefile`, `libft.h`, `*.c`           |
| Makefile:                  | `NAME`, `all`, `clean`, `fclean`, `re` |
| Funciones autorizadas:     | Se detallan en cada función.           |
| Se permite usar `<libft>`: | Todavía no la tienes. :sweat_smile:    |

## Consideraciones técnicas

- Declarar variables globales está prohibido.
- Si necesitas separar una función compleja en varias, asegúrate de utilizar la palabra `static` para ello. De esta forma, las funciones se quedarán en el archivo apropiado.
- Pon todos tus archivos en la raíz de tu repositorio.
- Se prohibe entregar archivos no utilizados.
- Todos los archivos `.c` deben compilarse con las flags `-Wall -Werror -Wextra`.
- Debes utilizar el comando `ar`[^1] para generar la librería. El uso de `libtool` queda prohibido.
- Tu `libft.a` tiene que ser creado en la raíz del repositorio.

---
## Glosario

[^1]: La utilidad `ar` crea y mantiene grupos de ficheros combinados en un archivo. `man ar`

[libft-badge]: https://raw.githubusercontent.com/RicardoVelaC/42-project-badges/main/badges/libft.png "42 Libft badge"
