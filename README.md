<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Стартовое меню</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            height: 100vh;
            background-color: #FFC0CB; 
        }
        .header {
            position: absolute;
            top: 20px;
            left: 20px;
        }
        .header img {
            width: 70px;
            height: auto;
        }
        .menu {
            display: flex;
            align-items: center;
            position: absolute;
            left: 200px; 
            top: 50%; 
            transform: translateY(-50%); 
        }
        .menu img {
            width: 350px; 
            height: 500px; 
            margin-right: 20px; 
            border-bottom-left-radius: 20px;
            border-top-right-radius: 60px;
            border-bottom-left-radius: 60px;
        }
        .menu-content {
            display: flex;
            flex-direction: column;
            align-items: flex-start;
        }
        .menu-content .text {
            font-family: 'Courier New', Courier, monospace;
            font-size: 50px; 
            font-weight: bold; 
            margin-bottom: 20px; 
            color: #ffffff; 
            text-align: left; 
        }
        .menu-content button {
            padding: 10px 20px;
            font-size: 16px;
            cursor: pointer;
            border-radius: 20px; 
            border: 2px solid #d63f6f; 
            background-color: #f5c6c6; 
            color: #d63f6f;
            transition: background-color 3.10s, color 3.10s; 
        }
        .menu-content button:hover {
            background-color: #d63f6f; 
            color: #ffffff; 
        }
        .about-us {
            position: absolute;
            top: 20px;
            right: 20px;
        }
        .about-us a {
            text-decoration: none; 
        }
        .about-us button {
            background: transparent; 
            color: #d63f6f;
            border: 2px solid #d63f6f;
            border-radius: 20px;
            font-size: 16px;
            cursor: pointer;
            padding: 10px 20px; 
            transition: background-color 0.30s, color 0.30s;
        }
        .about-us button:hover {
            background: #d63f6f;
            color: #ffffff; 
        }
    </style>
</head>
<body>


    <div class="header">
        <img src="img/Logo2_x2.svg" alt="Логотип">
    </div>

    <div class="about-us">
        <a href="aboutus.htm"><button>About Us</button></a>
    </div>

    <div class="menu">
        <img src="img/Image.png" alt="Рисунок">
        <div class="menu-content">
            <div class="text">Change your life today</div>
            <a href="htmll — копия.htm"><button>Get started</button></a>
        </div>
    </div>

</body>
</html>
