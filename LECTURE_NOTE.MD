강의 : https://codingnoona.thinkific.com/

1. https://projects.verou.me/css3patterns/#cross-dots
2. https://fontawesome.com/
3. flex 연습 사이트  : https://flexboxfroggy.com/#ko 10단계까지 함. 11단계 할 차례

### CDN
CDN : contents delivery network (fontawesome 쓸 때 head 안에 script 넣는 거 같은 거) 남이 만든 스타일이나 코드를 가지고 오는 것이 cdn이다. 내가 만들지 않아도 남이 만든 것을 가지고 올 수 있다. 

### position
###### position: relative; 
하고 top left 주면 내가 있던 위치에서 밀리는데, 다른 요소는 가만히 있고 나만 밀림. 
###### position: absolute; 
는 내가 속한 부모의 전체 픽셀을 기준으로 움직임. (부모 : position이 relative, absolute, fixed 중 하나여야 한다.)
###### position: static;
은 웹브라우저의 기본값 default. left top bottom right 이해 못함. 몰라도 됨.
###### position: fixed;
스크롤 생겼을 때 스크롤 해도 고정시키는 거. 영원히 따라옴. 반면, absoulte는 안 따라 옴.
###### position: sticky;
?

### flexbox
화면사이즈에 유동적
###### display: flex;
세로가 가로 정렬이 됨. 
###### justify-content: flex-end;
화면 가로 끝으로 감
###### justify-content: center;
계산해서 중앙
###### justify-content: space-between;
엄마 밑에 3개 있으면 3개 사이에 정확하게 공간을 줌
###### justify-content: space-around;
양끝에 있는거에 공간 좀 주는 거 
###### flex-direction: column;
