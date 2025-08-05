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

### day09 - bootstrap practice-louis vuitton
부트스트랩 스타일을 오바라이트(수정테이프로 지우고 다시쓰기)한다. 바꿀 스타일 클래스를 복사해서 style.css에 쓰고 내가 쓰고 싶은 스타일 지정함.
나중에 오는 css가 더 중요하다.( 그 전에 것을 오버라이트 한다.)
- 부트스트랩 각 속성값이 궁금하면 하나씩 없애면서 차이를 보면서 놀아보세요. 
- p태그는 기본적으로 margin-bottom: 1rem이 있습니다.
###### rem
은 root 즉 html 기준(최상위)의 font-size 기준으로 계산을 합니다. 
html 폰트사이즈가 12px이면 1rem하면 12px, 2rem 24px, 3rem 하면 36px임. 
###### layout
- 아이템이 가로로 한 줄에 들어갈 때 : row와 col로 그린다. (row 안에 col)
- 모바일에서 한 줄에 아이템(카드) 하나 넣을 때 col-sm-12
###### layout - container
가운데로 모아줌 row 위에 단에다가 container를 써주는 것임




