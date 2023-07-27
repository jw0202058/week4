# 🔥 MadCamp Week4

## 🏃 RUNNER LEARNER

## 🐯 팀원
* 고려대학교 컴퓨터학과 21학번 조재원<br>
* 고려대학교 컴퓨터학과 21학번 이정원

## 🖥️ 개발 환경
* Language: C#
* IDE: Unity

## 🏃‍♂️ 프로젝트 소개
시간 내에 장애물을 피해 목적지에 도달하는 레이싱 게임
여러가지 버전의 맵을 2분 30초 내에 통과

### Intro
<img src="https://github.com/jw0202058/week4/assets/123575547/0393c01f-c882-4f73-9d6f-7c4a11c1295f.png"  width="350" height="250"/>
<img src="https://github.com/jw0202058/week4/assets/123575547/a0fa8fd6-09d2-403a-9939-e304ef17fb39.png"  width="350" height="250"/>

* 고려대학교를 배경으로 하는 맵의 전체적인 뷰를 감상
* 인트로 화면이 끝나면 자동으로 MainMenuScene으로 넘어가며, 아무 키나 입력 시에도 넘어감

### MainMenuScene
<img src="https://github.com/jw0202058/week4/assets/121816472/6e052671-8db8-4960-86cd-a3e527d9fa97.png"  width="350" height="250"/>
<img src="https://github.com/jw0202058/week4/assets/121816472/b819e1fa-f39f-4aea-b1e8-6b096b282fff.png"  width="350" height="250"/>

* Dress
  * 내 캐릭터의 모습을 미리 볼 수 있고 커스터마이징 가능
  * 클릭 시 캐릭터 줌인, 줌아웃 가능
  * white, black, navy, crimson, 그리고 카이스트의 넙죽이, 고려대의 호이, 숙명여대의 눈송이 중 하나의 옷을 선택

* Front
  * 해당 씬에서는 달리는 모션을 시뮬레이션 할 수 있으며, Front 버튼 클릭 시 정면을 바라봄

* Map
  * Day, Night 중에서 맵을 선택

* Start
  * 게임을 시작하는 버튼

### LoadingScene
<img src="https://github.com/jw0202058/week4/assets/123575547/4ba459a0-c6f6-4460-b119-1eca1be8c6fb.png"  width="350" height="250"/>


### GameMap_Day
<img src="https://github.com/jw0202058/week4/assets/121816472/8ab5b4f6-3ee9-47bc-a1ba-0bcdc5db8510.png"  width="350" height="250"/>
<img src="https://github.com/jw0202058/week4/assets/121816472/338687ed-7825-4321-a482-102202210b2c.png"  width="350" height="250"/>
<img src="https://github.com/jw0202058/week4/assets/121816472/543bd8a7-26b5-45a6-a96c-047d5c87d565.png"  width="350" height="250"/>
<img src="https://github.com/jw0202058/week4/assets/121816472/99c699fc-db73-43fb-8a08-9207072bb25d.png"  width="350" height="250"/>
![s5](https://github.com/jw0202058/week4/assets/121816472/d40a3085-afd0-4da5-a4b0-bcd1416fc6a7)

![s6](https://github.com/jw0202058/week4/assets/121816472/f674acc4-f76f-4c1e-871d-f8e5b1f2faf9)

* 게임의 Day 버전
* 여러 장애물과 트랙 등의 요소가 있으며, 보물 상자가 있는 곳에 도달 시 골인
* 게임 정지 버튼
  * 클릭 시 타이머 정지
  * restart 버튼 - 해당 맵을 처음부터 다시 시작
  * resume 버튼 - 게임 재개 버튼, 누르면 타이머 재가동
  * home 버튼 - MainMenuScene으로 씬 전환
* Minimap
  * 캐릭터를 위에서 바라보는 모습을 UI에 띄워 줌

### GameMap_Night
```
```
![e3](https://github.com/jw0202058/week4/assets/121816472/f1c5f1c7-3e07-4c57-ae99-25971d1b2a1b)

* 게임의 Night 버전
* Day 버전과 요소는 동일하며, 맵을 밝히는 조명이 추가
* 캐릭터의 앞을 밝혀 주는 조명이 추가
