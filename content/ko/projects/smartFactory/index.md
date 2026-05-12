---
title: 클라우드 기반 지능형 스마트팩토리 통합 관제 시스템
date: 2025-12-18
weight: 1
featured: true
links:
  - name: Smart-Factory-Project
    icon: brands/github
    url: https://github.com/imsh429/Smart-Factory-Project.git
  - name: 발표 자료
    url: uploads/cloud_computing.pdf
tags:
  - Cloud-Native
  - Serverless
  - Predictive Maintenance
  - AWS
  - Main
---

<p style="text-align:justify;">
현대적인 스마트 팩토리 환경에서는 초당 수천 개의 IoT 센서 데이터가 쏟아집니다. 이 프로젝트는 단순한 데이터 수집을 넘어, <b>'트래픽 폭주에도 굴하지 않는 가용성'</b>과 <b>'데이터 기반의 예지 보전'</b>을 실현한 클라우드 네이티브 관제 시스템입니다.
</p>

## 💡 프로젝트 소개

기존 스마트 팩토리 시스템이 가진 단일 처리 구조의 한계를 극복하기 위해 Loose Coupling과 **Serverless** 아키텍처를 핵심 원칙으로 삼았습니다. 데이터 수집부터 이상 탐지, 자가 복구, 그리고 시각화에 이르기까지 전 과정을 완전 자동화된 파이프라인으로 구축했습니다.


### 주요 해결 과제 및 성과
* **고가용성 파이프라인**: API Gateway와 SNS Fan-out 구조를 도입하여 초당 수천 건의 트래픽을 지연 없이 병렬 처리합니다.
* **지능형 예지 보전**: Amazon Athena를 활용해 누적된 Cold Data의 표준편차를 분석, 장비의 불안정 지수가 5.0을 초과할 경우 잠재적 결함으로 판단하여 사전 경고를 발생시킵니다.
* **자가 복구 시스템 (Fault Tolerance)**: 처리 실패 데이터가 발생하면 SQS DLQ가 이를 격리하고, Step Functions가 주기적으로 재처리를 시도하여 **데이터 유실 Zero**를 달성했습니다.
* **데이터 이원화 전략**: 즉각적인 모니터링을 위한 Hot Data(DynamoDB)와 장기 분석용 Cold Data(S3)를 분리하여 시스템 효율성을 극대화했습니다.

---

## 🛠 기술 스택

본 프로젝트는 비용 효율성과 확장성을 최우선으로 고려하여 선별된 기술들을 사용합니다.

### **Cloud Infrastructure (AWS)**
| 분류 | 서비스 | 역할 |
| :--- | :--- | :--- |
| **Compute** | **Lambda**, **Step Functions** | 서버리스 로직 실행 및 복구 워크플로우 오케스트레이션 |
| **Messaging** | **SNS**, **SQS**, **EventBridge** | 서비스 간 비동기 결합 및 장애 격리(DLQ), 스케줄링 |
| **Storage** | **DynamoDB**, **S3** | 실시간 상태 저장(NoSQL) 및 대용량 원시 데이터 로그 저장 |
| **Analytics** | **Athena** | S3에 저장된 비정형 데이터 대상 표준편차 기반 SQL 분석 |
| **Gateway** | **API Gateway** | IoT 장비 데이터 수집을 위한 RESTful 엔드포인트 |

### **Development & Visualization**
* **Language**: Python (3.9+)
* **Framework**: Streamlit (실시간 관제 및 분석 대시보드 구축)
* **Data Library**: Pandas (데이터 전처리), Plotly (인터랙티브 차트 시각화)
* **DevOps**: CloudWatch를 통한 전 계층 모니터링 및 로깅

---

## 📈 시스템 아키텍처 진화
초기 통합형 Lambda 구조에서 발생하던 쓰로틀링 문제를 해결하기 위해, **SNS를 필두로 한 Fan-out 아키텍처**로 고도화했습니다. 이를 통해 저장 로직과 이상 탐지 로직을 분리하여 유지보수성과 장애 격리 능력을 비약적으로 향상시켰습니다.

<!--more-->
