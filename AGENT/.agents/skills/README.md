# Skills

- .agents/skills는 에이전트가 사용할 수 있는 스킬들을 관리하는 곳.
- 각 스킬은 `.agents/skills/{skill-name}/SKILL.md` 형식으로, 디렉토리 하나에 스킬 하나를 둔다.
- 스킬 디렉토리는 분류 없이 `.agents/skills/` 바로 하위에 평평하게 둔다. (하위 분류 디렉토리는 에이전트가 인식하지 못할 수 있음)
- 스킬의 기능별 분류는 디렉토리 대신 하단 스킬 목록의 분류 컬럼으로 관리한다.
- 스킬을 추가하거나 제거할땐 하단 스킬 목록도 함께 수정한다.
- 외부 스킬은 원본을 수정하지 않고 그대로 가져오며, 출처를 기록한다.

## 스킬 목록

| 스킬 | 분류 | 설명 | 경로 | 출처 |
|---|---|---|---|---|
| hallmark | front/design | AI가 만든 것처럼 보이지 않는 웹 UI 디자인. 새 페이지 생성, redesign, audit | `.agents/skills/hallmark/SKILL.md` | [nutlope/hallmark](https://github.com/nutlope/hallmark) (MIT) |
