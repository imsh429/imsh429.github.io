---
title: 실시간 일정 관리 TODO APP
date: 2025-12-18
weight: 1
featured: true
links:
  - name: Web
    icon: brands/github
    url: https://github.com/imsh429/todo-app.git
  - name: Mobile
    icon: brands/github
    url: https://github.com/imsh429/todo-app-mobile.git
tags:
  - Vue.js
  - Flutter
  - Firebase
  - Cross-Platform
  - Side
---

<p style="text-align:justify;">
웹과 모바일 환경 어디에서나 중단 없는 일정 관리 경험을 제공하기 위해 개발된 <b>크로스 플랫폼 투두 애플리케이션</b>입니다. Vue 3 기반의 웹 서비스와 Flutter 기반의 모바일 앱을 병행 개발하였으며, <b>Firebase</b>를 공통 백엔드로 활용하여 플랫폼 간 데이터의 실시간 동기화를 구현했습니다. 캘린더 인터페이스를 통해 사용자가 자신의 생산성을 직관적으로 관리할 수 있도록 돕습니다.
</p>

## 💡 프로젝트 소개

단일 플랫폼의 한계를 넘어, 데스크톱 브라우저와 모바일 기기 모두에서 동일한 데이터에 접근하고 관리할 수 있는 **'통합 일정 관리 시스템'** 구축을 목표로 했습니다. Firebase Cloud Firestore의 리얼타임 리스너를 활용하여 웹에서 수정한 일정이 모바일 앱에 즉시 반영되는 용자 경험을 제공하는 데 집중했습니다.

### 주요 기능
* **통합 사용자 인증 (Auth)**: Google OAuth를 이용한 소셜 로그인 시스템을 통해 웹과 모바일 모두에서 간편하고 안전한 인증 체계를 구축했습니다.
* **실시간 데이터 동기화 (Sync)**: NoSQL 기반의 Firestore를 연동하여 오프라인 환경에서 온라인으로 전환 시 데이터 유실 없는 즉각적인 동기화를 보장합니다.
* **시각적 일정 관리 (Calendar)**: FullCalendar(Web) 및 맞춤형 캘린더 UI(Mobile)를 도입하여 단순 목록형 관리를 넘어 날짜별 흐름을 한눈에 파악할 수 있게 설계했습니다.
* **사용자 친화적 UI/UX**: 다이얼로그(Dialog) 기반의 입력 인터페이스와 직관적인 상태 토글 기능을 통해 조작 편의성을 극대화했습니다.

---

## 🛠 기술 스택

각 플랫폼에 최적화된 최신 프레임워크를 선정하여 개발 효율성과 퍼포먼스를 동시에 확보했습니다.

### **Common Backend**
* **Firebase Auth**: 구글 계정 기반 통합 사용자 인증 관리
* **Cloud Firestore**: 웹/모바일 실시간 동기화를 위한 NoSQL 데이터베이스

### **Web Application**
* **Framework**: Vue 3 (Composition API) + Vite
* **State Management**: Pinia (인증 상태 및 일정 데이터 전역 관리)
* **UI Library**: PrimeVue, Tailwind CSS
* **Deployment**: JCLOUD 기반 배포 완료

### **Mobile Application**
* **Framework**: Flutter (Dart)
* **State Management**: Provider (효율적인 위젯 트리 상태 관리)
* **Build Tool**: Gradle (안드로이드 배포 빌드 및 Keystore 보안 서명 적용)

---

## 🚀 개발 성과 및 회고

* **멀티 플랫폼 연동 역량**: 동일한 백엔드(Firebase)를 공유하며 성격이 다른 두 프레임워크(Vue, Flutter)를 유기적으로 연결하는 풀스택 개발 과정을 경험했습니다.
* **상태 관리 최적화**: 웹의 Pinia와 모바일의 Provider를 각각 적용하며 플랫폼별 특성에 맞는 최적의 전역 상태 관리 아키텍처를 구현했습니다.
* **실무적 배포 경험**: JCLOUD를 통한 웹 서비스 배포와 안드로이드 APK 빌드 및 서명 과정을 직접 수행하여 실제 서비스 릴리즈의 전 과정을 마쳤습니다.