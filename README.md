<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <title>First One - 메인</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>나의 여행 홈페이지</h1>
        <nav>
            <a href="firstone.html">홈</a>
            <a href="about.html">소개</a>
            <a href="gallery.html">사진</a>
        </nav>
    </header>

    <section class="main">
        <img src="images/main.jpg" class="main-img">
        <h2>환영합니다!</h2>
        <p>제가 여행하면서 찍은 사진을 정리한 홈페이지입니다.</p>
    </section>

    <footer>
        © 2025 My Travel Page
    </footer>
</body>
</html>

<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <title>소개 - First One</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>소개</h1>
        <nav>
            <a href="firstone.html">홈</a>
            <a href="about.html">소개</a>
            <a href="gallery.html">사진</a>
        </nav>
    </header>

    <section>
        <h2>나의 여행 기록</h2>
        <p>이 홈페이지는 제가 여행하면서 남긴 추억들을 사진으로 정리한 공간입니다.</p>
        <p>단순하지만 HTML과 CSS만 사용해 만들었습니다.</p>
    </section>

    <footer>
        © 2025 My Travel Page
    </footer>
</body>
</html>

<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <title>사진 갤러리 - First One</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>사진 갤러리</h1>
        <nav>
            <a href="firstone.html">홈</a>
            <a href="about.html">소개</a>
            <a href="gallery.html">사진</a>
        </nav>
    </header>

    <section class="gallery">
        <img src="images/travel1.jpg">
        <img src="images/travel2.jpg">
        <img src="images/travel3.jpg">
    </section>

    <footer>
        © 2025 My Travel Page
    </footer>
</body>
</html>

body {
    margin: 0;
    font-family: Arial, sans-serif;
    text-align: center;
}

header {
    background: #333;
    padding: 20px;
    color: white;
}

nav a {
    color: white;
    margin: 0 10px;
    text-decoration: none;
    font-weight: bold;
}

nav a:hover {
    text-decoration: underline;
}

.main-img {
    width: 70%;
    border-radius: 10px;
    margin-top: 20px;
}

.gallery img {
    width: 30%;
    margin: 10px;
    border-radius: 10px;
}

section {
    padding: 20px;
}

footer {
    margin-top: 30px;
    background: #eee;
    padding: 10px;
}

<img src="images/main.jpg">
