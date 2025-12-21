# file lifecycle

`git status` 명령어로 파일의 상태를 확인할 수 있다.

### untracked

- Git이 아직 관리하지 않는 파일로 새로 생성된 파일이 해당된다.

### tracked

- Git이 관리 중인 파일로, unmodified, modified, staged 상태를 가진다.
  - unmodified: 마지막 커밋 이후 변경되지 않은 상태
  - modified: 파일이 변경되었지만 아직 스테이징되지 않은 상태
  - staged: 변경 사항이 스테이징 영역에 올라간 상태