---
title: Convert TYPE1 to WOFF2 | .NET 
description: Convert TYPE1 to WOFF2 using .NET API on Windows. Integrate this native TYPE1 to WOFF2 font conversion functionality into your own solution.
keywords: type1 to woff2 api, tpe12woff2 solution, type1 to woff2 net
url: /net/conversion/type1-to-woff2/
family: font
platformtag: net
feature: conversion
informat: TYPE1
outformat: WOFF2
otherformats: TTF WOFF
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Convert TYPE1 to WOFF2 via C#" h2="Convert TYPE1 to WOFF2, TTF & WOFF smoothly on Windows and Linux. Create your own font converter by means of this Font API solution for .NET.">}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="TYPE1 to WOFF2 Conversion on .NET" %}}
1. Open TYPE1 font using [Open](https://apireference.aspose.com/font/net/aspose.font/font/methods/open/index) method
2. Specify the WOFF2 output settings 
3. Convert TYPE1 to WOFF2 using [SaveToFormat](https://apireference.aspose.com/font/net/aspose.font/font/methods/savetoformat) method and pass WOFF2 as [FontSavingFormats](https://apireference.aspose.com/font/net/aspose.font/fontsavingformats)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Get Started with .NET Font API" %}}
Install from command line as ```nuget install Aspose.Font``` or via Package Manager Console of Visual Studio with ```Install-Package Aspose.Font```.

Alternatively, get the offline MSI installer or DLLs in a ZIP file from [downloads](https://downloads.aspose.com/font/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< app/font/converter ".NET C# Code for Type1 to WOFF2 Conversion" Type1 WOFF2 TTF WOFF>}}
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

{{< blocks/products/pf/support-learning-resources >}}
{{< blocks/products/pf/slr-tab tabTitle="Learning Resources" tabId="resources" >}}
{{< blocks/products/pf/slr-element name="Documentation" href="https://docs.aspose.com/font/net" >}}
{{< blocks/products/pf/slr-element name="Source Code" href="https://github.com/aspose-font/Aspose.Font-for-.NET" >}}
{{< blocks/products/pf/slr-element name="API References" href="https://apireference.aspose.com/font/net" >}}
{{< blocks/products/pf/slr-element name="Tutorial Videos" href="https://www.youtube.com/user/asposevideo" >}}
{{< /blocks/products/pf/slr-tab >}}

{{< blocks/products/pf/slr-tab tabTitle="Product Support" tabId="support" >}}
{{< blocks/products/pf/slr-element name="Free Support" href="https://forum.aspose.com/c/font" >}}
{{< blocks/products/pf/slr-element name="Paid Support" href="https://helpdesk.aspose.com/" >}}
{{< blocks/products/pf/slr-element name="Blog" href="https://blog.aspose.com/category/font/" >}}
{{< /blocks/products/pf/slr-tab >}}

{{< blocks/products/pf/slr-tab tabTitle="Why Aspose.Font for .NET?" tabId="success-stories" >}}
{{< blocks/products/pf/slr-element name="Customers List" href="https://company.aspose.com/customers" >}}
{{< blocks/products/pf/slr-element name="Success Stories" href="https://company.aspose.com/customers/success-stories/" >}}
{{< /blocks/products/pf/slr-tab >}}

{{< /blocks/products/pf/support-learning-resources >}}

{{< /blocks/products/pf/main-wrap-class >}}