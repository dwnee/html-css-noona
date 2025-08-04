강의 : https://codingnoona.thinkific.com/

1. https://projects.verou.me/css3patterns/#cross-dots
2. https://fontawesome.com/
3. flex 연습 사이트  : https://flexboxfroggy.com/#ko

### CDN
CDN : contents delivery network (fontawesome 쓸 때 head 안에 script 넣는 거 같은 거) 남이 만든 스타일이나 코드를 가지고 오는 것이 cdn이다. 내가 만들지 않아도 남이 만든 것을 가지고 올 수 있다. / font awesome, bootstrap 같은 거

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


### day06-spotify
- body의 기본값은 display block
- font-family: Circular, spotify-circular, Helvetica, Arial, Helvetica, sans-serif; 이것은 circular가 없으면 spotify-circular가 나오고 그게 없으면 helvetica가 나온다는 뜻임. 
- em : font size 기준으로 배수하는거? 모바일, 반응형일 때 쓴다.

### day07 
https://youtu.be/tkkbYCajCjM?si=w8mcABYIzR8dzwxM

### day08 - bootstrap
모바일 버전, 남이 만들어놓은 거 갖다 쓰는 거.
미리 모든 걸 만들어놓은거임.
5분만에 만들 수 있음. 웹사이트를.
https://getbootstrap.com/
###### grid
부트스트랩은 웹사이트 한 줄 전체를 12로 나눴다. 
###### container
보통 사용자가 읽기 편한 픽셀이 1170px 이라고 함?
사용자가 읽기 편한 구조로 만들어주는 기능
저는 웹사이트를 구성하는데 있어서 과학적으로 구상을 하였습니다.
유저가 읽기 편한 사이즈에 컨텐츠를 넣어서 유저의 눈의 피로도를 낮췄습니다.
