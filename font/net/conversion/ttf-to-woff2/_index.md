---
title: Convert TTF to WOFF2 with .NET 
description: Convert Fonts using .NET API on Windows
url: /net/conversion/ttf-to-woff2/
family: font
platformtag: net
feature: conversion
informat: TTF
outformat: WOFF2
otherformats: WOFF
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Convert TTF to WOFF2 via C#" h2="Convert TTF to WOFF2, WOFF &  vice versa on Windows">}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="TTF to WOFF2 Conversion on .NET" %}}
1. Open TTF font using [Open](https://apireference.aspose.com/font/net/aspose.font/font/methods/open/index) method
2. Specify the WOFF2 output settings 
3. Convert TTF to WOFF2 using [SaveToFormat](https://apireference.aspose.com/font/net/aspose.font/font/methods/savetoformat) method and pass WOFF2 as [FontSavingFormats](https://apireference.aspose.com/font/net/aspose.font/fontsavingformats)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Get Started with .NET Font API" %}}
Install from command line as ```nuget install Aspose.Font``` or via Package Manager Console of Visual Studio with ```Install-Package Aspose.Font```.

Alternatively, get the offline MSI installer or DLLs in a ZIP file from [downloads](https://downloads.aspose.com/font/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title=".NET C# Code for TTF to WOFF2 Conversion" gistPath="" %}}
```cs
// Open TTF font
FontDefinition fontDefinition = new FontDefinition(FontType.TTF, new FontFileDefinition(new FileSystemStreamSource("input.ttf")));
Aspose.Font.Font font = Aspose.Font.Font.Open(fontDefinition);
// WOFF2 output settings
FileStream outStream = File.Create("output.woff2");
//Convert TTF to WOFF2
font.SaveToFormat(outStream, FontSavingFormats.WOFF2);
```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}