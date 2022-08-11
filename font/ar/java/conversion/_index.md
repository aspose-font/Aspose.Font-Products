---
translation: true
template: /_templates/conversion-java.md
title: واجهة برمجة تطبيقات تحويل الخطوط | جافا
url: /java/conversion/
description: وظائف تحويل ملفات خطوط جافا. قم بتحويل خطوط مختلفة مثل CFF و EOT و WOFF و TTF والنوع 1 ببضعة أسطر من كود Java.
keywords: تحويل الخطوط جافا ، تحويل الخط جافا ، غلاف الخط جافا
family: font
platformtag: java
feature: conversion
---

{{<section banner>}}
---
h1: تحويل الخطوط
h2: محول تنسيق الخطوط API لجافا. تحويل خطوط WOFF2 و TTF و EOT و CFF.
---

{{<section overview>}}
---
p1: يمكن لـ Java font API تحميل وحفظ وتحويل خطوط مختلفة بسهولة مثل مجموعات CFF و OpenType و Type1 و TrueType. يوفر بنية بيانات الخط جنبًا إلى جنب مع أي حرف رسومي بالإضافة إلى معلومات الترميز لجميع أنواع الخطوط التي تمثل تعيينًا بين رموز الأحرف ومعرفات الحروف الرسومية. يمكن لواجهة برمجة التطبيقات (API) تقديم أي حرف رسومي أو نص مرغوب فيه ، بالإضافة إلى صور رمزية خاصة ، والتي يمكن تقديمها عن طريق تنفيذ واجهات باستخدام وظائف رسومات بسيطة مثل نقطة التحرك ، ورسم الخط ، والمنحنى ، إلخ.
p2: "نظرًا للطبيعة المتنوعة للأدوات ، والبيئات ، وبعض أنظمة التشغيل ، والعديد من المجالات الأخرى لاستخدام تنسيقات خطوط مختلفة لخدمة أغراض مختلفة مثل استخدام خطوط مختلفة على صفحات الويب والتطبيقات والنشر. في بعض الأحيان تكون هناك حاجة لتحويل خط إلى آخر لتلبية العرض المطلوب."
p3: "نقدم لك حل Java Api الذي يدعم الخطوط التالية كتنسيقات إخراج: TrueType (TTF) وتنسيق Web Open Font Format (WOFF و WOFF2) وتنسيق OpenType المضمن (EOT) والنوع 1 وتنسيق الخط المضغوط (CFF)."
---

{{<section feature1>}}
---
title: TrueType Font to Web Open Font Format التحويل الإصدار 2.0.
item1: تدعم واجهة برمجة التطبيقات خطوطًا مختلفة للقراءة والكتابة ، إليك [قائمة](https://docs.aspose.com/font/java/convert/#formats-supported-for-reading-andor-writing) للقراءة والكتابة. للنظر في تحويل TTF إلى WOFF2 ، فإن العملية هي تحميل خط من أي من التنسيقات المدعومة ، TrueType Font للسيناريو الحالي. استخدم الأسلوب [*SaveToFormat()*](https://reference.aspose.com/font/java/com.aspose.font/Font#saveToFormat-java.io.OutputStream-com.aspose.font.FontSavingFormats-) من [فئة الخط](https://reference.aspose.com/font/java/com.aspose.font/Font#save-java.lang.String-) بها دفق إخراج معاملين و [*FontSavingFormats*](https://reference.aspose.com/font/java/com.aspose.font/FontSavingFormats) تعداد لاختيار تنسيق خط الإخراج.
item2: أخيرًا ، اتصل بـ SaveToFormat () لحفظ الخطوط في أي من تنسيقات الإخراج المدعومة ، حاليًا تنسيق Web Open Font Format الإصدار 2.0 WOFF2.
item3: لرؤية هذه الوظيفة تتحقق في تطبيق فعلي عبر الأنظمة الأساسية ، انتقل إلى [Aspose Font Converter app](https://products.aspose.app/font/conversion). هناك يمكنك أيضًا العثور على العديد من [حلول واجهة برمجة التطبيقات](https://products.aspose.app/font/applications) للعمل مع الخطوط والنصوص.
item4: انتقل إلى [الوثائق](https://docs.aspose.com/font/net/) للحصول على جميع المعلومات المطلوبة لبدء العمل مع الحل ، مثل البرامج التعليمية للميزات الرئيسية أو مجموعة المقالات التي ستعلمك حول الخط وملاحظات الإصدار ودليل المطور وأشياء أخرى مفيدة.
---

{{<section codeexample>}}
---
title: كود جافا لتحويل CFF إلى TTF
---