# Software Security Week06
#### ๐ Oct 12th, 2022
1. [git restore](###-`git-restore`)
2. [GitHub](##-GitHub)
***
### `git restore`
๋ญ๊ฐ ๋๋๋ฆด ์ผ์ด ์์ ๋ ์ฌ์ฉ 

- `git restore [FILE_NAME]`: ํด๋น ํ์ผ์ ๊ฐ์ฅ ์ต๊ทผ commit ์ํ๋ก ๋๋๋ฆผ  
- `git restore --source [COMMIT_ID] [FILE_NAME]`: ํด๋น ํ์ผ์ ํด๋น commit ์ํ๋ก ๋๋๋ฆผ  
- `git restore --stage [FILE_NAME]`  

## GitHub
### Commands for remote repository
- `git remote`: ์๊ฒฉ์ ์ฅ์๋ฅผ ๊ด๋ฆฌํ๊ธฐ ์ํ ๋ช๋ น์ด
  - `git remote add origin [GITHUB_URL]`: ์๊ฒฉ์ ์ฅ์ ์ถ๊ฐ
  - `git remote -v`: ํ์ฌ ์ง์ ๋ ์๊ฒฉ์ ์ฅ์ ์ ๋ณด ํ์ธ
โข `git clone`: ์๊ฒฉ์ ์ฅ์์ ์๋ repo๋ฅผ local๋ก ๋ณต์ 
- `git clone [GITHUB_REPO_URL]`: ํด๋น github์ ์๋ repo๋ฅผ local๋ก ๋ณต์ 

- `git push`: local repo์ ์๋ commit๋ค์ remote repo๋ก ์๋ก๋
    - `git push [REMOTE] [LOCAL]`
### Other useful commands
- `git merge & git rebase`: ๋ ๊ฐ์ branch๋ฅผ ํฉ์น  ๋ ์ฌ์ฉ, ๋จ, ์ถฉ๋์ ์ ์
- `git diff`: ์๋ก ๋ค๋ฅธ ๋ commit ๊ฐ์ ์ฐจ์ด์ ์ ๋ณด์ฌ์ค
- `git stash`: commit๊น์ง ํ  ๊ฑด ์๋๊ณ , ์์ ์ ์ฅํ  ๋ ์ฌ์ฉ
- `git revert & git reset`: ํ์ฌ ์ํ๋ฅผ ์์์ commit์ผ๋ก ๋๋๋ฆด ๋ ์ฌ์ฉ