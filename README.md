
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Login Page</title>
  <style>
    body{
      background-color: black;
    

    }
    .main{
      height: 500px;
      width: 400px;
      background-color: rgb(15, 15, 15);
      border: 2px solid rebeccapurple;
      filter: blur(1px);
      border-radius: 20px;
      display: flex;
      flex-direction: column;
      margin-left: 65%;
      margin-top: 60px;
      
      box-shadow: rgba(248, 246, 246, 0.35) 0px 5px 15px;
    }
    .main{
      position: relative;
      filter: blur(0px);
      padding-left: 20px;
      color: white;
      
    }
    .form input[type=email] , input[type=password]{ 
      border-top: 2px solid rgb(197, 121, 121);
      border-bottom:  2px solid rgb(197, 121, 121);
      border-left: 5px solid rgb(197, 121, 121);
     border-right:5px solid rgb(197, 121, 121) ;
      height: 50px;
      width: 90%;
      border-radius: 10px;
      background-color: rgb(34, 32, 32);
      color: white;
    }
    .form button{
      width: 92.5%;
      height: 30px;
      border: 1px solid rgb(77, 49, 49);
      border-radius: 15px;
      background-image:linear-gradient(to left,rgb(136, 38, 84),rgb(243, 44, 44)) ;
      color: white;
      transition: ease 0.5s;
     
    }
   .form button:hover{
     opacity: 0.3;
   }
   .second a{
     color: white;
   }
   .second{
    padding-left: 43%;
   }
   .headder{
    position: absolute;
    color: lightyellow;
    margin-left: 20px;
    
    
   }
   .nav ul{
     display: inline-block;
     list-style-type: none;
     margin: 0;
     padding: 0;
     width: 100%;
     
     overflow: hidden;
     background-color: rgb(139, 139, 133);
     
     
   }
   .nav li{
     float: left;
   }
   .nav  li a{
     display: block;
     padding: 10px 30px;
     text-align: center;
     color: blanchedalmond;
     text-decoration: none;

   }
   .nav li a:hover{
     background-color: crimson;
     color: blue;
   }
  </style>
</head>
<body>

<div class="nav">

<ul>
  <li><a href="#">Home</a></li>
  <li><a href="#">Product</a></li>
  <li><a href="#">Contact</a></li>
  <li style="float: right"><a href="#">About</a></li>
</ul>



</div>




  <diV class="headder">

    <h1>WELCOME to My Site!</h1>
  </diV>

  <div class="main">

   <div class="first">
     <br>
     <h1>Login In</h1>

   </div>
   <div class="form">
    
    <Label>Email:</Label><br><br>
    <input type="email" id="e1" placeholder="enter your email" required>

    <br>
    <br>
    <Label>Password:</Label><br><br>
    <input type="password" id="e1" >
  <br><br><br>
    <a><button class="login">Login</button></a>
   </div>
<div class="second">
  <p>don't have an account?<a href="#">Sign Up</a></p>
</div>

  </div>


</body>
</html>
