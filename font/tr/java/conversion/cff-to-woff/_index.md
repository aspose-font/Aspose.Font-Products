﻿---
translation: true
template: /_templates/conversion-child-java.md
title: CFF'den WOFF'a Dönüştürücü API'sı | Java
description: Windows ve Linux'ta Java API kullanarak CFF'yi WOFF'a dönüştürün. Bu yerel CFF'yi WOFF yazı tipi dönüştürme işlevini kendi çözümünüze entegre edin.
keywords: cff'den java api'ye, cff2woff java çözümüne, cff'den java'ya
url: /java/conversion/cff-to-woff/
family: font
platformtag: java
feature: conversion
otherformats: TTF WOFF2
---

{{<section banner>}}
---
h1: CFF'yi WOFF'ye dönüştür
h2: Java için CFF'den WOFF'a Dönüştürme işlevi. Yazı tiplerini dönüştürmek için API.
---

{{<section overview>}}
---
p1: Java tabanlı uygulamalarda sadece birkaç satır kodla CFF'den WOFF'a dönüştürme. С++ için Font API Çözümü ürününüze entegre etmek gerçekten çok kolay. Bu Java API, karakter kodları ve glif tanımlayıcıları arasındaki bir eşlemeyi temsil eden tüm yazı tipi türleri için kodlama bilgilerinin yanı sıra herhangi bir glif ile birlikte yazı tipi veri yapısı sağlar. API, istenen herhangi bir glif veya metnin yanı sıra hareket noktası, çizim çizgisi ve eğri vb. gibi basit grafik işlevleri kullanılarak arabirimler uygulanarak oluşturulabilen özel glifleri oluşturabilir.
p2: "Gadget'ların, ortamların, birkaç işletim sisteminin ve diğer birçok alanın farklı doğası nedeniyle, web sayfalarında, uygulamalarda ve yayınlarda farklı yazı tiplerini kullanmak gibi farklı amaçlara hizmet etmek için farklı yazı tipi biçimleri kullanmak. Bu nedenle, bazen gerekli ekranı karşılamak için CFF yazı tipini farklı bir formatta başka bir yazı tipine dönüştürme ihtiyacıyla karşı karşıya kalabilirsiniz."
p3: "Giriş biçimleri olarak sonraki yazı tiplerini destekleyen Java Api Çözümü sunuyoruz: TrueType (TTF) ve Web Açık Yazı Tipi Biçimi (WOFF ve WOFF2)."
---

{{<section feature1>}}
---
title: Java'da CFF'den WOFF'a Dönüştürme
item1: API ile çalışmak için ihtiyacınız olan her şey ve bunları kodlamanıza yardımcı olacak yazı tipleriyle ilgili temel bilgiler hakkında daha fazla bilgi edinmek için [Belgelere](https://docs.aspose.com/font/) gidin ve kodladığınız dili seçin içinde.
item2: '[*Open()*](https://reference.aspose.com/font/java/com.aspose.font/Font#open-com.aspose.font.FontDefinition-) Yöntemini kullanarak CFF yazı tipini açın.'
item3: WOFF çıkış ayarlarını belirtin.
item4: "[*SaveToFormat()*](https://reference.aspose.com/font/java/com.aspose.font/Font#saveToFormat-java.io.OutputStream-com.aspose.font.FontSavingFormats-) kullanarak CFF'yi WOFF'a dönüştürün Yöntem ve WOFF'u [FontSavingFormats](https://reference.aspose.com/font/java/com.aspose.font/FontSavingFormats) olarak iletin."
---

{{<section feature2>}}
---
title: Dönüşüm Gereksinimleri
item1: "CFF'den WOFF'a dönüştürmeye devam etmek için Java Yazı Tipi API'si ana gereksinimdir."
item2: "Java tabanlı proje için doğrudan bir [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-font)'den Font API'sini alın ve kitaplıkları pom.xml'niz."
item3: "Alternatif olarak, [indirilenler](https://downloads.aspose.com/font/java) adresinden bir ZIP dosyası alabilirsiniz."
item4: Bahsedilen işlevselliğin platformlar arası Aspose [CFF to WOFF Converter](https://products.aspose.app/font/conversion/cff-to-woff) uygulamasında gerçekleştirilme örneğine bakın. Java için Font API Çözümü ile nasıl çalışılacağına ilişkin daha fazla kod örneği almak için [GitHub](https://github.com/aspose-font/Aspose.Font-Documentation/tree/master/java-examples) depomuza gidin.
---

{{<section codeexample>}}
---
title: CFF'den WOFF'a Dönüştürme için Java Kodu
---