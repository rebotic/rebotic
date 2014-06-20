---
layout: post
title: "Como blogear"
date: 2014-06-19 10:13:03 -0300
comments: true
categories:
---

Este es un blog de [Octopress](http://octopress.org/). Octopress es una aplicación para hacer blogs que utiliza [Markdown](http://daringfireball.net/projects/markdown/) para procesar el texto

## Clonate

Para clonarte el repo en tu compu

``git clone git@github.com:rebotic/rebotic.git rebotic``

pasate al rama source y no pushees nada a las otras ramas.

``git checkout source``

## Escribí

Para hacer un nuevo post.

``rake new_post["título del nuevo post"]``

Esto creará un nuevo archivo en la carpeta source/posts, editalo y armalo usando markdown.


## Probalo

Para ver tu cambios, podes correr de forma local el repo.

``rake preview``

## Subí tus cambios

Una vez que todos los cambios estén listo, hace el commit

``git add .``

``git commit -m "mensaje"``

Corré las tareas de rake

``rake generate``

``rake deploy``
