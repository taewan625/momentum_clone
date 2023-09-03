# momentum_clone

## 목차
  - [개요](#개요)
  - [기획](#기획)
  - [실행환경](#실행환경)
  - [구현기능](#구현기능)
  - [참조](#reference)

## 개요
- 프로젝트 이름 : momentum clone 코딩 - chrome 내부 확장 프로그램 중 배경화면 및 todo service 제공
- 프로젝트 기간 : 2022.07.04 ~ 2022.07.17
- 개발 언어    : html, css, JS(ES6)
- 사용 tool   : vscode

## 기획
- 기획의도 : html5 css3 Vanilla JS 학습 목적 클론 코딩

## 실행환경
- Tool : vscode
- Language : html5, css3, JS(ES6)

## 구현기능
- github pages : https://taewan625.github.io/momentum_clone/
- 학습 기능
  - background img, 명언 refresh시, random()으로 변화하도록 적용
  - JS 시간 library 이용해서 실시간 시간 보여주기
  - ```event.preventDefault(); localStorage.setItem(key, value)``` 이용한 username 유지
  - localStorage를 이용한 create, delete todo를 JS로 수행
  - 날씨 API를 받아와서 browser에 적용하는 Ajax, fetch-then 문법 적용 (location과 api-key 받아오는 작업으로 리팩터링 필요)

- 페이지별 구현
1. index page  
시간, 날씨(추후 수정 예정), to-do, user-name, 명언  나타남  
<img width="450" height="300" alt="스크린샷 2023-09-03 오후 4 21 36" src="https://user-images.githubusercontent.com/104051002/265251060-bf85f436-15a4-44a1-a375-ddaa2e5cfe0b.png" style="max-width: 100%;">
<img width="450" height="300" alt="스크린샷 2023-09-03 오후 4 20 58" src="https://user-images.githubusercontent.com/104051002/265251065-1ea13fe5-256b-4a5e-b967-91c7e669b59d.png" style="max-width: 100%;">

2. user명, todo (입력, 삭제) 작성 화면  
```event.preventDefault(); localStorage.setItem(key, value) ``` 이용한 username, to-do 유지
<img width="450" height="300" alt="스크린샷 2023-09-03 오후 4 22 30" src="https://user-images.githubusercontent.com/104051002/265251099-f6a596d5-b6eb-4e07-b88d-be3b21694355.png" style="max-width: 100%;">
<img width="450" height="300" alt="스크린샷 2023-09-03 오후 4 22 50" src="https://user-images.githubusercontent.com/104051002/265251098-d050f98a-d087-4da0-a89a-3f89885d965b.png" style="max-width: 100%;">
<img width="450" height="300" alt="스크린샷 2023-09-03 오후 4 22 58" src="https://user-images.githubusercontent.com/104051002/265251096-4d6a4dda-a37d-4939-8f4d-e6b03f6e0bda.png" style="max-width: 100%;">


## reference
- nomadCoders.co
- MDN Web docs
- https://api.openweathermap.org/
