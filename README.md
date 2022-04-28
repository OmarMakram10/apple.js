# apple.js
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>apple</title>
    <link rel="stylesheet" href="css/style.css">
</head>
<body>

    <div class="container">
        <header>
            <a href="#"><img src="images/logo.png" ></a>
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#">Product</a></li>
                <li><a href="#">News</a></li>
                <li><a href="#">About</a></li>
                <li><a href="#">Contact</a></li>
                
            </ul>
        </header>
        <div class="content">
            <div class="text">
                <h2>Iphone 12 Pro max</h2>
                <p>Lorem ipsum dolor sit amet consectetur 
                    dolor sit amet consectetur adipisicing elit. 
                    quia aliquid explicabo numquam veniam  ut odit!
                </p>
                    <a href="#">All Producta</a>
            </div>
            <div class="image">
                <img class="img" src="images/0.png" >
                
            </div>
        </div>
        <div class="icons">
            <img onclick="phones(this.src); colors('#000')"  src="images/0.png" >
            <img onclick="phones(this.src); colors('#247ec8')"  src="images/1.png" >            
            <img onpointerenter="phones(this.src); colors('#1e1e1e')"  src="images/2.png" >
            <img onclick="phones(this.src); colors('#c79b58')"  src="images/3.png" >
            <img onclick="phones(this.src); colors('#c82525')"  src="images/4.png" >            
        </div>
    </div>














    <script src="js/main.js"></script>
</body>
</html>
