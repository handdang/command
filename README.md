# 내가 보고 쓰려고 저장해두는 터미널 명령어👩‍💻

+ 포트 충돌 났을 경우 사용중인 포트 찾아서, Kill 하기(MAC ver)
```
sudo lsof -i:포트번호
sudo kill -9 pid값
```

+ Git 계정 변경 방법
```
git config — global user.name handdang
git config — global user.email yunha97@naver.com
```
또는 소스트리 설에서 변경해도 됨 ㅎ

+ Git requested URL returned Error 403 
```
git remote set-url origin https://handdang@github.com/handdang/vanilajs.git
```
