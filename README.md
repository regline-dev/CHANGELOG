# CHANGELOG

프로젝트별 **작업·구조 변경 이력**을 모아 두는 저장소입니다.  
파일에 버전을 붙이지 않고, 각 `*_CHANGELOG.md`에 날짜 섹션으로 누적합니다.

## 파일 규칙

| 파일 | 대상 |
|------|------|
| `{프로젝트명}_CHANGELOG.md` | 해당 프로젝트 이력 (예: `regline-hub_CHANGELOG.md`) |
| `CHANGELOG.md` | 예시·레거시 포맷 참고용 |

새 프로젝트는 `프로젝트명_CHANGELOG.md`를 추가하면 됩니다.

## 작성 요령 (요약)

- **반드시:** 구조·사양·배포·메뉴 등 의도가 바뀌는 것
- **생략:** 오타·표현만 바뀌고 의도가 같은 것
- 최신 날짜·버전이 **맨 위**, 같은 주제는 같은 날 섹션을 **업데이트**
- `변경 내용` 한 줄은 한 달 뒤에도 “어디가 어떻게 됐는지” 보이게 (UI면 메뉴 경로)

상세 규칙은 워크스페이스 `.cursor/rules/changelog.mdc`를 따릅니다.

## hub와 연결

포트폴리오 포털(`regline-hub`)의 **Works**는 왼쪽 카드 / 오른쪽 패널(50:50)입니다.

| Works 카드 | 진행현황 | 운영로그 |
|------------|----------|----------|
| 챗봇/RAG 프로젝트 | `chatbot-rag_README.md` (임시) | `chatbot-rag_CHANGELOG.md` |
| regline-hub | `regline-hub` 레포 `README.md` | `regline-hub_CHANGELOG.md` |
| 다른 프로젝트 02 / 03 | 준비 중 | 준비 중 |

- 카드 제목은 **프로젝트명**. CHANGELOG/README는 오른쪽 패널 내용
- 이 레포에 push만 하면 hub 재배포 없이 운영로그·(임시) README가 갱신됩니다
- hub Production: `https://regline-hub-three.vercel.app`

## 주의

- Public 저장소입니다. 시크릿·상세 주소·민감 정보는 적지 마세요.
- README는 “어떻게 쓰는지”만 적고, 이력 본문은 각 `*_CHANGELOG.md`에만 남깁니다.
