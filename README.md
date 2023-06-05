# Git 명령어

## Git 로컬 켬퓨터에 사용자 등록하기

- git config --global user.name "YANGSANGHYUK"
- git config --global user.email "didtkdgur333@naver.com"

## Git 시작하기

- git init
- git add .
- git commit -m "최초 커밋"

## Github 업로드하기

- git remote add origin 주소
- git push origin master

## 다시 업로드 법

- 소스코드 변경
- git add .
- git commit -m "변경내용 적고"
- git push origin master

//잘 안될 때 해결법

- gir remote -v
- git reomote rm origin
