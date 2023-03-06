<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="./subhan2.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.3.0/css/all.min.css"
    integrity="sha512-SzlrxWUlpfuzQ+pcUCosxcglQRNAq/DZjVsC0lE40xsADsfeQoEypE+enwcOiGjk/bSuGGKHEyjSoQ1zVisanQ=="
    crossorigin="anonymous" referrerpolicy="no-referrer" />
    <title>Document</title>
    <style>
    *{
    padding: 0px;
    margin: 0px;
}
body{
    font-family: Impact, Haettenschweiler, 'Arial Narrow Bold', sans-serif;
    background-color: rgb(57, 53, 53);
}
.container{
    width: 100%;
    height: 100px;
    display: flex;
    justify-content: space-between;
    align-items: center;
}
.img-1{
 margin-top: 10px;   
 color: aliceblue;
}
.para-1{
    color: aliceblue;
    margin: 10px;
    font-size: 20px;
}
ul{
    list-style: none;    
}
li{
    display: inline-block;
    margin: 20px;
    color: aliceblue;
}
.img-2{
    margin: 10px;
    color: aliceblue;
}
.img-3{
    margin: 10px;
    color: aliceblue;
}
.img-4{
    margin-left: 10px;
    color: aliceblue;
}
a{
    text-decoration: none;
    color: aliceblue;
    
}
.center-div{
    border: 2px solid wheat;
    width: 99%;
    height: 900px;
    display: flex;
    border-color: blue;
}
.div-3{
    margin-top: 0px;
}
.item-1{
  width: 20%;
  height: 400px;
  border: 2px solid black;
  margin-top: 300px;
  margin-left: 100px;  
  border-color: brown;
}

.item-3{
 width: 20%;
 height: 400px;
 border: 2px solid black;
 margin-top: 300px;
 margin-left: 150px;
 border-color: royalblue;   
}
.para-2{
    font-size: 50px;
    color: rgb(182, 175, 175);
}
.para-3{
    font-size: 70px;
    color: aliceblue;
}
.line{
 border: 2px solid yellow;
 width: 35%;
 height: 0px;
 margin-top: 20px;
}
.para-4{
    font-size: 25px;
    color: aliceblue;
    margin-top: 20px;
}
.div-5{
    border: 1px solid grey;
    width: 450px;
    height:450px;  
    display: flex;
    justify-content: center;
    align-items: center;
    border-radius: 50%;  
    background-color: black;
    margin-left: 150px;
    margin-top: 250px;
    }
.para-6{
    font-size: 25px;
    color: rgb(214, 200, 200);
}
.para-7{
    font-size: 20px;
    margin-top: 20px;
    color: rgb(214, 200, 200);
}
.para-8{
    color: yellow;
    margin-top: 20px;
}
.arrow{
    margin-left: 15px;
}
.div-pic{
    display: flex;
}
.pic{
    margin-top: 10px; 
    padding: 10px; 
    height: 15px;
    width: 15px;
    background-color: yellow;
    }
    .imgs{
        width: 100%;
        height: 800px;
    }
    
    </style>
</head>
<body>
    <div class="container">
        <div class="div1"><span class="img-1"><i class="fa-sharp fa-solid fa-face-laugh"></i></span>
          <span class="para-1"> subhan</span>
        </div>
        <div class="div-2">
            <ul>
               <li><a href="#">Home</a></li>
               <li><a href="#">Portfolio</a></li>
               <li><a href="#">Testimonial</a></li>
               <li><a href="#">About</a></li>

            </ul>
        </div>
        <div class="div3">
            <span class="img-2"><i class="fa-solid fa-earth-americas"></i></span>
            <span class="img-3"><i class="fa-brands fa-linkedin"></i></span>
            <span class="img-4"><i class="fa-solid fa-bars"></i></span>
          </div>
    </div>
    <div class="center-div">
       <div class="item-1">
        <h1 class="para-2">I'm</h1>
        <h1 class="para-3">Subhan Khan</h1>
        <div class="line"></div>
        <p class="para-4">A freelancer who provides <br>services for digital programming <br>and design content needs, for <br>all businesses with more than <br>10 year of experience</p>
       </div>
       <div class="div-5">
        <div><img class="imgs" src="./image2/subhan3.png" alt="MY-PIC"></div>
       </div>
       <div class="item-3">
        <p class="para-6">Services</p>
        <p class="para-7">Lorem ipsum dolor sit amet consectetur adipisicing elit. Excepturi esse ipsa placeat a ad explicabo, accusamus perferendis. Architecto quae ab minima, repudiandae consectetur temporibus tempore, incidunt, saepe sapiente provident ipsum.</p>
        <p class="para-8">Show more   <span class="arrow"><i class="fa-solid fa-arrow-right"></i></span></p>
        <div class="div-pic">
            <div class="pic"><span class="pics-1"><i class="fa-brands fa-facebook"></i></span></div>
            <div class="pic"><span class="pics-2"><i class="fa-brands fa-twitter"></i></span></div>
            <div class="pic"><span class="pics-3"><i class="fa-brands fa-instagram"></i></span></div>
            <div class="pic"><span class="pics-4"><i class="fa-brands fa-pinterest-p"></i></span></div>
        </div>
       </div>
    </div>
 
</body>
</html>
