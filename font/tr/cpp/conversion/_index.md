---
translation: true
template: /_templates/conversion-cpp.md
title: Yazı Tipleri Dönüştürme | C++
url: /cpp/conversion/
description: C++ Yazı tipi işleme kitaplığı ve web uygulamalarıyla yazı tiplerini dönüştürün. TTF, WOFF, CFF, EOT ve Type 1 yazı tipleriyle çalışabilen dönüştürme işlevi.
metakeywords: c++ yazı tipi dönüştürme, yazı tipi dönüştürme çözümleri c++, yazı tipi conerter cpp
family: font
platformtag: cpp
feature: conversion
---

{{<section banner>}}
---
h1: Yazı Tiplerini Dönüştür
h2: С++ için yazı tipi formatı dönüştürücü API'si. WOFF2, TTF, EOT ve CFF yazı tiplerini dönüştürün.
---

{{<section overview>}}
---
p1: С++ font API'si, CFF, OpenType, Type1 ve TrueType koleksiyonları gibi farklı fontları kolayca yükleyebilir, kaydedebilir ve dönüştürebilir. Karakter kodları ve glif tanımlayıcıları arasındaki bir eşlemeyi temsil eden tüm yazı tipi türleri için kodlama bilgilerinin yanı sıra herhangi bir glif ile birlikte yazı tipi veri yapısı sağlar. API, istenen herhangi bir glif veya metnin yanı sıra hareket noktası, çizim çizgisi ve eğri vb. gibi basit grafik işlevleri kullanılarak arabirimler uygulanarak oluşturulabilen özel glifleri oluşturabilir.
p2: "Gadget'ların, ortamların, birkaç işletim sisteminin ve diğer birçok alanın farklı doğası nedeniyle, web sayfalarında, uygulamalarda ve yayınlarda farklı yazı tiplerini kullanmak gibi farklı amaçlara hizmet etmek için farklı yazı tipi biçimleri kullanmak. Bazen gerekli gösterimi karşılamak için bir yazı tipini diğerine dönüştürmek gerekebilir."
p3: "Size çıktı biçimleri olarak sonraki yazı tiplerini destekleyen С++ Api Çözümü sunuyoruz: TrueType (TTF), Web Açık Yazı Tipi Formatı (WOFF ve WOFF2), Gömülü OpenType formatı (EOT), Tip 1 ve Kompakt Yazı Tipi Formatı (CFF)."
---

{{<section feature1>}}
---
title: TrueType Yazı Tipinden Web'e Açık Yazı Tipi Biçimi sürüm 2.0 Dönüştürme.
item1: API, okuma ve yazma için farklı yazı tiplerini destekler, işte okuma ve yazma için [liste](https://docs.aspose.com/font/cpp/convert/#formats-supported-for-reading-andor-writing). TTF'den WOFF2'ye dönüştürmeyi değerlendirmek için işlem, mevcut senaryo için desteklenen biçimlerden herhangi birinden bir yazı tipi yüklemektir, TrueType Yazı Tipi. İki parametreli çıktı akışına ve [*SaveToFormat()*](https://reference.aspose.com/font/cpp/class/aspose.font.font#a670ea97404fd72c2e51b0e8c543c8a45) içeren [*FontSavingFormats*](https://reference.aspose.com/font/cpp/namespace/aspose.font#a93d0dcc7c00f5c7027d60e14a5433c74)  Yöntemini kullanın Çıktı yazı tipi biçimini seçmek için numaralandırma.
item2: Son olarak, yazı tiplerini desteklenen çıktı biçimlerinden herhangi birine kaydetmek için SaveToFormat()'ı çağırın, şu anda Web Açık Yazı Tipi Biçimi sürüm 2.0 WOFF2 biçimi.
item3: Gerçek bir platformlar arası uygulamada gerçekleştirilen bu işlevselliği görmek için [Aspose Font Converter uygulamasına](https://products.aspose.app/font/conversion) gidin. Burada ayrıca yazı tipleri ve metinle çalışmak için daha birçok [API çözümü](https://products.aspose.app/font/applications) bulabilirsiniz.
item4: Çözümle çalışmaya başlamak için gerekli tüm bilgileri almak üzere [Belgelere](https://docs.aspose.com/font/net/) gidin, örneğin ana özelliklere yönelik Öğreticiler veya size öğretecek makaleler grubu gibi yazı tipi, Sürüm Notları, Geliştirici Kılavuzu ve diğer faydalı şeyler hakkında.
---

{{<section codeexample>}}
---
title: C++ kod örneği TTF'den WOFF2'ye dönüştürme
---



