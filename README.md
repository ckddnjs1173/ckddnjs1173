<div align="center">

# 박창원 · Changwon Park

### Recruitment Operations · HR Systems · Workflow Automation

채용과 HR 운영에서 반복되는 문제를 **업무 흐름, 데이터 구조, 권한, 자동화**의 문제로 다시 정의하고  
실제 운영에 사용할 수 있는 시스템으로 구현합니다.

[![Email](https://img.shields.io/badge/Email-ckddnjs1173%40naver.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:ckddnjs1173@naver.com)

</div>

---

## Focus

- **Recruiting Operations** — 후보자, 고객사, 공고, 전형, 일정, 소싱 데이터를 하나의 운영 흐름으로 연결
- **HR & Labor Systems** — 근태, Case, 계산, 문서, 공식 절차를 데이터와 규칙 중심으로 구조화
- **Workflow Automation** — 반복 입력·검수·문서 생성·리포팅·AI 보조 업무의 자동화
- **Operational Design** — 실제 사용자의 권한, 예외, 감사 기록, 데이터 보존까지 포함해 설계

## Selected Work

### SearchDB
**Recruitment Operations Database & Candidate Discovery**

후보자·고객사·채용공고·전형·일정·이력서 데이터를 관리하는 채용 운영 시스템입니다.  
외부 후보 탐색 결과도 운영 DB에 바로 적재하지 않고 **검토 → 선별 → 전환** 단계를 거치도록 구성했습니다.

`Next.js` · `TypeScript` · `PostgreSQL` · `Prisma` · `Candidate Discovery`

### 인사야 · Insaya
**HR / Labor Problem-Solving Platform**

근로자와 사업주의 노무 문제를 Case 단위로 구조화하고, 계산·문서·공식 근거·절차·전문가 연결까지 이어지는 흐름을 설계했습니다.  
핵심 법률 판단과 계산은 자유로운 AI 생성보다 **deterministic Rule, Legal Governance, 사람의 검토**를 우선합니다.

`Node.js` · `PostgreSQL` · `Case Engine` · `Legal Governance` · `AI`

### The Lobby
**Candidate Portal & Recruiting Platform**

후보자의 채용공고 탐색·프로필·지원 경험과 리크루터의 Talent Pool·전형 파이프라인·커뮤니케이션을 연결하는 채용 플랫폼입니다.  
후보자-facing 서비스와 내부 운영 영역의 인증·데이터·배포 경계를 분리해 설계했습니다.

`Next.js` · `TypeScript` · `Firebase` · `Recruiting Workflow` · `AI Resume Intake`

### HR Attendance System
**Attendance, Leave & Audit Workflow**

출퇴근·자리비움·복귀·근무시간, 휴가·연장근로와 관리자 운영을 다루는 내부 HR 시스템입니다.  
다중 근무 세션, PostgreSQL RLS, 권한 분리, 관리자 보정과 **immutable audit log**를 함께 구성했습니다.

`Next.js` · `TypeScript` · `Supabase` · `PostgreSQL RLS` · `Audit Log`

## Engineering Principles

```text
업무 문제 확인
→ 프로세스와 예외 분해
→ 데이터 모델 / 권한 / 상태 정의
→ 작은 단위로 구현·검증
→ 테스트·감사·운영 기준 추가
→ 중복 기능 통합
→ 실제 사용 기준으로 반복 개선
```

제가 중요하게 보는 기준은 기능의 개수보다 **데이터 무결성, 권한 경계, 추적 가능성, 운영자의 사용성**입니다.

## Stack

<p>
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" />
<img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" />
<img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=111111" />
<img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white" />
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" />
<img src="https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white" />
<img src="https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white" />
<img src="https://img.shields.io/badge/Firebase-DD2C00?style=flat-square&logo=firebase&logoColor=white" />
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
</p>

---

개인 프로젝트 저장소는 필요에 따라 private으로 유지하며, 프로필에는 제품의 문제 정의·설계 방향·구현 범위를 중심으로 정리합니다.
