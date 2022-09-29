---
layout: post
title:  "FreeDocs"
date:   2022-09-06 18:00:00 +0900
categories: Imaginery update
---
[FreeDocs] 를 헤로쿠로 배포하기

1. 프로젝트에 gunicorn 설치
2. Procfile 생성
  - web: gunicorn {main 진입점을 포함한 파일}:app
  - 띄어쓰기 매우매우매우매우매우매우매우 중요, 대부분의 에러가 이 부분에서 발생.

3. 헤로쿠에 프로젝트 생성
4. 깃허브 연결
  - 배포용 브랜치가 따로 있으면 좋다.
5. 배포성공


[FreeDocs]: https://github.com/nordap/electron/releases/tag/test
