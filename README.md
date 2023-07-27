# 🔥 MadCamp Week4

## 🏃 프로젝트명... 뭐 하지

## 🐯 팀원
* 고려대학교 컴퓨터학과 21학번 조재원<br>
* 고려대학교 컴퓨터학과 21학번 이정원

## 🖥️ 개발 환경
* Language: C#
* IDE: Unity

## 🏃‍♂️ 프로젝트 소개
고려대학교를 배경으로 하는 레이싱 게임
제한 시간은 2분 30초로, 시간 내에 장애물을 피해 목적지에 도달하는 것이 목표

### Intro
```
인트로 화면? 화면 녹화 해야 되나
```
* 게임 화면을 전체적으로 볼 수 있음
* 인트로 화면이 끝나면 자동으로 MainMenuScene으로 넘어가며, 아무 키나 입력 시에도 넘어간다

### MainMenuScene
```
```
* Dress
  * 클릭 시 캐릭터 줌인, 줌아웃
  * white, black, navy, crimson, 그리고 카이스트의 넙죽이, 고려대의 호이, 숙명여대의 눈송이 중 하나의 옷을 선택할 수 있는 버튼

* Front
  * 해당 씬에서는 달리는 모션을 시뮬레이션 할 수 있으며, Front 버튼 클릭 시 정면을 바라봄

* Map
  * Day, Night 중에서 맵을 선택할 수 있음. Done을 눌러야 변경 사항이 반영이 되며, Map이 선택되어 있는 상태에서만 Start 버튼이 활성화

* Start
  * 게임 시작 버튼

### LoadingScene
```
```


### GameMap_Day
```
```
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
