---
title: AI 기반 랜덤 여행지 추천 및 경로 최적화 서비스
date: 2025-06-22
weight: 1
featured: true
links:
  - name: Frontend
    icon: brands/github
    url: https://github.com/imsh429/random-trip-frontend.git
  - name: Backend
    icon: brands/github
    url: https://github.com/imsh429/random-trip-backend.git
tags:
  - Full-Stack
  - Generative-AI(GPT API)
  - SpringBoot
  - Java
  - React
  - TypeScript
  - Main
---

<p style="text-align:justify;">
사용자의 감성과 실제 이동 동선을 결합한 지능형 여행 플래닝 서비스입니다. 사용자의 기분과 목적지에 맞춰 OpenAI가 장소를 큐레이션하고, 카카오 모빌리티 기술을 통해 최적화된 경로를 제공합니다.
</p>

## 💡 프로젝트 소개

이 서비스는 단순한 장소 나열을 넘어, **사용자의 감성과 실제 이동 동선을 결합**하는 데 집중했습니다. 사용자가 자신의 상태(기분)와 가고 싶은 지역을 선택하면, 생성형 AI(GPT)가 테마에 맞는 장소를 추천하고 카카오 모빌리티 기술을 통해 최적의 여행 코스를 완성합니다.

### 주요 해결 과제 및 성과
* **감성 기반 AI 큐레이션**: OpenAI API를 연동하여 사용자의 기분에 맞춘 맞춤형 장소 추천 로직을 구현했습니다.
* **실시간 경로 최적화**: 추천된 장소들을 Kakao Mobility API로 연결하여, 실제 도로 상황을 고려한 최적의 이동 순서와 경로를 지도 위에 시각화합니다.
* **보안 인증 체계 구축**: Kakao OAuth2와 JWT를 결합하여 소셜 로그인의 편의성과 토큰 기반 인증의 보안성을 동시에 확보했습니다.
* **데이터 관리 효율화**: JPA를 활용하여 사용자, 여행, 장소, 경로로 이어지는 복잡한 관계형 데이터를 체계적으로 모델링했습니다.

---

## 🛠 기술 스택

### Frontend
| 분류 | 기술 스택 | 역할 |
| :--- | :--- | :--- |
| **Framework** | React, TypeScript | 타입 안정성 확보 및 컴포넌트 기반 UI 개발 |
| **Styling** | Tailwind CSS | 유틸리티 기반의 신속하고 일관된 디자인 시스템 적용 |
| **State** | Recoil, Axios | 전역 상태 관리 및 JWT 인증 기반의 API 통신 |
| **Maps** | Kakao Maps API | 지도 시각화, 마커 및 경로 Polyline 표시 |
| **Build** | Vite | 빠른 개발 환경 구성 및 최적화된 번들링 |

### Backend
| 분류 | 기술 스택 | 역할 |
| :--- | :--- | :--- |
| **Core** | Java 17, Spring Boot 3 | 확장성 있는 서버 애플리케이션 구축 |
| **Security** | Spring Security, OAuth2, JWT | 카카오 소셜 로그인 및 보안 토큰 관리 |
| **Data** | JPA (Hibernate), MySQL | 객체 지향적 DB 설계 및 데이터 영속화 |
| **AI / Maps** | OpenAI API, Kakao Mobility | GPT 기반 장소 추천 및 경로 최적화 엔진 연동 |
| **Infra** | JCloud, GitHub Actions | 클라우드 서버 배포 및 CI/CD 파이프라인 자동화 |

---

## 🧭 주요 기능

* **AI 여행 플래닝**: 사용자의 기분과 선택 지역에 따른 GPT 맞춤형 장소 제안
* **랜덤 장소 큐레이션**: 지역 기반의 즉흥적인 랜덤 여행지 추천 기능
* **경로 최적화 시각화**: 카카오 모빌리티 API를 활용한 이동 경로 최적화 및 지도 표시
* **여행 기록 관리**: 확정된 여행 코스 저장 및 과거 여행 경로 다시 보기 기능
* **보안 로그인**: 카카오 계정 연동을 통한 간편한 인증 및 개인화 서비스 제공

---

## 🚀 개발 회고

> **API 오케스트레이션**: OpenAI의 비정형 데이터와 Kakao의 지리 정보를 하나의 서비스 흐름으로 결합하며 복합 API 연동 역량을 강화했습니다.

* **사용자 중심 설계**: 사용자가 최소한의 입력만으로 최대의 만족을 얻을 수 있도록 직관적인 UI/UX와 백엔드 로직을 긴밀하게 연결하는 경험을 쌓았습니다.
* **Full-Stack 개발 역량**: 프론트엔드부터 백엔드, DB 설계, 배포 자동화까지 서비스의 전체 생명 주기를 직접 경험하며 시스템 통합 능력을 키웠습니다.