<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>faltu</title>
    <link rel="icon" href="favicon.ico">
</head>
<style>
    body{
        color: #40514e;
        background-color: #e4f9f5;
        text-align: center;
        font-family:'Merriweather',serif;
    }
    .cloud1{
        margin-left: 400px;
        padding-top: 50px;
    }
    #text h1{
        font-family: 'sacramento',cursive;
    }
    #text h4{
        font-family: 'Montserrat',sans-serif;
    }
    #cloud2{
        position: absolute;
        margin-left: 300px;
    }
    #i{
        display: flex;
    }
    .i img{
        width: 10%;
            border-radius: 20px;
            margin-top:100px;
    }
    .code{
        width: 35%;
            border-radius: 20px;
            float: left;
            margin-right: 30px;
            
        
    }
    .hob{
        width: 25%;
            border-radius: 20px;
            float: right;
            
    }
    .skill{
        width: 50%;
        margin: auto;
        text-align: left;
        line-height: 2;
        padding-top: 80px;
    }
    hr{
        border: dotted;
        border-bottom:none ;
        width: 4%;
        margin: 100px auto;
    }
    .tet{
        width: 40%;
        margin: 40px auto;
    }
    .btn {
  background: #11cdd4;
  background-image: -webkit-linear-gradient(top, #11cdd4, #1199);
  background-image: -moz-linear-gradient(top, #11cdd4, #1199);
  background-image: -ms-linear-gradient(top, #11cdd4, #1199);
  background-image: -o-linear-gradient(top, #11cdd4, #1199);
  background-image: linear-gradient(to bottom, #11cdd4, #1199);
  -webkit-border-radius: 8;
  -moz-border-radius: 8;
  border-radius: 8px;
  font-family: 'Montserrat',sans-serif;
  color: #ffffff;
  font-size: 20px;
  padding: 10px 20px 10px 20px;
  text-decoration: none;
}

.btn:hover {
  background: #30e3cb;
  background-image: -webkit-linear-gradient(top, #30e3cb, #2bc4ad);
  background-image: -moz-linear-gradient(top, #30e3cb, #2bc4ad);
  background-image: -ms-linear-gradient(top, #30e3cb, #2bc4ad);
  background-image: -o-linear-gradient(top, #30e3cb, #2bc4ad);
  background-image: linear-gradient(to bottom, #30e3cb, #2bc4ad);
  text-decoration: none;
}
.bottom{
    background-color: #11cdd4;
    padding: 50px;
    margin-top: 20px;
}
a{
    color: #11999e;
    font-family: 'Montserrat',sans-serif;
}
#link a{
    text-decoration: none;
    color: black;
    width: 50px;
}
::-webkit-scrollbar{
    width: 0;
}
#scroll{
    position: fixed;
    top: 0;
    right: 0;
    width: 10px;
    height: 100%;
    background: rgba(255, 255, 255, 0.05);
}
#bar{
    position: fixed;
    top: 0;
    right: 0;
    width: 10px;
    height: 100%;
    background: linear-gradient(to top,#008aff,#00ffe7);
    animation: animate 5s linear infinite;
}
@keyframes animate{
    0%,100%{
        filter:hue-rotate(0deg);
    }
    50%{
        filter: hue-rotate(360deg);
    }
}
#bar:before{
    content: '';
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background: linear-gradient(to top,#008aff,#00ffe7);
    filter: blur(10px);
}
#bar:before{
    content: '';
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background: linear-gradient(to top,#008aff,#00ffe7);
    filter: blur(30px);
}
.navbar{
            display: flex;
    position: sticky;
    top: 0px;
    cursor: pointer;
        }
        .nav-list{
            width: 70%; 
    display: flex;
    justify-content: left;
    align-items: center;
        }
        .nav-list li{
            list-style: none;
            padding: 26px 30px;
        }
        .nav-list li a{
            text-decoration: none;
            color: white;
        }
        .nav-list li a:hover{
            color: gray;
        }
        .rightnav{
            width: 50%;
            text-align:center;
            margin-top: 30px;
        }
        #search{
            padding: 5px;}
            .background{
            background: rgba(0, 0 , 0, 0.75) url(https://images.pexels.com/photos/302769/pexels-photo-302769.jpeg?cs=srgb&dl=pexels-pixabay-302769.jpg&fm=jpg);
        }
</style>
<body>
    <div id="bar"></div>
    <div id="scroll"></div>
   <!--<div id="link">
        <a href="port1.html">More info |</a>
    </div>-->
    <nav class="navbar background">
        <ul class="nav-list">
          <!--  <div class="logo">
                <img src="https://xamanakib.github.io/webschool/img/logo.png" alt="logo">
            </div>-->
            <li><a href="port.html">home</a></li>
            <li><a href="about.html">about</a></li>
            <li><a href="port1.html">More info |</a></li>
            <li><a href="#contact">contact us</a></li>
        </ul>
        <div class="rightnav">
            <input type="text" name="search" id="search">
            <button class="butsm">search</button>
        </div>
    </nav>
    <div class="cloud1">
    <img src="C:\Users\gaurav\Desktop\web\cloud.png" alt=""></div>
    <div id="text">
    <h1>i'm Sourav Thakur</h1>
    <h4>a web devloper</h4>
</div>
<div id="cloud2">
<img src="C:\Users\gaurav\Desktop\web\cloud.png" alt=""></div>
<img src="C:\Users\gaurav\Desktop\web\mountain.png" alt="">
<div class="i">
<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTfNnPT6X8FXmdiRFRV1BXVFOUoy6psc9ZEpQ&usqp=CAU" alt="code img"></div>
<h2>hello</h2>
<p> i'm a web devloper and i have a knowleged in java,html,css,javascript and many more</p>
<hr>
<!--<div>
    <h2>My Skill</h2>
    <div class="skill">
    <img class="code" src="https://i.pinimg.com/originals/68/a5/80/68a5805ee62de226ae2fa7dd16b52353.gif" alt="">
    <h3>design and devlopment</h3>
    <p>Lorem ipsum dolor sit, amet con, iusto quo! Neque, quas illo dolorgadyhreyuht tgreya ye4yqatgedtr5 y j orjtieirtjht teti hakih t re laboriosam fugiat et, rem dolores minus reprehenderit similique ad unde animi voluptas?</p>
</div>
</div>
<div class="skill">
    <img class="hob" src="https://i.gifer.com/6T5.gif" alt="">
    <h3>Hobbies</h3>
    <p>Is to do skating and play basketball</p>
</div>
<hr>
<div> -->
    <h2>Get In Touch</h2>
    <h3> If you love it</h3>
    <p class="tet">Lorem ipsum dolor sit amet consectetur adipisicing elit. Fugit cumque ullam qui ducimus nobis explicabo officia provident ratione, voluptate nihil, laboriosam ipsa harum. Eius labore non unde porro, tenetur magni?</p>
    <a class="btn" id="contact"  href="mailto:thakursaurav2017@gmail.com">contact me</a>
</div>
<div class="bottom">
    <a href="">instagram</a>
    <a href="">facebook</a>
    <a href="">twetter</a>
    <p> © Copyright. 2022. XYZ. All Rights Reservered.</p>
</div>
<script>
    let progress=document.getElementById('bar');
    let totalHeight=document.body.scrollHeight-window.innerHeight;
    window.onscroll=function(){
        let progressHeight=(window.pageYOffset/totalHeight)*100;
        progress.style.height= progressHeight+"%";
    }
</script>
</body>
</html>
