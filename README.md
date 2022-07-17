# 딥러닝
## 주제
타이타닉 사고가 일어났다고 했을 때 생존 여부 예측

## 데이터 설명
[타이타닉 승객 정보](https://web.stanford.edu/class/archive/cs/cs109/cs109.1166/stuff/titanic.csv)를 이용하여 생존 여부에 대한 2-class classification
### 칼럼 설명
*   Survived : 생존 여부(1/0)
*   Pclass : 티켓 등급(1/2/3)
*   Name : 이름
*   Sex : 성별
*   Age : 나이
*   Siblings/Spouses Aboard : 함께 탑승한 형제, 배우자의 수
*   Parents/Cildren Aboard : 함께 탑승한 부모, 자식의 수
*   Fare : 탑승료
### 데이터 예시
| | Survived | Pclass | Sex | Age | Siblings/Spouses Aboard | Parents/Children Aboard | Fare |
---|---|---|---|---|---|---|---|---|
0 | 0 | 3 | Mr. Owen Harris Braund | male | 22.0 | 1 | 0 | 7.2500 |
1 | 1 | 1 | Mrs. John Bradley (Florence Briggs Thayer) Cum... | female | 38.0 | 1 | 0 | 71.2833 |
