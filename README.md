# 임대사업 관리 시스템

임대사업자를 위한 전세/월세 매물 관리 시스템입니다.

## 프로젝트 개요

이 시스템은 임대사업자가 보유한 매물을 관리하고, 월세 납부 일정을 추적하며, 알림을 받을 수 있는 종합 관리 플랫폼입니다.

### 핵심 기능

- 회원 관리 (일반 로그인, 카카오 소셜 로그인)
- 매물 정보 관리
- 월세 관리 달력
- 알림 시스템
- 다크/라이트 모드 지원
- 반응형 디자인

## 기술 스택

### 프론트엔드
- React 18.x
- Material UI
- 달력 컴포넌트 (FullCalendar 또는 React Big Calendar)

### 백엔드
- Spring Boot 3.x
- Spring Security + JWT
- Spring Data JPA

### 데이터베이스
- MySQL

### 서버
- Lukcy Linux 9.1
- Nginx

## 개발 환경 설정

### 백엔드 설정

```bash
cd backend
# 백엔드 실행 명령어
```

### 프론트엔드 설정

```bash
cd frontend
npm install
npm start
```

## 배포

CI/CD 파이프라인을 통해 자동 배포됩니다. GitHub Actions 워크플로우는 `.github/workflows/ci-cd.yml`에 정의되어 있습니다.

## 프로젝트 구조

```
rental-property-management/
├── backend/           # Spring Boot 백엔드
├── frontend/          # React 프론트엔드
├── docs/              # 프로젝트 문서
├── .github/           # GitHub Actions 워크플로우
└── README.md          # 프로젝트 설명
```

## 라이센스

MIT
