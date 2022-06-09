---
title: Convert WOFF2 to WOFF | C++  
description: Convert WOFF2 to TTF Fonts using this C++ API. The Conversion functionality works on Windows and Linux, and in any development environment that supports C++.
metakeywords: c++ WOFF2 to WOFF, WOFF2 to WOFF solutions c++, WOFF2 to WOFF font conerter cpp
url: /cpp/conversion/woff2-to-woff/
family: font
platformtag: cpp
feature: conversion
informat: WOFF2
outformat: WOFF
otherformats: TTF
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Convert WOFF2 to WOFF via C++" h2="Convert WOFF2 to WOFF, TTF &  vice versa on Windows. When developing applications Aspose.Font for C++ to can be used in any development environment that supports C++">}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="WOFF2 to WOFF Conversion on C++" %}}
1. Open WOFF2 font using [Open](https://reference.aspose.com/font/cpp/class/aspose.font.font#ac2387bf04ccb5bac51cf37984d4ebf33) method
2. Specify the WOFF output settings 
3. Convert WOFF2 to WOFF using [SaveToFormat](https://reference.aspose.com/font/cpp/class/aspose.font.font#a670ea97404fd72c2e51b0e8c543c8a45) method and pass WOFF as [FontSavingFormats](https://reference.aspose.com/font/cpp/namespace/aspose.font#a93d0dcc7c00f5c7027d60e14a5433c74)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Get Started with C++ Font API" %}}
Install from command line as ```nuget install Aspose.Font.Cpp``` or via Package Manager Console of Visual Studio with ```Install-Package Aspose.Font.Cpp```.

Alternatively, get the offline MSI installer or DLLs in a ZIP file from [downloads](https://downloads.aspose.com/font/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< app/font/converter "C++ code example WOF2F to WOFF conversion" WOFF2 WOFF TTF>}}
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