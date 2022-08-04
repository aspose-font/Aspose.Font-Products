---
translation: true
template: /_templates/conversion-java.md
title: फ़ॉन्ट रूपांतरण एपीआई | जावा
url: /java/conversion/
description: जावा फ़ॉन्ट फ़ाइलें रूपांतरण कार्यक्षमता। जावा कोड की कुछ पंक्तियों के साथ विभिन्न फोंट जैसे CFF, EOT, WOFF, TTF और टाइप 1 को कन्वर्ट करें।
keywords: फ़ॉन्ट कनवर्ट करें जावा, फ़ॉन्ट रूपांतरण जावा, फ़ॉन्ट कवरर जावा
family: font
platformtag: java
feature: conversion
---

{{<section banner>}}
---
h1: कन्वर्ट फ़ॉन्ट्स
h2: जावा के लिए फ़ॉन्ट प्रारूप कनवर्टर एपीआई। WOFF2, TTF, EOT और CFF फोंट कन्वर्ट करें।
---

{{<section overview>}}
---
p1: जावा फॉन्ट एपीआई सीएफएफ, ओपन टाइप, टाइप1 और ट्रू टाइप कलेक्शन जैसे विभिन्न फॉन्ट को आसानी से लोड, सेव और कन्वर्ट कर सकता है। यह किसी भी ग्लिफ़ के साथ-साथ वर्ण कोड और ग्लिफ़ पहचानकर्ताओं के बीच मैपिंग का प्रतिनिधित्व करने वाले सभी फ़ॉन्ट प्रकारों के लिए एन्कोडिंग जानकारी के साथ-साथ फ़ॉन्ट डेटा संरचना प्रदान करता है। एपीआई किसी भी वांछित ग्लिफ़ या टेक्स्ट, साथ ही विशेष ग्लिफ़ को प्रस्तुत कर सकता है, जिसे सरल ग्राफिक्स कार्यक्षमता जैसे मूव पॉइंट, ड्रॉ लाइन और कर्व आदि का उपयोग करके इंटरफेस को लागू करके प्रदान किया जा सकता है।
p2: "गैजेट्स, वातावरण, कुछ परिचालन प्रणालियों और कई अन्य क्षेत्रों की विविध प्रकृति के कारण विभिन्न उद्देश्यों की पूर्ति के लिए विभिन्न फ़ॉन्ट प्रारूपों का उपयोग करना जैसे वेब पेज, एप्लिकेशन और प्रकाशन पर विभिन्न फ़ॉन्ट्स का उपयोग करना। कभी-कभी आवश्यक प्रदर्शन को पूरा करने के लिए एक फ़ॉन्ट को दूसरे में बदलने की आवश्यकता होती है।"
p3: "हम आपको जावा एपीआई सॉल्यूशन प्रदान करते हैं जो आउटपुट स्वरूपों के रूप में अगले फोंट का समर्थन करता है: ट्रू टाइप (टीटीएफ), वेब ओपन फॉन्ट फॉर्मेट (डब्ल्यूओएफएफ और डब्ल्यूओएफएफ 2), एंबेडेड ओपन टाइप फॉर्मेट (ईओटी), टाइप 1 और कॉम्पैक्ट फॉन्ट फॉर्मेट (सीएफएफ)।"
---

{{<section feature1>}}
---
title: ट्रू टाइप फॉन्ट टू वेब ओपन फॉन्ट फॉर्मेट वर्जन 2.0 कन्वर्जन।
item1: एपीआई पढ़ने और लिखने के लिए विभिन्न फोंट का समर्थन करता है, यहां पढ़ने और लिखने के लिए [सूची](https://docs.aspose.com/font/java/convert/#formats-supported-for-reading-andor-writing) है। TTF से WOFF2 रूपांतरण पर विचार करने के लिए, वर्तमान परिदृश्य के लिए किसी भी समर्थित प्रारूप, ट्रू टाइप फ़ॉन्ट से एक फ़ॉन्ट लोड करने की प्रक्रिया है। [*SaveToFormat()*](https://reference.aspose.com/font/java/com.aspose.font/Font#saveToFormat-java.io.OutputStream-com.aspose.font.FontSavingFormats-) विधि का उपयोग करें [Font class](https://reference.aspose.com/font/java/com.aspose.font/Font#save-java.lang.String-) के दो पैरामीटर आउटपुट स्ट्रीम और [*FontSavingFormats*](https://reference.aspose.com/font/java/com.aspose.font/FontSavingFormats) आउटपुट फॉन्ट फॉर्मेट को चुनने के लिए एन्यूमरेशन।
item2: अंत में, किसी भी समर्थित आउटपुट स्वरूप में फोंट को सहेजने के लिए SaveToFormat () को कॉल करें, वर्तमान में वेब ओपन फ़ॉन्ट प्रारूप संस्करण 2.0 WOFF2 प्रारूप।
item3: वास्तविक क्रॉस-प्लेटफ़ॉर्म एप्लिकेशन में महसूस की गई इस कार्यक्षमता को देखने के लिए [Aspose Font Converter ऐप](https://products.aspose.app/font/conversion) पर जाएं। वहां आपको फ़ॉन्ट और टेक्स्ट के साथ काम करने के लिए और भी कई [API समाधान](https://products.aspose.app/font/applications) मिल सकते हैं।
item4: समाधान के साथ काम करना शुरू करने के लिए सभी आवश्यक जानकारी प्राप्त करने के लिए [दस्तावेज़ीकरण](https://docs.aspose.com/font/net/) पर जाएं, जैसे मुख्य विशेषताओं के लिए ट्यूटोरियल या आपको सिखाने के लिए लेखों का सेट फ़ॉन्ट, रिलीज नोट्स, डेवलपर गाइड और अन्य उपयोगी चीजों के बारे में।
---

{{<section codeexample>}}
---
title: सीएफएफ से टीटीएफ रूपांतरण के लिए जावा कोड
---

{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/agp/feature-section >}}
{{< app/font/converter "Java Code for CFF to TTF Conversion" CFF TTF WOFF WOFF2>}}
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