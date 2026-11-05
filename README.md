# 안녕하세요, ninestring입니다 👋

펫테크 스타트업에서 5년간 백엔드를 만들고 운영해 온 개발자입니다.
펄송(2021.09 ~ 2023.12)에서 시작했고, 펄송을 인수한 온힐(2024.01 ~ 현재)에서 온힐 서비스와 펄송 서비스를 함께 맡고 있습니다.
IoT 센서 로그 수집부터 정기구독 결제, 인앱결제, AI 상담까지 서비스의 서버 전 영역을 다뤄 왔고,
요즘은 NestJS · Prisma · PostgreSQL 기반 실시간 매칭 서비스를 혼자 설계하면서, M1 Mac mini 홈서버를 Terraform · Argo CD로 코드화하는 홈랩을 만들고 있습니다.

- 🧭 **주력**: TypeScript / Node.js 백엔드 (GraphQL · REST), MySQL · PostgreSQL, Redis
- ☁️ **운영**: Docker · GitHub Actions · AWS ECS/ECR 배포 파이프라인을 직접 구축하고 서비스를 5년간 안정 운영
- 🧪 **관심사**: 데이터 정합성과 멱등성, DB 로그 기반 관측성, LLM 에이전트를 실제 서비스에 녹이는 일
- 🔀 필요하면 프론트엔드(Next.js)와 클라우드 비용 최적화까지 경계를 넘어 일합니다

---

## 🛠 Tech Stack

