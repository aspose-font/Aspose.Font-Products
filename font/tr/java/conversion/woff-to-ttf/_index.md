---
translation: true
template: /_templates/conversion-child-java.md
title: WOFF'tan TTF'ye Dönüştürücü API'sı | Java
description: Windows ve Linux'ta Java API kullanarak WOFF'u TTF'ye dönüştürün. Bu yerel WOFF'u TTF yazı tipi dönüştürme işlevini kendi çözümünüze entegre edin.
keywords: woff'tan ttf'ye java api, woff2ttf java çözümü, woff'tan ttf java'ya
url: /java/conversion/woff-to-ttf/
family: font
platformtag: java
feature: conversion
informat: WOFF
outformat: TTF
faq: faqchild
otherformats: WOFF2
---

{{<section banner>}}
---
h1: WOFF'yi TTF'ye dönüştür
h2: Java için WOFF'tan TTF'ye Dönüştürme işlevi. Yazı tiplerini dönüştürmek için API.
---

{{<section overview>}}
---
p1: Java tabanlı uygulamalarda yalnızca birkaç satır kodla WOFF'tan TTF'ye dönüştürme. С++ için Font API Çözümü ürününüze entegre etmek gerçekten çok kolay. Bu Java API, karakter kodları ve glif tanımlayıcıları arasındaki bir eşlemeyi temsil eden tüm yazı tipi türleri için kodlama bilgilerinin yanı sıra herhangi bir glif ile birlikte yazı tipi veri yapısı sağlar. API, istenen herhangi bir glif veya metnin yanı sıra hareket noktası, çizim çizgisi ve eğri vb. gibi basit grafik işlevleri kullanılarak arabirimler uygulanarak oluşturulabilen özel glifleri oluşturabilir.
p2: "Gadget'ların, ortamların, birkaç işletim sisteminin ve diğer birçok alanın farklı doğası nedeniyle, web sayfalarında, uygulamalarda ve yayınlarda farklı yazı tiplerini kullanmak gibi farklı amaçlara hizmet etmek için farklı yazı tipi biçimleri kullanmak. Bu nedenle, bazen gerekli ekranı karşılamak için WOFF yazı tipini farklı bir formatta başka bir yazı tipine dönüştürme ihtiyacıyla karşı karşıya kalabilirsiniz."
p3: "Giriş biçimleri olarak sonraki yazı tiplerini destekleyen Java Api Çözümü sunuyoruz: TrueType (TTF) ve Web Açık Yazı Tipi Biçimi (WOFF ve WOFF2)."
---

{{<section feature1>}}
---
title: Java'da WOFF'dan TTF'ye Dönüştürme
item1: API ile çalışmak için ihtiyacınız olan her şey ve bunları kodlamanıza yardımcı olacak yazı tipleriyle ilgili temel bilgiler hakkında daha fazla bilgi edinmek için [Belgelere](https://docs.aspose.com/font/) gidin ve kodladığınız dili seçin içinde.
item2: '[*Open()*](https://reference.aspose.com/font/java/com.aspose.font/Font#open-com.aspose.font.FontDefinition-) Yöntemini kullanarak WOFF yazı tipini açın.'
item3: TTF çıkış ayarlarını belirtin.
item4: "[*SaveToFormat()*](https://reference.aspose.com/font/java/com.aspose.font/Font#saveToFormat-java.io.OutputStream-com.aspose.font.FontSavingFormats-) kullanarak WOFF'u TTF'ye dönüştürün Yöntem ve TTF'yi [FontSavingFormats](https://reference.aspose.com/font/java/com.aspose.font/FontSavingFormats) olarak iletin."
---

{{<section feature2>}}
---
title: Dönüşüm Gereksinimleri
item1: "WOFF'dan TTF'ye dönüştürmeye devam etmek için Java Yazı Tipi API'si ana gereksinimdir."
item2: "Java tabanlı proje için doğrudan bir [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-font)'den Font API'sini alın ve kitaplıkları pom.xml'niz."
item3: "Alternatif olarak, [indirilenler](https://releases.aspose.com/font/java/) adresinden bir ZIP dosyası alabilirsiniz."
item4: Platformlar arası Aspose [WOFF to TTF Converter](https://products.aspose.app/font/conversion/woff-to-ttf)'de bahsedilen işlevselliğin gerçekleştirilme örneğine bakın. Java için Font API Çözümü ile nasıl çalışılacağına ilişkin daha fazla kod örneği almak için [GitHub](https://github.com/aspose-font/Aspose.Font-Documentation/tree/master/java-examples) depomuza gidin.
---

{{<section codeexample>}}
---
title: WOFF'den TTF'ye Dönüştürme için Java Kodu
---