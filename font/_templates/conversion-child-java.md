---
template: true
title: {{i18n.title}}
description: {{i18n.description}}
url: {{i18n.url}}
family: font
platformtag: java
feature: conversion
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="{{i18n.banner.h1}}" h2="{{i18n.banner.h2}}">}}

{{% blocks/products/pf/feature-page-summary %}}

<p>{{i18n.overview.p1}}</p>
<p>{{i18n.overview.p2}}</p>
<p>{{i18n.overview.p3}}</p>

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="{{i18n.feature1.title}}" %}}
{{i18n.feature1.item1}}
1. {{i18n.feature1.item2}}
1. {{i18n.feature1.item3}}
1. {{i18n.feature1.item4}}
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="{{i18n.feature2.title}}" %}}
{{i18n.feature2.item1}}
1. {{i18n.feature2.item2}}
1. {{i18n.feature2.item3}}
1. {{i18n.feature2.item4}}
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< app/font/converter "{{i18n.feature1.title}}" CFF WOFF TTF WOFF2 >}}
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

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/support-learning-resources >}}
{{< blocks/products/pf/slr-tab tabTitle="{{<import path="/{{lang}}/partials/_content.md" section="learningresources.tabTitle">}}" tabId="resources" >}}
{{< blocks/products/pf/slr-element name="{{<import path="/{{lang}}/partials/_content.md" section="learningresources.name1">}}" href="https://docs.aspose.com/font/java/" >}}
{{< blocks/products/pf/slr-element name="{{<import path="/{{lang}}/partials/_content.md" section="learningresources.name2">}}" href="https://github.com/aspose-font/Aspose.Font-for-Java" >}}
{{< blocks/products/pf/slr-element name="{{<import path="/{{lang}}/partials/_content.md" section="learningresources.name3">}}" href="https://reference.aspose.com/font/java" >}}
{{< /blocks/products/pf/slr-tab >}}

{{< blocks/products/pf/slr-tab tabTitle="{{<import path="/{{lang}}/partials/_content.md" section="support.tabTitle">}}" tabId="support" >}}
{{< blocks/products/pf/slr-element name="{{<import path="/{{lang}}/partials/_content.md" section="support.name1">}}" href="https://forum.aspose.com/c/font" >}}
{{< blocks/products/pf/slr-element name="{{<import path="/{{lang}}/partials/_content.md" section="support.name2">}}" href="https://helpdesk.aspose.com/" >}}
{{< blocks/products/pf/slr-element name="{{<import path="/{{lang}}/partials/_content.md" section="support.name3">}}" href="https://blog.aspose.com/category/font/" >}}
{{< blocks/products/pf/slr-element name="Release Notes" href="https://docs.aspose.com/font/java/release-notes/" >}}
{{< /blocks/products/pf/slr-tab >}}

{{< blocks/products/pf/slr-tab tabTitle="{{<import path="/{{lang}}/partials/_content.md" section="why.tabTitlejava">}}" tabId="success-stories" >}}
{{< blocks/products/pf/slr-element name="{{<import path="/{{lang}}/partials/_content.md" section="why.name1">}}" href="https://helpdesk.aspose.com/" >}}
{{< blocks/products/pf/slr-element name="{{<import path="/{{lang}}/partials/_content.md" section="why.name2">}}" href="https://blog.aspose.com/category/font/" >}}
{{< /blocks/products/pf/slr-tab >}}

{{< /blocks/products/pf/support-learning-resources >}}

{{< blocks/products/pf/download-section downloadFreeTrialLink="https://releases.aspose.com/font/java/" pricingInformationLink="https://purchase.aspose.com/pricing/font/java" >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}