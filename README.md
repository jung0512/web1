# jsp-
학교 수행평가 실습

<header id="header">
	<h1>쇼핑몰 회원관리 ver 1.0</h1>
</header>
쇼핑몰의 위에 뜨게 만들었다
<nav id="nav">
	<ul>
		<li><a href="#">회원등록</a></li>
		<li><a href="#">회원목록조회/수정</a></li>
		<li><a href="#">회원매출조회</a></li>
		<li><a href="index.jsp">홈으로</a></li>
	</ul>
	</nav>
  하이퍼링크를 걸어서 index.jsp을 실행하게 하였다
  
 <section class="section">
	<h2>쇼핑몰회원관리 프로그램</h2>
	<p>
	쇼핑몰 회원정보와 회원매출정보 데이터베이스를 구출하고 회원관리 프로그램을 작성하는 프로그램이다.<Br>
	프로그램 작성 순서<Br>
	1. 회원정보 테이블을 생성한다.<Br>
	2. 매출정보 테이블을 생성한다.<Br>
	3. 회원정보, 매출정보 테이블에 제시된 문제지와 참조데이터를 추가 생성한다.<Br>
	4. 회원정보 입력 화면프로그램을 작성한다.<Br>
	5. 회원정보 조회 프로그램을 작성한다.<Br>
	6. 회원매출정보 조회 프로그램을 작성한다.<Br>
	</p>	
	</section>
   가운데에 계속 바뀌기 때문에 css로 고정을 해주지 않았다<br>
    
    <footer id="footer">
	<p>HRDKOREA Copyright&copy;2016 All rights reserved. Human Resources Development Service of Korea.</p>
	</footer>
    저작권 표기법을 써놨다
    <header >
	    <jsp:include page="layout/header.jsp"></jsp:include>
</header>
<nav><jsp:include page="layout/nav.jsp"></jsp:include></nav>
<section><jsp:include page="layout/section.jsp"></jsp:include></section>
<footer><jsp:include page="layout/footer.jsp"></jsp:include></footer>
위에서 만들것들을 한개의 파일로 불러들어서 출력<br>
![image](https://user-images.githubusercontent.com/102035198/170624378-60b78c84-4eb8-40bd-bf20-20f38b90dbf3.png)<br>
![image](https://user-images.githubusercontent.com/102035198/170624395-6f5f71f8-fd0e-4159-ba65-548f3b18cfb5.png)<br>
css로 각 파일들의 설정들을 해주어서 만들었다 <br>
밑에 사진은 결과 사진이다<br>
![image](https://user-images.githubusercontent.com/102035198/170625394-7d9d78d5-b2d2-4c29-8ad4-b6456ca75182.png)<br>

		


