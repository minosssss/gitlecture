# Git백업

> 원격저장소를 통한 각 컴퓨터에서 Push / Pull 하며 백업을 진행

### Git Hosting & Push

여러 호스팅이 있지만 `Github`로 진행

###### Github 연결 및 백업방법

<u>http</u>를 통한 통신방법 추천

- `git remote add [별명] [연결할 원격저장소]` 입력하여 연결
- `git remote -v` 를 통하여 연결주소 확인
- `git push [별명] [브랜치]` 입력 후 `Github`로그인 진행하면 백업

###### 기존 호스팅 삭제

- `git remote remove [별명]` 진행 후 `git remote -v` 입력하여 확인

### Git Clone

신규 컴퓨터에 백업한 내용을 다른 컴퓨터로 복제

- `Github` 에서 복사할 `Repo` 의 주소 확인
- 복사를 진행할 폴더에서 `git clone [주소]`
  - **<u>Git 오픈소스</u>** > `git clone [주소]` 입력하여 다운로드도 가능

### Git Pull

작업을 옮겨가며 할 수 있게 동기화 진행

- 1번 컴퓨터에서 작업 진행 후 `git push` 진행하면 원격저장소로 이동
- 2번 컴퓨터에서 `git pull` 을 통하여 업데이트 진행

### 수업을 마치며

- 인증의 불편을 없애기 위해 `SSH`를 통해 해결가능
- issue tracker 를 통한 프로젝트 문제해결 및 협업가능
- 협업파트 공부를 통해 confilct 최소화하기
