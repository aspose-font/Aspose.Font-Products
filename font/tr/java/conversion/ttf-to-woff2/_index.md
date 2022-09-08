---
translation: true
template: /_templates/conversion-child-java.md
title: TTF'den WOFF2'ye Dönüştürücü API'sı | Java
description: Windows ve Linux'ta Java API kullanarak TTF'yi WOFF2'ye dönüştürün. Bu yerel TTF'yi WOFF2 yazı tipi dönüştürme işlevini kendi çözümünüze entegre edin.
keywords: ttf'den woff2'ye java api, ttf2woff2 java çözümü, ttf'den woff2 java'ya
url: /java/conversion/ttf-to-woff2/
family: font
platformtag: java
feature: conversion
informat: WOFF
outformat: TTF
faq: faqchild
otherformats: WOFF
---

{{<section banner>}}
---
h1: TTF'yi WOFF2'ye Dönüştür
h2: Java için TTF'den WOFF2'ye Dönüştürme işlevi. Yazı tiplerini dönüştürmek için API.
---

{{<section overview>}}
---
p1: Java tabanlı uygulamalarda yalnızca birkaç satır kodla TTF'den WOFF2'ye dönüştürme. С++ için Font API Çözümü ürününüze entegre etmek gerçekten çok kolay. Bu Java API, karakter kodları ve glif tanımlayıcıları arasındaki bir eşlemeyi temsil eden tüm yazı tipi türleri için kodlama bilgilerinin yanı sıra herhangi bir glif ile birlikte yazı tipi veri yapısı sağlar. API, istenen herhangi bir glif veya metnin yanı sıra hareket noktası, çizim çizgisi ve eğri vb. gibi basit grafik işlevleri kullanılarak arabirimler uygulanarak oluşturulabilen özel glifleri oluşturabilir.
p2: "Gadget'ların, ortamların, birkaç işletim sisteminin ve diğer birçok alanın farklı doğası nedeniyle, web sayfalarında, uygulamalarda ve yayınlarda farklı yazı tiplerini kullanmak gibi farklı amaçlara hizmet etmek için farklı yazı tipi biçimleri kullanmak. Bu nedenle, bazen gerekli ekranı karşılamak için TTF yazı tipini farklı bir formatta başka bir yazı tipine dönüştürme ihtiyacıyla karşı karşıya kalabilirsiniz."
p3: "Giriş biçimleri olarak sonraki yazı tiplerini destekleyen Java Api Çözümü sunuyoruz: TrueType (TTF) ve Web Açık Yazı Tipi Biçimi (WOFF ve WOFF2)."
---

{{<section feature1>}}
---
title: Java'da TTF'den WOFF2'ye Dönüştürme
item1: API ile çalışmak için ihtiyacınız olan her şey ve bunları kodlamanıza yardımcı olacak yazı tipleriyle ilgili temel bilgiler hakkında daha fazla bilgi edinmek için [Belgelere](https://docs.aspose.com/font/) gidin ve kodladığınız dili seçin içinde.
item2: '[*Open()*](https://reference.aspose.com/font/java/com.aspose.font/Font#open-com.aspose.font.FontDefinition-) Yöntemini kullanarak TTF yazı tipini açın.'
item3: WOFF2 çıkış ayarlarını belirtin.
item4: "[*SaveToFormat()*](https://reference.aspose.com/font/java/com.aspose.font/Font#saveToFormat-java.io.OutputStream-com.aspose.font.FontSavingFormats-) kullanarak TTF'yi WOFF2'ye dönüştürün Yöntem ve WOFF2'yi [FontSavingFormats](https://reference.aspose.com/font/java/com.aspose.font/FontSavingFormats) olarak iletin."
---

{{<section feature2>}}
---
title: Dönüşüm Gereksinimleri
item1: "TTF'den WOFF2'ye dönüştürmeye devam etmek için Java Yazı Tipi API'si ana gereksinimdir."
item2: "Java tabanlı proje için doğrudan bir [Aspose Maven Repository](https://repository.aspose.com/font/)'den Font API'sini alın ve kitaplıkları pom.xml'niz."
item3: "Alternatif olarak, [indirilenler](https://releases.aspose.com/font/java/) adresinden bir ZIP dosyası alabilirsiniz."
item4: Platformlar arası Aspose [TTF to WOFF2 Converter](https://products.aspose.app/font/conversion/ttf-to-woff2)'de bahsedilen işlevselliğin gerçekleştirilme örneğine bakın. Java için Font API Çözümü ile nasıl çalışılacağına ilişkin daha fazla kod örneği almak için [GitHub](https://github.com/aspose-font/Aspose.Font-Documentation/tree/master/java-examples) depomuza gidin.
---

{{<section codeexample>}}
---
title: TTF'den WOFF2'ye Dönüştürme için Java Kodu
---
