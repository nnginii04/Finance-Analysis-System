# Finance-Analysis-System

금융 소비 데이터를 분석하여 사용자의 소비 패턴을 시각화하고, 소비 성향 및 금융 인사이트를 제공하는 웹 기반 플랫폼입니다.

## 프로젝트 소개

FIN:SIGHT는 사용자의 소비 내역 데이터를 기반으로 소비 패턴을 분석하고 시각화하여 보다 합리적인 소비 습관 형성을 지원하는 서비스입니다.

사용자는 자신의 소비 데이터를 확인하고 카테고리별 소비 비중, 월별 소비 추이, 주요 지출 영역 등을 한눈에 파악할 수 있습니다.

---

## 주요 기능

### 사용자 인증

* 회원가입
* 로그인
* JWT 기반 인증

### 소비 데이터 관리

* 소비 내역 등록
* 소비 내역 수정 및 삭제
* 카테고리별 분류

### 소비 패턴 분석

* 월별 소비 통계
* 카테고리별 소비 비율 분석
* 소비 추이 시각화

### 대시보드

* 총 지출 금액 조회
* 소비 비중 그래프
* 주요 소비 카테고리 분석

---

## 기술 스택

### Frontend

* React
* JavaScript
* Axios

### Backend

* Node.js
* Express.js

### Database

* MySQL

### Authentication

* JWT (JSON Web Token)

---

## 프로젝트 구조

```text
Finance-Analysis-System
├── client
│   ├── src
│   └── public
│
├── server
│   ├── routes
│   ├── controllers
│   ├── middleware
│   └── config
│
└── database
```

## 실행 방법

### 1. Repository Clone

```bash
git clone https://github.com/your-id/fin-sight.git
```

### 2. Backend 실행

```bash
cd server

npm install

npm start
```

### 3. Frontend 실행

```bash
cd client

npm install

npm start
```

### 4. Database 설정

MySQL 서버 실행 후 `.env` 파일에 DB 정보를 입력합니다.

```env
DB_HOST=localhost
DB_USER=root
DB_PASSWORD=your_password
DB_NAME=geumso_pae
```
---

## 기대 효과

* 소비 습관 개선
* 데이터 기반 소비 분석
* 사용자 맞춤형 금융 인사이트 제공

---

## License

This project is developed for Software Engineering Course Project.
