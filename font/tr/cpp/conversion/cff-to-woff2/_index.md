﻿---
translation: true
template: /_templates/conversion-child-cpp.md
title: CFF'den WOFF2'ye Dönüştürücü API'sı | C++
description: Bu C++ API'sini kullanarak CFF'yi WOFF2 Yazı Tiplerine dönüştürün. Dönüştürme işlevi, Windows ve Linux'ta ve C++'ı destekleyen herhangi bir geliştirme ortamında çalışır.
metakeywords: c++ CFF'den WOFF2'ye, CFF'den WOFF2'ye çözümler c++, CFF'den WOFF2'ye yazı tipi conerter cpp
url: /cpp/conversion/cff-to-woff2/
family: font
platformtag: cpp
feature: conversion
informat: CFF
outformat: WOFF2
faq: faqchild
otherformats: TTF WOFF
---

{{<section banner>}}
---
h1: CFF'yi WOFF2'ye Dönüştür
h2: C++ için CFF'den WOFF2'ye Dönüştürme işlevi. Yazı tiplerini dönüştürmek için API.
---

{{<section overview>}}
---
p1: Sadece birkaç satır kodla С++ tabanlı uygulamalarda CFF'den WOFF2'ye dönüştürme. С++ için Font API Çözümü ürününüze entegre etmek gerçekten çok kolay. Bu C++ API, karakter kodları ve glif tanımlayıcıları arasındaki bir eşlemeyi temsil eden tüm yazı tipi türleri için kodlama bilgilerinin yanı sıra herhangi bir glif ile birlikte yazı tipi veri yapısı sağlar. API, istenen herhangi bir glif veya metnin yanı sıra hareket noktası, çizim çizgisi ve eğri vb. gibi basit grafik işlevleri kullanılarak arabirimler uygulanarak oluşturulabilen özel glifleri oluşturabilir.
p2: "Gadget'ların, ortamların, birkaç işletim sisteminin ve diğer birçok alanın farklı doğası nedeniyle, web sayfalarında, uygulamalarda ve yayınlarda farklı yazı tiplerini kullanmak gibi farklı amaçlara hizmet etmek için farklı yazı tipi biçimleri kullanmak. Bu nedenle, bazen gerekli ekranı karşılamak için CFF yazı tipini farklı bir formatta başka bir yazı tipine dönüştürme ihtiyacıyla karşı karşıya kalabilirsiniz."
p3: "Giriş biçimleri olarak sonraki yazı tiplerini destekleyen С++ Api Çözümü sunuyoruz: TrueType (TTF) ve Web Açık Yazı Tipi Formatı (WOFF ve WOFF2)."
---

{{<section feature1>}}
---
title: C++'da CFF'den WOFF2'ye Dönüştürme
item1: API ile çalışmak için ihtiyacınız olan her şey ve bunları kodlamanıza yardımcı olacak yazı tipleriyle ilgili temel bilgiler hakkında daha fazla bilgi edinmek için [Belgelere](https://docs.aspose.com/font/) gidin ve kodladığınız dili seçin içinde.
item2: '[*Open()*](https://reference.aspose.com/font/cpp/class/aspose.font.font#ac2387bf04ccb5bac51cf37984d4ebf33) Yöntemini kullanarak CFF yazı tipini açın.'
item3: WOFF2 çıkış ayarlarını belirtin.
item4: "[*SaveToFormat()*](https://reference.aspose.com/font/cpp/class/aspose.font.font#a670ea97404fd72c2e51b0e8c543c8a45) Yöntemini kullanarak CFF'yi WOFF2'ye dönüştürün ve WOFF2'yi olarak iletin [FontSavingFormats](https://reference.aspose.com/font/cpp/namespace/aspose.font#a93d0dcc7c00f5c7027d60e14a5433c74)."
---

{{<section feature2>}}
---
title: C++ Yazı Tipi API'sini Kullanmaya Başlayın
item1: Komut satırından ```nuget install Aspose.Font.Cpp``` veya Visual Studio'nun Paket Yönetici Konsolu üzerinden ```Install-Package Aspose.Font.Cpp`` ile kurun.
item2: Alternatif olarak, çevrimdışı MSI yükleyicisini veya DLL'leri [indirilenler](https://releases.aspose.com/font/cpp/) adresinden bir ZIP dosyasında alın.
item3: Platformlar arası Aspose [CFF to WOFF2 Converter](https://products.aspose.app/font/conversion/cff-to-woff2)'de bahsedilen işlevselliği gerçekleştirme örneğine bakın. C++ için Font API Çözümü ile nasıl çalışılacağı hakkında daha fazla kod örneği almak için [GitHub](https://github.com/aspose-font/Aspose.Font-Documentation/tree/master/cpp-examples) depomuza gidin.
---

{{<section codeexample>}}
---
title: C++ kod örneği CFF'den WOFF2'ye dönüştürme
---