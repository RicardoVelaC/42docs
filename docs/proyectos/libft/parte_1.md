---
layout: default
nav_order: 6
title: Parte 1
grand_parent: Proyectos
parent: Libft
permalink: proyectos/libft/parte_1
---

# Libft - Parte 1


## ft_tolower

``` c
int	ft_tolower(int c)
{
	if (c >= 'A' && c <= 'Z')
		c = c + 32;
	return (c);
}
```