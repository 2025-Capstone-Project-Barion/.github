# 배리온(Barion): On-Device AI 기반 스마트 배리어프리 키오스크 플렛폼

<p align="center">
  <img src="https://github.com/user-attachments/assets/eacb4e32-7059-4a9c-a345-d5083d3ee58a" alt="Barion 로고" width="100"/>
</p>

> **Barrier-Free + Innovation(혁신): 배리어프리를 넘어 On-Device AI 기반의 더 스마트한 혁신적 솔루션**

## 2025 캡스톤 프로젝트
- **개발자**: 2071449 이원준

## 📋 프로젝트 개요

### 문제 제기
2025년 1월 28일부로 시행된 배리어프리 키오스크 설치 의무화(장애인차별금지법 개정)에 따라 소상공인들은 상당한 경제적 부담을 겪고 있습니다. 일반 키오스크 대비 최대 3배까지 비싼 가격(약 800만원), 낮은 제도 인지도, 그리고 실효성에 대한 의문으로 소상공인들의 고충이 커지고 있습니다.

기존에 인건비 절감과 운영 효율성 강화를 위해 키오스크를 도입했지만, 현재는 "굳이 키오스크를 사용할 필요가 없다"는 의견이 많아지고 있는 상황입니다. 실제로 소상공인의 85% 이상이 변경 의무화에 대해 인지하지 못하고 있으며, 비용부담과 교체 과정의 불편함이 큰 문제가 되고 있습니다.

### 프로젝트 목표
본 프로젝트는 **Rubik Pi3**, **20인치 터치 디스플레이**, **안드로이드 앱**, **AWS**, **센서 및 모터**를 활용하여 소상공인의 부담을 줄이면서도 접근성이 강화된 배리어프리 스마트 키오스크를 개발하는 것을 목표로 합니다.

기기의 전면 교체 없이, 간단한 모듈 교체 및 소프트웨어 업데이트만으로 기존 키오스크를 배리어프리 키오스크로 변환할 수 있는 솔루션을 제공합니다.

## 🌟 핵심 가치

- **접근성**: 장애 유형(시각, 청각, 지체 등), 노인, 외국인 등 신체적, 언어적 장벽을 넘어 누구나 쉽게 사용할 수 있는 서비스 제공
- **경제성**: 모듈형 설계, AI 모델을 적극 활용하여 하드웨어적 요소를 최소화하고 소프트웨어적으로 효율적인 기술 적용, 정부 지원 사업 연계를 통한 초기 도입 비용 및 유지 보수 비용 경감
- **편의성**: 직관적인 UI/UX, 음성 인식, 센서 및 모터 활용을 통한 사용자 경험 극대화
- **효율성**: 소상공인의 운영 효율성을 높이고, 고객 만족도 향상

## 💡 주요 기능

### 1. AI 기반 음성 인식 (TTS/STT)
- **Whisper-Tiny-EN 모델 (Qualcomm AI Hub)**: 고성능 음성 인식 모델을 활용한 정확한 음성 명령 인식
- **자연어 처리**: 단순 명령어를 넘어 자연스러운 대화 형태로 키오스크 조작 가능
  - 예: "햄버거 세트 하나랑 콜라 라지 사이즈로 줘" → 정확히 인식하여 주문 반영
- **다국어 음성 지원**: 영어, 중국어, 일본어 등 주요 언어 지원
- **음성 안내**: 메뉴, 옵션, 결제 방법, 사용 안내 등을 음성으로 제공

### 2. 접근성 기능 강화
- **장애 유형별 설정**: 시각, 청각, 지체 등 장애 유형에 따라 필요 기능 선택 가능
  - 시각 장애: 음성 안내, 고대비 모드, 화면 확대
  - 청각 장애: 수어 안내(옵션), 텍스트 표시
