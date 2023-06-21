# Practica Cloud Java 2022-2023

Aitor Iturrioz & Pablo Rubio

Este repositorio es el código inicial del ejercicio principal del Curso Cloud de Tknika.

---

**Ejercicio:**

Desarrolla un GitHub Action que al crear un tag nuevo publique un contenedor en GitHub Registry (en tu repositorio).

**Pistas:**

Se puede realizar utilizando los mismo action que para DockerHub.

Necesitaras un OAuth Token de GitHub.

El nombre de tu usuario se puede obtener mediante: ${{ github.actor }}

Antes del push conviene utilizar el siguiente action: (Teniendo en cuenta que env.REGISTRY es el repositorio (ghcr.io) e Image name el nombre completo de tu repositorio)

```

```

Y así definir el tag del contenedor con:

```

```
