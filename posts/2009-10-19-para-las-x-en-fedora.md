---
title: "Parar las X en Fedora"
date: "2009-10-19"
categories: 
  - "sin-categoria"
---

Ando un poco perdido en un proyecto de HP Openview corriendo sobre Red-Hat , gracias a un compañero que lo instalo en una fedora 10 , tenemos un entorno de pruebas . Hoy hemos tuenado un poco el entorno con servicios nuevos para oracle y la aplicación. Ahora estoy en modo optimización asi que dije si no uso grafico ya que conecto con cliente para que quiero unas X gastando memoria .

`su - vi /etc/inittab` y ponemos `id:3:initdefault:`
