# Git branch & conflict

---

### Git branch

> 각 브랜치를 설정하게 되면 해당 브랜치로 순간이동 할 수 있음👍

1. `git branch` 브랜치 목록 확인

2. `git branch [이름]` 으로 **branch** 추가 가능

3. `git log --oneline`을 통해 현재 `HEAD`위치 확인 가능

4. `git check out mino` 변경하게 되면 `HEAD` 위치가 해당 `mino`를 가리키며,

   내용 또한 `mino`의 `commit` 형태로 표기 된다.

   ​ <u>✔선택한 브랜치의 작업사항으로 변경</u>

### Git Merge

> 각 흩어진 브랜치를 한개로 합치는 것🙏

1. 우선 `master` 브랜치로 설정.
2. 현재 브랜치로 병합하고 싶은 브랜치를 `git merge [이름]` 명령.
3. `git reset --hard [버전명]` 을 통해 과거 상태로 가능
