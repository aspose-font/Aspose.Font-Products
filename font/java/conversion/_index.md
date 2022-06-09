---
title: Java Fonts Conversion
url: /java/conversion/
description: Java Font Files Conversion functionality. Convert different fonts such as CFF, EOT, WOFF, TTF, and Type 1 with a few lines of Java code.
keywords: convert fonts java, font conversion Java, font coverter java
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Fonts Conversion via Java" h2="Convert different fonts like WOFF2, TTF, EOT, CFF and more to build cross-platform Java applications." >}}

{{% blocks/products/pf/feature-page-summary %}}

Java font API deals all font related properties such as style, variant, weight, size/line height, family and types. Moreover it can easily read, save and convert various fonts such as OpenType, Type1 CFF, and TrueType collections. Its rendering subsystem helps end-users for rendering any desired glyph or text. Depending on application nature either it's a web page, applications or there is need of publishing, Developers have to transform one font into another to meet the required display and view. Few of the supported fonts are  Embedded OpenType format EOT, Type 1 and Compact Font Format CFF, TrueType TTF, Web Open Font Format WOFF and WOFF2.

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Compact Font Format CFF to TrueType Font TTF Conversion" %}}

API supports various fonts for reading and writing, here is [list](https://docs.aspose.com/font/java/convert/#formats-supported-for-reading-andor-writing) for reading and writing. For considering CFF to TTF conversion, process is load font from any of the supported formats, Compact Font Format CFF for the current scenario. Use [saveToFormat()](https://apireference.aspose.com/font/java/com.aspose.font/Font#saveToFormat-java.io.OutputStream-com.aspose.font.FontSavingFormats-) method of [Font class](https://apireference.aspose.com/font/java/com.aspose.font/Font#save-java.lang.String-) having two parameters output stream and [FontSavingFormats](https://apireference.aspose.com/font/java/com.aspose.font/FontSavingFormats) enumeration for selecting the output font format. Finally call the saveToFormat() to save fonts into any of the output formats supported, currently TrueType Font TTF format.
 
{{% /blocks/products/pf/feature-page-section %}}

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