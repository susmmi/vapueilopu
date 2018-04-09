# vapueilopu

<!DOCTYPE html>
<html>
    
    <head>
        <meta charset="utf-8">
        <meta http-equiv="X-UA-Compatible" content="IE=edge">
         <meta name="viewport" content="width=device-width, initial-scale=1">
        <title>Vapputapahtumien tyytväisyyskysely</title>
        <meta name="description" content="An interactive getting started guide for Brackets.">
        <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">
        <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.3.1/jquery.min.js"></script>
        <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js"></script>
        <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
        <link rel="stylesheet" href="main.css">
      <link href="https://fonts.googleapis.com/css?family=Arvo" rel="stylesheet">
        

    </head>
    <body>
    
        <script>
$(document).ready(function(){
    $("#container").hide();
    $("h2").click(function(){
        $("h2").hide("slow");
        $("#container").show("slow");
    });
});
</script>
     <h2>Kyselyyn</h2>   
        <style>
            h2 {
                color: white;
                font-size: 6em;
                font-family: 'Arvo', serif;
                
            }
           
            p {
                font-size: 1.5em;
                color: black;
               text-align: center;
            }
            
               h1 {
                font-size: 3em;
                color: black;
               text-align: center;
            }
            
        body {
               background-image: url(2.jpg);
                background-repeat:no-repeat;
                background-size:cover;
                background-attachment: fixed;
            background-position: center;

            font-style:oblique;
            font-size: 15px;
            text-align: center;
            }
        
            button {
                font-size: 3em; 
            }
            
            #container {
                width: 60%;
                max-width: 1000px;
                margin: auto;
                background-color: rgba(249, 227, 253, 0.94);
            }
        </style>
        <div id="container">
        <h1>Helgan 8 päivän Vappu</h1>
        
        <p>Vapputapahtumien tyytyväisyyskysely</p>
        

            <div id="lomake">
    <form>
    Monen vuoden opiskelija olet?
    <br>
    <input type="number" id="vuosi"> <br>
    <br> 
    
    Sukupuoli:
        <br>
        <input type="radio" id="nainen"> Nainen <br>
        <input type="radio" id="mies"> Mies
        <br>
        <br>
    Kuinka moneen vapputapahtumaan olet osallistunut?
        <br>
        <br>
    Oliko tapahtumissa oheistoimintaa?
        <br>
        <input type="radio" id="kyllä"> Kyllä
    <input type="radio" id="Ei"> Ei
        <br>
        <br>
        
    Jos oli, osallistuitko?
        <br>
        
        <!-- NÄIHIN HYMYNAAMAT?? -->
        
        <input type="radio" id="kyllä"> Kyllä
        <input type="radio" id="En"> En
        
        <br>
        <br>
        
    Menitkö tapahtumiin yksin vai kavereiden kanssa?
        <br>
    <input type="text" id="kaverit">
        <br>
        <br>
    
    Mikä oli paras tapahtuma johon osallistuit?
        <br>
        <br>
        <input type="checkbox" id="eka">
        21.4 Operaatio slummijuna - Atkins ry<br>
        <input type="checkbox" id="toka">
        22.4 Kallion korkkaus - Sture ry<br>
        <input type="checkbox" id="kolmas">
        23.4 Gastroappro - Pore ry<br>
        <input type="checkbox" id="neljäs">
        24.4 Lots in Helsinki - Ids helga &amp;Esn helga<br>
        <input type="checkbox" id="viides">
        25.4 Haalarinkastajaiset - Helga&amp; Laureamko<br>
        <input type="checkbox" id="kuudes">
        26.4 Jokikadun appro - Hepo ry<br>
        <input type="checkbox" id="seiska">
        27.4 Fotoralli - Skuuppi ry<br>
        <input type="checkbox" id="kasi">
        28.4 Mushroom hunt x beer bong &#43; Waraslähtö wappuun - Talko ry <br>
        <input type="checkbox" id="ysi"> 29.4 After ski - Hsoy ry <br>
        <input type="checkbox" id="kybä">
        30.4 Runaway train - Hattara ry<br>
        <input type="checkbox" id="11">1.5 Kaivarin wappu - Helga <br>

        
        <br>
        <br>
        
    Tutustuitko uusiin ihmisiin?
        <br>
       <input type="text" id="viesti">
        <br>
        <br>
        
    Kuinka tyytyväinen olit osallistumiisi tapahtumiin?
       <br>
        <br>
        
    <!-- hymynaamat also -->
        <input type="radio" id="tylsää">
        <input type="radio" id="ihan ok">
        <input type="radio" id="en osaa sanoo">
        <input type="radio" id="kivaa">
        <input type="radio" id="tosi kivaa">
        <br>
        <br>
        
        Kehitysideoita, omin sanoin?
        <br>
        <input type="text" id="idea">
        <br>
        <br>
        <br>
        <br>
        
       <button>Lähetä</button> 
        </form>
    
        </div>
        
        </div> 
        

     
        
    </body>
</html>
