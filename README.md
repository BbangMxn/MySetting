# MySetting

![마법사 모자를 쓴 고양이](assets/witch-cat.png)

제가 사용하는 Codex 설정과 스킬을 모아두는 라이브러리입니다. 새 스킬을 추가하면 아래 목록도 갱신합니다.

## Agent 설정

[AGENTS.md](AGENTS.md)에 기본 대화 방식과 코드 작업 원칙을 정리했습니다. `caveman`과 `ponytail` 스킬을 참조합니다.

## 스킬 목록

| 스킬 | 용도 |
| --- | --- |
| [aside](skills/aside/SKILL.md) | Obsidian Aside 댓글 작업 |
| [caveman](skills/caveman/SKILL.md) | 간결한 응답 방식 |
| [codegraph](skills/codegraph/SKILL.md) | 코드 구조와 호출 관계 탐색 |
| [frontend-design](skills/frontend-design/SKILL.md) | 프런트엔드 화면 디자인 |
| [ponytail](skills/ponytail/SKILL.md) | 최소한의 코드로 문제 해결 |
| [rtk](skills/rtk/SKILL.md) | 명령 출력과 토큰 사용량 관리 |

## 설치

1. 필요한 스킬 폴더를 `~/.codex/skills/`에 복사합니다.
2. [AGENTS.md](AGENTS.md)를 `~/.codex/AGENTS.md`에 복사하거나 기존 파일에 내용을 합칩니다.
3. `AGENTS.md`를 사용한다면 `caveman`과 `ponytail`도 설치합니다.

스킬마다 필요한 도구와 사용 조건은 각 `SKILL.md`를 확인하세요.
