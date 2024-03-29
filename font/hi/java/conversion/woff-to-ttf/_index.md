﻿---
translation: true
template: /_templates/conversion-child-java.md
title: WOFF से TTF कन्वर्टर API | जावा
description: विंडोज़ और लिनक्स पर जावा एपीआई का उपयोग करके डब्ल्यूओएफएफ को टीटीएफ में कनवर्ट करें। इस मूल WOFF को अपने स्वयं के समाधान में TTF फ़ॉन्ट रूपांतरण कार्यक्षमता में एकीकृत करें।
keywords: ttf जावा एपीआई के लिए woff, woff2ttf जावा समाधान, ttf जावा के लिए woff
url: /java/conversion/woff-to-ttf/
family: font
platformtag: java
feature: conversion
informat: WOFF
outformat: TTF
faq: faqchild
otherformats: WOFF2
---

{{<section banner>}}
---
h1: WOFF को TTF में बदलें
h2: जावा के लिए WOFF से TTF रूपांतरण कार्यक्षमता। फ़ॉन्ट बदलने के लिए एपीआई।
---

{{<section overview>}}
---
p1: कोड की कुछ पंक्तियों के साथ जावा-आधारित अनुप्रयोगों के भीतर WOFF से TTF रूपांतरण। ++ के लिए फ़ॉन्ट एपीआई समाधान आपके उत्पाद में एकीकृत करना वास्तव में आसान है। यह जावा एपीआई किसी भी ग्लिफ़ के साथ-साथ वर्ण कोड और ग्लिफ़ आइडेंटिफ़ायर के बीच मैपिंग का प्रतिनिधित्व करने वाले सभी फ़ॉन्ट प्रकारों के लिए फ़ॉन्ट डेटा संरचना के साथ-साथ एन्कोडिंग जानकारी प्रदान करता है। एपीआई किसी भी वांछित ग्लिफ़ या टेक्स्ट, साथ ही विशेष ग्लिफ़ को प्रस्तुत कर सकता है, जिसे सरल ग्राफिक्स कार्यक्षमता जैसे मूव पॉइंट, ड्रॉ लाइन और कर्व आदि का उपयोग करके इंटरफेस को लागू करके प्रदान किया जा सकता है।
p2: "गैजेट्स, वातावरण, कुछ परिचालन प्रणालियों और कई अन्य क्षेत्रों की विविध प्रकृति के कारण विभिन्न उद्देश्यों की पूर्ति के लिए विभिन्न फ़ॉन्ट प्रारूपों का उपयोग करना जैसे वेब पेज, एप्लिकेशन और प्रकाशन पर विभिन्न फ़ॉन्ट्स का उपयोग करना। इसलिए कभी-कभी आपको आवश्यक प्रदर्शन को पूरा करने के लिए WOFF फ़ॉन्ट को दूसरे प्रारूप में बदलने की आवश्यकता हो सकती है।"
p3: "हम आपको जावा एपीआई समाधान प्रदान करते हैं जो इनपुट स्वरूपों के रूप में अगले फोंट का समर्थन करता है: ट्रू टाइप (टीटीएफ) और वेब ओपन फ़ॉन्ट प्रारूप (डब्ल्यूओएफएफ और डब्ल्यूओएफएफ 2)।"
---

{{<section feature1>}}
---
title: जावा पर WOFF से TTF रूपांतरण
item1: उन सभी चीजों के बारे में अधिक जानने के लिए जो आपको एपीआई के साथ काम करने की जरूरत है और फोंट के बारे में बुनियादी जानकारी जो आपको उन्हें कोड करने में मदद करेगी [दस्तावेज़ीकरण](https://docs.aspose.com/font/) पर जाएं और वह भाषा चुनें जिसे आप कोड करते हैं में।
item2: '[*ओपन()*](https://reference.aspose.com/font/java/com.aspose.font/Font#open-com.aspose.font.FontDefinition-) विधि का उपयोग करके WOFF फ़ॉन्ट खोलें।'
item3: TTF आउटपुट सेटिंग्स निर्दिष्ट करें।
item4: '[*SaveToFormat()*](https://reference.aspose.com/font/java/com.aspose.font/Font#saveToFormat-java.io.OutputStream-com.aspose.font.FontSavingFormats-)का उपयोग करके WOFF को TTF में बदलें। विधि और TTF को [FontSavingFormats](https://reference.aspose.com/font/java/com.aspose.font/FontSavingFormats) के रूप में पास करें।'
---

{{<section feature2>}}
---
title: रूपांतरण आवश्यकताएँ
item1: "WOFF से TTF रूपांतरण के लिए आगे बढ़ने के लिए, Java Font API मुख्य आवश्यकता है।"
item2: "जावा आधारित प्रोजेक्ट के लिए [Aspose Maven Repository](https://repository.aspose.com/font/) से सीधे Font API प्राप्त करें और इसमें लाइब्रेरी शामिल करें आपका पोम.एक्सएमएल."
item3: "वैकल्पिक रूप से, आप [डाउनलोड](https://releases.aspose.com/font/java/) से एक ज़िप फ़ाइल प्राप्त कर सकते हैं।"
item4: क्रॉस-प्लेटफ़ॉर्म Aspose [WOFF to TTF Converter](https://products.aspose.app/font/conversion/woff-to-ttf) में उल्लिखित कार्यक्षमता की प्राप्ति का उदाहरण देखें। Java के लिए Font API सॉल्यूशन के साथ काम करने के तरीके के बारे में अधिक कोड उदाहरण प्राप्त करने के लिए हमारे [GitHub](https://github.com/aspose-font/Aspose.Font-Documentation/tree/master/java-examples) रिपॉजिटरी पर जाएं।
---

{{<section codeexample>}}
---
title: WOFF से TTF रूपांतरण के लिए जावा कोड
---