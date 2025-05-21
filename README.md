# Codigo-fuente
Codigo fuente
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    
    <style>
    *{
        margin:0;
        padding: 0;
        box-sizing: border-box;
    
    }
    header{
        background-color:rgb(60, 189, 146) ;
        color: white;
        padding: 10px 20px;
        position: relative;
    
    }
    
    nav {
        display: flex;
        justify-content: space-around;
        align-items: center;
    
    }
    
    h1{
        font-size: 40px;
        font-weight: bold;
    }
    
    h3{
        font-size: 40px;
        font-weight: bold;
        color: black;
    }
    .nav-links {
       list-style: none; 
       display: flex;
       gap: 15px;
    }
    
    .nav-links a{
        text-decoration: none;
        color: white;
        font-size: 18px;
    }
    
    .hamburguesa {
        display: none;
        flex-direction: column;
        cursor: pointer;
    }
    
    .bar {
        width: 25px;
        height: 3px;
        background-color: white;
        margin: 4px 0;
        transition: 0.3s;
    
    }
    
    @media (max-width:768px){
        nav{
            justify-content: space-between;
        }
        .nav-links{
            display: none;
            position: absolute;
            top: 100%;
            right: 0;
            background-color: black;
            width: 100%;
            flex-direction: column;
            text-align: center;
        }
        .nav-links li{
            margin: 15px;
        }
        .hamburguesa{
            display: flex;
        }
        .nav-links.show {
            display: flex;
            background-color: rgb(60, 189, 146);
        }
    }
    </style>
</head>
<body>
   <header>
    <nav>
        <h1>Producto integrador</h1>
        <ul class="nav-links" id="nav-links">
        <li><a href="https://docs.google.com/document/d/1JK54thYggYc-9kBznNmOh_D4C6tZ9-SxySJw4tqbK94/edit?usp=sharing">Actividades realizadas en el curso </a></li>
        <li><a href="#">Sistema implementado </a></li>
        <li><a href="#">Código fuente</a></li>
        <li><a href="#">Reporte de las modificaciones realizadas </a></li>
    </ul>

    <div class="hamburguesa" id="hamburguesa">
        <span class="bar"></span>
        <span class="bar"></span>
        <span class="bar"></span>
    </div>
</nav>

   </header>
    
  <h3>Github</h3> 
  <p>Se interga los codigos de github donde se ha realizado cada uno de los trabajos, tanto individuales como en equipo: Sprint, el corazón de SCRUM: https://github.com/AnaAlejandri/sprint.git  . Actividad integradora. Sprint, el corazón de SCRUM: https://github.com/AnaAlejandri/sprint.git . Trabajo en equipo, retomando mi primer sprint : https://github.com/AnaAlejandri/Backlogs.git .   Ultimo trabajo en equipo, Reunión para revisión de modificaciones https://github.com/AnaAlejandri/Reunion-Inicial</p>
</body>
</html>
