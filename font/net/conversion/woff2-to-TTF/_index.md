---
title: Convert WOFF2 to TTF with .NET 
description: Convert Fonts using .NET API on Windows
url: /net/conversion/woff2-to-TTF/
family: font
platformtag: net
feature: conversion
informat: WOFF2
outformat: TTF
otherformats: WOFF
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Convert WOFF2 to TTF via C#" h2="Convert WOFF2 to TTF, WOFF &  vice versa on Windows">}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="WOFF2 to TTF Conversion on .NET" %}}
1. Open WOFF2 font using [Open](https://apireference.aspose.com/font/net/aspose.font/font/methods/open/index) method
2. Specify the TTF output settings 
3. Convert WOFF2 to TTF using [SaveToFormat](https://apireference.aspose.com/font/net/aspose.font/font/methods/savetoformat) method and pass TTF as [FontSavingFormats](https://apireference.aspose.com/font/net/aspose.font/fontsavingformats)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Get Started with .NET Font API" %}}
Install from command line as ```nuget install Aspose.Font``` or via Package Manager Console of Visual Studio with ```Install-Package Aspose.Font```.

Alternatively, get the offline MSI installer or DLLs in a ZIP file from [downloads](https://downloads.aspose.com/font/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title=".NET C# Code for WOFF2 to TTF Conversion" gistPath="" %}}
```cs
// Open WOFF2 font
FontDefinition fontDefinition = new FontDefinition(FontType.WOFF2, new FontFileDefinition(new FileSystemStreamSource("input.woff2")));
Aspose.Font.Font font = Aspose.Font.Font.Open(fontDefinition);
// TTF output settings
FileStream outStream = File.Create("output.ttf");
//Convert WOFF2 to TTF
font.SaveToFormat(outStream, FontSavingFormats.TTF);
```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}