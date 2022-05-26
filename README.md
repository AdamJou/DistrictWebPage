<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
  
    <link rel="stylesheet" href="css/main.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta2/css/all.min.css" integrity="sha512-YWzhKL2whUzgiheMoBFwW8CKV4qpHQAEuvilg9FAn5VJUDwKZZxkJNuGM4XkWuk94WCrrwslk8yWNGmY1EduTA==" crossorigin="anonymous" referrerpolicy="no-referrer" />

    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Powiat Opoczyński</title>
</head>
<body>
    <section class="header">
      <nav>
          
            <a  class="logo-text" href="index.html"><img  src="img/logo.png"><span>Powiat </span> Opoczyński</a>
           
            <div class="nav-links" id="navLinks">
                <i class="fa-solid fa-xmark" onclick="hideMenu()"></i>
                <ul>
                    <li><a id="menu-1" href="#">HOME</a></li>
                    <li><a href="#">GMINY</a></li>
                    <li><a href="#">TURYSTYKA</a></li>
                    <li><a href="#">SZLAKI</a></li>
                    <li><a href="#">GALERIA</a></li>

                </ul>
            </div>
            <i class="fa-solid fa-bars" onclick="showMenu()"></i>

      </nav>

      
      <div class="text-box">

  

       
        <h1>Eksploruj świat natury!</h1>
        <p>Poznaj nas</p>
        <svg class="down-arrow" viewBox="0 0 16 132" fill="none" xmlns="http://www.w3.org/2000/svg">
            <path d="M7.29289 131.707C7.68341 132.098 8.31658 132.098 8.7071 131.707L15.0711 125.343C15.4616 124.953 15.4616 124.319 15.0711 123.929C14.6805 123.538 14.0474 123.538 13.6568 123.929L7.99999 129.586L2.34314 123.929C1.95262 123.538 1.31945 123.538 0.928927 123.929C0.538402 124.319 0.538402 124.953 0.928927 125.343L7.29289 131.707ZM7 -4.37114e-08L6.99999 131L8.99999 131L9 4.37114e-08L7 -4.37114e-08Z" fill="black"/>
        </svg>
   
      </div>

    </section>



    <section class="more-info">

        <h2>O nas</h2>
        <p id="about">
           
            Powiat Opoczyński leży na Wyżynie Kielecko - Sandomierskiej, obejmując obszar Wzgórz Opoczyńskich. Zajmuje teren 1039 km2 i liczy około 80 tys. mieszkańców.
            
            W skład powiatu wchodzą dwa miasta: Opoczno i Drzewica oraz sześć gmin wiejskich - Białaczów, Mniszków, Paradyż, Poświętne, Sławno i Żarnów. Niepowtarzalne walory przyrodnicze sprawiają, że opoczyńskie zaliczane jest do najciekawszych pod względem krajobrazowym i przyrodniczym rejonów Polski. Liczne wapienne i piaskowcowe pagórki, przepiękne doliny rzek i urocze ustronia leśne - to charakterystyczne elementy opoczyńskiego krajobrazu. Niezapomniane wrażenie pozostawiają malownicze kamieniołomy, hałdy powyrobiskowe, jary i wąwozy stanowiące świadectwo wielowiekowego pozyskiwania różnych kopalin - rud żelaza, piaskowców i glin ceramicznych. Rozległe obszary leśne, zbiorniki wodne i rzeki tworzą swoisty mikroklimat i doskonałe warunki do wypoczynku.</p>



        <div class="row">

            <div class="column">
                
                <h3>Lasy</h3>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Impedit vel porro commodi atque error, soluta obcaecati saepe possimus ad. Consequuntur cum quibusdam culpa a eius quaerat totam in modi facilis.</p>
                <img src="img/las.jpg">
            </div>
            <div class="column">
                <h3>Energetyka</h3>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Impedit vel porro commodi atque error, soluta obcaecati saepe possimus ad. Consequuntur cum quibusdam culpa a eius quaerat totam in modi facilis.</p>
                <img src="img/wiatrak.jpg">
            </div>
            <div class="column">
                <h3>Zbiorniki wodne</h3>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Impedit vel porro commodi atque error, soluta obcaecati saepe possimus ad. Consequuntur cum quibusdam culpa a eius quaerat totam in modi facilis.</p>
                <img src="img/staw.jpg">
            </div>

        </div>



    </section>


<footer>

<p>Adam Michoń • 2022 • <i class="fa-brands fa-github" id="git" ></i> </p>


</footer>






<script>


    var navLinks = document.getElementById("navLinks");
    function showMenu(){
        navLinks.style.right="0";
    
     
        
    

      
    }
    function hideMenu(){
        navLinks.style.right="-200px";
    
    
    }

    document.getElementById("git").onclick = function() {

        window.location.href="https://github.com/AdamJou";
      
    };




</script>

    
</body>
</html>
