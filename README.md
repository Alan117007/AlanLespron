<!DOCTYPE html>
<html>
<head>
<style>



/* Change background color of buttons on hover */
div.tab button:hover {
    background-color: #ddd;
}

/* Create an active/current tablink class */
div.tab button.active {
    background-color: #ccc;
}

/* Style the tab content */
.tabcontent {
    display: none;
    padding: 6px 12px;
    border: 1px solid #ccc;
    border-top: none;
}
</style>
</head>
<body>

<p>ALAN LESPRON</p>

<div class="tab">
  <button class="tablinks" onclick="openCity(event, 'Informacion personal')">Informacion personal</button>
  <button class="tablinks" onclick="openCity(event, 'Information academica ')">Information academica </button>
  <button class="tablinks" onclick="openCity(event, 'Blog')">Blog</button>
</div>

<div id="Informacion personal" class="tabcontent">
  <h3>Informacion personal</h3>
  <p>Datos generale: Nací en Cd.Juarez Chihuahua
  	<p>https://github.com/Alan117007
	<p>alan6lespron@gmail.com
	<p>Actualmente estudio en el Tecnológico de Monterrey
	<p>Pasatiempos:Mis pasatiempos favoritos son los videojuegos y los deportes.
	<p>Plan de vida personal: Mi plan es trabajar en alguna de las grandes empresas como Google o Microsoft y 	después de tener un poco de experiencia trabajar por mi cuenta.</p>
</div>

<div id="Information academica " class="tabcontent">
  <h3>Information academica </h3>
  <p>Actualmente estoy estudiando la carrera de ITC(Ingeniero En Tecnologías computacionales) que se enfoca en el diseño y desarrollo de software. Voy en primer semestre de esta carrera.
Planeo irme de intercambio un año a donde se me dé la oportunidad aun no lo tengo bien definido. 
Como es mi primer semestre  no he realizado ningún proyecto que tenga relevancia. </p> 
</div>

<div id="Blog" class="tabcontent">
  <h3>Blog</h3>
  <p></p>
</div>

<script>
function openCity(evt, cityName) {
    var i, tabcontent, tablinks;
    tabcontent = document.getElementsByClassName("tabcontent");
    for (i = 0; i < tabcontent.length; i++) {
        tabcontent[i].style.display = "none";
    }
    tablinks = document.getElementsByClassName("tablinks");
    for (i = 0; i < tablinks.length; i++) {
        tablinks[i].className = tablinks[i].className.replace(" active", "");
    }
    document.getElementById(cityName).style.display = "block";
    evt.currentTarget.className += " active";
}
</script>
     
</body>
</html> 
     
</body>
</html> 