- **자동 인식 (옵션)**: 카메라와 센서를 통해 휠체어 사용자, 시각 장애인 등을 자동으로 인식하여 적절한 접근성 모드 추천
- **수어 안내 (옵션)**: 주요 안내 프로세스를 3D 수어 아바타로 제공
- **지체 장애인 지원**: 대형 버튼, UI 최적화, 음성 인식, 터치 스크린 높이 및 각도 조절(옵션)

### 3. 카메라 및 객체 탐지(YOLOv8) 활용한 맞춤형 서비스
- **사용자 특성 파악**: 카메라와 YOLOv8 객체 탐지 모델을 활용한 사용자 특성(키, 휠체어 사용 여부, 시선 등) 실시간 파악
- **자동 높이 및 각도 조절**: 휠체어 사용자 인식 시 스크린 높이 및 각도 자동 조정
- **시선 추적 (옵션)**: 사용자 시선을 추적하여 관련 메뉴 설명 및 옵션 자동 활성화

### 4. 안드로이드 앱 서비스 (소상공인용)
- **메뉴 관리**:
  - 메뉴에 따른 재고예측, 원자재 관리
  - 메뉴 수정 및 추가, 적정 재고 현황, 재고조정
- **매출 관리**:
  - 일별, 주별, 월별 매출 데이터 분석 및 시각화
  - 마진율 계산, 정산 관리, 실시간 매출 현황
- **주문 관리**:
  - 실시간 주문 현황 리스트
  - 환불처리 및 주문 취소 처리
- **매장 관리**:
  - 매장 테이블 배치
  - 직원 관리(근태기록 통계, 시급관리 등)

## 🛠️ 주요 기술 및 플랫폼

- **Rubik Pi3**: 키오스크의 핵심 제어 장치로 리눅스 OS 기반 Electron 애플리케이션 실행, 센서 및 모터 제어
- **20인치 터치 디스플레이**: 다양한 사용자 인터페이스(UI) A구현
- **안드로이드 앱**: 소상공인용(매장 관리) 앱 개발 및 키오스크 연동
- **AWS**: 클라우드 기반 백엔드 시스템으로 데이터 저장, 분석, 보안, 확장성 제공
- **AI 기반 음성 인식 및 합성**: Qualcomm AI Hub의 Whisper-Tiny-EN 모델 활용
- **카메라 & 객체탐지**: YOLOv8을 활용한 사용자 특성 파악, 시선 추적, 상품 인식
- **모터 및 구동장치**: 리니어 액츄에이터를 통한 화면 높이 및 각도 동적 조절

## 🚀 시스템 구성도

<p align="center">
  <img src="/api/placeholder/600/300" alt="베리온 시스템 구성도" />
</p>

## 📅 개발 일정

| 단계 | 기간 | 내용 |
|------|------|------|
| 기획 및 요구사항 분석 | 2025.03 - 2025.04 | 시장 조사, 사용자 요구사항 분석, 기술 검토 |
| 설계 | 2025.04 - 2025.05 | 시스템 아키텍처 설계, UI/UX 디자인, DB 설계 |
| 개발 | 2025.05 - 2025.09 | 하드웨어 구성, 소프트웨어 개발, AI 모델 구현 |
| 테스트 | 2025.09 - 2025.10 | 단위 테스트, 통합 테스트, 사용자 테스트 |
| 배포 및 실증 | 2025.10 - 2025.12 | 파일럿 테스트, 피드백 수집, 개선 |

## 👥 팀 구성

- **이원준**: 프로젝트 총괄 및 개발 책임

## 📊 기대 효과

1. **소상공인**: 합리적인 비용으로 법적 의무를 충족하면서 효율적인 매장 운영 가능
2. **장애인 및 노약자**: 다양한 접근성 기능을 통해 키오스크 이용의 어려움 해소
3. **일반 사용자**: 더 직관적이고 편리한 사용자 경험 제공
4. **사회적 가치**: 디지털 포용성을 높여 정보 격차 해소에 기여

## 📞 연락처

- **이메일**: example@domain.com
- **GitHub**: [Barion GitHub Organization](https://github.com/2025-Capstone-Project-Barion)

---

© 2025 Barion Project | All Rights Reserved
