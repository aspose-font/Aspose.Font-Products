---
translation: true
template: /_templates/conversion-cpp.md
title: Conversión de fuentes | C++
url: /cpp/conversion/
description: Convierta fuentes con la biblioteca de procesamiento de fuentes C++ y las aplicaciones web. Funcionalidad de conversión que puede funcionar con fuentes TTF, WOFF, CFF, EOT y Type 1.
metakeywords: conversión de fuentes c++, soluciones de conversión de fuentes c++, conversión de fuentes cpp
family: font
platformtag: cpp
feature: conversion
---

{{<section banner>}}
---
h1: Convertir fuentes
h2: API de conversión de formato de fuente para С++. Convierta fuentes WOFF2, TTF, EOT y CFF.
---

{{<section overview>}}
---
p1: La API de fuentes С++ puede cargar, guardar y convertir fácilmente diferentes fuentes, como las colecciones CFF, OpenType, Type1 y TrueType. Proporciona estructura de datos de fuentes junto con cualquier glifo, así como información de codificación para todos los tipos de fuentes que representan un mapeo entre códigos de caracteres e identificadores de glifos. La API puede representar cualquier glifo o texto deseado, así como glifos especiales, que se pueden representar mediante la implementación de interfaces que utilizan funciones gráficas simples como punto de movimiento, línea de dibujo y curva, etc.
p2: "Debido a la naturaleza diversa de los dispositivos, entornos, algunos sistemas operativos y muchas otras áreas, se utilizan diferentes formatos de fuente para cumplir diferentes propósitos, como el uso de diferentes fuentes en páginas web, aplicaciones y publicaciones. A veces es necesario transformar una fuente en otra para cumplir con la visualización requerida."
p3: "Le ofrecemos la solución С++ Api que admite las siguientes fuentes como formatos de salida: TrueType (TTF), formato de fuente abierta web (WOFF y WOFF2), formato OpenType integrado (EOT), tipo 1 y formato de fuente compacto (CFF)."
---

{{<section feature1>}}
---
title: Conversión de fuente TrueType a formato de fuente abierta Web versión 2.0.
item1: API admite diferentes fuentes para leer y escribir, aquí está la [lista](https://docs.aspose.com/font/cpp/convert/#formats-supported-for-reading-andor-write) para leer y escribir. Para considerar la conversión de TTF a WOFF2, el proceso consiste en cargar una fuente de cualquiera de los formatos admitidos, fuente TrueType para el escenario actual. Utilice el método [*SaveToFormat()*](https://reference.aspose.com/font/cpp/class/aspose.font.font#a670ea97404fd72c2e51b0e8c543c8a45) que tiene un flujo de salida de dos parámetros y [*FontSavingFormats*](https://reference.aspose.com/font/cpp/namespace/aspose.font#a93d0dcc7c00f5c7027d60e14a5433c74) Enumeración para seleccionar el formato de fuente de salida.
item2: Finalmente, llame a SaveToFormat() para guardar las fuentes en cualquiera de los formatos de salida admitidos, actualmente el formato Web Open Font Format versión 2.0 WOFF2.
item3: Para ver esta funcionalidad realizada en una aplicación multiplataforma real, vaya a [aplicación Aspose Font Converter](https://products.aspose.app/font/conversion). Allí también puede encontrar muchas más [soluciones API](https://products.aspose.app/font/applications) para trabajar con fuentes y texto.
item4: Vaya a la [Documentación](https://docs.aspose.com/font/net/) para obtener toda la información necesaria para comenzar a trabajar con la solución, como los Tutoriales para las funciones principales o el conjunto de artículos para enseñarle sobre la fuente, las notas de la versión, la guía del desarrollador y otras cosas útiles.
---

{{<section codeexample>}}
---
title: Ejemplo de código C++ Conversión de TTF a WOFF2
---



