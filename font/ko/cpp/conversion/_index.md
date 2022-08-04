---
translation: true
template: /_templates/conversion-cpp.md
title: 글꼴 변환 | C++
url: /cpp/conversion/
description: C++ 글꼴 처리 라이브러리 및 웹 응용 프로그램을 사용하여 글꼴을 변환합니다. TTF, WOFF, CFF, EOT 및 Type 1 글꼴과 함께 작동할 수 있는 변환 기능.
metakeywords: C++ 글꼴 변환, 글꼴 변환 솔루션 C++, 글꼴 변환기 cpp
family: font
platformtag: cpp
feature: conversion
---

{{<section banner>}}
---
h1: 글꼴 변환
h2: С++용 글꼴 형식 변환기 API. WOFF2, TTF, EOT 및 CFF 글꼴을 변환합니다.
---

{{<section overview>}}
---
p1: С++ 글꼴 API는 CFF, OpenType, Type1 및 TrueType 컬렉션과 같은 다양한 글꼴을 쉽게 로드, 저장 및 변환할 수 있습니다. 문자 코드와 글리프 식별자 간의 매핑을 나타내는 모든 글꼴 유형에 대한 인코딩 정보뿐만 아니라 모든 글리프와 함께 글꼴 데이터 구조를 제공합니다. API는 점 이동, 선 그리기, 곡선 등과 같은 간단한 그래픽 기능을 사용하여 인터페이스를 구현하여 렌더링할 수 있는 특수 문자뿐 아니라 원하는 글리프 또는 텍스트를 렌더링할 수 있습니다.
p2: "가제트, 환경, 몇 가지 운영 체제 및 기타 여러 영역의 다양한 특성으로 인해 웹 페이지, 응용 프로그램 및 게시에서 다른 글꼴을 사용하는 것과 같은 다양한 목적을 위해 다른 글꼴 형식을 사용합니다. 때때로 필요한 디스플레이를 충족시키기 위해 한 글꼴을 다른 글꼴로 변환해야 할 필요가 있습니다."
p3: "TrueType(TTF), Web Open Font Format(WOFF 및 WOFF2), Embedded OpenType 형식(EOT), Type 1 및 Compact Font Format(CFF)과 같은 다음 글꼴을 출력 형식으로 지원하는 С++ Api 솔루션을 제공합니다."
---

{{<section feature1>}}
---
title: 트루타입 글꼴을 웹 열기 글꼴 형식 버전 2.0으로 변환합니다.
item1: API는 읽기 및 쓰기를 위한 다양한 글꼴을 지원합니다. 읽기 및 쓰기를 위한 [목록](https://docs.aspose.com/font/cpp/convert/#formats-supported-for-reading-andor-writing)은 다음과 같습니다. TTF에서 WOFF2로의 변환을 고려하기 위해 프로세스는 현재 시나리오에 대해 지원되는 형식인 TrueType 글꼴에서 글꼴을 로드하는 것입니다. 출력 스트림과 [*FontSavingFormats*](https://reference.aspose.com/font/cpp/namespace/aspose.font#a93d0dcc7c00f5c7027d60e14a5433c74) 출력 글꼴 형식을 선택하기 위한 열거입니다.
item2: 마지막으로 SaveToFormat()을 호출하여 지원되는 출력 형식(현재 Web Open Font Format 버전 2.0 WOFF2 형식)으로 글꼴을 저장합니다.
item3: 실제 크로스 플랫폼 애플리케이션에서 구현된 이 기능을 보려면 [Aspose 글꼴 변환기 앱](https://products.aspose.app/font/conversion)으로 이동하십시오. 글꼴 및 텍스트 작업을 위한 더 많은 [API 솔루션](https://products.aspose.app/font/applications)을 찾을 수도 있습니다.
item4: '[Documentation](https://docs.aspose.com/font/net/)으로 이동하여 주요 기능에 대한 자습서 또는 가르칠 기사 세트와 같이 솔루션 작업을 시작하는 데 필요한 모든 정보를 얻으십시오. 글꼴, 릴리스 정보, 개발자 가이드 및 기타 유용한 정보를 제공합니다.'
---

{{<section codeexample>}}
---
title: C++ 코드 예제 TTF에서 WOFF2로 변환
---



