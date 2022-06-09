---
title: Convert EOT to TTF with Java 
description: Convert EOT to TTF using Java API on Windows. Integrate this native EOT to TTF font conversion functionality into your own solution.
keywords: eot to ttf java api, eot2ttf java solution, eot to ttf java
url: /java/conversion/eot-to-ttf/
family: font
platformtag: java
feature: conversion
informat: EOT
outformat: TTF
otherformats: WOFF WOFF2
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Convert EOT to TTF via Java" h2="EOT to TTF conversion  with just few lines of code within Java based applications.">}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="How to Convert EOT to TTF" %}}
1. Open EOT font using [open](https://apireference.aspose.com/font/java/com.aspose.font/Font#open-com.aspose.font.FontDefinition-) method
2. Specify the TTF output settings 
3. Convert EOT to TTF using [saveToFormat](https://apireference.aspose.com/font/java/com.aspose.font/Font#saveToFormat-java.io.OutputStream-com.aspose.font.FontSavingFormats-) method and pass TTF as [FontSavingFormats](https://apireference.aspose.com/font/java/com.aspose.font/FontSavingFormats) as parameters
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Conversion Requirement" %}}
To proceed for EOT to TTF conversion, Java Font API is the main requirement.
- Get Font API directly from a [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-font) for Java based project and include libraries in your pom.xml.
- Alternatively, you can get a ZIP file from [downloads](https://downloads.aspose.com/font/java).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< app/font/converter "Java Code for EOT to TTF Conversion" EOT TTF WOFF WOFF2>}}
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

{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}