---
translation: true
template: /_templates/conversion-child-net.md
title: TTF'den WOFF'a Dönüştürücü API |.NET
description: Windows'ta .NET API kullanarak WOFF2'yi WOFF'a dönüştürün. Bu yerel WOFF2'den WOFF'a yazı tipi dönüştürme işlevini kendi çözümünüze entegre edin.
keywords: woff2'den woff net api'ye, woff22woff net çözümüne, woff2'den woff net'e
url: /net/conversion/woff2-to-woff/
family: font
platformtag: net
feature: conversion
informat: WOFF2
outformat: WOFF
faq: faqchild
otherformats: TTF
---

{{<section banner>}}
---
h1: TTF'yi WOFF'ye dönüştür
h2: C№ .NET için TTF'den WOFF'a Dönüştürme işlevi. Yazı tiplerini dönüştürmek için API.
---

{{<section overview>}}
---
p1: Yalnızca birkaç satır kodla .NET tabanlı uygulamalarda TTF'den WOFF'a dönüştürme. С# için Font API Çözümü ürününüze entegre etmek gerçekten çok kolay. Bu .NET API, karakter kodları ve glif tanımlayıcıları arasındaki bir eşlemeyi temsil eden tüm yazı tipi türleri için kodlama bilgilerinin yanı sıra herhangi bir glif ile birlikte yazı tipi veri yapısı sağlar. API, istenen herhangi bir glifi veya metni ve ayrıca hareket noktası, çizim çizgisi ve eğri vb. gibi basit grafik işlevleri kullanılarak arayüzler uygulanarak oluşturulabilen özel glifleri oluşturabilir.
p2: "Gadget'ların, ortamların, birkaç işletim sisteminin ve diğer birçok alanın farklı doğası nedeniyle, web sayfalarında, uygulamalarda ve yayınlarda farklı yazı tiplerinin kullanılması gibi farklı amaçlara hizmet etmek için farklı yazı tipi biçimleri kullanmak. Bu nedenle, bazen gerekli ekranı karşılamak için TTF yazı tipini farklı bir formatta başka bir yazı tipine dönüştürme ihtiyacıyla karşı karşıya kalabilirsiniz."
p3: "Giriş biçimleri olarak sonraki yazı tiplerini destekleyen С# .NET Api Çözümü sunuyoruz: TrueType (TTF) ve Web Açık Yazı Tipi Formatı (WOFF ve WOFF2)."
---

{{<section feature1>}}
---
title: C#'da TTF'den WOFF'a Dönüştürme
item1: API ile çalışmak için ihtiyacınız olan her şey ve bunları kodlamanıza yardımcı olacak yazı tipleriyle ilgili temel bilgiler hakkında daha fazla bilgi edinmek için [Belgelere](https://docs.aspose.com/font/) gidin ve kodladığınız dili seçin içinde.
item2: '[*Open()*](https://reference.aspose.com/font/net/aspose.font/font/open/) Yöntemini kullanarak TTF yazı tipini açın.'
item3: WOFF çıkış ayarlarını belirtin.
item4: "[*SaveToFormat()*](https://reference.aspose.com/font/net/aspose.font/font/savetoformat/) Yöntemini kullanarak TTF'yi WOFF'a dönüştürün ve WOFF'u olarak iletin [FontSavingFormats](https://reference.aspose.com/font/net/aspose.font/fontsavingformats/)."
---

{{<section feature2>}}
---
title: .NET Yazı Tipi API'sini Kullanmaya Başlayın
item1: Komut satırından ```nuget install Aspose.Font``` veya Visual Studio'nun Paket Yönetici Konsolu üzerinden ```Install-Package Aspose.Font`` ile kurun.
item2: Alternatif olarak, çevrimdışı MSI yükleyicisini veya DLL'leri [indirilenler](https://releases.aspose.com/font/net/) adresinden bir ZIP dosyasında alın.
item3: Platformlar arası Aspose [TTF to WOFF Converter](https://products.aspose.app/font/conversion/ttf-to-woff)'da bahsi geçen işlevselliğin gerçekleştirilmesi örneğine bakın. C# için Font API Çözümü ile nasıl çalışılacağına ilişkin daha fazla kod örneği almak için [GitHub](https://github.com/aspose-font/Aspose.Font-Documentation/tree/master/net-examples) depomuza gidin.NET.
---

{{<section codeexample>}}
---
title: C# kod örneği TTF'den WOFF'a dönüştürme
---