---
title: Convert EOT to WOFF2 with C++ 
description: Convert Fonts using C++ API on Windows
url: /cpp/conversion/eot-to-woff2/
family: font
platformtag: cpp
feature: conversion
informat: EOT
outformat: WOFF2
otherformats: TTF WOFF
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Convert EOT to WOFF2 via C++" h2="Convert EOT to TTF, WOFF & WOFF2 easily on Windows">}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="EOT to WOFF2 Conversion on C++" %}}
1. Open EOT font using [Open](https://reference.aspose.com/font/cpp/class/aspose.font.font#ac2387bf04ccb5bac51cf37984d4ebf33) method
2. Specify the WOFF2 output settings 
3. Convert EOT to WOFF2 using [SaveToFormat](https://reference.aspose.com/font/cpp/class/aspose.font.font#a670ea97404fd72c2e51b0e8c543c8a45) method and pass WOFF2 as [FontSavingFormats](https://reference.aspose.com/font/cpp/namespace/aspose.font#a93d0dcc7c00f5c7027d60e14a5433c74)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Get Started with C++ Font API" %}}
Install from command line as ```nuget install Aspose.Font.Cpp``` or via Package Manager Console of Visual Studio with ```Install-Package Aspose.Font.Cpp```.

Alternatively, get the offline MSI installer or DLLs in a ZIP file from [downloads](https://downloads.aspose.com/font/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< app/font/converter "C++ code example EOT to WOFF2 conversion" EOT WOFF2 TTF WOFF>}}
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