---
translation: true
template: /_templates/conversion-cpp.md
title: Teckensnittskonvertering | C++
url: /cpp/conversion/
description: Konvertera teckensnitt med C++ Font-behandlingsbiblioteket och webbapplikationer. Konverteringsfunktionalitet som kan fungera med TTF, WOFF, CFF, EOT och Type 1-teckensnitt.
metakeywords: c++ teckensnittskonvertering, teckensnittskonverteringslösningar c++, teckensnittsconerter cpp
family: font
platformtag: cpp
feature: conversion
---

{{<section banner>}}
---
h1: Konvertera teckensnitt
h2: Font format converter API för С++. Konvertera WOFF2-, TTF-, EOT- och CFF-teckensnitt.
---

{{<section overview>}}
---
p1: С++ font API kan enkelt ladda, spara och konvertera olika typsnitt som CFF, OpenType, Type1 och TrueType samlingar. Den tillhandahåller teckensnittsdatastruktur tillsammans med valfri glyf samt kodningsinformation för alla teckensnittstyper som representerar en mappning mellan teckenkoder och glyfidentifierare. API kan rendera alla önskade glyf eller text, såväl som speciella glyf, som kan renderas genom att implementera gränssnitt med enkla grafikfunktioner som flytta punkt, ritlinje och kurva, etc.
p2: "På grund av den mångfaldiga karaktären hos prylar, miljöer, ett fåtal operativa system och många andra områden för att använda olika teckensnittsformat för att tjäna olika syften som att använda olika typsnitt på webbsidor, applikationer och publicering. Ibland finns det ett behov av att omvandla ett teckensnitt till ett annat för att möta den önskade visningen."
p3: "Vi erbjuder dig С++ Api-lösning som stöder nästa typsnitt som utdataformat: TrueType (TTF), Web Open Font Format (WOFF och WOFF2), Embedded OpenType-format (EOT), Type 1 och Compact Font Format (CFF)."
---

{{<section feature1>}}
---
title: TrueType Font to Web Open Font Format version 2.0 Conversion.
item1: API stöder olika typsnitt för läsning och skrivning, här är [listan](https://docs.aspose.com/font/cpp/convert/#formats-supported-for-reading-andor-writing) för läsning och skrivning. För att överväga konvertering av TTF till WOFF2, är processen att ladda ett teckensnitt från något av de format som stöds, TrueType Font för det aktuella scenariot. Använd metoden [*SaveToFormat()*](https://reference.aspose.com/font/cpp/class/aspose.font.font#a670ea97404fd72c2e51b0e8c543c8a45) med två parametrar utdataström och [*FontSavingFormats*](https://reference.aspose.com/font/cpp/namespace/aspose.font#a93d0dcc7c00f5c7027d60e14a5433c74) Uppräkning för val av utdatateckensnittsformat.
item2: Slutligen, anrop SaveToFormat() för att spara teckensnitt i något av de utdataformat som stöds, för närvarande Web Open Font Format version 2.0 WOFF2-format.
item3: Gå till [Aspose Font Converter-appen](https://products.aspose.app/font/conversion) för att se den här funktionen realiserad i en verklig plattformsoberoende applikation. Där kan du också hitta många fler [API-lösningar](https://products.aspose.app/font/applications) för att arbeta med typsnitt och text.
item4: Gå till [Dokumentation](https://docs.aspose.com/font/net/) för att få all nödvändig information för att börja arbeta med lösningen, som handledningarna för huvudfunktionerna eller uppsättningen artiklar som du ska lära dig om typsnitt, versionskommentarer, utvecklarguide och andra användbara saker.
---

{{<section codeexample>}}
---
title: C++ kodexempel TTF till WOFF2 konvertering
---



