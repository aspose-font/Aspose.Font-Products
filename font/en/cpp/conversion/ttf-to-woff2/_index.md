---
title: Convert TTF to WOFF2 | C++ 
description: Convert TTF to WOFF2 Fonts using this C++ API. The Conversion functionality works on Windows and Linux, and in any development environment that supports C++.
metakeywords: c++ TTF to WOFF2, TTF to WOFF2 solutions c++, TTF to WOFF2 font conerter cpp
url: /cpp/conversion/ttf-to-woff2/
family: font
platformtag: cpp
feature: conversion
informat: TTF
outformat: WOFF2
otherformats: WOFF
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Convert TTF to WOFF2 via C++" h2="Convert TTF to WOFF2, WOFF &  vice versa on Windows. When developing applications Aspose.Font for C++ to can be used in any development environment that supports C++.">}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="TTF to WOFF2 Conversion on C++" %}}
1. Open TTF font using [Open](https://reference.aspose.com/font/cpp/class/aspose.font.font#ac2387bf04ccb5bac51cf37984d4ebf33) method
2. Specify the WOFF2 output settings 
3. Convert TTF to WOFF2 using [SaveToFormat](https://reference.aspose.com/font/cpp/class/aspose.font.font#a670ea97404fd72c2e51b0e8c543c8a45) method and pass WOFF2 as [FontSavingFormats](https://reference.aspose.com/font/cpp/namespace/aspose.font#a93d0dcc7c00f5c7027d60e14a5433c74)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Get Started with C++ Font API" %}}
Install from command line as ```nuget install Aspose.Font.Cpp``` or via Package Manager Console of Visual Studio with ```Install-Package Aspose.Font.Cpp```.

Alternatively, get the offline MSI installer or DLLs in a ZIP file from [downloads](https://downloads.aspose.com/font/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< app/font/converter "C++ code example TTF to WOFF2 conversion" TTF WOFF2 WOFF>}}
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