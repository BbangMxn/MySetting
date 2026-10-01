# MySetting

![마법사 모자를 쓴 고양이](assets/witch-cat.png)

제가 쓰는 Codex Agent 지침과 재사용 가능한 스킬을 모아둔 저장소입니다.

## 구성

- `AGENTS.md`: 기본 대화 방식과 코드 작업 원칙
- `skills/`: 개인적으로 사용하는 범용 스킬
- `assets/`: README 이미지

업무별 스킬, 실행 기록, 인증 정보, 로컬 경로가 포함된 `config.toml`은 공개 범위에서 제외했습니다.

## 사용

1. `AGENTS.md`를 자신의 `~/.codex/AGENTS.md`로 복사합니다. 기존 파일이 있다면 덮어쓰기 전에 내용을 합치세요.
2. 필요한 스킬 폴더를 `~/.codex/skills/`에 복사합니다.
3. `AGENTS.md`에서 참조하는 `caveman`, `ponytail` 스킬을 함께 설치합니다.

각 스킬의 `SKILL.md`를 읽고 본인의 환경에 맞게 조정하세요. 일부 스킬은 별도 도구가 설치되어 있어야 작동합니다.
