---
title: Convert CFF to WOFF with .NET 
description: Convert CFF to WOFF using .NET API on Windows. Integrate this native CFF to WOFF font conversion functionality into your own solution.
keywords: cff to woff api, cff2woff solution, cff to woff net
url: /net/conversion/cff-to-woff/
family: font
platformtag: net
feature: conversion
informat: CFF
outformat: WOFF
otherformats: TTF WOFF2
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Convert CFF to WOFF via C#" h2="Convert CFF to WOFF, TTF & WOFF2 effortlessly on Windows">}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="CFF to WOFF Conversion on .NET" %}}
1. Open CFF font using [Open](https://apireference.aspose.com/font/net/aspose.font/font/methods/open/index) method
2. Specify the WOFF output settings 
3. Convert CFF to WOFF using [SaveToFormat](https://apireference.aspose.com/font/net/aspose.font/font/methods/savetoformat) method and pass WOFF as [FontSavingFormats](https://apireference.aspose.com/font/net/aspose.font/fontsavingformats)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Get Started with .NET Font API" %}}
Install from command line as ```nuget install Aspose.Font``` or via Package Manager Console of Visual Studio with ```Install-Package Aspose.Font```.

Alternatively, get the offline MSI installer or DLLs in a ZIP file from [downloads](https://downloads.aspose.com/font/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< app/font/converter ".NET C# Code for CFF to WOFF Conversion" CFF WOFF TTF WOFF2>}}
    // Open {{input lower}} font
    string fontPath = Path.Combine(DataDir, "{{inputFile}}");
    FontDefinition fontDefinition = new FontDefinition(FontType.{{input upper}}, new FontFileDefinition(new FileSystemStreamSource(fontPath)));
    Font font = Font.Open(fontDefinition);
    
    // {{output camel}} output settings
    string outPath = Path.Combine(OutputDir, "{{outputFile}}");
    FileStream outStream = File.Create(outPath);
    
    // Convert {{input lower}} to {{output lower}}
    font.SaveToFormat(outStream, FontSavingFormats.{{output upper}});
{{< /app/font/converter >}}

{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}