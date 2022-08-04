---
translation: true
template: /_templates/conversion-java.md
title: Font Conversion API | Java 
url: /java/conversion/
description: Java Font Files Conversion functionality. Convert different fonts such as CFF, EOT, WOFF, TTF, and Type 1 with a few lines of Java code.
keywords: convert fonts java, font conversion Java, font coverter java
family: font
platformtag: java
feature: conversion
---

{{<section banner>}}
---
h1: Convert Fonts
h2: Font format converter API for Java. Convert WOFF2, TTF, EOT, and CFF fonts.
---

{{<section overview>}}
---
p1: Java font API can easily load, save and convert different fonts such as CFF, OpenType, Type1, and TrueType collections. It provides font data structure along with any glyph as well as encoding information for all the font types representing a mapping between character codes and glyph identifiers. API can render any desired glyph or text, as well as special glyphs, which can be rendered by implementing interfaces using simple graphics functionality like move point, draw line, and curve, etc.
p2: "Due to the diverse nature of gadgets, environments, a few operational systems, and many other areas to use different font formats to serve different purposes such as using different fonts on web pages, applications, and publishing. Sometimes there is a need to transform one font into another to meet the required display. "
p3: "We offer you Java Api Solution that supports the next fonts as output formats: TrueType (TTF), Web Open Font Format (WOFF and WOFF2), Embedded OpenType format (EOT), Type 1, and Compact Font Format (CFF)."
---

{{<section feature1>}}
---
title: TrueType Font to Web Open Font Format version 2.0 Conversion.
item1: API supports different fonts for reading and writing, here is the [list](https://docs.aspose.com/font/java/convert/#formats-supported-for-reading-andor-writing) for reading and writing. For considering TTF to WOFF2 conversion, the process is to load a font from any of the supported formats, TrueType Font for the current scenario. Use the [*SaveToFormat()*](https://apireference.aspose.com/font/java/com.aspose.font/Font#saveToFormat-java.io.OutputStream-com.aspose.font.FontSavingFormats-) Method of [Font class](https://apireference.aspose.com/font/java/com.aspose.font/Font#save-java.lang.String-) having two parameters output stream and [*FontSavingFormats*](https://apireference.aspose.com/font/java/com.aspose.font/FontSavingFormats) Enumeration for selecting the output font format. 
item2: Finally, call the SaveToFormat() to save fonts into any of the output formats supported, currently Web Open Font Format version 2.0 WOFF2 format.
item3: To see this functionality realized in an actual cross-platform application go to [Aspose Font Converter app](https://products.aspose.app/font/conversion). There you can also find many more [API solutions](https://products.aspose.app/font/applications) to work with fonts and text.
item4: Go to the [Documentation](https://docs.aspose.com/font/net/) to get all the needed information to start working with the solution, like the Tutorials for the main features or the set of articles to teach you about font, Release Notes, Developer Guide, and other useful things.
---

{{<section codeexample>}}
---
title: Java Code for CFF to TTF Conversion
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