---
template: true
title: {{i18n.title}}
description: {{i18n.description}}
url: {{i18n.url}}
family: font
platformtag: Java
feature: conversion
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="{{i18n.banner.h1}}" h2="{{i18n.banner.h2}}" >}}

{{% blocks/products/pf/feature-page-summary %}}

<p>{{i18n.overview.p1}}</p>

<p>{{i18n.overview.p2}}</p>

<p>{{i18n.overview.p3}}</p>

{{% /blocks/products/pf/feature-page-summary  %}}


{{% blocks/products/pf/feature-page-section  h2="{{i18n.feature1.title}}" %}}

{{i18n.feature1.item1}}

{{i18n.feature1.item2}}

{{i18n.feature1.item3}}

{{i18n.feature1.item4}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/agp/feature-section >}}
{{< app/font/converter "i18n.codeexample.title" CFF TTF WOFF WOFF2>}}
    // Open {{input lower}} font
    String fontPath = Paths.get(getDataDir(), "{{inputFile}}").toString();
    FontDefinition fontDefinition = new FontDefinition(FontType.{{input upper}}, new FontFileDefinition({{input lower}}, new FileSystemStreamSource(fontPath)));
    Font font = Font.open(fontDefinition);

    // {{output camel}} output settings
    String outPath = Paths.get(getOutputDir(), "{{outputFile}}").toString();
    FileOutputStream outStream = new FileOutputStream(outPath);

    // Convert {{input lower}} to {{output lower}}
    font.SaveToFormat(outStream, FontSavingFormats.{{output upper}});
{{< /app/font/converter >}}
{{< /blocks/products/pf/agp/feature-section>}}
{{< /blocks/products/pf/main-wrap-class>}}

{{< blocks/products/pf/feature-page-options pairs="cff-to-ttf cff-to-woff cff-to-woff2 eot-to-ttf eot-to-woff eot-to-woff2 ttf-to-woff type1-to-ttf type1-to-woff type1-to-woff2 woff2-to-ttf woff2-to-woff woff-to-ttf woff-to-woff2" >}}