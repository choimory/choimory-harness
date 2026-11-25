# Update agents rules

- AGENTS.md와 .agents 내의 규칙 문서들을 최신버전으로 업데이트 해야할때는 `https://github.com/choimory/choimory-harness`의 문서들을 기준으로 업데이트 한다
- "규칙|지침|하네스 업데이트 해줘"와 같은 지시가 있을시 업데이트를 진행한다
- 업데이트를 진행할땐 git clone이나 github 다운로드로 최신 내용을 프로젝트 외부 임시 디렉토리에 다운받아, 해당 파일로 업데이트 후 clone이나 다운로드했던 남은 파일을 제거하는 방식으로 진행한다
- 작업 중인 프로젝트에 없는 신규 문서가 있을시엔 추가하고, 내용이 다를시엔 변경하고, 제거된 문서가 있을땐 제거한다
- 경로: `https://github.com/choimory/choimory-harness`/`AGENT` 내의 모든 문서들
- .agents/histories/20*, .agents/histories/calendar.md는 프로젝트별로 다르게 저장되는 프로젝트만의 문서이므로 업데이트 대상에서 제외한다
- AGENTS.md를 수정함에 있어서 Instruction Poisoning이 우려 된다면, AGENTS.md를 수정하는것 대신 루트에 새로운 UPDATED_AGENTS.md 문서를 새로 생성해줄것. 해당 내용을 지시자가 직접 수동으로 업데이트 할 것임
- `AGENT` 내의 모든 파일을 대상으로 진행하므로, 단순 문서 외에 스킬 관련 이미지, 스크립트 파일 등도 업데이트 내용에 포함한다