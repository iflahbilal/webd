<!DOCTYPE html>
<html lang="en">
<head>
    

    
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title> Iflah Bilal</title>

    
    <link rel="stylesheet" href="styleassesment.css">
    
</head>
<body>
    
       <img class=" top-cloud "src="C:\Users\hp\OneDrive\web development\HTML- Personal site\CSS\CSS - Bacon Fansite\css-mysite\css\CSS - My Site Images\cloud.png" alt="cloud-img">
        <h1 class="name"> Iflah Bilal</h1>
        <p> I am a<span class="pro"> pro</span> grammer </p>
        <p> hello <span class ="world"> world  </span> how are you  </p>
        
        <img class=" bottom-cloud" src="C:\Users\hp\OneDrive\web development\HTML- Personal site\CSS\CSS - Bacon Fansite\css-mysite\css\CSS - My Site Images\mountain.png" alt="mountain-img">
        <img src="C:\Users\hp\OneDrive\web development\HTML- Personal site\CSS\CSS - Bacon Fansite\css-mysite\css\CSS - My Site Images\mountain.png"> 
        </div>
        <div class="middle-container">
            <div class="profile">
              <img src="C:\Users\hp\OneDrive\web development\HTML- Personal site\CSS\CSS - Bacon Fansite\css-mysite\css\CSS - My Site Images\angela.png" alt="me">
              <h2>Hello.</h2>
              <p class="intro">Hey ! i am Iflah Bilal . I am pursuing MCA from Jamia Millia Islamia .</p>
            <hr>
            </div>
            
            <div class="skillsof">
              <h2>My Skills.</h2>
              <div class="skill-row">
                <h3>Programming</h3>
                <img class="skills" src="C:\Users\hp\OneDrive\web development\HTML- Personal site\CSS\CSS - Bacon Fansite\css-mysite\css\CSS - My Site Images\computer.png" alt="skils">
                <p>I am  a learner and i am at beginner level of c++ and python . i am learning webd feom UDEMY it is a nice course  </p>
               
                <h3>Cooking </h3>
                <img class="cooking" src="C:\Users\hp\OneDrive\web development\HTML- Personal site\CSS\CSS - Bacon Fansite\css-mysite\css\CSS - My Site Images\chillies.png">
                <p class="text"> i love cooking in free time. i make delcious sandwiches and  chowmin . i also love dancing which makes me happy and lively </p>
              </div>
            </div>
              <hr>
               <h2> Get In touch </h2>
                <div class="contact-me">
                  <a class="btn " href="mailto:iflahbilal2508@gmail.com">CONTACT ME</a>
                </div>
              </hr>
            </div>
          </div>
          
          
          <div class="bottom-container">
            <a class="footer-link" href="https://www.linkedin.com/">LinkedIn</a>
            <a class="footer-link" href="https://twitter.com/">Twitter</a>
            <a class="footer-link" href="https://www.appbrewery.co/">Website</a>
            <p>©Iflah Bilal</p>
          </div>
          
        

</body>
</html>


body{
    margin: 0;
    color:darkgray;
    text-align: center;
    font-weight: normal;
}
.top-cloud{
    position: relative;
    left:300px;
    top: 50px;
}
.skillsof{
    text-align: center;
    width: 50%;
    margin: auto 100px auto 100px;
}
h1{
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    font-size: 400%;
     background-color: deeppink;
     color: deeppink;
     line-height: 30px;
}
h2{
    font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
    color: rgba(0, 72, 148, 0.847);
    text-align: center;
    padding: 10px; ;
}
h3{
    text-decoration: solid;
    text-align: center;
    margin: 50px;
}

.skills{
    width: 25%;
    margin: auto 100px 50px 100px;
    float: left;
}
.text{
    margin: 100px;
}

.cooking{
    width: 25%;
    margin: auto 100px auto 100px;
    float: right ;
}
.name{
    margin-top: 0px;
    background-color: aqua;
    display: block;
    font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
}
hr{
    border: dotted gray 6px ;
    border-bottom: none;
    width: 3%;
    margin: auto 200px auto 200px;
}
.bottom-cloud{
    position:absolute;
    

}
.mount{
    position:absolute ;
    left: 100px;
    display: block;
    
}
p{
    line-height: 2;
}
.intro{
    width:30%;
    margin: auto;
}
.top{
    background-color: aqua;
   position: 
    
}
.middle-container{
    margin: 100px;
   
}
.btn {
    background: #a4db2e;
    background-image: -webkit-linear-gradient(top, #a4db2e, #a8b82b);
    background-image: -moz-linear-gradient(top, #a4db2e, #a8b82b);
    background-image: -ms-linear-gradient(top, #a4db2e, #a8b82b);
    background-image: -o-linear-gradient(top, #a4db2e, #a8b82b);
    background-image: linear-gradient(to bottom, #a4db2e, #a8b82b);
    -webkit-border-radius: 10;
    -moz-border-radius: 10;
    border-radius: 10px;
    font-family: Georgia;
    color: #420505;
    font-size: 27px;
    padding: 7px 20px 10px 20px;
    text-decoration: none;
  }
  
  .btn:hover {
    background: #3cb0fd;
    background-image: -webkit-linear-gradient(top, #3cb0fd, #3498db);
    background-image: -moz-linear-gradient(top, #3cb0fd, #3498db);
    background-image: -ms-linear-gradient(top, #3cb0fd, #3498db);
    background-image: -o-linear-gradient(top, #3cb0fd, #3498db);
    background-image: linear-gradient(to bottom, #3cb0fd, #3498db);
    text-decoration: none;
  }
.contact-me{
    width: 40%;
    margin: 40px auto 40px auto;
}
.skill-row{
      font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
   
}
.span{
    background-color:darkkhaki ;
    
}
.pro{
  text-decoration: underline;
  background-color: palevioletred;

}
.container{
    background-color: rgba(224, 16, 154, 0.307);
}
a{
    color: rgb(173, 74, 125);
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
margin: 20px 0px 20px;
}
a:hover{
    color: palevioletred;
}
.bottom-container{
    background-color: pink;
    padding: 50px 0px 60px 20px;
}



