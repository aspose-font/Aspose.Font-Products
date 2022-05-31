---
title: C# Fonts Conversion
url: /net/conversion/
description: Font conversion functionality. Convert different fonts such as CFF, EOT, WOFF, TTF, and Type 1 with a few lines of C# code via the .NET library.
keywords: cont converter .net, font converter net, c# font coversion
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Fonts Conversion via C#" h2="Convert different fonts like WOFF2, TTF, EOT, CFF and more to build cross-platform .NET applications." >}}

{{% blocks/products/pf/feature-page-summary %}}

.NET font API can easily load, save and convert different fonts such as CFF, OpenType, Type1 and TrueType collections. It provides font data structure along with any glyph as well as encoding information for all the font types representing a mapping between character codes and glyph identifiers. API can render any desired glyph or text as well as special glyphs can be rendered by implementing interfaces using simple graphics functionality like move point, draw line and curve etc. 


Due to diverse nature of gadgets, environments, a few operational systems, and many other areas to use different font formats to serve different purposes such as using different fonts on web pages, applications and publishing. Sometimes there is need to transform one font into another to meet the required display. Few of the supported fonts are TrueType TTF, Web Open Font Format WOFF and WOFF2, Embedded OpenType format EOT, Type 1 and Compact Font Format CFF.

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="TrueType Font to Web Open Font Format version 2.0 Conversion" %}}

API supports different fonts for reading and writing, here is [list](https://docs.aspose.com/font/net/convert/#formats-supported-for-reading-andor-writing) for reading and writing. For considering TTF to WOFF2 conversion, process is load font from any of the supported formats, TrueType Font for the current scenario. Use [SaveToFormat()](https://apireference.aspose.com/font/net/aspose.font/font/methods/savetoformat) method having two parameters output stream and [FontSavingFormats](https://apireference.aspose.com/font/net/aspose.font/fontsavingformats) enumeration for selecting the output font format. Finally call the SaveToFormat() to save fonts into any of the output formats supported, currently Web Open Font Format version 2.0 WOFF2 format.
 
{{% blocks/products/pf/feature-page-code h3="C# Code for TTF to WOFF2 Conversion" %}}

{{< gist "aspose-com-gists" "3d4ec418932bd997550748a6b53e3cc5" "convert-ttf-to-woff2.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="cff-to-ttf cff-to-woff cff-to-woff2 eot-to-ttf eot-to-woff eot-to-woff2 ttf-to-woff type1-to-ttf type1-to-woff type1-to-woff2 woff2-to-ttf woff2-to-woff woff-to-ttf woff-to-woff2" >}}