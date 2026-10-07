# web261007

## 6주차 수업 실습 - 영화 포스터 카드

### 선택한 영화
- 영화 제목: 히트 (Heat)
- 개봉 연도: 1995
- 평점: 7.9

### 구현 내용
- HTML과 CSS를 이용하여 영화 포스터 카드 제작
- TMDB 포스터 이미지 사용
- 평점 배지 표시
- Google Fonts 적용
- 배경에 그라데이션 적용
- 카드에 둥근 모서리와 그림자 적용
- 마우스를 올리면 카드가 위로 이동하고 노란색 그림자가 나타나는 효과 적용

### 질문과 답변 요약

Q. 카드의 모서리를 둥글게 만드는 방법은?  
A. CSS의 border-radius 속성을 사용한다.

Q. 카드에 마우스를 올렸을 때 위로 움직이게 하는 방법은?  
A. :hover와 transform: translateY(-8px)을 사용한다.

Q. 평점 배지를 포스터 오른쪽 위에 배치하는 방법은?  
A. 카드에 position: relative를 적용하고 배지에 position: absolute를 적용한다.

Q. 포스터 이미지 비율을 유지하는 방법은?  
A. aspect-ratio와 object-fit: cover를 사용한다.
