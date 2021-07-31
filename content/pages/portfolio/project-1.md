---
title: Tweetable
subtitle: Clon de Twitter en Ruby on Rails
date: '2021-01-13'
thumb_image: images/1_thumb.jpg
thumb_image_alt: 'White, black, and red shoe sole'
image: images/1.jpg
image_alt: Vista de Tweetable en Ruby on Rails
seo:
  title: Project Title 1
  description: This is the project 1 description
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: Project Title 1
      keyName: property
    - name: 'og:description'
      value: This is the project 1 description
      keyName: property
    - name: 'og:image'
      value: images/1.jpg
      keyName: property
      relativeUrl: true
    - name: 'twitter:card'
      value: summary_large_image
    - name: 'twitter:title'
      value: Project Title 1
    - name: 'twitter:description'
      value: This is the project 1 description
    - name: 'twitter:image'
      value: images/1.jpg
      relativeUrl: true
layout: project
---
Para el desarrollo de Tweetable se tuvo medio día para crear una versión más simple y modificada de Twitter. Esta versión consta de 3 entidades como Usuario, Tweet y comentario, así mismo a cada entidad se le añadió una capa de validaciones.

> ## Gemas usadas:
>
> *   [**Devise**](https://github.com/heartcombo/devise) para el registro de usuarios y control de sesiones.
>
> *   [**Pundit**](https://github.com/varvet/pundit) para la autorización de permisos y acceso de los usuarios.

Puedes ver el código fuente en mi repositorio de Github: [Tweetable (Twitter clone)](https://github.com/jcvegab/tweetable-individual)

