﻿---
translation: true
template: /_templates/conversion-cpp.md
title: تحويل الخطوط | C ++
url: /cpp/conversion/
description: قم بتحويل الخطوط باستخدام مكتبة معالجة الخطوط C ++ وتطبيقات الويب. وظائف التحويل التي يمكن أن تعمل مع خطوط TTF و WOFF و CFF و EOT والنوع 1.
metakeywords: تحويل الخط c ++ ، حلول تحويل الخطوط c ++ ، الخط conerter cpp
family: font
platformtag: cpp
feature: conversion
---

{{<section banner>}}
---
h1: تحويل الخطوط
h2: واجهة برمجة تطبيقات محول تنسيق الخط لـ С ++. تحويل خطوط WOFF2 و TTF و EOT و CFF.
---

{{<section overview>}}
---
p1: يمكن لواجهة برمجة تطبيقات الخط С ++ تحميل وحفظ وتحويل خطوط مختلفة بسهولة مثل مجموعات CFF و OpenType و Type1 و TrueType. يوفر بنية بيانات الخط جنبًا إلى جنب مع أي حرف رسومي بالإضافة إلى معلومات الترميز لجميع أنواع الخطوط التي تمثل تعيينًا بين رموز الأحرف ومعرفات الحروف الرسومية. يمكن لواجهة برمجة التطبيقات (API) تقديم أي حرف رسومي أو نص مرغوب فيه ، بالإضافة إلى صور رمزية خاصة ، والتي يمكن تقديمها عن طريق تنفيذ واجهات باستخدام وظائف رسومات بسيطة مثل نقطة التحرك ، ورسم الخط ، والمنحنى ، إلخ.
p2: "نظرًا للطبيعة المتنوعة للأدوات ، والبيئات ، وبعض أنظمة التشغيل ، والعديد من المجالات الأخرى لاستخدام تنسيقات خطوط مختلفة لخدمة أغراض مختلفة مثل استخدام خطوط مختلفة على صفحات الويب والتطبيقات والنشر. في بعض الأحيان تكون هناك حاجة لتحويل خط إلى آخر لتلبية العرض المطلوب."
p3: "نقدم لك حل С ++ Api الذي يدعم الخطوط التالية كتنسيقات إخراج: TrueType (TTF) وتنسيق خط الويب المفتوح (WOFF و WOFF2) وتنسيق OpenType المضمن (EOT) والنوع 1 وتنسيق الخط المضغوط (CFF)."
---

{{<section feature1>}}
---
title: TrueType Font to Web Open Font Format التحويل الإصدار 2.0.
item1: تدعم واجهة برمجة التطبيقات خطوطًا مختلفة للقراءة والكتابة ، إليك [قائمة](https://docs.aspose.com/font/cpp/convert/#formats-supported-for-reading-andor-writing) للقراءة والكتابة. للنظر في تحويل TTF إلى WOFF2 ، فإن العملية هي تحميل خط من أي من التنسيقات المدعومة ، TrueType Font للسيناريو الحالي. استخدم [*SaveToFormat()*](https://reference.aspose.com/font/cpp/class/aspose.font.font#a670ea97404fd72c2e51b0e8c543c8a45) الأسلوب الذي يحتوي على معلمتين دفق الإخراج و [*FontSavingFormats*](https://reference.aspose.com/font/cpp/namespace/aspose.font#a93d0dcc7c00f5c7027d60e14a5433c74) تعداد لتحديد تنسيق خط الإخراج.
item2: أخيرًا ، اتصل بـ SaveToFormat () لحفظ الخطوط في أي من تنسيقات الإخراج المدعومة ، حاليًا تنسيق Web Open Font Format الإصدار 2.0 WOFF2.
item3: لرؤية هذه الوظيفة تتحقق في تطبيق فعلي عبر الأنظمة الأساسية ، انتقل إلى [Aspose Font Converter app](https://products.aspose.app/font/conversion). هناك يمكنك أيضًا العثور على العديد من [حلول واجهة برمجة التطبيقات](https://products.aspose.app/font/applications) للعمل مع الخطوط والنصوص.
item4: انتقل إلى [الوثائق](https://docs.aspose.com/font/net/) للحصول على جميع المعلومات المطلوبة لبدء العمل مع الحل ، مثل البرامج التعليمية للميزات الرئيسية أو مجموعة المقالات التي ستعلمك حول الخط وملاحظات الإصدار ودليل المطور وأشياء أخرى مفيدة.
---

{{<section codeexample>}}
---
title: مثال على كود C ++ TTF لتحويل WOFF2
---


