<div align="center">

# 박창원 · Changwon Park

### Recruitment Operations · HR Systems · Workflow Automation

채용·HR 운영을 직접 수행하면서 발견한 반복 업무와 운영 문제를  
**프로세스, 데이터, 권한, 자동화 구조**로 바꾸는 일을 하고 있습니다.

[![Email](https://img.shields.io/badge/Email-ckddnjs1173%40naver.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:ckddnjs1173@naver.com)

</div>

---

## Professional Focus

- **Recruitment Operations** — 후보자, 고객사, 채용공고, 전형, 일정, 소싱 데이터를 하나의 운영 흐름으로 구조화
- **HR Systems** — 근태, 노무 Case, 계산, 문서, 권한, 감사 기록을 실제 운영 기준으로 설계
- **Workflow Automation** — 반복 입력, 검수, 문서 생성, 리포팅, AI 보조 업무를 자동화
- **Applied AI for Operations** — AI를 독립 기능으로 두기보다 기존 업무 프로세스 안에서 검토·판단·문서화 보조 수단으로 활용

저는 기능의 개수보다 **현장에서 실제로 쓸 수 있는지, 데이터 흐름이 끊기지 않는지, 책임과 권한이 명확한지**를 더 중요하게 봅니다.

## Selected Systems

| Project | Role in the workflow | Key design focus |
| --- | --- | --- |
| **SearchDB** | 내부 채용 운영 및 인재 탐색 | Candidate / Client / Job / Pipeline / Discovery 통합 |
| **인사야 · Insaya** | HR·노무 문제 해결 플랫폼 | Case, Rule, Legal Governance, Document, Expert Handoff |
| **The Lobby** | 후보자-facing 채용 플랫폼 | Candidate Portal, Talent Pool, Application Pipeline |
| **HR Attendance System** | 내부 HR 운영 | Attendance, Leave, RLS, Admin Workflow, Audit Log |

### SearchDB
**Recruitment Operations Database & Candidate Discovery**

후보자·고객사·채용공고·전형·일정·이력서 데이터를 하나의 운영 DB에서 관리하는 채용 시스템입니다.  
외부 후보 탐색 결과도 바로 DB에 적재하지 않고 **탐색 → 검토 → 선별 → 전환** 단계를 거치도록 설계했습니다.

`Next.js` · `TypeScript` · `PostgreSQL` · `Prisma` · `Candidate Discovery`

### 인사야 · Insaya
**HR / Labor Problem-Solving Platform**

근로자와 사업주의 인사·노무 문제를 Case 단위로 구조화하고, 계산·문서·공식 근거·절차·전문가 연결까지 이어지는 흐름을 설계한 프로젝트입니다.  
핵심 법률 판단과 계산은 자유로운 AI 생성보다 **deterministic rule, 공식 근거, 사람의 검토**를 우선하도록 구성했습니다.

`Node.js` · `PostgreSQL` · `Case Engine` · `Legal Governance` · `AI`

### The Lobby
**Candidate Portal & Recruiting Platform**

후보자의 채용공고 탐색·프로필·지원 경험과 리크루터의 Talent Pool·전형 파이프라인·커뮤니케이션을 연결하는 채용 플랫폼입니다.  
후보자-facing 경험과 내부 운영 영역을 분리해 인증·데이터·운영 경계를 독립적으로 설계했습니다.

`Next.js` · `TypeScript` · `Firebase` · `Recruiting Workflow` · `AI Resume Intake`

### HR Attendance System
**Attendance, Leave & Audit Workflow**

출퇴근·자리비움·복귀·근무시간, 휴가·연장근로, 관리자 보정과 감사 기록을 다루는 내부 HR 시스템입니다.  
단순 근태 입력보다 **권한 분리, PostgreSQL RLS, 다중 근무 세션, immutable audit log** 같은 운영 통제를 함께 설계했습니다.

`Next.js` · `TypeScript` · `Supabase` · `PostgreSQL RLS` · `Audit Log`

## How I Work

```text
현장 문제 확인
→ 실제 업무 흐름과 예외 분해
→ 데이터 / 상태 / 권한 정의
→ 작은 단위로 구현·검증
→ 테스트 / 감사 / 운영 기준 추가
→ 중복 기능과 프로젝트 통합
→ 실제 사용 기준으로 반복 개선
```

## Tools & Stack

`TypeScript` · `Next.js` · `React` · `Node.js` · `Python`  
`PostgreSQL` · `Prisma` · `Supabase` · `Firebase`  
`GitHub` · `Microsoft 365` · `Power Platform` · `Workflow Automation`

---

개인 프로젝트 저장소는 필요에 따라 private으로 유지합니다.  
프로필에는 코드 공개 여부보다 **문제 정의, 운영 구조, 설계 의도, 실제 구현 범위**를 중심으로 정리합니다.
