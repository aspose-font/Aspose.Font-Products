---
title: Convert TYPE1 to TTF | C++ 
description: Convert TYPE1 to TTF Fonts using this C++ API. The Conversion functionality works on Windows and Linux, and in any development environment that supports C++.
metakeywords: c++ TYPE1 to TTF, TYPE1 to TTF solutions c++, TYPE1 to TTF font conerter cpp
url: /cpp/conversion/type1-to-ttf/
family: font
platformtag: cpp
feature: conversion
informat: TYPE1
outformat: TTF
otherformats: WOFF WOFF2
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Convert TYPE1 to TTF via C++" h2="Convert TYPE1 to TTF, WOFF & WOFF2 easily on Windows. When developing applications Aspose.Font for C++ to can be used in any development environment that supports C++">}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="TYPE1 to TTF Conversion on C++" %}}
1. Open TYPE1 font using [Open](https://reference.aspose.com/font/cpp/class/aspose.font.font#ac2387bf04ccb5bac51cf37984d4ebf33) method
2. Specify the TTF output settings 
3. Convert TYPE1 to TTF using [SaveToFormat](https://reference.aspose.com/font/cpp/class/aspose.font.font#a670ea97404fd72c2e51b0e8c543c8a45) method and pass TTF as [FontSavingFormats](https://reference.aspose.com/font/cpp/namespace/aspose.font#a93d0dcc7c00f5c7027d60e14a5433c74)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Get Started with C++ Font API" %}}
Install from command line as ```nuget install Aspose.Font.Cpp``` or via Package Manager Console of Visual Studio with ```Install-Package Aspose.Font.Cpp```.

Alternatively, get the offline MSI installer or DLLs in a ZIP file from [downloads](https://downloads.aspose.com/font/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< app/font/converter "C++ code example Type1 to TTF conversion" Type1 TTF WOFF WOFF2>}}
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

{{< blocks/products/pf/support-learning-resources >}}
{{< blocks/products/pf/slr-tab tabTitle="Learning Resources" tabId="resources" >}}
{{< blocks/products/pf/slr-element name="Documentation" href="https://docs.aspose.com/font/cpp" >}}
{{< blocks/products/pf/slr-element name="Source Code" href="https://github.com/aspose-font/Aspose.Font-for-C" >}}
{{< blocks/products/pf/slr-element name="API References" href="https://reference.aspose.com/font/cpp" >}}
{{< blocks/products/pf/slr-element name="Tutorial Videos" href="https://www.youtube.com/user/asposevideo" >}}
{{< /blocks/products/pf/slr-tab >}}

{{< blocks/products/pf/slr-tab tabTitle="Product Support" tabId="support" >}}
{{< blocks/products/pf/slr-element name="Free Support" href="https://forum.aspose.com/c/font" >}}
{{< blocks/products/pf/slr-element name="Paid Support" href="https://helpdesk.aspose.com/" >}}
{{< blocks/products/pf/slr-element name="Blog" href="https://blog.aspose.com/category/font/" >}}
{{< /blocks/products/pf/slr-tab >}}

{{< blocks/products/pf/slr-tab tabTitle="Why Aspose.Font for C++?" tabId="success-stories" >}}
{{< blocks/products/pf/slr-element name="Customers List" href="https://company.aspose.com/customers" >}}
{{< blocks/products/pf/slr-element name="Success Stories" href="https://company.aspose.com/customers/success-stories/" >}}
{{< /blocks/products/pf/slr-tab >}}

{{< /blocks/products/pf/support-learning-resources >}}

{{< /blocks/products/pf/main-wrap-class >}}