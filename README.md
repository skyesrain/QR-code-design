# QR-code-design
QR CODE
took the code from scratch , with a step by step approach
however i faced some challenges with alignment with Css grid so i decided to proceed with the normal 
positionig techniques
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0"> <!-- displays site properly based on user's device -->
  <link rel="icon" type="image/png" sizes="32x32" href="./images/favicon-32x32.png">
  <link rel="stylesheet" href="style.css">
  <link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Outfit:wght@100;200&display=swap" rel="stylesheet">

  <title>Frontend Mentor | QR code component</title>
</head>
<body>

  <div class="container">
   
    <div class="qr">
     <img src="images/image-qr-code.png">
     <h3>improve your front-end skills by building projects</h3>
     <p>scan the QR code to visit frontend mentor and take your
       coding skills to the next level</p>

    </div>

  </div>


  <div class="attribution">
    Challenge by <a href="https://www.frontendmentor.io?ref=challenge" target="_blank">Frontend Mentor</a>. 
    Coded by <a href="#">Taddeo Namusanga</a>.
  </div>
</body>

</html>

*{
    box-sizing: border-box;
    margin:0;
    padding:0;
}
/* utilities */
body{
 background-color:rgb(176,172,172);
  font-family: 'Outfit', sans-serif;
  font-size: 15px;
  width:100%;
  height: 100%;
}

.container{
background-color:#D8e4ec;
width:70%;
height:500px;
margin: auto;
margin-top: 200px;
border:30px solid lightgray
}
/* main qr code break down */
.qr{
background-color: #ffff;
margin:auto;
width:200px;
height:80%;
position:relative;
top:30px;
border-radius: 5px;

}
h3{
    font-weight: 700;
    position: absolute;
    bottom: 90px;
    text-align: center;
    font-size: 15px;
    font-family: 'Outfit', sans-serif;
}
p{
    font-weight: 400;
    position: absolute;
    bottom: 10px;
    text-align: center;
    font-size: 15px;
    padding:0;
    font-family: 'Outfit', sans-serif;
}
img{

    width:180px;
    position: absolute;
    left:10px;
    top:10px;
    border-radius: 5px;
    margin:0;
    padding:2px;
  
}






