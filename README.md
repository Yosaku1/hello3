<!DOCTYPE html> 
<html lang="ja" >
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<style>
    body {
    margin: 0;
    font-family: Arial, Helvetica, sans-serif;
    }

    .topnav {
    overflow: hidden;
    background-color: #333;
    }

    .topnav a {
    float: left;
    display: block;
    color: #f2f2f2;
    text-align: center;
    padding: 14px 16px;
    text-decoration: none;
    font-size: 17px;
    }

    .topnav a:hover {
    background-color: #ddd;
    color: black;
    }

    .topnav a.active {
    background-color: #4CAF50;
    color: white;
    }

    .topnav .icon {
    display: none;
    }

    @media screen and (max-width: 600px) {
    .topnav a:not(:first-child) {display: none;}
    .topnav a.icon {
        float: right;
        display: block;
    }
    }

    @media screen and (max-width: 600px) {
    .topnav.responsive {position: relative;}
    .topnav.responsive .icon {
        position: absolute;
        right: 0;
        top: 0;
    }
    .topnav.responsive a {
        float: none;
        display: block;
        text-align: left;
    }
    }
</style>

<!---->
<style>
body, html {
  height: 85%;
}

* {
  box-sizing: border-box;
}

.bg-image {
  /* The image used */
  background-image: url("images/kouyou.png");


  /* Full height */
  height: 100%;

  /* Center and scale the image nicely */
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
}

/* Position text in the middle of the page/image */
.bg-text {
  background-color: rgb(0,0,0); /* Fallback color */
  background-color: rgba(0,0,0, 0.4); /* Black w/opacity/see-through */
  color: white;
  font-weight: bold;
  border: 3px solid #f1f1f1;
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  z-index: 2;
  width: 80%;
  padding: 20px;
  text-align: center;
}

</style>


<!--Botton-->
<style>
    .button {
        border: none;
        color: white;
        padding: 16px 32px;
        text-align: center;
        text-decoration: none;
        display: inline-block;
        font-size: 16px;
        margin: 4px 2px;
        transition-duration: 0.4s;
        cursor: pointer;
        }

    .button1 {
        background-color: white; 
        color: black; 
        border: 2px solid #4CAF50;
        }

    .button1:hover {
        background-color: #4CAF50;
        color: white;
        }

    .button2 {
        background-color: white; 
        color: black; 
        border: 2px solid #008CBA;
        }

    .button2:hover {
        background-color: #008CBA;
        color: white;
        }

</style>


</head>








<body>
<!--Top menu-->
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">

<div class="topnav" id="myTopnav">

<img width="80" height="50" src="images/Japon.Go.png" class="attachment-full size-full wp-post-image jetpack-lazy-image" alt="プロレド・パートナーズ 戦略コンサルティングファーム2" loading="lazy" 
    data-lazy-srcset="images/Japon.Go.png" 
    data-lazy-sizes="(max-width: 1409px) 300vw, 1409px" 
    data-lazy-src="images/Japon.Go.png" 
    srcset="images/Japon.Go.png" />

  <a href="#home" class="active">Home</a>
  <a href="#news">News</a>
  <a href="#contact">Contact</a>
  <a href="#about">About</a>
  <a href="javascript:void(0);" class="icon" onclick="myFunction()">
    <i class="fa fa-bars"></i>
  </a>
</div>



<!--Back Ground -->

<div class="bg-image"></div>

<div class="bg-text">
  <h1>Clase de Japones en linea</h1>

<!--Botton-->
<button class="button button1">mas informacion</button>


</div>

<div class="column" style="background-color:#f5deb3">
    <br><br><br><br><br><br><br><br><br>
</div>    
</body>
</html>
