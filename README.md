# Final-project-3team
🌸 꽃동네 (Flower Neighborhood)

우리 동네 꽃집을 가장 쉽게 찾는 방법

꽃동네는 사용자의 위치 정보를 기반으로 주변 꽃집과 소비자를 연결하는 모바일 기반 O2O 플랫폼입니다.
소비자는 꽃다발, 꽃바구니 등 화훼 상품을 탐색 → 비교 → 주문 → 결제까지 하나의 플랫폼에서 해결할 수 있으며,
판매자는 별도의 온라인 쇼핑몰 구축 없이도 자신의 꽃집과 상품을 효과적으로 홍보하고 판매할 수 있습니다.

본 프로젝트는 위치 기반 서비스(GIS), REST API 설계, 관계형 데이터베이스 모델링, 생성형 AI 활용을 통해 실제 서비스 수준의 시스템 구현을 목표로 합니다.

📌 프로젝트 개요
항목	내용
프로젝트명	꽃동네 (Flower Neighborhood)
프로젝트 유형	위치 기반 O2O 플랫폼
개발 목적	지역 꽃집과 소비자를 연결하는 통합 플랫폼 구축
대상 사용자	꽃을 구매하려는 소비자 / 지역 꽃집 판매자
개발 기간	2026 졸업 프로젝트
플랫폼	Mobile App + Backend Server
🚀 프로젝트 배경

화훼 상품을 구매할 때 소비자는 다음과 같은 과정을 거치는 경우가 많습니다.

1️⃣ 인스타그램 / 블로그에서 꽃집 스타일 확인
2️⃣ 지도 앱에서 위치 검색
3️⃣ 전화 또는 카카오톡으로 가격 문의
4️⃣ 예약 가능 여부 확인

이처럼 정보가 여러 플랫폼에 분산되어 있어 구매 과정이 비효율적입니다.

또한 꽃집 판매자는

자체 쇼핑몰 구축 비용

SNS 마케팅 관리 부담

온라인 판매 환경 구축 어려움

등의 문제를 겪고 있습니다.

꽃동네는 이러한 문제를 해결하기 위해 기획되었습니다.

✨ 주요 기능
📍 위치 기반 꽃집 탐색

사용자 위치 기반 주변 꽃집 검색

지도 기반 꽃집 위치 표시

매장 운영 상태 확인

판매 상품 정보 확인

사용 기술

GPS

GIS (지도 API)

🌼 생성형 AI 상품 미리보기

사용자의 취향과 구매 기록을 기반으로
생성형 AI를 이용해 꽃다발 이미지를 생성합니다.

이를 통해 소비자는

원하는 스타일 확인

구매 전 상품 분위기 파악

만족도 높은 구매 경험

을 할 수 있습니다.

🏪 판매자 SNS 기능

꽃집 판매자는 앱 내에서

꽃 상품 사진 업로드

매장 홍보 포스팅

브랜드 스타일 소개

등의 SNS형 콘텐츠 기능을 사용할 수 있습니다.

🛒 주문 및 결제 시스템

상품 주문

결제 연동

주문 알림

예약 관리

등을 통해 판매자는 온라인 판매 환경을 쉽게 운영할 수 있습니다.

🏗 시스템 아키텍처
Mobile App (Flutter / React Native)
        │
        │ REST API
        ▼
Backend Server
(Django / Spring / Node)
        │
        │
        ▼
Database
(MySQL / PostgreSQL)

        │
        ▼
External Services
- 지도 API (GIS)
- 결제 API
- 생성형 AI API
🛠 기술 스택
Frontend

Flutter / React Native

지도 API

UI Framework

Backend

RESTful API

Server Framework

Authentication

Database

MySQL / PostgreSQL

RDB 모델링

AI

Generative AI Image Model

사용자 취향 기반 이미지 생성

기타

GitHub

Docker (optional)

Cloud Server

📂 프로젝트 구조 (예시)
flower-town
│
├─ backend
│   ├─ api
│   ├─ models
│   ├─ services
│   └─ controllers
│
├─ frontend
│   ├─ screens
│   ├─ components
│   └─ assets
│
├─ docs
│
└─ README.md
👥 팀원
이름	역할	전공
김건호	팀장	컴퓨터공학
정희원	개발	컴퓨터공학
신성현	개발	컴퓨터공학
🎯 기대 효과

본 프로젝트를 통해 다음과 같은 역량을 향상시킬 수 있습니다.

위치 기반 서비스(GIS) 구현 경험

RESTful API 설계 및 개발

관계형 데이터베이스 모델링

생성형 AI 모델 활용 경험

실제 서비스 수준의 시스템 설계 경험

또한 지역 꽃집과 소비자를 연결하는 플랫폼을 통해 로컬 화훼 시장 활성화에 기여하는 것을 목표로 합니다.

📌 향후 확장 가능성

꽃 정기 구독 서비스

AI 기반 꽃 추천 시스템

이벤트 / 기념일 자동 추천

지역 기반 꽃 배달 서비스
