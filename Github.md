# Github
* **Repositories Link**
`https://github.com/[Nickname]/[Repositories Name].git`

* **Private Repositories Link**
[Tokens](https://github.com/settings/tokens) > `https://[Tokens]@github.com/[Nickname]/[Repositories Name].git`

* [JetBrains IDE에서 "Squash Commits..." 메뉴가 비활성화된 경우](https://blog.naver.com/techshare/223071617477)

* **New**
```bash
git init
git add .
git commit -m "Project Reset"
git remote add origin [Repositories Link]
git push -u origin main
```
* **Update**
```bash
git pull origin main
```
* **Edit**
```bash
git add .
git commit -m "commit"
git push -u origin main
```
* **Command**
```bash
# Upload History Check
git hist

# Branch Check
git remote -v

# Change Repositories
git remote set-url origin [Repositories Link] 

# Clone
git clone [Repositories Link] 
```
* **Error**
```bash
# origin Branch가 이미 존재하여 연결 불가
Error: remote origin already exists

# User Email , Nickname Register
Error : Author identity unknown
git config --global user.email "you@example.com"
git config --global user.name "Nickname"

# 레퍼런스를 'https://github.com/~'에 푸시하는데 실패
! [rejected]        main -> main (non-fast-forward)
git pull origin main
git config pull.rebase false
git pull origin main

# 병합 충돌
* branch            main       -> FETCH_HEAD
해당하는 파일을 열고

<<<<<<< HEAD
(내 컴퓨터에서 작성한 내용)
=======
(GitHub 서버에서 가져온 내용)
>>>>>>> main (혹은 commit hash)

<<<<<<<, =======, >>>>>>> 기호가 있는 줄을 모두 지우고
내용 정리 후 > git add . 

```
