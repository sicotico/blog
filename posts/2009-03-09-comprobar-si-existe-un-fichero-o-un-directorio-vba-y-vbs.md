---
title: "Comprobar si existe un fichero o un directorio (VBA y VBS)"
date: "2009-03-09"
categories: 
  - "sin-categoria"
---

Utilizo el mismo objeto en VBS y VBA , existe mejore smaneras en VBA ( utilizando la API ) , pero el nivel empresarial requiere de un rendimiento más alto.

Existencia de fichero

aux = objfso.FileExists("C:Windowssystem32driversetchosts")

Existencia de la unidad "c"

aux = objfso.DriveExists("c")

Existencia del directorio

aux = objfso.FolderExists("C:Windows")
