# regline-hub CHANGELOG

포트폴리오 포털(`regline-hub`) 계획·구조·배포 변경 이력.
파일에 버전을 표기하지 않고 이 문서에 누적한다.

---

## 2026-07-17 (v1)

**변경 파일**: Docs/20260716_regline-hub_Vercel배포_계획.md, .cursor/rules/changelog.mdc

**변경 내용**: 호스팅을 Hetzner `:3003` → Vercel(옵션 A 단독 레포)로 확정

- Production URL `regline-hub-three.vercel.app` 유지
- CHANGELOG 규칙 도입 (구조/사양 변경만 기록)

---

## 2026-07-16 (v1)

**변경 파일**: Docs/20260716_Worls_Links_작업계획.md, Docs/20260716_Works_구조_부록.md, src/App.tsx

**변경 내용**: Works/Links 메뉴 분리, Profile 이력서 카드 추가

- Projects(완성) / Works(진행) / Links(외부) 분리
- 이유: 포털 골격 MVP

---

## 2026-07-15 (v1)

**변경 파일**: Docs/20260715_포트폴리오_카드포털_계획.md

**변경 내용**: regline-hub 카드 포털 MVP 착수

- 카드 클릭 → 기존 서비스 이동, 데이터는 `works.ts` 한곳
