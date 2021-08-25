# Tarea-HTML-Santiago-Bernardi
Trabajo HTML/CSS.
//html
<!DOCTYPE html>
<html>
    <head> 
        <link rel="stylesheet" href="styles.css">
        <title>Tarea HTML de Santaigo Bernardi</title>
        
    </head>
    <body>
        <div class="divClass">
            <h1>Santiago Bernardi</h1>
            <h3>Henry</h3>
            <h4>Tarea HTML / CSS</h4>
        </div>
        
        <div class="divClass">
            <span id="spanId">Mi comida favorita son los fideos con tuco :</span>
            <a href="https://www.tripadvisor.com/Restaurant_Review-g1064242-d17519695-Reviews-Ristorante_Italiano-Novelda_Province_of_Alicante_Valencian_Country.html">Mi restaurante favorito</a>
        </div >
        
        <div id="thirdDiv" class="divClass">
            <ul>
                <li><img src="https://external-preview.redd.it/YEJN6AA6NVXfStwIfNH2C-3fd8JAoeHjPjtAP-ByCOs.jpg?auto=webp&s=5b16c39f9b854b292366371c8284cd1d89cb23de"></li>
                <li><img src ="https://i.pinimg.com/736x/ee/81/69/ee8169cf1fd615145b3cb72a034b62ea.jpg"></li>
            </ul>
        </div>
    </body>
</html>

//css

h1{
    color: red;
}

img{
    width: 400px;
}
.thirdDiv{
    height: 600px;
    width: 500px; 
    background: black solid;
    padding : 50px;
    border : 12px solid red;
}
.spanId{
    font-size: 18px;
}
