---
title: Convert TYPE1 to WOFF | Java 
description: Convert TYPE1 to WOFF using Java API on Windows and Linux. Integrate this native TYPE1 to WOFF font conversion functionality into your own solution.
keywords: type1 to woff java api, type12woff java solution, type1 to woff java
url: /java/conversion/type1-to-woff/
family: font
platformtag: java
feature: conversion
informat: TYPE1
outformat: WOFF
otherformats: TTF WOFF2
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Convert TYPE1 to WOFF via Java" h2="TYPE1 to WOFF conversion with just few lines of code within Java based applications. Font API Solution for Java that is really easy to integrate into your product.">}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="How to Convert TYPE1 to WOFF" %}}
1. Open TYPE1 font using [open](https://apireference.aspose.com/font/java/com.aspose.font/Font#open-com.aspose.font.FontDefinition-) method
2. Specify the WOFF output settings 
3. Convert TYPE1 to WOFF using [saveToFormat](https://apireference.aspose.com/font/java/com.aspose.font/Font#saveToFormat-java.io.OutputStream-com.aspose.font.FontSavingFormats-) method and pass WOFF as [FontSavingFormats](https://apireference.aspose.com/font/java/com.aspose.font/FontSavingFormats) as parameters
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Conversion Requirement" %}}
To proceed for TYPE1 to WOFF conversion, Java Font API is the main requirement.
- Get Font API directly from a [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-font) for Java based project and include libraries in your pom.xml.
- Alternatively, you can get a ZIP file from [downloads](https://downloads.aspose.com/font/java).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< app/font/converter "Java Code for Type1 to WOFF Conversion" Type1 WOFF TTF WOFF2>}}
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
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< /blocks/products/pf/main-container >}}

{{< blocks/products/pf/support-learning-resources >}}
{{< blocks/products/pf/slr-tab tabTitle="Learning Resources" tabId="resources" >}}
{{< blocks/products/pf/slr-element name="Documentation" href="https://docs.aspose.com/font/java" >}}
{{< blocks/products/pf/slr-element name="Source Code" href="https://github.com/aspose-font/Aspose.Font-for-Java" >}}
{{< blocks/products/pf/slr-element name="API References" href="https://apireference.aspose.com/font/java" >}}
{{< blocks/products/pf/slr-element name="Tutorial Videos" href="https://www.youtube.com/user/asposevideo" >}}
{{< /blocks/products/pf/slr-tab >}}

{{< blocks/products/pf/slr-tab tabTitle="Product Support" tabId="support" >}}
{{< blocks/products/pf/slr-element name="Free Support" href="https://forum.aspose.com/c/font" >}}
{{< blocks/products/pf/slr-element name="Paid Support" href="https://helpdesk.aspose.com/" >}}
{{< blocks/products/pf/slr-element name="Blog" href="https://blog.aspose.com/category/font/" >}}
{{< /blocks/products/pf/slr-tab >}}

{{< blocks/products/pf/slr-tab tabTitle="Why Aspose.Font for Java?" tabId="success-stories" >}}
{{< blocks/products/pf/slr-element name="Customers List" href="https://company.aspose.com/customers" >}}
{{< blocks/products/pf/slr-element name="Success Stories" href="https://company.aspose.com/customers/success-stories/" >}}
{{< /blocks/products/pf/slr-tab >}}

{{< /blocks/products/pf/support-learning-resources >}}

{{< /blocks/products/pf/main-wrap-class >}}