---
layout: default
title: Home
nav_order: 1
description: "42Docs es una pequeña documentación sobre los proyectos del cursus versión 2022"
permalink: /
---

# 42Docs
{: .no_toc }

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}


---

Esta es una pequeña guía con recursos y apuntes sobre los proyectos
incluidos en el cursus de la escuela 42 de Madrid, basados en la
versión de 2022.

Esto es una prueba.

## Librerías

- [libft](./libs/libft.html)
- [printf](./libs/printf.html)

## Apuntes sobre proyectos

- [Born2beRoot](./projects/born2beroot.html)
- [get_next_line](./projects/get_next_line.html)
- [Pipex](./projects/pipex.html)

<!-- ![](../../assets/images/small-image.jpg)

![](docs/images/logo-header@2x.png) -->

<button class="btn js-toggle-dark-mode">Cambiar modo</button>

<script>
const toggleDarkMode = document.querySelector('.js-toggle-dark-mode');

jtd.addEvent(toggleDarkMode, 'click', function(){
  if (jtd.getTheme() === 'light') {
    jtd.setTheme('dark');
    toggleDarkMode.textContent = 'Cambiar modo';
  } else {
    jtd.setTheme('light');
    toggleDarkMode.textContent = 'Cambiar modo';
  }
});
</script>


### Labels

I'm a label
{: .label }

blue
{: .label .label-blue }
green
{: .label .label-green }
purple
{: .label .label-purple }
yellow
{: .label .label-yellow }
red
{: .label .label-red }

**bold**
{: .label }
*italic*
{: .label }
***bold + italic***
{: .label }

### Mermaid Diagrams

The following code is displayed as a diagram only when a `mermaid` key supplied in `_config.yml`.

```mermaid
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
```


```
The final element.
```