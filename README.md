<svg fill="none" viewBox="0 0 800 400" width="800" height="400" xmlns="http://www.w3.org/2000/svg">
  <foreignObject width="100%" height="100%">
    <div xmlns="http://www.w3.org/1999/xhtml">

      <style>
        /* your CSS */
       @import url("https://fonts.googleapis.com/css2?family=Poppins:wght@400;500;600;700&display=swap");


*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family: 'Poppins', sans-serif;
}

a {
    text-decoration: none;
}

.hero{
    width:100%;
    height:100vh;
    background-color: #1a0e2d;
}
nav{
    display:flex;
    align-items:center;
    justify-content:space-between;
    padding:30px 100px;


}

nav ul li{
    list-style: none;
    display:inline-block;
    padding: 10px 20px;
}

nav ul li a{
    color:#fff;
    position: relative;
    padding: 5px 0;

}

nav ul li a:hover{
    color:#fff;
}

nav ul li a:after{
    content: "";
    position: absolute;
    left: 0;
    bottom: 0;
    width: 0;
    height: 3px;
    background: #fff;
    transition: 0.5s;

}

nav ul li a:hover:after{
    width: 100%;
}

.btn{
    color: #fff;
    font: size 16px;
    text-transform: uppercase;
    letter-spacing: 2px;
    padding:16px 40px;
    border-radius: 500px;
    display: inline-block;
    font-weight: 500;
    transition:all 0.4s ease-in-out;
    background-size:152% 100%;
    box-shadow: 0 10px 30px rgba(0,0,0,0.1);
    border:2px solid #fff;


}

.btn:hover{
    background:transparent;
    border-color: #fd4766;
    color: #fd4766;
}

.content{
    position: absolute;
    top:35%;
    left:8%;

}
.content .title{
    color: #fff;
    font-size:25px;
    text-transform: uppercase;
    letter-spacing: 4px;
    display: inline-block;
    margin-bottom: 20px;
    background: linear-gradient(120deg, #1c99fe 20.69%, #7644ff 50.19%, #fd4766 79.69%); 
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
}

.content h1{
    color: #fff;
    font-size: 60px;
    font-weight: 700;
    line-height:90px;
    margin-bottom:inherit;
    width: 70%;
}

.content p{
    color: #fff;
    font-size: 20px;
    font-weight: 300;
    line-height: 30px;
    margin-bottom: 30px;
    width: 70%;
}


 

@media(min-width: 320px) and (max-width: 1024px){
    nav{
        padding: 30px 50px;
    }
    .content{
        left:5%;
    }
    .content h1{
        font-size: 40px;
        line-height: 50px;
        width: 100%;
    }
    .content p{
        font-size: 16px;
        line-height: 25px;
        width: 100%;
    }
}
      </style>

      <!DOCTYPE html>
<html lang="en">
 

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.10.2/css/all.min.css"/>
</head>
<body>
    <div class="hero">
        <nav>
            <ul class="nav-links">
                <li><a href="#">Home</a></li>
                <li><a href="#">About</a></li>
                <li><a href="#">Projects</a></li>
                <li><a href="#">Contact</a></li>
            </ul>
            <a href="#" class="btn">Resume</a>
        </nav>
        <div class="content">
            <span class="title">Data Scientist</span>
            <h1>Hi, I'm <span class="name">Akaash</span></h1>
            <p>I'm a data scientist with a passion for solving problems and building products.</p>
            <a href="#" class="btn">Download CV</a>
        </div>
    </div>
    </div>
      
</body>
</html>


    </div>
  </foreignObject>
</svg>
