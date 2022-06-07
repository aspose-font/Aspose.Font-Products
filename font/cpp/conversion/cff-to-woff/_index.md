---
title: Convert CFF to WOFF with C++ 
description: Convert Fonts using C++ API on Windows
url: /cpp/conversion/cff-to-woff/
family: font
platformtag: cpp
feature: conversion
informat: CFF
outformat: WOFF
otherformats: TTF WOFF2
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Convert CFF to WOFF via C++" h2="Convert CFF to WOFF, TTF & WOFF2 effortlessly on Windows">}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="CFF to WOFF Conversion on C++" %}}
1. Open CFF font using [Open](https://reference.aspose.com/font/cpp/class/aspose.font.font#ac2387bf04ccb5bac51cf37984d4ebf33) method
2. Specify the WOFF output settings 
3. Convert CFF to WOFF using [SaveToFormat](https://reference.aspose.com/font/cpp/class/aspose.font.font#a670ea97404fd72c2e51b0e8c543c8a45) method and pass WOFF as [FontSavingFormats](https://reference.aspose.com/font/cpp/namespace/aspose.font#a93d0dcc7c00f5c7027d60e14a5433c74)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Get Started with C++ Font API" %}}
Install from command line as ```nuget install Aspose.Font.Cpp``` or via Package Manager Console of Visual Studio with ```Install-Package Aspose.Font.Cpp```.

Alternatively, get the offline MSI installer or DLLs in a ZIP file from [downloads](https://downloads.aspose.com/font/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< app/font/converter "C++ code example CFF to WOFF conversion" CFF WOFF TTF WOFF2>}}
    using namespace System;
    using namespace Aspose::Font::Sources;
    using namespace Aspose::Font::Ttf;
    using namespace Aspose::Font;

    // Open ttf font
    SharedPtr<FontFileDefinition> fontFileDefinition = MakeObject<FileSystemStreamSource>(u"{{inputFile}}");
    SharedPtr<FontDefinition> fontDefinition = MakeObject<FontDefinition>(FontType::{{input}}, fontFileDefinition);
    SharedPtr<Font> font = Font::Open(fontDefinition);
    
    // Woff output settings
    SharedPtr<IO::FileStream> outStream = IO::File::Create(u"{{outputFile}}");
    
    // Convert ttf to woff
    font-&gt;SaveToFormat(outStream, FontSavingFormats::{{output upper}});
{{< /app/font/converter >}}

{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}