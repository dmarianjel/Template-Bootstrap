Primero creamos 3 archivos ccs: media, main, grid.
En media colocaremos imagenes y tabajaremos con @media
en grid colocaremos los estilos col y row
En main personalizaremos estilos (estilos que vamos generando)
En html debo colocar meta view <meta name="viewport" content="width=device-width, user-scalable=no, initial-scale=1.0, maximum-scale=1.0, minimum-scale=1.0">
	<meta http-equiv="X-UA-Compatible" content="IE=edge"><!--para qeue sea compatible con todos los navegadores-->
	<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css" integrity="sha384-BVYiiSIFeK1dGmJRAkycuHAHRg32OmUcww7on3RYdg4Va+PmSTsz/K68vbdEjh4u" crossorigin="anonymous">
	<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.2.1/jquery.min.js"></script>
  	<script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js" integrity="sha384-Tc5IQib027qvyjSMfHjOMaLkfuWVxZxUPnCJA7l2mCWNIpG9mGCD8wGNIcPD7Txa" crossorigin="anonymous"></script>
  	<script type="text/javascript" src=script.js></script>
font: font-family: 'Roboto', sans-serif;
tonos: /* #fb8d6f color fondo, head,etc
#a7e093 background about panda y atributes
*/
Usaré grid se 12 (n/12)* 100
Para cada sección realizo un div container para dar estilos como border, padding, background, etc.
Luego genero un div row que contendra la o las col necesarias para disponer los elementos.