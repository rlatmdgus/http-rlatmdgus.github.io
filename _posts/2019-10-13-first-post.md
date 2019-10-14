---
title: "나만의 웹 만들기"
date: 2019-10-13
categories: GitHub
---
새로 프로젝트 만들어서
<img src = "https://blog.chulgil.me/content/images/2019/01/Blog6-1-1.jpeg">
이미지 처럼 저장소 이름을 사용자.github.io 만들면 된다.

이제 콘솔창에서
```
$ git clone https://github.com/사용자이름/사용자이름.github.io.git
```
저장할 폴더에 가져와서 index.html을 만들어 그안에 Hello World를 추가 합니다.
```
$ cd 사용자이름.gitgub.io
$ echo "Hellow World"> index.html
```
변경사항 추가하고 커밋 및 푸시 합니다.
```
$ git add --all
$ git commit -m "1 commit"
$ git push
```
다 한다음 https://사용자.github.io 접속을 하게 되면 Hello World 뜨면서 나만에 웹이 만들어 집니다.
