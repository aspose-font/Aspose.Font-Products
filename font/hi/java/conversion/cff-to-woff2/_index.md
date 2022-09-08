---
translation: true
template: /_templates/conversion-child-java.md
title: CFF से WOFF2 कन्वर्टर API | जावा
description: विंडोज़ और लिनक्स पर जावा एपीआई का उपयोग करके सीएफएफ को डब्ल्यूओएफएफ में कनवर्ट करें। इस मूल CFF को अपने स्वयं के समाधान में WOFF फ़ॉन्ट रूपांतरण कार्यक्षमता में एकीकृत करें।
keywords: cff से woff2 जावा एपीआई, cff2woff2 जावा समाधान, cff से woff2 जावा;
url: /java/conversion/cff-to-woff2/
family: font
platformtag: java
feature: conversion
informat: CFF
outformat: WOFF2
faq: faqchild
otherformats: TTF WOFF
---

{{<section banner>}}
---
h1: CFF को WOFF2 में बदलें
h2: जावा के लिए CFF से WOFF2 रूपांतरण कार्यक्षमता। फ़ॉन्ट बदलने के लिए एपीआई।
---

{{<section overview>}}
---
p1: कोड की कुछ पंक्तियों के साथ जावा-आधारित अनुप्रयोगों के भीतर CFF से WOFF2 रूपांतरण। ++ के लिए फ़ॉन्ट एपीआई समाधान आपके उत्पाद में एकीकृत करना वास्तव में आसान है। यह जावा एपीआई किसी भी ग्लिफ़ के साथ-साथ वर्ण कोड और ग्लिफ़ आइडेंटिफ़ायर के बीच मैपिंग का प्रतिनिधित्व करने वाले सभी फ़ॉन्ट प्रकारों के लिए फ़ॉन्ट डेटा संरचना के साथ-साथ एन्कोडिंग जानकारी प्रदान करता है। एपीआई किसी भी वांछित ग्लिफ़ या टेक्स्ट, साथ ही विशेष ग्लिफ़ को प्रस्तुत कर सकता है, जिसे सरल ग्राफिक्स कार्यक्षमता जैसे मूव पॉइंट, ड्रॉ लाइन और कर्व आदि का उपयोग करके इंटरफेस को लागू करके प्रदान किया जा सकता है।
p2: "गैजेट्स, वातावरण, कुछ परिचालन प्रणालियों और कई अन्य क्षेत्रों की विविध प्रकृति के कारण विभिन्न उद्देश्यों की पूर्ति के लिए विभिन्न फ़ॉन्ट प्रारूपों का उपयोग करना जैसे वेब पेज, एप्लिकेशन और प्रकाशन पर विभिन्न फ़ॉन्ट्स का उपयोग करना। तो कभी-कभी आपको आवश्यक प्रदर्शन को पूरा करने के लिए सीएफएफ फ़ॉन्ट को एक अलग प्रारूप में बदलने की आवश्यकता का सामना करना पड़ सकता है।"
p3: "हम आपको जावा एपीआई समाधान प्रदान करते हैं जो इनपुट स्वरूपों के रूप में अगले फोंट का समर्थन करता है: ट्रू टाइप (टीटीएफ) और वेब ओपन फ़ॉन्ट प्रारूप (डब्ल्यूओएफएफ और डब्ल्यूओएफएफ 2)।"
---

{{<section feature1>}}
---
title: जावा पर CFF से WOFF2 रूपांतरण
item1: उन सभी चीजों के बारे में अधिक जानने के लिए जो आपको एपीआई के साथ काम करने की जरूरत है और फोंट के बारे में बुनियादी जानकारी जो आपको उन्हें कोड करने में मदद करेगी [दस्तावेज़ीकरण](https://docs.aspose.com/font/) पर जाएं और वह भाषा चुनें जिसे आप कोड करते हैं में।
item2: '[*Open()*](https://reference.aspose.com/font/java/com.aspose.font/Font#open-com.aspose.font.FontDefinition-) विधि का उपयोग करके CFF फ़ॉन्ट खोलें।'
item3: WOFF2 आउटपुट सेटिंग्स निर्दिष्ट करें।
item4: '[*SaveToFormat()*](https://reference.aspose.com/font/java/com.aspose.font/Font#saveToFormat-java.io.OutputStream-com.aspose.font.FontSavingFormats-)का उपयोग करके CFF को WOFF2 में बदलें। विधि और WOFF2 को [FontSavingFormats](https://reference.aspose.com/font/java/com.aspose.font/FontSavingFormats) के रूप में पास करें।'
---

{{<section feature2>}}
---
title: रूपांतरण आवश्यकताएँ
item1: "CFF से WOFF2 रूपांतरण के लिए आगे बढ़ने के लिए, Java Font API मुख्य आवश्यकता है।"
item2: "जावा आधारित प्रोजेक्ट के लिए [Aspose Maven Repository](https://repository.aspose.com/font/) से सीधे Font API प्राप्त करें और इसमें लाइब्रेरी शामिल करें आपका पोम.एक्सएमएल."
item3: "वैकल्पिक रूप से, आप [डाउनलोड](https://releases.aspose.com/font/java/) से एक ज़िप फ़ाइल प्राप्त कर सकते हैं।"
item4: क्रॉस-प्लेटफ़ॉर्म Aspose [CFF to WOFF2 Converter](https://products.aspose.app/font/conversion/cff-to-woff2) में उल्लिखित कार्यक्षमता की प्राप्ति का उदाहरण देखें। Java के लिए Font API सॉल्यूशन के साथ काम करने के तरीके के बारे में अधिक कोड उदाहरण प्राप्त करने के लिए हमारे [GitHub](https://github.com/aspose-font/Aspose.Font-Documentation/tree/master/java-examples) रिपॉजिटरी पर जाएं।
---

{{<section codeexample>}}
---
title: CFF से WOFF2 रूपांतरण के लिए जावा कोड
---