<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=soft&color=auto&height=200&text=JungMin%20Kim&desc=Full-Stack%20Developer%20%C2%B7%20Node.js%20%26%20React&animation=scaleIn&fontColor=000000&fontSize=50&descSize=18&descAlignY=62" />
</div>

<div align="center">

### 서버부터 화면까지, 사용자에게 닿는 흐름 전체를 만듭니다.

</div>

<br>

## 👋 About Me

- 🧩 **백엔드와 프론트엔드를 모두 책임져 본 개발자입니다.** [채택](https://checktask.kr)에서는 5인 백엔드 팀의 **팀장**으로 아키텍처와 알림 시스템을 설계했고, [투명지](https://tomyongji.com)·Deokive에서는 **팀 내 프론트엔드 최다 기여자**로 화면을 만들었습니다.
- 🚀 **만든 걸 실제로 운영합니다.** 투명지는 웹·iOS로 실서비스 중이고, 채택은 3차 릴리즈까지 배포했습니다.
- 🔍 **"왜 안 되는가"를 구조로 해결합니다.** UTC/KST 9시간 어긋남, 크론 중복 발송, 쿼리 캐시 stale — 증상을 덮지 않고 원인 지점을 고치는 걸 좋아합니다.
- 🎓 명지대학교 · 2026 상반기 캡스톤디자인으로 실시간 주식 시세 + AI 뉴스 분석 백엔드를 만들었습니다.

<br>

## 🛠️ Tech Stacks

**Back-End**

<img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=Node.js&logoColor=white"> <img src="https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=Express&logoColor=white"> <img src="https://img.shields.io/badge/NestJS-E0234E?style=for-the-badge&logo=NestJS&logoColor=white"> <img src="https://img.shields.io/badge/Prisma-2D3748?style=for-the-badge&logo=Prisma&logoColor=white"> <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=MySQL&logoColor=white"> <img src="https://img.shields.io/badge/Redis-FF4438?style=for-the-badge&logo=Redis&logoColor=white"> <img src="https://img.shields.io/badge/Socket.io-010101?style=for-the-badge&logo=socketdotio&logoColor=white">

**Front-End**

<img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=TypeScript&logoColor=white"> <img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=React&logoColor=black"> <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=Next.js&logoColor=white"> <img src="https://img.shields.io/badge/React%20Query-FF4154?style=for-the-badge&logo=reactquery&logoColor=white"> <img src="https://img.shields.io/badge/Zustand-433E38?style=for-the-badge&logo=react&logoColor=white"> <img src="https://img.shields.io/badge/Tailwind%20CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white"> <img src="https://img.shields.io/badge/Expo-000020?style=for-the-badge&logo=expo&logoColor=white">

**Infra & Tools**

<img src="https://img.shields.io/badge/AWS%20EC2-FF9900?style=for-the-badge&logo=amazonec2&logoColor=white"> <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=Docker&logoColor=white"> <img src="https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=Nginx&logoColor=white"> <img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white"> <img src="https://img.shields.io/badge/Firebase-DD2C00?style=for-the-badge&logo=firebase&logoColor=white"> <img src="https://img.shields.io/badge/Vitest-6E9F18?style=for-the-badge&logo=vitest&logoColor=white"> <img src="https://img.shields.io/badge/Storybook-FF4785?style=for-the-badge&logo=storybook&logoColor=white">

<br>

## 📂 Projects

### 📌 채택 (Check-Task) — 대학생 과제 관리 서비스
> 개인·팀 과제를 한곳에서 관리하고, 마감 알림과 실시간 협업을 제공하는 서비스

**`Back-End 팀장`** · 백엔드 5 / 프론트 3 · 커밋 **265건 (팀 내 최다)** · [🔗 checktask.kr](https://checktask.kr) · [Frontend](https://github.com/check-task/frontend) · [Mobile](https://github.com/check-task/mobile-frontend)

- 백엔드 초기 세팅과 **Controller–Service–Repository 계층 구조** 설계, 공통 응답·커스텀 에러 체계와 Swagger 문서화 표준 정립
- **마감 알림 파이프라인 전담 구현** — `node-cron` 5분 주기 스케줄러 → 미발송 알림 조회 → Firebase FCM 푸시 → Socket.IO 실시간 반영
- 자체 회원가입·카카오 OAuth·JWT + Redis 토큰 관리, 비밀번호 찾기와 회원탈퇴/복구까지 인증 도메인 전반 구현
- 비대해진 Controller를 **Zod 미들웨어**로 분리하고 Vitest 단위·통합 테스트로 알림 로직 검증

`Node.js` `Express` `Prisma` `MySQL` `Redis` `Socket.IO` `node-cron` `FCM` `JWT` `AWS EC2/S3` `Nginx` `GitHub Actions`

<br>

### 📌 투명지 (ToMyongJi) — 학생회비 투명 공개 플랫폼
> 학과 학생회비 집행 내역을 투명하게 공개해 신뢰를 회복하는 플랫폼 · **웹 + iOS 실서비스 운영 중**

**`Web Front-End`** · 커밋 **148건 (프론트 최다)** · [🔗 tomyongji.com](https://tomyongji.com) · [Repository](https://github.com/ToMyongJi/ToMyongJi-front-TS)

- **어드민 페이지 전체 구현** — 학생회장·부원 조회/관리 UI, 권한 분기, 로딩 상태 처리
- **'학생회 이전' 다단계 마법사** — 잔류 인원 선택 → 새 회장 설정 → 인증까지 Step별 컴포넌트화 및 검증 기반 분기
- **Axios 인터셉터로 토큰 만료 감지 → 자동 로그아웃 + 안내 + 리다이렉트**, 조용히 실패하던 API 흐름을 일관되게 정리
- 사이드바 인터랙션, 서비스 점검 페이지, Google Analytics 연동 등 UX 개선

`React 19` `TypeScript` `Vite` `TanStack Query` `Zustand` `React Hook Form + Zod` `Tailwind CSS 4` `Storybook` `Playwright` `PWA`

<br>

### 📌 Deokive (덕키브) — 덕질 아카이브 웹 서비스
> 아이돌·애니·게임 등 덕질 경험을 일기·캘린더·D-Day로 기록하는 개인 아카이브 (연합동아리 DEPth 메인 프로젝트)

**`Front-End`** · 기획 2 / 디자인 1 / 프론트 2 / 백엔드 2 · 커밋 **197건 (프론트 최다)** · [Repository](https://github.com/Deokive/FE)

- 카카오·구글 **소셜 로그인 및 세션 관리** — Zustand 기반 로그인 상태, 자동 로그아웃, 로그인 여부에 따른 네비게이션 분기
- 아카이브 **CRUD 전반과 페이지네이션 조회**, 공개 범위 설정 API 연동
- 편집 모드가 있는 **다이어리 기능** — 작성·수정 UI, 본인/타 유저 열람 뷰 분리
- 홈·피드 정렬, 좋아요, 이벤트·스티커·뱃지 연동, **스켈레톤 UI**로 로딩 경험 개선
- Jira 칸반 기반 애자일 스프린트로 협업

`React 19` `TypeScript` `Vite` `TanStack Query` `Zustand` `React Router v7` `Tailwind CSS 4`

<br>

### 📌 Jumoney — 실시간 시세 · AI 뉴스 분석 백엔드
> 한국투자증권(KIS) API로 KOSPI 200 실시간 시세를 수집·서빙하고, 네이버 뉴스를 Gemini로 분석하는 명지대학교 2026 캡스톤디자인 백엔드

**`Back-End`** · [Repository](https://github.com/MJU-Capstone-Design-1/Jumoney_Node_BE)

- KIS **WebSocket 실시간 시세**를 수집해 Redis ZSET에 히스토리로 적재하고 SSE·REST로 서빙
- 시간 단위 **네이버 뉴스 수집 → Google Gemini 분석 파이프라인** 구성
- **멀티스테이지 Dockerfile + docker compose**로 앱과 Redis를 EC2에서 함께 운영, graceful shutdown 및 환경변수 누락 시 즉시 종료로 운영 Redis 오접속 방지

`Node.js 22` `TypeScript` `Express 5` `ws` `Redis 7` `Gemini API` `Docker` `AWS EC2` `pnpm`

<br>

## 🏅 Stats

<div align="center">

![JungMINI-developer's GitHub stats](https://github-readme-stats.vercel.app/api?username=JungMINI-developer&show_icons=true&theme=dracula&v=2)
![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=JungMINI-developer&layout=compact&theme=dracula&v=2)

</div>

<br>

## 📮 Contact

<a href="mailto:kjmhs501@gmail.com"><img src="https://img.shields.io/badge/kjmhs501@gmail.com-EA4335?style=for-the-badge&logo=Gmail&logoColor=white"></a>
