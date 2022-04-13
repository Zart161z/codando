<!DOCTYPE html>
<html>
<head>
<title>GAFio | Login</title>
<style>
    body{
        font-family: Arial,Helvetica
    }
    .janelaLogin{
        background-color: white;
        position: absolute;
        top: 46%;
        left: 60%;
        transform: translate(0,-50%);
        padding: 80px;
        border-radius: 15px;
        box-shadow: 2px -2px 5px 1px #9e9eff;
    }
    input{
        padding: 15px;
        border-radius: 15px;
        border-width: 0px;
        outline: none;
        background-color: rgb(189, 189, 189);
    }
    .image{
        transform: translate(8.6%,6.5%);
        width: 70.5%;
        height: 70.5%;
        border-radius: 15px;
    }
    button{
        background-color: rgb(65, 65, 134);
        border-radius: 15px;
        padding: 2px;
        width: 100%;
        border-width: 0px;
        
    }
</style>
</head>

<body>
  <div class="image">
    <img src="https://untobaccocontrol.org/kh/alternatives/wp-content/uploads/sites/9/2020/12/fiocruz_20060109_peter_ilicciev_00230-scaled.jpg" alt="image" class="image">
  </div>
  <div class="janelaLogin">
    <h1><center>LOGIN</center></h1>
    <label for="email"><b>Email</b></label><br>
    <input type="email">
    <br><br>
    <label for="password"><b>Senha</b></label><br>
    <input type="password">
    <br><br>
    <button><p style="color:white">LOGIN</p></button>
  </div>
  
</body>

</html>
