# ignis
A phone tarot reading booking platform built with React and Spring Boot for enhanced user convenience. Allows users to easily book and manage tarot sessions remotely.


# 이그니스 타로 예약 시스템 (Ignis Tarot Booking System)

## 프로젝트 개요

**프로젝트명**: 이그니스 타로 예약 시스템

**목표**: 번거로운 회원가입 절차 없이, 전화번호와 닉네임을 통해 편리하게 타로 상담을 예약하고 관리할 수 있는 모바일 웹사이트를 구축합니다.

**주요 기능**:
- 전화 타로 상담 예약
- 상담사 스케줄 관리
- 예약 내역 조회 및 관리

**타겟 사용자**:
- 타로 상담을 원하는 고객
- 상담 스케줄을 관리하는 타로 마스터

---

## 기능적 요구사항 (Functional Requirements)

### 예약 및 고객 시스템

- **[REQ-100] 예약 조회**: 
  - 고객은 전화번호와 닉네임을 입력해 자신의 예약 내역을 조회할 수 있어야 합니다.
  
- **[REQ-101] 예약하기**:
  - 고객은 상담 가능한 날짜와 시간을 선택하고, 전화번호와 닉네임을 입력하여 예약을 확정할 수 있어야 합니다.

- **[REQ-102] 예약 취소**:
  - 고객은 예약 조회 페이지에서 본인 확인 후, 예약을 취소할 수 있어야 합니다.

### 상담사(관리자) 시스템

- **[REQ-200] 관리자 로그인**:
  - 상담사는 관리자 페이지에 로그인할 수 있어야 합니다.

- **[REQ-201] 스케줄 관리**:
  - 상담사는 자신의 상담 가능한 시간(요일, 시간대)을 설정하고 수정할 수 있어야 합니다.

- **[REQ-202] 예약 현황 확인**:
  - 상담사는 들어온 예약 내역을 실시간으로 확인하고 관리할 수 있어야 합니다.

---

## 비기능적 요구사항 (Non-Functional Requirements)

- **성능**: 페이지 로딩 시간은 3초를 넘지 않아야 합니다.
  
- **보안**: 고객의 전화번호와 같은 개인 정보는 안전하게 암호화하여 저장해야 합니다.
  
- **사용성**: 모든 페이지는 모바일 환경에 최적화된 반응형 웹으로 구현해야 합니다.

---

## 기술 스택 (Technology Stack)

- **Frontend**: React, HTML5, CSS3, JavaScript
- **Backend**: Spring Boot (Java)
- **Database**: MySQL
- **Security**: AES 암호화, JWT 토큰 인증
- **Hosting/Cloud**: AWS, Heroku (배포 환경)

---

