# website
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>web_dev_hackathon</title>
    <style>
        *{
       margin: 0;
       font-family:Arial;
       border:border-box;
       
        }
        .aboveNavBar{
            background-color: aliceblue;
            height: 50px;
        }
    .navBar{
        position:fixed;
        background-color:rgb(191, 219, 243);
        height: 50px;
        width:2000px;
    }
    .logo{
        color:rgb(8, 8, 31);
        font-family: BOLD;
        font-size : 30px;
        margin-left:50px;
        margin-right: 700px;
    }
    .home{
        margin:15px;
    }
    .about{
        margin:15px;
    }
    .services{
        margin:15px;
    }
    .departments{
        margin:15px;
    }
    .doctors{
        margin:15px;
    }
    .contact{
        margin:15px;
    }
    button{
        background-color: rgb(37, 37, 128);
        border-radius: 2px solid;
        height:30px;
        width:200px;
        margin:15px;
        
    }
    .appointment{
        color:white;
    }
    .img1-container{
    
       position:relative;
    }
    .text-overlay1{
        font-size:bold;
        position:absolute;
        padding:10px;
        font-size:50px;
        color:rgb(6, 6, 92);
    top:200px;
    left:100px;
    }
    
    .text-overlay2{
        position:absolute;
        padding:10px;
        font-size:40px;
        color:rgb(6, 6, 93);
        top:270px;
        left:100px;
    }
    .text-overlay3{
        position:absolute;

        padding:0px;
        font:25px white;
        
        color:rgb(3, 3, 55);
        top:320px;
        left:100px;
    }
    .button2{
       border-radius: 2px;
    }
    .box{
        height:100px;
        width:50px;
    }
    .custom-box{
        display:flex;
    }
     .custom-box1{
        height:400px;
        width:400px;
        border:2px solid;
        background-color: rgb(24, 135, 214);
        margin-left:100px;
     }
     .custom-box1Text1{
        color:white;
        font-size: 50px;
        font-family:bold;
        margin-left:20px;
        margin-top:20px;
     }
     .custom-box1Text2{
        color:white;
        font-size: 30px;
        font-family:bold;
        margin-left:20px;
        margin-top:10px;
       
     }
     .custom-box2{
        height:400px;
        width:400px;
        border:2px solid;
        background-color: rgb(234, 239, 243);
        margin-left:100px;
     }
     .custom-box2Text1{
        color:black;
        font-size: 50px;
        font-family:bold;
        margin-left:20px;
        margin-top:20px;
     }
     .custom-box2Text2{
        color:black;
        font-size: 30px;
        font-family:bold;
        margin-left:20px;
        margin-top:10px;
       
     }
     .custom-box3{
        height:400px;
        width:400px;
        border:2px solid;
        background-color: rgb(245, 247, 248);
        margin-left:100px;
     }
     .custom-box3Text1{
        color:rgb(9, 1, 1);
        font-size: 50px;
        font-family:bold;
        margin-left:20px;
        margin-top:20px;
     }
     .custom-box3Text2{
        color:rgb(16, 1, 1);
        font-size: 30px;
        font-family:bold;
        margin-left:20px;
        margin-top:10px;
       
     }
     .custom-box4{
        height:400px;
        width:400px;
        border:2px solid;
        background-color: rgb(232, 236, 240);
        margin-left:100px;
     }
     .custom-box4Text1{
        color:black;
        font-size: 50px;
        font-family:bold;
        margin-left:20px;
        margin-top:20px;
     }
     .custom-box4Text2{
        color:rgb(20, 2, 2);
        font-size: 30px;
        font-family:bold;
        margin-left:20px;
        margin-top:10px;
       
     }
     .image2-container{
     display:flex;
     }
     .for-para{
display:content;
     }
     .image2-container-1-para-bold{
        margin-top:30px;
        margin-left: 50px;
        font-size: 30px;
        font-family:bold;
     }
     .image2-container-2-para-light{
        margin-top:30px;
        margin-left: 50px;
        font-size: 30px;
        
     }
     .image2-container-3-para-bold{
        margin-top:30px;
        margin-left: 50px;
        font-size: 30px;
        font-family:bold;
     }
     .image2-container-4-para-light{
        margin-top:30px;
        margin-left: 50px;
        font-size: 30px;
        
     }
     .image2-container-5-para-bold{
        margin-top:30px;
        margin-left: 50px;
        font-size: 30px;
        font-family:bold;
     }
     .image2-container-6-para-light{
        margin-top:30px;
        margin-left: 50px;
        font-size: 30px;
        
     }
     .image2-container-7-para-light{
        margin-top:30px;
        margin-left: 50px;
        font-size: 30px;
        font-family:bold;
     }
     
     
     

        
        </style>
</head>
<body>
    <header>
        <div class="aboveNavBar">
            <span>contact@example.com</span>
            <span>+1 5589 5548655</span>
        </div>
        <div class="navBar">
        <div class="text">
            <span Class="logo">LOREM_IPSUM</span>    
         <span class="home">Home</span>
                <span class="about">about</span>
               <span claa="services">Services</span>
                <span class="departments">Departments</span>
                <span class="doctors">Doctors</span>
                <select>
                    <option>Drop Down</option>
                </select>
                <span>contact</span>
                <button>
                <span class="appointment">Make an appointment</span>
                </button>
            </span>
           </div>
            
        </div>
        
    <div class="img1-container">
       
            
            <img src="about.jpg" alt="doctor image" height="800px" width="2000px">
            <p class="text-overlay1">WELCOME TO LOREM_IPSUM</p>
            <p class="text-overlay2">LOREM_IPSUM</p>
            <button class="text-overlay3" class="button2">
               get started</button>
            </div>
            <div class="custom-box">
            <div class="custom-box1">
                <p class="custom-box1Text1">Why Choose</p>
                <p class="custom-box1Text2">LOREM_IPSUM?</p>
                <p>underneath element will be written after</p>
        </div>
        <div class="custom-box2">
            <p class="custom-box2Text1">Why Choose</p>
            <p class="custom-box2Text2">LOREM_IPSUM?</p>
            <p>underneath element will be written after</p>
    </div>
    <div class="custom-box3">
        <p class="custom-box3Text1">Why Choose</p>
        <p class="custom-box3Text2">LOREM_IPSUM?</p>
        <p>underneath element will be written after</p>
</div>
<div class="custom-box4">
    <p class="custom-box4Text1">Why Choose</p>
    <p class="custom-box4Text2">LOREM_IPSUM?</p>
    <p>underneath element will be written after</p>
</div>


</div>



<div class="image2-container">


    <img src="hero-bg.jpg" alt="doctorimg" height="500px" width="1000px">
    <div class="for-para"></div>
<p class="image2-container-1-para-bold">will be written afterwards</p>
<p class="image2-container-2-para-light">lets see</p>
<p class="image2-container-3-para-bold">LOrem Ipsum</p>
<p class="image2-container-4-para-light">written after</p>
<p class="image2-container-5-para-bold">Nemo Enim</p>
<p class="image2-container-6-para-light">likhta hu</p>
<p class="image2-container-7-para-bold">Dine Pad</p>
<p class="image2-container-8-para-light">will write</p>


</div>
</div>

            
    
        
    
    </header>
    
</body>
</html>
