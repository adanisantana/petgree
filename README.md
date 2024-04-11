<html>
<head>
    <style>
      
.bem_vindo{color:#24938c;text-align: center; font-family: 'Lucida Sans Unicode',sans-serif; font-size: 50px;}
    
.agendamento_link,.ecommerce_link,.pedido_acompanhamento,.link_cadastro{background-color: #D7F5F4;text-align: center;
    max-width: 1800px; height: 200px;display:flexbox;margin-top: 3cm; margin-left: 5cm;margin-right: 5cm;
    font-family: Helvetica, sans-serif;font-size: 35px;border-radius: 33cm;

}

.nav_carrinho{
    margin-left:1300px; 
   }

.form-inline{margin-left: 1100px;}


.menu{margin-top: 10px; }

.ul{padding: 25px; list-style: none; position: relative; left:50px;width:1800px; height: 50px; border:1px solid #bbb ;background-color: #D7F5F4;
    margin-top: 25px; padding-bottom: 5px;}

.item{border:1px solid #bbb; display:contents; background-color: #D7F5F4;margin-right:2px;
    text-align: center; padding-left: 10px;padding-right: 10px;padding-bottom: 5px;}


input:focus{color:#000000;
background-color: #e1e1e1; width: 400px;}


.item_login:last-child,.item_carrinho:last-child{
background-color: #D7F5F4;width: 30px;
}

.menu:before,.menu:after{
content:" "; position: absolute;
transition: all 0.25s linear;
}
.menu:after{
height: 4em; background-color: #9cbec7;
bottom: -2.25em;
left: 1.5em;
transform:rotate(90deg) skew(0,45deg);
}
.menu:before{
height: 2.5em;
background-color: #9dbbb9;
top: 0.25em;
left:0.5em;
transform:skeWY(-45deg)
}
.banho_img,.transporte_img,.racao_img,.perfil_img{
border-radius: 35cm;
border:1px black;
box-shadow: 5px 5px white;
}

    </style>
      
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-
    alpha2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-
    aFq/bzH65dt+w6FI2ooMVUpc+21e0SRygnTpmBvdBgSdnuTN7QbdgL+OapgHtvPp"
    crossorigin="anonymous">

<title>Página Inicial</title>
</head>
<body>


  <!-- Menu -->
<nav class="navbar navbar-light bg-light">
    <a class="nav_login" href="login.html">
      <img src="imagens/login.svg" width="35" height="35" alt="login">
    </a>

    <a class="nav_carrinho" href="carrinho.html">
        <img src="imagens/carrinho.svg" width="35" height="35" alt="carrinho">
      </a>
        
  </nav>


    <br><br><br><br><br>
   
    <h1 class="bem_vindo"><img class="logo" src="imagens/logo.png"> Olá Dani, Bem vinda (o) a PetGree!</h1>
    
    <div class="agendamento_link" name="div1">
        <div class="imagem_dog">
            <img class="banho_img" src="imagens/cachorro.jpg" width="200px" height="200px" align="left">
        </div>
            <agendamento_pet class="texto_link" >
        
                Agende o Banho & Tosa<br> do seu pet aqui!
        
            </agendamento_pet>
        
           
    </div>
        <br><br>
