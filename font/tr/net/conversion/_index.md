---
translation: true
template: /_templates/conversion-net.md
title: Yazı Tipleri Dönüştürme API'sı | .AĞ
url: /net/conversion/
description: Yazı tipi dönüştürme işlevi. .NET kitaplığı aracılığıyla CFF, EOT, WOFF, TTF ve Type 1 gibi farklı yazı tiplerini birkaç satırlık C# koduyla dönüştürün.
keywords: yazı tipi dönüştürücü .net, yazı tipi dönüştürücü net, c# yazı tipi kaplaması
family: font
platformtag: net
feature: conversion
---

{{<section banner>}}
---
h1: Yazı Tiplerini C# ile Dönüştür
h2: .NET için yazı tipi formatı dönüştürücü API'si. WOFF2, TTF, EOT ve CFF yazı tiplerini dönüştürün.
---

{{<section overview>}}
---
p1: .NET font API'si, CFF, OpenType, Type1 ve TrueType koleksiyonları gibi farklı fontları kolayca yükleyebilir, kaydedebilir ve dönüştürebilir. Karakter kodları ve glif tanımlayıcıları arasındaki bir eşlemeyi temsil eden tüm yazı tipi türleri için kodlama bilgilerinin yanı sıra herhangi bir glif ile birlikte yazı tipi veri yapısı sağlar. API, istenen herhangi bir glif veya metnin yanı sıra hareket noktası, çizim çizgisi ve eğri vb. gibi basit grafik işlevleri kullanılarak arabirimler uygulanarak oluşturulabilen özel glifleri oluşturabilir.
p2: "Gadget'ların, ortamların, birkaç işletim sisteminin ve diğer birçok alanın farklı doğası nedeniyle, web sayfalarında, uygulamalarda ve yayınlarda farklı yazı tiplerini kullanmak gibi farklı amaçlara hizmet etmek için farklı yazı tipi biçimleri kullanmak. Bazen gerekli gösterimi karşılamak için bir yazı tipini diğerine dönüştürmek gerekebilir."
p3: "Buradaki çözüm, çıktı biçimleri olarak sonraki yazı tiplerini destekler: TrueType (TTF), Web Açık Yazı Tipi Formatı (WOFF ve WOFF2), Gömülü OpenType formatı (EOT), Tip 1 ve Kompakt Yazı Tipi Formatı (CFF)."
---

{{<section feature1>}}
---
title: TrueType Yazı Tipinden Web'e Açık Yazı Tipi Biçimi sürüm 2.0 Dönüştürme.
item1: API, okuma ve yazma için farklı yazı tiplerini destekler, işte okuma ve yazma için [liste](https://docs.aspose.com/font/net/convert/#formats-supported-for-reading-andor-writing). TTF'den WOFF2'ye dönüştürmeyi değerlendirmek için işlem, mevcut senaryo için desteklenen biçimlerden herhangi birinden bir yazı tipi yüklemektir, TrueType Yazı Tipi. [*SaveToFormat()*](https://reference.aspose.com/font/net/aspose.font/font/savetoformat/) Yöntemini iki parametreli çıktı akışına ve [*FontSavingFormats*](https://reference.aspose.com/font/net/aspose.font/fontsavingformats/) Çıktı yazı tipi biçimini seçmek için numaralandırma.
item2: Son olarak, yazı tiplerini desteklenen çıktı biçimlerinden herhangi birine kaydetmek için SaveToFormat()'ı çağırın, şu anda Web Açık Yazı Tipi Biçimi sürüm 2.0 WOFF2 biçimi.
item3: Gerçek bir platformlar arası uygulamada gerçekleştirilen bu işlevselliği görmek için [Aspose Font Converter uygulamasına](https://products.aspose.app/font/conversion) gidin. Burada ayrıca yazı tipleri ve metinle çalışmak için daha birçok [API çözümü](https://products.aspose.app/font/applications) bulabilirsiniz.
item4: Çözümle çalışmaya başlamak için gerekli tüm bilgileri almak üzere [Belgelere](https://docs.aspose.com/font/net/) gidin, örneğin ana özelliklere yönelik Öğreticiler veya size öğretecek makaleler grubu gibi yazı tipi, Sürüm Notları, Geliştirici Kılavuzu ve diğer faydalı şeyler hakkında.
---

{{<section codeexample>}}
---
title: C# kod örneği TTF'den WOFF2'ye dönüştürme
---
