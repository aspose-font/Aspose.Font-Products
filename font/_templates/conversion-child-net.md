---
template: true
title: {{i18n.title}}
description: {{i18n.description}}
url: {{i18n.url}}
family: font
platformtag: net
feature: conversion
informat: {{i18n.informat}}
outformat: {{i18n.outformat}}
otherformats: {{i18n.otherformats}}
---

{{<meta path="/{{lang}}/meta/conversion/default.md" section="faq">}}

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
1. {{i18n.feature2.item1}}
1. {{i18n.feature2.item2}}
1. {{i18n.feature2.item3}}
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< app/font/converter "{{i18n.feature1.title}}" CFF TTF WOFF WOFF2>}}
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

<h2>{{<import path="/{{lang}}/partials/_faqs.md" section="faq-converter-child.h2">}}</h2>

<b>1. {{<import path="/{{lang}}/partials/_faqs.md" section="faq-converter-child.Q1">}}</b>

{{<import path="/{{lang}}/partials/_faqs.md" section="faq-converter-child.A1">}}

<b>2. {{<import path="/{{lang}}/partials/_faqs.md" section="faq-converter-child.Q2">}}</b>

{{<import path="/{{lang}}/partials/_faqs.md" section="faq-converter-child.A2">}}

<b>3. {{<import path="/{{lang}}/partials/_faqs.md" section="faq-converter-child.Q3">}}</b>

{{<import path="/{{lang}}/partials/_faqs.md" section="faq-converter-child.A3">}}

{{< blocks/products/pf/support-learning-resources >}}
{{< blocks/products/pf/slr-tab tabTitle="{{<import path="/{{lang}}/partials/_content.md" section="learningresources.tabTitle">}}" tabId="resources" >}}
{{< blocks/products/pf/slr-element name="{{<import path="/{{lang}}/partials/_content.md" section="learningresources.name1">}}" href="https://docs.aspose.com/font/net/" >}}
{{< blocks/products/pf/slr-element name="{{<import path="/{{lang}}/partials/_content.md" section="learningresources.name2">}}" href="https://github.com/aspose-font/Aspose.Font-for-.NET" >}}
{{< blocks/products/pf/slr-element name="{{<import path="/{{lang}}/partials/_content.md" section="learningresources.name3">}}" href="https://reference.aspose.com/font/net/" >}}
{{< /blocks/products/pf/slr-tab >}}

{{< blocks/products/pf/slr-tab tabTitle="{{<import path="/{{lang}}/partials/_content.md" section="support.tabTitle">}}" tabId="support" >}}
{{< blocks/products/pf/slr-element name="{{<import path="/{{lang}}/partials/_content.md" section="support.name1">}}" href="https://forum.aspose.com/c/font/41" >}}
{{< blocks/products/pf/slr-element name="{{<import path="/{{lang}}/partials/_content.md" section="support.name2">}}" href="https://helpdesk.aspose.com/" >}}
{{< blocks/products/pf/slr-element name="{{<import path="/{{lang}}/partials/_content.md" section="support.name3">}}" href="https://blog.aspose.com/category/font/" >}}
{{< blocks/products/pf/slr-element name="Release Notes" href="https://docs.aspose.com/font/net/release-notes/" >}}
{{< /blocks/products/pf/slr-tab >}}

{{< blocks/products/pf/slr-tab tabTitle="{{<import path="/{{lang}}/partials/_content.md" section="why.tabTitlenet">}}" tabId="success-stories" >}}
{{< blocks/products/pf/slr-element name="{{<import path="/{{lang}}/partials/_content.md" section="why.name1">}}" href="https://helpdesk.aspose.com/" >}}
{{< blocks/products/pf/slr-element name="{{<import path="/{{lang}}/partials/_content.md" section="why.name2">}}" href="https://blog.aspose.com/category/font/" >}}
{{< /blocks/products/pf/slr-tab >}}

{{< /blocks/products/pf/support-learning-resources >}}

{{< blocks/products/pf/download-section downloadFreeTrialLink="https://releases.aspose.com/font/net/" pricingInformationLink="https://purchase.aspose.com/pricing/font/net" >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}