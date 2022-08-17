---
translation: true
template: /_templates/conversion-child-java.md
title: واجهة برمجة تطبيقات محول CFF إلى WOFF2 | جافا
description: قم بتحويل CFF إلى WOFF باستخدام Java API على نظامي التشغيل Windows و Linux. قم بدمج CFF الأصلي مع وظيفة تحويل خط WOFF في الحل الخاص بك.
keywords: cff إلى woff2 java api ، cff2woff2 java solution ، cff to woff2 java
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
h1: تحويل CFF إلى WOFF2
h2: وظائف تحويل CFF إلى WOFF2 لجافا. API لتحويل الخطوط.
---

{{<section overview>}}
---
p1: تحويل CFF إلى WOFF2 ضمن التطبيقات المستندة إلى Java مع بضعة أسطر من التعليمات البرمجية. من السهل حقًا دمج Font API Solution لـ С ++ في منتجك. توفر Java API هذه بنية بيانات الخط جنبًا إلى جنب مع أي حرف رسومي بالإضافة إلى معلومات الترميز لجميع أنواع الخطوط التي تمثل تعيينًا بين رموز الأحرف ومعرفات الحروف الرسومية. يمكن لواجهة برمجة التطبيقات (API) تقديم أي حرف رسومي أو نص مرغوب فيه ، بالإضافة إلى صور رمزية خاصة ، والتي يمكن تقديمها عن طريق تنفيذ واجهات باستخدام وظائف رسومات بسيطة مثل نقطة التحرك ، ورسم الخط ، والمنحنى ، إلخ.
p2: "نظرًا للطبيعة المتنوعة للأدوات ، والبيئات ، وبعض أنظمة التشغيل ، والعديد من المجالات الأخرى لاستخدام تنسيقات خطوط مختلفة لخدمة أغراض مختلفة مثل استخدام خطوط مختلفة على صفحات الويب والتطبيقات والنشر. لذلك قد تواجه أحيانًا حاجة لتحويل خط CFF إلى خط آخر بتنسيق مختلف لتلبية العرض المطلوب."
p3: "نقدم لك حل Java Api الذي يدعم الخطوط التالية كتنسيقات إدخال: TrueType (TTF) وتنسيق Web Open Font Format (WOFF و WOFF2)."
---

{{<section feature1>}}
---
title: CFF لتحويل WOFF2 على جافا
item1: لمعرفة المزيد حول كل ما تحتاجه للعمل مع واجهة برمجة التطبيقات والمعلومات الأساسية حول الخطوط التي ستساعدك في ترميزها ، انتقل إلى [الوثائق](https://docs.aspose.com/font/) واختر اللغة التي ترمز إليها في.
item2: افتح خط CFF باستخدام طريقة  [*Open()*](https://reference.aspose.com/font/java/com.aspose.font/Font#open-com.aspose.font.FontDefinition-).
item3: حدد إعدادات إخراج WOFF2.
item4: تحويل CFF إلى WOFF2 باستخدام [*SaveToFormat()*](https://reference.aspose.com/font/java/com.aspose.font/Font#saveToFormat-java.io.OutputStream-com.aspose.font.FontSavingFormats-) الطريقة وتمرير WOFF2 كـ [FontSavingFormats](https://reference.aspose.com/font/java/com.aspose.font/FontSavingFormats).
---

{{<section feature2>}}
---
title: متطلبات التحويل
item1: "للمضي قدما في تحويل CFF إلى WOFF2 ، فإن Java Font API هي المطلب الرئيسي."
item2: "احصل على Font API مباشرةً من [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-font) لمشروع يستند إلى Java وتضمين مكتبات في ملفك pom.xml."
item3: "بدلاً من ذلك ، يمكنك الحصول على ملف ZIP من [التنزيلات](https://releases.aspose.com/font/java/)."
item4: انظر مثال تحقيق الوظيفة المذكورة في Aspose متعدد المنصات [CFF to WOFF2 Converter](https://products.aspose.app/font/conversion/cff-to-woff2). انتقل إلى مستودع [GitHub](https://github.com/aspose-font/Aspose.Font-Documentation/tree/master/java-examples) للحصول على المزيد من أمثلة التعليمات البرمجية حول كيفية العمل مع Font API Solution لجافا.
---

{{<section codeexample>}}
---
title: كود جافا لتحويل CFF إلى WOFF2
---