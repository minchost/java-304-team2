# java-304-team2
이젠304 2조
<!DOCTYPE html>
<html lang="en">

<head>
		<meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="Content-Security-Policy" content="upgrade-insecure-requests">
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.6.0/jquery.min.js"></script>
    <title>나만의 동기부여 홈화면 만들기</title>

    <script src="index.js"></script>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@500&display=swap');

        * {
            font-family: 'Poppins', sans-serif;
        } 

        body {
            background-image: url("https://cdn.britannica.com/16/99616-050-72CD201A/Colosseum-Rome.jpg");
            background-position: center;

            color: white;
        }

        .time {
            font-size: 90px;
            font-weight: bold;
        }

        .greeting {
            font-size: 50px;
        }

        .todo {
            font-size: 30px;
        }

        .author {
            font-size: small;
        }

        .main {
            width: 100vw
            height 80vh;

            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
        }

        .quote {
            width: 100vw;
            height: 20vh;

            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
        }
    </style>

    <script>
    </script>
</head>

<body>
    <div class="main">
        <div id="time" class="time">12:00</div>
        <div class="greeting">안녕하세요</div>
        <div class="todo">아버지한테 연락드리기 </div>
    </div>
    <div class="quote">
        <div id="author" class="author">- 명언의 저자 -</div>
        <div id="content" class="content">" 명언의 내용 "</div>
    </div>
</body>

</html>
