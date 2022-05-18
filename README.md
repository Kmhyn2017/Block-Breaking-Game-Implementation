# 블럭깨기 게임 구현

팀장 : 김기현

팀원 : 신영룡, 서창환

---
요약 : 블럭과 공이 있으면, 공은 항상 이동하면서 서로 간의 거리를 측정한다. 또한 블럭과 공의 충돌 여부도 체크한다. 충돌한다는 것을 응용하면 게임에서는 블록깨기 게임으로 공을 튕기거나 블록을 파괴하는 것도 구현할 수 있을 것이다. 블럭을 생성하고 공을 맞추면 점수가 상승하는 게임을 구현하였습니다. 일정 점수를 획득하면, 공의 속도를 올려 난이도를 올렸습니다.  
  
개요 : dist() 함수를 사용하여 블럭과 공 사이 값을 구하고 일정 거리 안에 들시 충돌 판정으로 블럭이 파괴되는 것을 구현한다. 공 객체를 만들고 기본적인 공의 움직임을 만듭니다.
조종하는 패들에 공이 닿는 면에 따라서 공이 튕겨저 나오는 방향을 조종할 수 있도록합니다.

### 목표
1. 배경,벽돌, 공, 패들 그리기
2. 남은 벽돌 갯수, 사용자의 생명 text로 입력
3. 패들 조작
4. 공으로 블럭을 충돌 시켜 파괴 시키기
5. 충돌 될 시 점수 상승
6. 5점 획득 시 공의 속도 상승

### 예상 결과물
![1](https://user-images.githubusercontent.com/92089428/169038126-d52f9240-30cb-4923-a333-4aba26ee6055.PNG)

팀원 업무 분담

회의록
|일요일|월요일|화요일|
|:---:|:---:|:---:|
|15일|16일|17일|
|왼쪽정렬|오른쪽정렬|중앙정렬|
|왼쪽정렬|오른쪽정렬|중앙정렬|

참고 문헌  
https://wikidocs.net/102871 ( 도형의 거리와 충돌)  
https://velog.io/@tonic523/javascript-%EB%B2%BD%EB%8F%8C%EA%B9%A8%EA%B8%B0-%EA%B2%8C%EC%9E%84-%EB%A6%AC%EB%B7%B0

