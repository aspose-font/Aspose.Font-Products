---
title: Convert EOT to WOFF with .NET 
description: Convert Fonts using .NET API on Windows
url: /net/conversion/eot-to-woff/
family: font
platformtag: net
feature: conversion
informat: EOT
outformat: WOFF
otherformats: TTF WOFF2
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Convert EOT to WOFF via C#" h2="Convert EOT to WOFF, TTF & WOFF2 easily on Windows">}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="EOT to WOFF Conversion on .NET" %}}
1. Open EOT font using [Open](https://apireference.aspose.com/font/net/aspose.font/font/methods/open/index) method
2. Specify the WOFF output settings 
3. Convert EOT to WOFF using [SaveToFormat](https://apireference.aspose.com/font/net/aspose.font/font/methods/savetoformat) method and pass WOFF as [FontSavingFormats](https://apireference.aspose.com/font/net/aspose.font/fontsavingformats)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Get Started with .NET Font API" %}}
Install from command line as ```nuget install Aspose.Font``` or via Package Manager Console of Visual Studio with ```Install-Package Aspose.Font```.

Alternatively, get the offline MSI installer or DLLs in a ZIP file from [downloads](https://downloads.aspose.com/font/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title=".NET C# Code for EOT to WOFF Conversion" gistPath="" %}}
```cs
// Open EOT font
FontDefinition fontDefinition = new FontDefinition(FontType.EOT, new FontFileDefinition(new FileSystemStreamSource("input.eot")));
Aspose.Font.Font font = Aspose.Font.Font.Open(fontDefinition);
// WOFF output settings
FileStream outStream = File.Create("output.woff");
//Convert EOT to WOFF
font.SaveToFormat(outStream, FontSavingFormats.WOFF);
```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}