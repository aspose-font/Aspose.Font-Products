---
title: Fonts Conversion | C++
url: /cpp/conversion/
description: Convert fonts with the C++ Font processing library and web applications. Conversion functionality that can work with TTF, WOFF, CFF, EOT and Type 1 fonts.
metakeywords: c++ font conversion, font conversion solutions c++, font conerter cpp
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Fonts Conversion via C++" h2="Convert different fonts like WOFF2, TTF, EOT, CFF and more to build cross-platform applications." >}}

{{% blocks/products/pf/feature-page-summary %}}
C++ font API can easily load, save and convert different fonts such as CFF, OpenType, Type1 and TrueType collections. It provides font data structure along with any glyph as well as encoding information for all the font types representing a mapping between character codes and glyph identifiers. API can render any desired glyph or text as well as special glyphs can be rendered by implementing interfaces using simple graphics functionality like move point, draw line and curve etc. 


Due to diverse nature of gadgets, environments, a few operational systems, and many other areas to use different font formats to serve different purposes such as using different fonts on web pages, applications and publishing. Sometimes there is need to transform one font into another to meet the required display. Few of the supported fonts are TrueType TTF, Web Open Font Format WOFF and WOFF2, Embedded OpenType format EOT, Type 1 and Compact Font Format CFF.

Here you can find the example of [applications](https://products.aspose.app/font/conversion) to convert fonts that is developed using this solution.

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="TrueType Font to Web Open Font Format version 2.0 Conversion" %}}

API supports different fonts for reading and writing, here is [list](https://docs.aspose.com/font/cpp/convert/#formats-supported-for-reading-andor-writing) for reading and writing. For considering TTF to WOFF2 conversion, process is load font from any of the supported formats, TrueType Font for the current scenario. Use [SaveToFormat()](https://reference.aspose.com/font/cpp/class/aspose.font.font#a670ea97404fd72c2e51b0e8c543c8a45) method having two parameters output stream and [FontSavingFormats](https://reference.aspose.com/font/cpp/namespace/aspose.font#a93d0dcc7c00f5c7027d60e14a5433c74) enumeration for selecting the output font format. Finally call the SaveToFormat() to save fonts into any of the output formats supported, currently Web Open Font Format version 2.0 WOFF2 format.

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/agp/feature-section >}}
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
{{< /blocks/products/pf/agp/feature-section>}}
{{< /blocks/products/pf/main-wrap-class>}}

{{< blocks/products/pf/feature-page-options pairs="cff-to-ttf cff-to-woff cff-to-woff2 eot-to-ttf eot-to-woff eot-to-woff2 ttf-to-woff type1-to-ttf type1-to-woff type1-to-woff2 woff2-to-ttf woff2-to-woff woff-to-ttf woff-to-woff2" >}}



