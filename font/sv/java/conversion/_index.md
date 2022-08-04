﻿---
translation: true
template: /_templates/conversion-java.md
title: Font Conversion API | Java
url: /java/conversion/
description: Java Font Files Conversion funktionalitet. Konvertera olika typsnitt som CFF, EOT, WOFF, TTF och Type 1 med några rader Java-kod.
keywords: konvertera teckensnitt java, teckensnittskonvertering Java, teckensnittscover java
family: font
platformtag: java
feature: conversion
---

{{<section banner>}}
---
h1: Konvertera teckensnitt
h2: Font format converter API för Java. Konvertera WOFF2-, TTF-, EOT- och CFF-teckensnitt.
---

{{<section overview>}}
---
p1: Java font API kan enkelt ladda, spara och konvertera olika typsnitt som CFF-, OpenType-, Type1- och TrueType-samlingar. Den tillhandahåller teckensnittsdatastruktur tillsammans med valfri glyf samt kodningsinformation för alla teckensnittstyper som representerar en mappning mellan teckenkoder och glyfidentifierare. API kan rendera alla önskade glyf eller text, såväl som speciella glyf, som kan renderas genom att implementera gränssnitt med enkla grafikfunktioner som flytta punkt, ritlinje och kurva, etc.
p2: "På grund av den mångfaldiga karaktären hos prylar, miljöer, ett fåtal operativa system och många andra områden för att använda olika teckensnittsformat för att tjäna olika syften som att använda olika typsnitt på webbsidor, applikationer och publicering. Ibland finns det ett behov av att omvandla ett teckensnitt till ett annat för att möta den önskade visningen."
p3: "Vi erbjuder dig Java Api-lösning som stöder nästa typsnitt som utdataformat: TrueType (TTF), Web Open Font Format (WOFF och WOFF2), Embedded OpenType-format (EOT), Type 1 och Compact Font Format (CFF)."
---

{{<section feature1>}}
---
title: TrueType Font to Web Open Font Format version 2.0 Conversion.
item1: API stöder olika typsnitt för läsning och skrivning, här är [listan](https://docs.aspose.com/font/java/convert/#formats-supported-for-reading-andor-writing) för läsning och skrivning. För att överväga konvertering av TTF till WOFF2, är processen att ladda ett teckensnitt från något av de format som stöds, TrueType Font för det aktuella scenariot. Använd metoden [*SaveToFormat()*](https://reference.aspose.com/font/java/com.aspose.font/Font#saveToFormat-java.io.OutputStream-com.aspose.font.FontSavingFormats-) av [Font class](https://reference.aspose.com/font/java/com.aspose.font/Font#save-java.lang.String-) med två parametrar output stream och [*FontSavingFormats*](https://reference.aspose.com/font/java/com.aspose.font/FontSavingFormats) Uppräkning för val av utdatateckensnittsformat.
item2: Slutligen, anrop SaveToFormat() för att spara teckensnitt i något av de utdataformat som stöds, för närvarande Web Open Font Format version 2.0 WOFF2-format.
item3: Gå till [Aspose Font Converter-appen](https://products.aspose.app/font/conversion) för att se den här funktionen realiserad i en verklig plattformsoberoende applikation. Där kan du också hitta många fler [API-lösningar](https://products.aspose.app/font/applications) för att arbeta med typsnitt och text.
item4: Gå till [Dokumentation](https://docs.aspose.com/font/net/) för att få all nödvändig information för att börja arbeta med lösningen, som handledningarna för huvudfunktionerna eller uppsättningen artiklar som du ska lära dig om typsnitt, versionskommentarer, utvecklarguide och andra användbara saker.
---

{{<section codeexample>}}
---
title: Java-kod för CFF till TTF-konvertering
---

{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/agp/feature-section >}}
{{< app/font/converter "Java Code for CFF to TTF Conversion" CFF TTF WOFF WOFF2>}}
    // Open {{input lower}} font
    String fontPath = Paths.get(getDataDir(), "{{inputFile}}").toString();
    FontDefinition fontDefinition = new FontDefinition(FontType.{{input upper}}, new FontFileDefinition({{input lower}}, new FileSystemStreamSource(fontPath)));
    Font font = Font.open(fontDefinition);

    // {{output camel}} output settings
    String outPath = Paths.get(getOutputDir(), "{{outputFile}}").toString();
    FileOutputStream outStream = new FileOutputStream(outPath);

    // Convert {{input lower}} to {{output lower}}
    font.SaveToFormat(outStream, FontSavingFormats.{{output upper}});
{{< /app/font/converter >}}
{{< /blocks/products/pf/agp/feature-section>}}
{{< /blocks/products/pf/main-wrap-class>}}

{{< blocks/products/pf/feature-page-options pairs="cff-to-ttf cff-to-woff cff-to-woff2 eot-to-ttf eot-to-woff eot-to-woff2 ttf-to-woff type1-to-ttf type1-to-woff type1-to-woff2 woff2-to-ttf woff2-to-woff woff-to-ttf woff-to-woff2" >}}