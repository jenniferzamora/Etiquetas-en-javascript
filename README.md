Etiquetas-en-javascript
=======================
<html>
<body>
<script>
document.bgColor="#F5ECCE";
document.write(" -- ETIQUETAS HTML 5 ---");

</script>

<form id="ola">

<div id="bloque"></div>

<script> 
var strVariable = "Conoce nuestra informacion academica, informate sobre la malla curricular, pensum de estudios, descripcion de la carrera, cual es el perfil de nuestros postulantes y los requisitos que necesitas para empezar a estudiar en nuestra unidad.";
document.write(strVariable.sup())

</script>
</form>
<script>
var Variable = 'FACCI';
var fieldset = document.createElement ("fieldset");
            var legend = document.createElement ("legend");
			legend.innerHTML = Variable ;
			fieldset.appendChild (legend);
			var form = document.getElementById ("ola");
            form.parentNode.insertBefore (fieldset, form);
            fieldset.appendChild (form);
			 var texto="<img src='http://www.certifacci.uleam.edu.ec/recursos/images/img_facci.png' alt='Imagen' />"+"<BR></br>";
            document.writeln(texto);
			var strariable = "ULEAM."+"<BR></br>";
			var trariable = "FACCI.";
document.write(strariable.link("http://www.facci.uleam.edu.ec/"));
document.write(trariable.link("http://www.uleam.edu.ec/"));
</script>

<header><h3>Audio</h3></header><audio controls='controls'> <source src='D:\music\Prince Royce - Darte Un Beso (iTunes) (Www.FlowHoT.NeT).mp3' type='audio/mp3' /></audio>"

</body>
</html>
