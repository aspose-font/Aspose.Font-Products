﻿---
translation: true
template: /_templates/conversion-child-java.md
title: CFF เป็น WOFF2 Converter API | Java
description: แปลง CFF เป็น WOFF โดยใช้ Java API บน Windows และ Linux รวมฟังก์ชันการแปลงฟอนต์ CFF ดั้งเดิมนี้เป็น WOFF เข้ากับโซลูชันของคุณเอง
keywords: cff ถึง woff2 java api, cff2woff2 โซลูชันจาวา cff ถึง woff2 java
url: /java/conversion/cff-to-woff2/
family: font
platformtag: java
feature: conversion
informat: CFF
outformat: WOFF2
faq: faqchild
otherformats: TTF WOFF
---

{{<section banner>}}
---
h1: แปลง CFF เป็น WOFF2
h2: ฟังก์ชันการแปลง CFF เป็น WOFF2 สำหรับ Java API เพื่อแปลงแบบอักษร
---

{{<section overview>}}
---
p1: การแปลง CFF เป็น WOFF2 ภายในแอปพลิเคชันที่ใช้ Java ด้วยโค้ดเพียงไม่กี่บรรทัด Font API Solution สำหรับ С++ นั้นง่ายต่อการรวมเข้ากับผลิตภัณฑ์ของคุณ Java API นี้จัดเตรียมโครงสร้างข้อมูลฟอนต์พร้อมกับสัญลักษณ์ใดๆ รวมทั้งข้อมูลการเข้ารหัสสำหรับฟอนต์ทุกประเภทที่แสดงการแมประหว่างโค้ดอักขระและตัวระบุสัญลักษณ์ API สามารถแสดงสัญลักษณ์หรือข้อความที่ต้องการได้ เช่นเดียวกับร่ายมนตร์พิเศษ ซึ่งสามารถแสดงผลได้โดยใช้อินเทอร์เฟซโดยใช้ฟังก์ชันกราฟิกที่เรียบง่าย เช่น จุดเคลื่อนที่ ขีดเส้น และเส้นโค้ง เป็นต้น
p2: "เนื่องจากธรรมชาติของแกดเจ็ต สภาพแวดล้อม ระบบปฏิบัติการบางส่วน และพื้นที่อื่น ๆ อีกมากมายจึงต้องใช้รูปแบบแบบอักษรที่แตกต่างกันเพื่อให้บริการตามวัตถุประสงค์ที่แตกต่างกัน เช่น การใช้แบบอักษรที่แตกต่างกันบนหน้าเว็บ แอปพลิเคชัน และการเผยแพร่ ดังนั้นบางครั้งคุณอาจต้องเผชิญกับความต้องการแปลงแบบอักษร CFF เป็นรูปแบบอื่นเพื่อให้ตรงกับการแสดงผลที่ต้องการ"
p3: "เราขอเสนอโซลูชัน Java Api ที่รองรับฟอนต์ถัดไปเป็นรูปแบบอินพุต: TrueType (TTF) และรูปแบบฟอนต์ Web Open (WOFF และ WOFF2)"
---

{{<section feature1>}}
---
title: การแปลง CFF เป็น WOFF2 บน Java
item1: หากต้องการเรียนรู้เพิ่มเติมเกี่ยวกับสิ่งที่คุณต้องใช้ในการทำงานกับ API และข้อมูลพื้นฐานเกี่ยวกับแบบอักษรที่จะช่วยให้คุณเขียนโค้ดได้ ให้ไปที่[เอกสารประกอบ](https://docs.aspose.com/font/) และเลือกภาษาที่คุณเขียนโค้ด ใน.
item2: เปิดแบบอักษร CFF โดยใช้ [*Open()*](https://reference.aspose.com/font/java/com.aspose.font/Font#open-com.aspose.font.FontDefinition-) วิธี
item3: ระบุการตั้งค่าเอาต์พุต WOFF2
item4: แปลง CFF เป็น WOFF2 โดยใช้ [*SaveToFormat()*](https://reference.aspose.com/font/java/com.aspose.font/Font#saveToFormat-java.io.OutputStream-com.aspose.font.FontSavingFormats-)   เมธอดและส่ง WOFF2 เป็น [FontSavingFormats](https://reference.aspose.com/font/java/com.aspose.font/FontSavingFormats)
---

{{<section feature2>}}
---
title: ข้อกำหนดการแปลง
item1: "ในการดำเนินการแปลง CFF เป็น WOFF2 Java Font API เป็นข้อกำหนดหลัก"
item2: "รับ Font API โดยตรงจาก [Aspose Maven Repository](https://repository.aspose.com/font/) สำหรับโปรเจ็กต์ที่ใช้ Java และรวมไลบรารีใน pom.xml ของคุณ"
item3: "หรือคุณสามารถรับไฟล์ ZIP จาก [ดาวน์โหลด](https://releases.aspose.com/font/java/)"
item4: ดูตัวอย่างการใช้งานฟังก์ชันที่กล่าวถึงใน Aspose ข้ามแพลตฟอร์ม [CFF to WOFF2 Converter](https://products.aspose.app/font/conversion/cff-to-woff2) ไปที่ที่เก็บ [GitHub](https://github.com/aspose-font/Aspose.Font-Documentation/tree/master/java-examples) ของเราเพื่อรับตัวอย่างโค้ดเพิ่มเติมเกี่ยวกับวิธีการทำงานกับ Font API Solution สำหรับ Java
---

{{<section codeexample>}}
---
title: รหัส Java สำหรับการแปลง CFF เป็น WOFF2
---