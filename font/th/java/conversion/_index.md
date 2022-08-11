---
translation: true
template: /_templates/conversion-java.md
title: API การแปลงแบบอักษร | Java
url: /java/conversion/
description: ฟังก์ชั่นการแปลงไฟล์ฟอนต์ Java แปลงฟอนต์ต่างๆ เช่น CFF, EOT, WOFF, TTF และ Type 1 ด้วยโค้ด Java สองสามบรรทัด
keywords: แปลงฟอนต์ java, แปลงฟอนต์ Java, ฟอนต์ coverter java
family: font
platformtag: java
feature: conversion
---

{{<section banner>}}
---
h1: แปลงแบบอักษร
h2: API ตัวแปลงรูปแบบฟอนต์สำหรับ Java แปลงฟอนต์ WOFF2, TTF, EOT และ CFF
---

{{<section overview>}}
---
p1: Java font API สามารถโหลด บันทึก และแปลงแบบอักษรต่างๆ เช่น CFF, OpenType, Type1 และ TrueType ได้อย่างง่ายดาย มันมีโครงสร้างข้อมูลฟอนต์พร้อมกับสัญลักษณ์ใด ๆ รวมถึงข้อมูลการเข้ารหัสสำหรับฟอนต์ทุกประเภทที่แสดงการแมประหว่างรหัสอักขระและตัวระบุสัญลักษณ์ API สามารถแสดงสัญลักษณ์หรือข้อความที่ต้องการได้ เช่นเดียวกับร่ายมนตร์พิเศษ ซึ่งสามารถแสดงผลได้โดยใช้อินเทอร์เฟซโดยใช้ฟังก์ชันกราฟิกที่เรียบง่าย เช่น จุดเคลื่อนที่ ขีดเส้น และเส้นโค้ง เป็นต้น
p2: "เนื่องจากธรรมชาติของแกดเจ็ต สภาพแวดล้อม ระบบปฏิบัติการบางส่วน และพื้นที่อื่น ๆ อีกมากมายจึงต้องใช้รูปแบบแบบอักษรที่แตกต่างกันเพื่อให้บริการตามวัตถุประสงค์ที่แตกต่างกัน เช่น การใช้แบบอักษรที่แตกต่างกันบนหน้าเว็บ แอปพลิเคชัน และการเผยแพร่ บางครั้งมีความจำเป็นต้องแปลงแบบอักษรหนึ่งเป็นแบบอักษรอื่นเพื่อให้ตรงกับการแสดงผลที่ต้องการ"
p3: "เราขอเสนอโซลูชัน Java Api ที่สนับสนุนแบบอักษรถัดไปเป็นรูปแบบเอาต์พุต: TrueType (TTF), รูปแบบแบบอักษร Web Open (WOFF และ WOFF2), รูปแบบ OpenType แบบฝัง (EOT), Type 1 และ Compact Font Format (CFF)"
---

{{<section feature1>}}
---
title: TrueType Font เป็น Web Open Font Format เวอร์ชัน 2.0 Conversion
item1: API รองรับแบบอักษรที่แตกต่างกันสำหรับการอ่านและการเขียน นี่คือ [รายการ](https://docs.aspose.com/font/java/convert/#formats-supported-for-reading-andor-writing) สำหรับการอ่านและการเขียน สำหรับการพิจารณาการแปลง TTF เป็น WOFF2 กระบวนการคือการโหลดฟอนต์จากรูปแบบที่รองรับ ฟอนต์ TrueType สำหรับสถานการณ์ปัจจุบัน ใช้วิธี [*SaveToFormat()*](https://reference.aspose.com/font/java/com.aspose.font/Font#saveToFormat-java.io.OutputStream-com.aspose.font.FontSavingFormats-) ของ [Font class](https://reference.aspose.com/font/java/com.aspose.font/Font#save-java.lang.String-) ที่มีพารามิเตอร์เอาต์พุตสตรีมสองตัวและ [*FontSavingFormats*](https://reference.aspose.com/font/java/com.aspose.font/Font#save-java.lang.String-) การแจงนับสำหรับการเลือกรูปแบบตัวอักษรที่ส่งออก
item2: สุดท้าย ให้เรียก SaveToFormat() เพื่อบันทึกฟอนต์เป็นรูปแบบเอาต์พุตที่รองรับ ซึ่งปัจจุบันเป็นรูปแบบ Web Open Font เวอร์ชัน 2.0 WOFF2
item3: หากต้องการดูฟังก์ชันการทำงานนี้ในแอปพลิเคชันข้ามแพลตฟอร์มจริง ให้ไปที่ [แอป Aspose Font Converter](https://products.aspose.app/font/conversion) คุณยังค้นหา[โซลูชัน API](https://products.aspose.app/font/applications) อื่นๆ อีกมากมายเพื่อทำงานกับแบบอักษรและข้อความได้จากที่นั่น
item4: ไปที่[เอกสารประกอบ](https://docs.aspose.com/font/net/) เพื่อรับข้อมูลที่จำเป็นทั้งหมดเพื่อเริ่มทำงานกับโซลูชัน เช่น บทแนะนำสำหรับคุณสมบัติหลักหรือชุดบทความที่จะสอนคุณ เกี่ยวกับแบบอักษร บันทึกประจำรุ่น คู่มือนักพัฒนา และสิ่งที่เป็นประโยชน์อื่นๆ
---

{{<section codeexample>}}
---
title: รหัส Java สำหรับการแปลง CFF เป็น TTF
---