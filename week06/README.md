# Software Security Week06
#### 📆Oct 12th, 2022
1. [git restore](###-`git-restore`)
2. [GitHub](##-GitHub)
***
### `git restore`
✅ 뭔가 되돌릴 일이 있을 때 사용 

- `git restore [FILE_NAME]`: 해당 파일을 가장 최근 commit 상태로 되돌림  
- `git restore --source [COMMIT_ID] [FILE_NAME]`: 해당 파일을 해당 commit 상태로 되돌림  
- `git restore --stage [FILE_NAME]`  

## GitHub
### Commands for remote repository
- `git remote`: 원격저장소를 관리하기 위한 명령어
  - `git remote add origin [GITHUB_URL]`: 원격저장소 추가
  - `git remote -v`: 현재 지정된 원격저장소 정보 확인
• `git clone`: 원격저장소에 있는 repo를 local로 복제
- `git clone [GITHUB_REPO_URL]`: 해당 github에 있는 repo를 local로 복제

- `git push`: local repo에 있는 commit들을 remote repo로 업로드
    - `git push [REMOTE] [LOCAL]`
