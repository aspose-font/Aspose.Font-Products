---
title: Convert TYPE1 to TTF with .NET 
description: Convert TYPE1 to TTF using .NET API on Windows. Integrate this native TYPE1 to TTF font conversion functionality into your own solution.
keywords: type1 to ttf api, tpe12ttf solution, type1 to ttf net
url: /net/conversion/type1-to-ttf/
family: font
platformtag: net
feature: conversion
informat: TYPE1
outformat: TTF
otherformats: WOFF WOFF2
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Convert TYPE1 to TTF via C#" h2="Convert TYPE1 to TTF, WOFF & WOFF2 easily on Windows">}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="TYPE1 to TTF Conversion on .NET" %}}
1. Open TYPE1 font using [Open](https://apireference.aspose.com/font/net/aspose.font/font/methods/open/index) method
2. Specify the TTF output settings 
3. Convert TYPE1 to TTF using [SaveToFormat](https://apireference.aspose.com/font/net/aspose.font/font/methods/savetoformat) method and pass TTF as [FontSavingFormats](https://apireference.aspose.com/font/net/aspose.font/fontsavingformats)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Get Started with .NET Font API" %}}
Install from command line as ```nuget install Aspose.Font``` or via Package Manager Console of Visual Studio with ```Install-Package Aspose.Font```.

Alternatively, get the offline MSI installer or DLLs in a ZIP file from [downloads](https://downloads.aspose.com/font/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< app/font/converter ".NET C# Code for Type1 to TTF Conversion" Type1 TTF WOFF WOFF2>}}
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