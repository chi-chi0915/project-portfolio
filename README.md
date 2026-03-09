
# AI / Backend / Android Projects

AI 기반 서비스와 데이터 처리 파이프라인을 중심으로 다양한 프로젝트를 수행했습니다.
모션 인식, 음성 인식, RAG 기반 검색, 멀티모달 AI 등 여러 기술을 실제 서비스 형태로 구현하며
사용자 환경에서 동작하는 시스템을 설계하고 개발했습니다.

관심 분야
- AI 서비스 아키텍처 설계
- 데이터 파이프라인 및 검색 시스템(RAG)
- 모바일 및 IoT 환경에서 동작하는 AI 서비스


# Projects

## POLA

개인 데이터를 자동으로 정리하고 검색할 수 있는 AI 기반 개인 데이터 관리 서비스

기간  
2025.10 – 2025.11

주요 내용
- Cloud Vision OCR과 Gemini를 활용한 이미지 및 텍스트 분석
- Vertex AI Embedding 기반 개인 데이터 RAG 검색 시스템 구축
- 카테고리 태그 기반 자동 분류 시스템 설계
- Redis 임베딩 캐시를 통한 응답 속도 최적화
- 질문 의도 분류 및 동적 필터링(back-off) 기반 검색 안정성 개선

성과
- SSAFY 프로젝트 우수상
- SSAFY 전시 발표회 3등

기술
Spring Boot, OpenSearch, Redis, Vertex AI, Gemini, Google Vision AI


## EEUM

음성 명령을 통해 스마트홈 기기를 제어할 수 있는 음성 기반 IoT 서비스

기간  
2025.08 – 2025.10

주요 내용
- Wakeword → STT → NLU → Intent 구조의 음성 파이프라인 설계
- 약 79만 개 발화 패턴을 처리하는 규칙 기반 NLU 시스템 구현
- MQTT 기반 디바이스 제어 시스템 구축
- Android 음성 비서 앱 및 Foreground Service 구현
- Docker 및 Jenkins 기반 CI/CD 구축

기술
Spring Boot, Android, MQTT, Google STT, Docker, Jenkins, PostgreSQL


## MonFit

스마트워치 센서를 활용한 모션 인식 기반 AR 게임

기간  
2025.07 – 2025.08

주요 내용
- 스마트워치 가속도 및 자이로 센서 데이터 기반 모션 인식 모델 개발
- 6채널 시계열 데이터를 활용한 1D CNN 모델 구현
- 슬라이딩 윈도우 방식 데이터 증강으로 데이터 수집 효율 개선
- Wear OS – Android – Unity 실시간 통신 구조 설계
- 워치 온디바이스 실시간 추론 구현

성과
- SSAFY 프로젝트 우수상

기술
PyTorch, Android, Wear OS, Unity, Health Connect


## SSAFé

카페 주문 및 혜택 관리를 위한 모바일 서비스

기간  
2025.06 – 2025.07

주요 내용
- Android 기반 카페 서비스 앱 개발
- 쿠폰, 주문, 결제 등 사용자 기능 구현
- Spring Boot 기반 백엔드 서버 구축
- GPT API 기반 사용자 추천 기능 구현

기술
Android, Spring Boot, MySQL, OpenAI API


# Research

## 딥러닝을 이용한 시니어 비접촉 수면 무호흡 모니터링 어플

기간  
2022.03 – 2022.06

개요
UWB 기반 비접촉 호흡 센서를 활용하여 수면 중 호흡 데이터를 측정하고,
산소포화도 센서를 정답 레이블로 사용하여 CNN 모델을 학습한 연구이다.
학습된 모델은 수면 중 호흡 데이터만을 입력으로 받아 무호흡 여부를 판단하며,
결과는 Bluetooth 통신을 통해 모바일 애플리케이션에서 실시간으로 확인할 수 있도록 설계하였다.

주요 내용
- UWB 비접촉 호흡 센서를 활용한 호흡 데이터 수집
- 산소포화도 센서를 활용한 자동 라벨링 데이터 구축
- CNN 기반 딥러닝 모델을 활용한 수면 무호흡 탐지
- 모바일 앱을 통한 실시간 모니터링 시스템 구현

성과
- 한국정보기술학회 학술대회 발표
- 학술대회 은상 수상


## 심장 부정맥 유발 약물 스크리닝을 위한 합성곱 신경망 알고리즘의 개발

기간  
2021.03 – 2021.06

개요
심장 세포 시뮬레이션 데이터를 활용하여 약물의 부정맥 유발 위험을 분류하기 위한 CNN 기반 모델을 개발한 연구이다.
재분극 과정에서 나타나는 최대 기울기 값(dVm/dtmax_repol)을 입력 특징으로 사용하여
약물을 고위험, 중위험, 저위험으로 분류하는 딥러닝 모델을 구축하였다.

주요 내용
- 심장 세포 시뮬레이션 데이터 기반 약물 위험도 분류 연구
- 재분극 최대 기울기(dVm/dtmax_repol)를 입력 특징으로 사용
- CNN 모델을 활용한 약물 위험도 분류
- Stratified K-Fold를 통한 데이터 불균형 문제 완화

성과
- 한국정보기술학회 학술대회 발표
- 학술대회 은상 수상

모델 성능
- High Risk AUC: 0.89
- Intermediate Risk AUC: 0.79
- Low Risk AUC: 0.93


# Skills

AI / ML
PyTorch, CNN, Time-series Modeling, RAG, Embedding Search

Backend
Spring Boot, REST API, OpenSearch, Redis, MQTT

Mobile
Android, Wear OS

Infra
Docker, Jenkins, CI/CD
