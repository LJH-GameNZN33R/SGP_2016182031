# Poker Defense


## 게임 컨셉

여러 등급의 유닛을 포커를 통해 뽑는다. 뽑은 유닛을 강화하면서, 일정 갯수의 적 웨이브를 막아낸다.


## 개발범위

- 포커 미니게임을 통한 랜덤 유닛 구매
- 유닛 간 종족 시너지
- 후반으로 갈수록 계속 강력해져가는 적 웨이브와 일정 웨이브마다 중간보스 소환
- 웨이브를 막아내며 포커를 하기 위한 재화와 강화 재화를 획득


## 예상 흐름

![Screenshot_20200809-204431](https://user-images.githubusercontent.com/53070557/160723718-d17fb9c1-1e2c-4133-8f0e-482c4760b8a2.png)

시작 버튼을 눌러 게임에 진입하면 다음과 같은 초기 화면을 구성한다.

![Screenshot_20200809-223007](https://user-images.githubusercontent.com/53070557/160723776-5aff8a2d-cdfd-4df7-a3fd-468d68f55c4d.png)

유닛을 뽑고 강화 및 배치하며 일정 시간마다 몰려오는 웨이브를 막아내도록 한다.

![640](https://user-images.githubusercontent.com/53070557/160723841-42cbd5d7-85df-4d65-877a-929425bedd7b.png)

중간에 적이나 아군 유닛을 터치하면 그 정보를 출력하도록 한다.

좌측에 웨이브 목록이 출력되는데 이를 모두 막아내면 성공, 중간에 필드에 소환된 적의 개체수가 일정 갯수 이상 넘어가면 패배하는 것으로 한다.


## 개발 일정

1주차 : 리소스 수집, 프로젝트 착수

2주차 : 게임 시작화면 디자인 및 구현

3주차 : 적 개체 메커니즘 구현

4주차 : 포커 미니게임 화면 제작

5주차 : 아군 유닛 능력 구현 및 포커 화면 결과와의 연동으로 소환 구현

6주차 : 적 캐체를 이용해 웨이브 레벨 디자인 제작

7주차 : 아군 유닛 강화 기능 구현

8주차 : 게임 중 실패 조건 확인기능, 게임 종료 후 재시작 구현

9주차 : 버그픽스 및 발표
