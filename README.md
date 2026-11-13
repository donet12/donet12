# 안녕하세요, 백엔드 개발자입니다.

> Backend Developer | 깔끔한 코드로 안정적이고 효율적인 시스템을 설계합니다.

코딩을 단순한 작업이 아니라 문제를 해결하는 도구로 여기며, 항상 기본기에 충실하면서도 새로운 기술을 빠르게 익히고 적용하는 것을 목표로 합니다.
결제 서비스 백엔드 인턴 경험을 바탕으로, **장애에 강하고 검증 가능한 시스템**을 만드는 데 관심이 많습니다.

---

## Tech Stack

### Backend
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Java](https://img.shields.io/badge/Java-007396?style=flat-square&logo=java&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-000000?style=flat-square&logo=express&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![MariaDB](https://img.shields.io/badge/MariaDB-003545?style=flat-square&logo=mariadb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)

### AI
![Claude Code](https://img.shields.io/badge/Claude%20Code-D97757?style=flat-square&logo=claude&logoColor=white)
![Codex](https://img.shields.io/badge/Codex-000000?style=flat-square&logo=openai&logoColor=white)

### Frontend
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)

### DevOps & Cloud
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Railway](https://img.shields.io/badge/Railway-0B0D0E?style=flat-square&logo=railway&logoColor=white)

### Tools
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Jira](https://img.shields.io/badge/Jira-0052CC?style=flat-square&logo=jira&logoColor=white)
![Notion](https://img.shields.io/badge/Notion-000000?style=flat-square&logo=notion&logoColor=white)

---

## Work Experience

### 무신사페이먼츠 결제서비스팀 · 백엔드 인턴 (2026.03 - 2026.08)
`Kotlin` `Spring Boot` `KCP`

- **PG 연동 방식 전환**: KCP 결제 연동을 SDK 실행 방식에서 REST API 호출 방식으로 전환하고 별도 서버(PG Outbound)로 분리
- **장애 격리**: 서킷브레이커 설계·적용, 승인·취소는 재시도 미적용 / 조회는 재시도 허용으로 중복 결제 위험 차단
- **무중단 전환**: DB 설정값으로 신규 방식 적용 비율을 조절하는 feature flag 방식으로 운영 배포 (가상계좌 발급·결제 취소 운영 반영)
- **테스트 자동화**: PG 명세와 기존 코드를 바탕으로 LLM이 결제 승인·취소·환불 등 약 200개의 E2E 테스트 케이스를 생성·실행하는 파이프라인 구축 (Claude Code + MCP + Playwright)

> 회사 코드는 외부에 공개하지 않습니다.

---

## Projects

| Project | Role | Tech | Period | Link |
|:---|:---:|:---|:---:|:---:|
| 정엘 CRM - 상담·전문가 배정 CRM 재구축 (외주) | Full-Stack | Java 21, Spring Boot, PostgreSQL, Flyway, React, TypeScript, Railway | 2026.08 - 진행 중 | [링크](https://alabaster-smash-73a.notion.site/CRM-3fe0b776e240818e8042f3f0b452732e?pvs=74) |
| 온라인 강의 플랫폼 (외주, 상용 운영) | Backend & Infra | Spring Boot, PostgreSQL, Redis, KCP, Railway | 2026.01 - 2026.03 | [링크](https://alabaster-smash-73a.notion.site/2f00b776e24080b4af62f507778a6b58?pvs=73) |
| FinSage Analyst - 금융 규제 문서 RAG 챗봇 | Solo | LangChain, OpenAI, FAISS, Flask | 2025.09 - 2025.12 | [GitHub](https://github.com/donet12/finsage-analyst) |
| 피어링(Peering) - 특수교육 행정 관리 솔루션 | Backend & Infra | Spring Boot, MySQL, JPA, Docker, AWS EC2·ECR, GitHub Actions | 2025.05 - 2025.11 | - |
| 럭킷(LuckEat) - 최우수상 | Backend Lead | Spring Boot, MariaDB, Redis, Docker, AWS | 2025.02 - 2025.05 | [링크](https://alabaster-smash-73a.notion.site/1ed0b776e240808d96affa5c5dbc1bec?pvs=74) |
| 포비야 - 해커톤 본상 | Backend | Whisper STT, LLM, ElevenLabs TTS | 2025.05 | - |
| 커뮤니티 사이트 | Full-Stack | React.js, Express.js, MySQL, AWS, Nginx | 2024.12 - 2025.02 | [링크](https://alabaster-smash-73a.notion.site/1990b776e2408068a70bc215a7de12d0?pvs=74) |

### 주요 포인트
- **정엘 CRM**: Apps Script·구글 시트 기반 CRM을 Spring Boot + React로 재구축. 기존 기능 대응표(F01~F43)를 만들어 누락 없이 이관하고 건수·담당·금액 대조, 역할을 화면·API 권한의 단일 기준으로 통일, 여러 창구로 흩어진 상담 신청을 CRM으로 통합(중복 접수 방지), 텔레그램 알림 연동
- **온라인 강의 플랫폼**: 결제 PG(KCP) 연동 직접 구현, 카카오·네이버 OAuth, JWT + Redis 인증, Presigned URL 기반 S3 호환 스토리지, 단계별 과정 구조 DB 설계
- **FinSage Analyst**: 금융당국·협회 PDF를 Markdown으로 변환하는 전처리 도구 작성, 답변마다 출처 번호와 참고 문서 목록을 표시해 환각 대응, 토큰 단위 스트리밍
- **피어링**: Spring Security + JWT 기반 RBAC, CLOVA OCR로 시간표 이미지 파싱, GitHub Actions → ECR → EC2 CI/CD 구성
- **럭킷**: Redis 캐시로 조회 API P90·P95·P99 응답 시간 70% 이상 개선, 예약 재고 오버셀링 방지를 위한 비관적 락, ALB + 오토스케일링 배포 구성, MySQL·MariaDB·PostgreSQL 동일 조건 벤치마크 후 MariaDB 이관
- **포비야**: 전화 공포증 극복용 AI 대화 시뮬레이션 — STT → LLM → TTS 실시간 음성 파이프라인 구현 및 지연 시간 최적화

---

## Education & Activities

| 기간 | 활동 | 기관 |
|:---|:---|:---|
| 2025.05 - 2025.11 | 예비 창업가 발굴 육성 과정 | 대학 창업지원 프로그램 |
| 2024.10 - 2025.05 | 카카오테크 부트캠프 클라우드 네이티브 (1,000시간) | 카카오 |
| 2024.07 - 2024.08 | 부스트캠프 웹·모바일 9기 챌린지 | 네이버 커넥트재단 |

---

## Awards

| 수상명 | 기관 | 날짜 |
|:---|:---|:---|
| 카카오테크 부트캠프 클라우드 과정 최우수상 | 카카오 | 2025.05 |
| 카카오테크 부트캠프 해커톤 본상 | 구름 | 2025.05 |
| 학기 최우등생 (2회) | - | 2024.08, 2026.01 |

## Certificates
- ADsP (데이터분석 준전문가)

---

[![Solved.ac 프로필](http://mazassumnida.wtf/api/v2/generate_badge?boj=qwe7105c)](https://solved.ac/qwe7105c)

<div align="center">

> "AI 시대, 기술에 휩쓸리는 것이 아닌 기술과 함께 성장하는 개발자가 되고자 노력합니다."

</div>
