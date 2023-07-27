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
![intro_AdobeExpress](https://github.com/jw0202058/week4/assets/123575547/0393c01f-c882-4f73-9d6f-7c4a11c1295f)
<br>
![intro_AdobeExpress (1)](https://github.com/jw0202058/week4/assets/123575547/a0fa8fd6-09d2-403a-9939-e304ef17fb39)
<img src="https://github.com/jw0202058/week4/assets/123575547/a0fa8fd6-09d2-403a-9939-e304ef17fb39.png  width="200" height="400"/>

* 고려대학교를 배경으로 하는 맵의 전체적인 뷰를 감상
* 인트로 화면이 끝나면 자동으로 MainMenuScene으로 넘어가며, 아무 키나 입력 시에도 넘어감

### MainMenuScene
```
```
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
![loading_AdobeExpress](https://github.com/jw0202058/week4/assets/123575547/4ba459a0-c6f6-4460-b119-1eca1be8c6fb)


### GameMap_Day

![s1](https://github.com/jw0202058/week4/assets/121816472/8ab5b4f6-3ee9-47bc-a1ba-0bcdc5db8510)
![s2](https://github.com/jw0202058/week4/assets/121816472/338687ed-7825-4321-a482-102202210b2c)
![s3](https://github.com/jw0202058/week4/assets/121816472/50ba325c-ac3e-47c2-817c-db569729153a)
![s4](https://github.com/jw0202058/week4/assets/121816472/543bd8a7-26b5-45a6-a96c-047d5c87d565)
![s5](https://github.com/jw0202058/week4/assets/121816472/99c699fc-db73-43fb-8a08-9207072bb25d)


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
* 게임의 Night 버전
* Day 버전과 요소는 동일하며, 맵을 밝히는 조명이 추가
* 캐릭터의 앞을 밝혀 주는 조명이 추가
