<!DOCTYPE html>
<html lang="ko">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Favorite Mangas</title>

   <style>
  body {
      font-family: Arial, sans-serif;
      margin: 0; /* 페이지 상단 여백  */
      padding: 0;/* 페이지 좌우 여백 */
      background-color: #4286f4;
  }

  h2 {
      text-align: center; /* 글자 가운데 정렬 */
      color: #203A43;
  }

  .container {
      display: flex; /* 플렉스 박스로 설정하여 요소들을 가로로 */
      justify-content: center; /* 요소들을 수평 중앙으로 */
      align-items: center; /* 요소들을 수직 중앙으로 */
      flex-wrap: wrap; /* 요소가 박스를 넘치면 줄바꿈 */
      padding: 10px;/*여백의 미 */
      width: calc(60%);
      position: absolute; top: 20%; left: 20%;
      
      
  }

  .picture {
      width: calc(50% - 20px);
      max-width: 200px; /* 최대 너비 */
      height: 250px; /* 높이 */
      background-color: #fff;
      border-radius: 13px; /*직사각형 모양 */
      box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1); /* 그림자 효과를 추가 */
      margin: 10px; /* 박스 주위에 여백*/
      padding: 30px; /*p 내부에 여백 */
      text-align: center; /* 글자 가운데 정렬 */
  }

  .picture img {
      width: 160px; 
      height: 160px; 
      border-radius: 0%; 
      margin-bottom: 10px;
  }

  .picture h3 {
      font-size: 16px; 
      margin-bottom: 5px; /* 제목 아래 여백 */
      color :black;
  }

  .picture p {
      font-size: 14px; 
      color: #2193b0; 
  }

  @media only screen and (max-width: 600px) {
      .container {
          flex-direction: column; 
      }
  }
  </style>

</head>
<body>
  <h2>좋아하는 일본만화들</h2>
  <div class="container">
    <div class="picture">
      <img src="https://upload.wikimedia.org/wikipedia/ko/3/32/%EC%9B%90%ED%94%BC%EC%8A%A4_1%EA%B6%8C_%ED%91%9C%EC%A7%80.jpg?20230625143009"
      height="150" 
      alt="">
      <h3>원피스</h3>
      <p>오다 에이치로</p>
    </div>
    <div class="picture">
      <img src="https://image.yes24.com/goods/103191765/XL"
      height="150" alt="">
      <h3>귀멸의 칼날</h3>
      <p>고토게 코요하루</p>
    </div>
    <div class="picture">
      <img src="https://image.yes24.com/goods/105174913/XL"
      height="150" 
      alt="">
      <h3>진격의 거인</h3>
      <p >이사야마 하지메</p>
    </div>
    <div class="picture">
      <img src="https://contents.kyobobook.co.kr/sih/fit-in/400x0/pdt/9791134887179.jpg"
      height="150"
       alt="">
      <h3>장송의 프리렌</h3>
      <p>야마다 카네히토</p>
    </div>
    <div class="picture">
      <img src="https://image.aladin.co.kr/product/25127/98/cover500/k342633273_1.jpg"
      height="150" 
      alt="">
      <h3>체인소맨</h3>
      <p>후지모토 타츠키</p>
    </div>
    <div class="picture">
      <img src="https://image.yes24.com/goods/89241541/XL"
      height="150"
       alt="">
      <h3>은혼</h3>
      <p>소라치 히데아키</p>
    </div>
    <div class="picture">
      <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTHI3hQ47RtT-nrnEH0rNQ2vs9fVpp1ZF9Rn5H8KpJiYw&s"
      height="150"
       alt="">
      <h3>카구야님은 고백받고 싶어</h3>
      <p>아카사카 아카</p>
    </div>
    <div class="picture">
      <img src="https://i.namu.wiki/i/knO_jHdyLoVOc1md7YjimA49fU9POoz_gOqKFx6jwAxw3OTyrLwr87xPAbKpic-rKvqnw_-qBcw8lCLPUsSHyQ.webp"
      height="150"
       alt="">
      <h3>내 마음의 위험한 녀석</h3>
      <p>사쿠라이 노리오</p>
    </div>
  <div>
</body>
</html>
