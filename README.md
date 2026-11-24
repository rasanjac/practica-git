# Práctica de Git: Ramas, Uniones y Conflictos

Este repositorio es una práctica de la Fase 0 para aprender a trabajar con ramas y resolver conflictos en Git usando una lista de películas (`peliculas.md`).

## ¿Qué es una rama (*branch*)?
Es una linea de desarrollo independiente que permite hacer cambios o arreglar errores sin afectar al main hasta que el trabajo esté listo para unirse.

## ¿Qué es un conflicto (*merge conflict*)?
Ocurre cuando dos ramas modifican exactamente la misma línea de un archivo de forma distinta y Git no puede decidir automáticamente cuál versión conservar. Para resolverlo, se elige manualmente qué contenido dejar, se borran las marcas de conflicto y se confirma con un nuevo commit.
## Diferencia entre git revert y git reset

* git revert:Es mas seguro ya que deshace un commit en especifico sin afectar lo demas
* git reset:Mueves el puntero hacia atras y elimina todo lo que estaba despues de ese puntero