**Backend**

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white)
![Fastify](https://img.shields.io/badge/Fastify-000000?style=flat-square&logo=fastify&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white)
![GraphQL](https://img.shields.io/badge/GraphQL-E10098?style=flat-square&logo=graphql&logoColor=white)
![Apollo](https://img.shields.io/badge/Apollo_Server-311C87?style=flat-square&logo=apollographql&logoColor=white)
![Socket.IO](https://img.shields.io/badge/Socket.IO-010101?style=flat-square&logo=socketdotio&logoColor=white)

**Data**

![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white)
![TypeORM](https://img.shields.io/badge/TypeORM-FE0803?style=flat-square&logo=typeorm&logoColor=white)
![Knex](https://img.shields.io/badge/Knex.js-D26B38?style=flat-square&logo=knexdotjs&logoColor=white)
![BullMQ](https://img.shields.io/badge/BullMQ-C8102E?style=flat-square)

**Infra · DevOps**

![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![PM2](https://img.shields.io/badge/PM2-2B037A?style=flat-square&logo=pm2&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase_FCM-DD2C00?style=flat-square&logo=firebase&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-844FBA?style=flat-square&logo=terraform&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes_(k3s)-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Argo CD](https://img.shields.io/badge/Argo_CD-EF7B4D?style=flat-square&logo=argo&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=flat-square&logo=cloudflare&logoColor=white)
![Tailscale](https://img.shields.io/badge/Tailscale-242424?style=flat-square&logo=tailscale&logoColor=white)

**Frontend (필요할 때)**

![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![TanStack Query](https://img.shields.io/badge/TanStack_Query-FF4154?style=flat-square&logo=reactquery&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)

**연동 경험**: PortOne(아임포트) · Apple App Store Server API · Google Play Developer API · Shopify Admin API · 카카오 알림톡 · SendGrid · OpenAI(Vercel AI SDK) · AWS Bedrock · AWS Rekognition · SmartThings Find

---

## 🚀 What I've Built

### 🐱 펫테크 플랫폼 백엔드 (펄송 → 온힐, 2021.09 ~ 현재)

스마트 고양이 화장실과 웨어러블 데이터로 반려동물 건강을 모니터링하고, 정기구독 커머스와 AI 수의사 상담을 제공하는 서비스. 앱 API · IoT 디바이스 API · 배치 서버 · 사내 어드민 4개 서버를 담당했고, 온힐 이적 후에도 계속 맡고 있습니다.

**앱 백엔드 (GraphQL / REST)** · Express, Apollo Server, type-graphql, TypeORM, MySQL, Redis

- 상품 · 주문 · 취소/반품/교환 · 정기구독 · 멤버십 · 쿠폰 · 포인트로 이어지는 커머스 도메인을 구현하고 고도화. 2024년부터는 서버 개발 · 운영 · 배포를 단독 전담
- Apple / Google 인앱결제 영수증 검증과 서버 간 알림(S2S, RTDN) 처리를 단독 구현
- OpenAI + Vercel AI SDK로 **AI 수의사 채팅** 구현. 반려동물 건강 데이터 조회 툴과 웹 검색 툴을 tool calling으로 연결한 5단계 에이전트 루프, 한/영/일 응답, 포인트 과금
- Apollo 플러그인 기반 Rate Limiter, DataLoader로 N+1 해소, Node 22 멀티스테이지 Docker + GitHub Actions → ECS 롤링 배포 파이프라인 구축

**IoT 디바이스 API** · Express, Knex, Redis, FCM

- 로드셀 무게 변화 · 체류 시간 · 고양이별 학습 통계를 결합한 **배변 유형 규칙 기반 분류기**와 다묘 가정 고양이 식별 로직 설계
- 95종 알림 키를 언어(ko/en/ja) · 말투 모드 · 수신 설정 · 타임존별로 발송하는 푸시 알림 V2 재설계
- MAX(id) 서브쿼리로 슬로우 쿼리 교체, request-id + TTL 키로 펌웨어 재전송 중복 저장 차단, SHA-256 기반 디바이스 요청 검증

**스케줄(배치) 서버** · node-schedule, Knex, node-kmeans, 단독 개발

- 타임존마다 현지 자정에 실행되는 **고양이 건강 점수 배치**: 14일 체중 선형회귀, 2σ 이상치 필터, 연령대별 가중 스코어 모델
- k-means(k=2) 기반 배변/소변 분류 학습, 빌링키 정기결제 파이프라인, 멤버십 승급 · 강등 정책 엔진 등 19개 잡 운영
- 잡별 성공 · 오류 · 발송 로그 DB 기록, Slack Webhook 알림 전환, 병렬 → 순차 처리로 DB 부하 완화

**사내 어드민 서버** · NestJS(Fastify), Prisma, 3개 데이터소스 통합

- 세션 · 역할 기반 전역 인증 가드, 요청/에러 DB 로깅 인터셉터, Prisma 미들웨어(소프트 삭제 · 타임존) 등 공통 아키텍처를 초기 설계
- IoT 생산 · QC 통계, PortOne 부분 취소/환불, 쿠폰 · 매출 통계 등 128개 REST API 중 핵심 운영 기능 개발

| 지표 (git · 코드 기준) | 값 |
| --- | --- |
| 앱 백엔드 본인 커밋 | 1,003개 (전체의 약 55%, 2024~2026은 98%) |
| GraphQL API | Query 155 · Mutation 129 · Subscription 2 |
| TypeORM 엔티티 / 코드 | 123개 / 약 68,000 LOC |
| 배치 서버 커밋 | 236건 중 235건 본인 |

### 🏥 동물병원 처방 커머스 플랫폼 (펄송 → 온힐, 2023.09 ~ 현재)

동물병원이 처방식을 처방하면 보호자가 앱에서 구매 · 구독하고, 병원과 판매자에게 매출을 정산하는 온힐의 B2B2C 플랫폼. 펄송 재직 중 착수해 온힐 이적 후에도 이어서 맡고 있으며, 백엔드와 두 개의 어드민 프론트엔드를 초기부터 만들었습니다.

**백엔드 (OnHeal API)** · NestJS, Fastify, Prisma, MySQL, Redis · 2023.09 ~ 현재

- 첫 커밋부터 9개월간 단독 개발로 15개 모듈 · 172개 엔드포인트 · 53개 테이블을 구축해 런칭 기반 마련
- 앱 사용자 · 병원 · 운영자 · 판매자 4종 클라이언트별 JWT 전략 + RoleGuard 컨벤션, Redis 발급 시각 비교 방식의 전 세션 즉시 무효화
- 빌링키 정기결제 · 부분취소 · 주문 상태 머신, 매월 1일 크론 기반 병원 · 판매자 정산 시스템(Prisma interactive transaction)

**병원 관리자 웹 · 운영 어드민 웹** · Next.js 14 App Router, TanStack Query/Table, shadcn/ui, NextAuth · 2023.10 ~ 2024.09

- MUI 프로토타입을 App Router 구조로 전면 재설계(206개 파일), 라우트 그룹 기반 인증 레이아웃과 60여 개 쿼리 훅 체계를 세워 이후 합류한 팀원들이 같은 패턴으로 확장
- 반려동물 선택 → 처방 제품 선택 → 미리보기 → 발행으로 이어지는 **처방전 작성 플로우**, 매출 · 정산 화면, 6종 매출 대시보드 차트 구현
- 운영 어드민은 최초 생성자로 초기 설계와 핵심 페이지를 맡고, 팀원 PR 13건 리뷰 · 머지. OIDC 인증 → ECR → SSH 배포 CI/CD 구축

### 🧪 반려동물 소변검사 앱 백엔드 (온힐, 2024.11 ~ 2026.11)

소변검사 스틱을 촬영하면 AI 이미지 분석 서버와 연동해 8개 항목 결과를 제공하는 일본 시장 대상 앱의 API 서버. 커밋 77건 중 65건을 작성하며 백엔드를 리드했습니다.

- NestJS + Fastify + Prisma 아키텍처 초기 구축, Apple / Google / LINE 소셜 로그인과 Access/Refresh 이중 토큰 + Redis 세션 무효화
- 이메일 인증을 Redis Pub/Sub → SSE로 실시간 전달해 다중 인스턴스 환경에서 폴링 없이 동작
- S3 Presigned URL 업로드 + **BullMQ 비동기 분석 파이프라인**, 10초 타임아웃과 15종 에러 매핑, QR 키트 사용권 트랜잭션 차감
- dev는 SSH 배포, prod는 ECS Task Definition 롤링 배포로 분리한 GitHub Actions 파이프라인

### 💬 데이팅 앱 백엔드 (사이드 프로젝트, 2025.04 ~ 진행 중)

일본 시장 대상 매칭 앱의 API 서버를 단독 백엔드로 설계 · 구현 · 배포 · 문서화하고 있습니다. 커밋 484건 중 481건.

- NestJS 11 · Fastify 5 · Prisma 7 · PostgreSQL 17(PostGIS, pgvector) · Redis · Socket.IO. 컨트롤러 22개, 엔드포인트 약 145개, Jest 테스트 파일 72개
- **실시간 WebSocket 계약 v2**: 채팅 · 알림을 단일 연결의 2개 네임스페이스로 통합, Redis adapter로 다중 인스턴스 전달, 사용자당 단일 세션 펜싱, 방별 원자적 시퀀스 + SET NX 클레임으로 메시지 멱등성 보장
- **AI 벡터 매칭**: AWS Bedrock으로 자기소개 속성 추출 → Cohere 임베딩 5벡터 → pgvector HNSW 재랭킹, 방향성 상호 적합도 tier 랭킹과 30분 배치 워커로 비동기 재구축
- AWS Rekognition Face Liveness · 신분증 대조 · OCR 본인확인, Apple / Google 인앱결제와 포인트 원장, 커플 상태 머신(HOLD 24h TTL 조건부 전이), Redlock 분산 락 크론
- 온보딩 문서 10편과 Apidog OpenAPI 패치로 앱 팀과 API 계약 동기화, Conventional Commits

### 🏠 homelab-gitops (개인 프로젝트, 2026.10 ~ 진행 중)

M1 Mac mini 위에 Lima(arm64 Ubuntu VM) + k3s 클러스터를 올리고, Terraform · Argo CD · Authentik SSO로 전 구성을 코드화하는 홈랩. "레포에 없는 설정은 존재하지 않는다"를 원칙으로 호스트 · 외부 자원 · 클러스터 워크로드를 모두 코드로 관리합니다.

- **Stack**: Lima · k3s · Terraform 1.17 · Cloudflare(DNS, R2, Tunnel) · Tailscale · Argo CD · Authentik · Traefik · cert-manager · SOPS + age · Helm · Kustomize · launchd
- **역할 경계**: 호스트 설정은 멱등 스크립트, 클러스터 밖 자원은 Terraform, 클러스터 안 워크로드는 GitOps로 분리하고, Terraform이 클러스터 안을 직접 건드리지 않도록 선을 그었습니다
- **ADR 12건**: K8s 실행 방식(Lima vs Colima vs Talos), GitOps 컨트롤러(Argo CD vs Flux), IdP(Authentik vs Keycloak), 시크릿(SOPS vs External Secrets), 상태 백엔드(R2 vs HCP Terraform) 등을 대안과 이유를 남기며 결정
- **멱등 호스트 부트스트랩**: pmset 전원 설정, macOS 자동 업데이트 차단, SSH 키 인증 강제, Brewfile, Lima VM 생성, kubeconfig를 Tailscale MagicDNS 주소로 재작성, launchd 등록까지 스크립트 한 번으로 처리
- **Lima VM 정의**: 4 CPU / 10GiB / 100GiB 자원 배분, 80/443/6443 포트포워딩, k3s provision, Tailscale 주소를 API 인증서 SAN에 주입, kubeconfig 권한 그룹 단위 최소화
- **상태 · 시크릿**: Terraform 원격 상태를 Cloudflare R2(S3 호환, use_lockfile)에 루트별 key로 분리, mise 버전 고정, direnv 자격 증명 주입, tfstate · kubeconfig · age 키는 .gitignore로 차단
- **다음 단계**: Cloudflare DNS · Tailscale ACL · Argo CD app-of-apps를 Terraform으로, cert-manager DNS-01 와일드카드 인증서, KSOPS, Authentik OIDC(Argo CD · Grafana) + forward auth, kube-prometheus-stack + Loki, Velero 백업 리허설, Renovate · kubeconform · trivy CI

### ☁️ 이커머스 AWS 인프라 · 비용 운영 (푸드나무 · 온힐 계열사, 2025.09 ~ 2026.09)

온힐 소속으로 계열사인 식품 이커머스 운영사의 AWS 인프라 운영과 IT 비용 관리를 맡았습니다.

- EC2 약 90대 · ALB 42대 · NAT GW 5대 · Aurora RI 3대 규모 계정의 비용 구조를 전수 분석하고, MSP 위탁 운영을 해지해 직접 운영 체제로 전환
- 파트너 이용내역서와 AWS 청구서를 시간 단위로 대조 검증, Savings Plan · RI 약정 현황 정리
- WAF · VPN · CDN · 알림톡 등 월 10여 개 IT 비용 항목 지출결의와 계약 검토, Java/Spring 레거시 모놀리스 환경 파악과 후임 인수인계

---

## 💡 How I Work

- **멱등하게**: 펌웨어 재전송, 웹훅 중복 수신, 채팅 재전송처럼 "같은 요청이 두 번 온다"는 전제로 설계합니다. Redis SET NX + TTL 클레임을 즐겨 씁니다.
- **추적 가능하게**: 모든 요청 · 실패 · 발송 이력을 DB 로그 테이블에 남기고 민감 필드는 마스킹합니다. 운영 중 장애는 로그 테이블에서 시작합니다.
- **시간대를 믿지 않게**: 타임존별 자정 판별, 기기 시계 오류로 미래 시각이 찍힌 로그 필터링, UTC/KST 처리를 애플리케이션 레이어로 통일한 경험이 있습니다.
- **혼자서도 끝까지**: 설계 스펙 → 구현 계획 → 구현 → Dockerfile → CI/CD → 온보딩 문서까지 한 사이클을 혼자 닫아 본 프로젝트가 여럿입니다.

---

## 📊 GitHub

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=NINESTRING&show_icons=true&theme=default&hide_border=true)
![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=NINESTRING&layout=compact&hide_border=true)

## 📫 Contact

- Email: koohoyn@naver.com
