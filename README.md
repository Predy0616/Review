# **Review**
<br><br>

# **풍선 총 쏘기**

## **문제**
### 영현이는 메이플스토리 풍선 총 쏘기 이벤트에 참가했다.
### 5000원이라는 거금을 내고 3발의 기회를 얻은 영현이가 최고 점수를 받는 방법을 찾아주자.
### N X M 개의 2차원 배열로 점수가 적힌 풍선의 점수를 입력받는다.
### 풍선 배열의 위, 왼쪽에서만 총을 쏠 수 있으며 총은 일직선으로 직진하여 모든 풍선을 터뜨린다.
### 총은 수직과 대각선 두 방향, 총 3방향으로 발사할 수 있다.
<br>

### 아래는 5 X 4 크기의 풍선 배열을 입력받은 모습이다.
### 'O' 에서만 총을 발사 할 수 있다.

|O|O|O|O|O|O|O|
|-|-|-|-|-|-|-|
|O|90|70|50|40|60|X|
|O|40|64|30|40|54|X|
|O|61|40|45|4|60|X|
|O|20|75|50|4|60|X|
|O|X|X|X|X|X|X|X|

<br>

### '!' 에서 수직으로 총을 발사한 모습이다.
|O|O|O|!|O|O|O|
|-|-|-|-|-|-|-|
|O|90|70|.|40|60|X|
|O|40|64|.|40|54|X|
|O|61|40|.|4|60|X|
|O|20|75|.|4|60|X|
|O|X|X|X|X|X|X|X|
### 175점을 얻었다.
<br>

### 두번째 발사
|O|O|O|!|O|O|O|
|-|-|-|-|-|-|-|
|!|.|.|.|.|.|X|
|O|40|64|.|40|54|X|
|O|61|40|.|4|60|X|
|O|20|75|.|4|60|X|
|O|X|X|X|X|X|X|X|
### 260점을 얻었다. (총 435점)
<br>

### 세번째 발사
|O|O|O|!|O|O|O|
|-|-|-|-|-|-|-|
|!|.|.|.|.|.|X|
|O|40|64|.|40|54|X|
|O|61|.|.|4|60|X|
|O|.|75|.|4|60|X|
|!|X|X|X|X|X|X|X|
### 60점을 얻었다. (총 495점)
<br>

### 이러한 방법으로 3발의 총알을 발사했을때 얻을 수 있는 최대 점수를 출력한다.
<br>

## **입력**
### 2차원 배열의 크기 N, M 을 입력 받은 후 풍선 점수 배열을 입력받는다.
```
5 4
90 70 50 40 60
40 64 30 40 54
61 40 45 4 60
20 75 50 4 60
```
<br>

## **출력(단순 예시, 정답 아님)**
```
495
```
<br>


### 알고리즘 분류
### BFS, DFS, 구현
