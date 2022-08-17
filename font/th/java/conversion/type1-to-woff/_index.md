---
translation: true
template: /_templates/conversion-child-java.md
title: TYPE1 เป็น WOFF Converter API | Java
description: แปลง TYPE1 เป็น WOFF โดยใช้ Java API บน Windows และ Linux รวมฟังก์ชันการแปลงฟอนต์ TYPE1 ดั้งเดิมเข้ากับ WOFF เข้ากับโซลูชันของคุณเอง
keywords: type1 ถึง woff java api, โซลูชัน type12woff java, type1 ถึง woff java
url: /java/conversion/type1-to-woff/
family: font
platformtag: java
feature: conversion
informat: TYPE1
outformat: WOFF
faq: faqchild
otherformats: TTF WOFF2
---


{{<section banner>}}
---
h1: แปลง TYPE1 เป็น WOFF
h2: ฟังก์ชันการแปลง TYPE1 เป็น WOFF สำหรับ Java API เพื่อแปลงแบบอักษร
---

{{<section overview>}}
---
p1: การแปลง TYPE1 เป็น WOFF ภายในแอปพลิเคชันที่ใช้ Java ด้วยโค้ดเพียงไม่กี่บรรทัด Font API Solution สำหรับ С++ นั้นง่ายต่อการรวมเข้ากับผลิตภัณฑ์ของคุณ Java API นี้จัดเตรียมโครงสร้างข้อมูลฟอนต์พร้อมกับสัญลักษณ์ใดๆ รวมทั้งข้อมูลการเข้ารหัสสำหรับฟอนต์ทุกประเภทที่แสดงการแมประหว่างโค้ดอักขระและตัวระบุสัญลักษณ์ API สามารถแสดงสัญลักษณ์หรือข้อความที่ต้องการได้ เช่นเดียวกับร่ายมนตร์พิเศษ ซึ่งสามารถแสดงผลได้โดยใช้อินเทอร์เฟซโดยใช้ฟังก์ชันกราฟิกที่เรียบง่าย เช่น จุดเคลื่อนที่ ขีดเส้น และเส้นโค้ง เป็นต้น
p2: "เนื่องจากธรรมชาติของแกดเจ็ต สภาพแวดล้อม ระบบปฏิบัติการบางส่วน และพื้นที่อื่น ๆ อีกมากมายจึงต้องใช้รูปแบบแบบอักษรที่แตกต่างกันเพื่อให้บริการตามวัตถุประสงค์ที่แตกต่างกัน เช่น การใช้แบบอักษรที่แตกต่างกันบนหน้าเว็บ แอปพลิเคชัน และการเผยแพร่ ดังนั้นบางครั้งคุณอาจต้องเผชิญกับความจำเป็นในการแปลงแบบอักษร TYPE1 เป็นรูปแบบอื่นเพื่อให้ตรงกับการแสดงผลที่ต้องการ"
p3: "เราขอเสนอโซลูชัน Java Api ที่รองรับฟอนต์ถัดไปเป็นรูปแบบอินพุต: TrueType (TTF) และรูปแบบฟอนต์ Web Open (WOFF และ WOFF2)"
---

{{<section feature1>}}
---
title: การแปลง TYPE1 เป็น WOFF บน Java
item1: หากต้องการเรียนรู้เพิ่มเติมเกี่ยวกับสิ่งที่คุณต้องใช้ในการทำงานกับ API และข้อมูลพื้นฐานเกี่ยวกับแบบอักษรที่จะช่วยให้คุณเขียนโค้ดได้ ให้ไปที่[เอกสารประกอบ](https://docs.aspose.com/font/) และเลือกภาษาที่คุณเขียนโค้ด ใน.
item2: เปิดแบบอักษร TYPE1 โดยใช้ [*Open()*](https://reference.aspose.com/font/java/com.aspose.font/Font#open-com.aspose.font.FontDefinition-) วิธี
item3: ระบุการตั้งค่าเอาต์พุต WOFF
item4: แปลง TYPE1 เป็น WOFF โดยใช้ [*SaveToFormat()*](https://reference.aspose.com/font/java/com.aspose.font/Font#saveToFormat-java.io.OutputStream-com.aspose.font.FontSavingFormats-)   เมธอดและส่ง WOFF เป็น [FontSavingFormats](https://reference.aspose.com/font/java/com.aspose.font/FontSavingFormats)
---

{{<section feature2>}}
---
title: ข้อกำหนดการแปลง
item1: "ในการดำเนินการแปลง TYPE1 เป็น WOFF Java Font API เป็นข้อกำหนดหลัก"
item2: "รับ Font API โดยตรงจาก [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-font) สำหรับโปรเจ็กต์ที่ใช้ Java และรวมไลบรารีใน pom.xml ของคุณ"
item3: "หรือคุณสามารถรับไฟล์ ZIP จาก [ดาวน์โหลด](https://releases.aspose.com/font/java/)"
item4: ดูตัวอย่างการใช้งานฟังก์ชันดังกล่าวใน Aspose ข้ามแพลตฟอร์ม [ตัวแปลง TYPE1 เป็น WOFF](https://products.aspose.app/font/conversion/type1-to-woff) ไปที่ที่เก็บ [GitHub](https://github.com/aspose-font/Aspose.Font-Documentation/tree/master/java-examples) ของเราเพื่อรับตัวอย่างโค้ดเพิ่มเติมเกี่ยวกับวิธีการทำงานกับ Font API Solution สำหรับ Java
---

{{<section codeexample>}}
---
title: รหัส Java สำหรับการแปลง TYPE1 เป็น WOFF
---
