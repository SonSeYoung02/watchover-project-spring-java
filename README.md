# AI 심리상담 챗봇 기반 감정 케어 서비스 - WatchOver



---

## AI 상담으로 오늘의 감정을 기록하고, 나를 돌보는 습관을 만들자

```
WatchOver는 사용자가 AI 상담 챗봇과 대화하며 하루의 감정을 정리하고,
감정 기록을 캘린더와 통계로 확인할 수 있도록 돕는 모바일 서비스입니다.

대화가 끝나면 감정 요약을 저장하고, 월별/일별 감정 흐름을 시각화합니다.
또한 커뮤니티, 출석 체크, 캐릭터 프로필, 심리 검사 결과 조회 기능을 통해
사용자가 꾸준히 자기 돌봄을 이어갈 수 있는 환경을 제공합니다.
```

---

## Project Info


> 성결대학교 컴퓨터공학부 전공종합설계
>
> 개발 기간: 2026.03 ~ 2026.05
>
> API 문서(Swagger): http://15.164.113.103/swagger-ui/index.html

---

## 🛠️ Stacks

### Environment

![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white)
![NodeJS](https://img.shields.io/badge/node.js-6DA55F.svg?style=for-the-badge&logo=node.js&logoColor=white)
![Gradle](https://img.shields.io/badge/Gradle-02303A.svg?style=for-the-badge&logo=Gradle&logoColor=white)
![Android](https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)

### Config

![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)
![AWS S3](https://img.shields.io/badge/AWS_S3-569A31?style=for-the-badge&logo=amazons3&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white)
![Swagger](https://img.shields.io/badge/Swagger-85EA2D?style=for-the-badge&logo=swagger&logoColor=black)

### Development

#### Backend

![Spring](https://img.shields.io/badge/spring-%236DB33F.svg?style=for-the-badge&logo=spring&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring_Security-6DB33F?style=for-the-badge&logo=springsecurity&logoColor=white)
![Spring Data JPA](https://img.shields.io/badge/Spring_Data_JPA-59666C?style=for-the-badge&logo=hibernate&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)

#### Frontend

![React Native](https://img.shields.io/badge/react_native-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Axios](https://img.shields.io/badge/Axios-5A29E4?style=for-the-badge&logo=axios&logoColor=white)
![React Navigation](https://img.shields.io/badge/React_Navigation-6B52AE?style=for-the-badge&logo=react&logoColor=white)

### Communication

![Notion](https://img.shields.io/badge/Notion-000000?style=for-the-badge&logo=notion&logoColor=white)
![Discord](https://img.shields.io/badge/Discord-%235865F2.svg?style=for-the-badge&logo=discord&logoColor=white)

---

## 💻 프로젝트 개발자

|     손세영     |   이준혁   |    김범진    |     임원석     |
|:-----------:|:-------:|:---------:|:-----------:|
|     팀장      |   팀원    |    팀원     |     팀원      |
|   Backend   | Backend | Frontend  |  Frontend   |
| [@SonSeYoung02](https://github.com/SonSeYoung02) |  [@junhyuk1024](https://github.com/junhyuk1024)  | [@KChupi](https://github.com/KChupi) | [@LIMWONSEOK](https://github.com/LIMWONSEOK) |

---

## 화면 구성

| Splash / Login | Home |
| --- | --- |
| 이미지 추가 예정 | 이미지 추가 예정 |

| AI Chat | Calendar |
| --- | --- |
| 이미지 추가 예정 | 이미지 추가 예정 |

| Community | Character / My Page |
| --- | --- |
| 이미지 추가 예정 | 이미지 추가 예정 |

---

## ✨ 주요 기능

### 로그인 및 회원 관리 모듈

- 회원가입, 로그인, 회원 정보 조회 기능
- JWT 기반 인증 처리
- 회원 정보 수정 및 탈퇴 기능

### 홈 대시보드 모듈

- 사용자 닉네임과 프로필 캐릭터 표시
- 명언/배너 조회
- 출석 체크와 연속 출석 현황 관리
- AI 상담, 커뮤니티, 캘린더 등 주요 화면으로 이동

### AI 상담 챗봇 모듈

- 심리상담 페르소나 기반 AI 채팅
- 채팅방 생성, 대화 전송, 대화 내역 조회
- 채팅방 목록 조회 및 삭제
- 상담 종료 시 대화 내용을 감정 기록으로 요약

### 감정 캘린더 및 분석 모듈

- 상담 대화를 기반으로 일별 감정 로그 저장
- 월별 감정 통계 조회
- 일별 감정 통계 및 분석 조회
- 캘린더 화면에서 감정 흐름 확인

### 캐릭터 모듈

- 이미지 업로드 기반 캐릭터 생성
- 내가 생성한 캐릭터 이미지 목록 조회
- 프로필 캐릭터 선택 및 변경

### 커뮤니티 모듈

- 게시글 작성, 수정, 삭제, 상세 조회
- 게시글 목록 및 인기 게시글 조회
- 댓글 작성 및 수정
- 좋아요, 북마크, 내 게시글/댓글/북마크 조회

### 출석 및 심리 검사 모듈

- 일일 출석 체크
- 연속 출석일 조회
- 사용자별 심리 검사 결과 목록 조회

### 배너 모듈

- 홈 화면에 노출할 명언/배너 목록 조회
- 배너 상세 조회

---

## 📃 문서

### ✍️ 케어해줘 API 명세서
https://www.notion.so/API-3209259f1c81800887f7c37323982b43?source=copy_link

### ⚙️ 기능 명세서
https://docs.google.com/spreadsheets/d/1cm9S2RCkA2d3p6BGudLL-VThHwegVQjG/edit?usp=sharing&ouid=109903368342368733672&rtpof=true&sd=true

### 💾 캐어해줘 데이터베이스 설계
https://docs.google.com/spreadsheets/d/1cm9S2RCkA2d3p6BGudLL-VThHwegVQjG/edit?gid=551324875#gid=551324875
