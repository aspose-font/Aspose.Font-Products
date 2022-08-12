---
translation: true
template: /_templates/conversion-child-cpp.md
title: WOFF เป็น WOFF2 Converter API | C++
description: แปลง WOFF เป็น WOFF2 Fonts โดยใช้ C ++ API นี้ ฟังก์ชันการแปลงทำงานบน Windows และ Linux และในสภาพแวดล้อมการพัฒนาใดๆ ที่รองรับ C++
metakeywords: c ++ WOFF เป็น WOFF2, โซลูชัน WOFF เป็น WOFF2 c ++, WOFF เป็น WOFF2 ตัวสร้างฟอนต์ cpp
url: /cpp/conversion/woff-to-woff2/
family: font
platformtag: cpp
feature: conversion
otherformats: TTF
---

{{<section banner>}}
---
h1: แปลง WOFF เป็น WOFF2
h2: ฟังก์ชันการแปลง WOFF เป็น WOFF สำหรับ C ++ API เพื่อแปลงแบบอักษร
---

{{<section overview>}}
---
p1: การแปลง WOFF เป็น WOFF2 ภายในแอปพลิเคชันที่ใช้ С++ ด้วยโค้ดเพียงไม่กี่บรรทัด Font API Solution สำหรับ С++ นั้นง่ายต่อการรวมเข้ากับผลิตภัณฑ์ของคุณ C ++ API นี้มีโครงสร้างข้อมูลแบบอักษรพร้อมกับสัญลักษณ์ใดๆ รวมทั้งข้อมูลการเข้ารหัสสำหรับแบบอักษรทุกประเภทที่แสดงถึงการจับคู่ระหว่างรหัสอักขระและตัวระบุสัญลักษณ์ API สามารถแสดงสัญลักษณ์หรือข้อความที่ต้องการได้ เช่นเดียวกับร่ายมนตร์พิเศษ ซึ่งสามารถแสดงผลได้โดยใช้อินเทอร์เฟซโดยใช้ฟังก์ชันกราฟิกที่เรียบง่าย เช่น จุดเคลื่อนที่ ขีดเส้น และเส้นโค้ง เป็นต้น
p2: "เนื่องจากธรรมชาติของแกดเจ็ต สภาพแวดล้อม ระบบปฏิบัติการบางส่วน และพื้นที่อื่น ๆ อีกมากมายจึงต้องใช้รูปแบบแบบอักษรที่แตกต่างกันเพื่อให้บริการตามวัตถุประสงค์ที่แตกต่างกัน เช่น การใช้แบบอักษรที่แตกต่างกันบนหน้าเว็บ แอปพลิเคชัน และการเผยแพร่ ดังนั้นบางครั้งคุณอาจต้องเผชิญกับความจำเป็นในการแปลงฟอนต์ WOFF เป็นรูปแบบอื่นเพื่อให้ตรงกับการแสดงผลที่ต้องการ"
p3: "เราขอเสนอ С++ Api Solution ที่รองรับฟอนต์ถัดไปเป็นรูปแบบอินพุต: TrueType (TTF) และ Web Open Font Format (WOFF และ WOFF2)"
---

{{<section feature1>}}
---
title: การแปลง WOFF เป็น WOFF2 บน C++
item1: หากต้องการเรียนรู้เพิ่มเติมเกี่ยวกับสิ่งที่คุณต้องใช้ในการทำงานกับ API และข้อมูลพื้นฐานเกี่ยวกับแบบอักษรที่จะช่วยให้คุณเขียนโค้ดได้ ให้ไปที่[เอกสารประกอบ](https://docs.aspose.com/font/) และเลือกภาษาที่คุณเขียนโค้ด ใน.
item2: เปิดฟอนต์ WOFF โดยใช้ [*Open()*](https://reference.aspose.com/font/cpp/class/aspose.font.font#ac2387bf04ccb5bac51cf37984d4ebf33) วิธีการ
item3: ระบุการตั้งค่าเอาต์พุต WOFF2
item4: แปลง WOFF เป็น WOFF2 โดยใช้ [*SaveToFormat()*](https://reference.aspose.com/font/cpp/class/aspose.font.font#a670ea97404fd72c2e51b0e8c543c8a45) Method และส่ง WOFF2 เป็น [FontSavingFormats](https://reference.aspose.com/font/cpp/namespace/aspose.font#a93d0dcc7c00f5c7027d60e14a5433c74)
---

{{<section feature2>}}
---
title: เริ่มต้นใช้งาน C++ Font API
item1: ติดตั้งจากบรรทัดคำสั่งเป็น ``` ติดตั้ง nuget Aspose.Font.Cpp``` หรือผ่าน Package Manager Console ของ Visual Studio ด้วย ```Install-Package Aspose.Font.Cpp```
item2: หรือรับตัวติดตั้ง MSI แบบออฟไลน์หรือ DLL ในไฟล์ ZIP จาก [ดาวน์โหลด](https://releases.aspose.com/font/cpp/)
item3: ดูตัวอย่างการใช้งานฟังก์ชันที่กล่าวถึงใน Aspose ข้ามแพลตฟอร์ม [ตัวแปลง WOFF เป็น WOFF2](https://products.aspose.app/font/conversion/woff-to-woff2) ไปที่ที่เก็บ [GitHub](https://github.com/aspose-font/Aspose.Font-Documentation/tree/master/cpp-examples) ของเราเพื่อรับตัวอย่างโค้ดเพิ่มเติมเกี่ยวกับวิธีการทำงานกับ Font API Solution สำหรับ C++
---

{{<section codeexample>}}
---
title: ตัวอย่างโค้ด C++ การแปลง WOFF เป็น WOFF2
---