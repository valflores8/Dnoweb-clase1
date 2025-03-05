<!DOCTYPE html>
<html>
    <head>
        <meta charset="utf-8" />
        <meta name="viewport" content="width=device-width, initial-scale=1" />
        <title>Clase 1</title>
        <!-- Usando CSS Grid Generator - https://cssgridgenerator.io/ -->
        <style>

        	body{background-color: lightyellow;}

        	header{
        		font-family: Cooper;
        		text-align: center;
        	}
        	main{
        		font-family: Helvetica ;
        		text-align: center;
        	}
            .parent {
                display: grid;
                grid-template-columns: repeat(2, 1fr);
                grid-template-rows: repeat(1, 1fr);
                gap: 8 px;
            }

            footer {
            	padding-top: 15vh;
            	font-family: cooper;
            }

        </style>
    </head>
    <body>
        <header> <h1>Gráficas comparativas</h1> </header>
        <main> 
			<div class="parent">
   			<div class="div1"> 
   				<svg width="100%" height="100%" viewBox="0 0 42 42" class="donut">
  <circle class="donut-hole" cx="21" cy="21" r="15.91549430918954" fill="lightyellow"></circle>
  <circle class="donut-ring" cx="21" cy="21" r="15.91549430918954" fill="transparent" stroke="#c9becf" stroke-width="3"></circle>
  <circle class="donut-segment" cx="21" cy="21" r="15.91549430918954" fill="transparent" stroke="#8411b5" stroke-width="3" stroke-dasharray="10 90" stroke-dashoffset="0"></circle>
</svg>
   				Prorcentaje de Acuerdos de Unión civil entre el mismo sexo (INE, diciembre 2024)

   			</div>
    		<div class="div2">
   				<svg width="100%" height="100%" viewBox="0 0 42 42" class="donut">
  <circle class="donut-hole" cx="21" cy="21" r="15.91549430918954" fill="lightyellow"></circle>
  <circle class="donut-ring" cx="21" cy="21" r="15.91549430918954" fill="transparent" stroke="#c9becf" stroke-width="3"></circle>
  <circle class="donut-segment" cx="21" cy="21" r="15.91549430918954" fill="transparent" stroke="#8411b5" stroke-width="3" stroke-dasharray="48 52" stroke-dashoffset="0"></circle>
</svg>
   				Porcentaje de Acuerdos de Unión civil del mismo sexo con residencia en la región Metropolitana (INE, diciembre 2024)
   				 
   			</div>
    		<div class="div3">
   				<svg width="100%" height="100%" viewBox="0 0 42 42" class="donut">
  <circle class="donut-hole" cx="21" cy="21" r="15.91549430918954" fill="lightyellow"></circle>
  <circle class="donut-ring" cx="21" cy="21" r="15.91549430918954" fill="transparent" stroke="#c9becf" stroke-width="3"></circle>
  <circle class="donut-segment" cx="21" cy="21" r="15.91549430918954" fill="transparent" stroke="#8411b5" stroke-width="3" stroke-dasharray="91 9" stroke-dashoffset="0"></circle>
</svg>
   				Porcentajes de nacimientos de madres entre los 10 y 39 años (INE, diciembre 2024)
   				 
   			</div>
    		<div class="div4">
   				<svg width="100%" height="100%" viewBox="0 0 42 42" class="donut">
  <circle class="donut-hole" cx="21" cy="21" r="15.91549430918954" fill="lightyellow"></circle>
  <circle class="donut-ring" cx="21" cy="21" r="15.91549430918954" fill="transparent" stroke="#c9becf" stroke-width="3"></circle>
  <circle class="donut-segment" cx="21" cy="21" r="15.91549430918954" fill="transparent" stroke="#8411b5" stroke-width="3" stroke-dasharray="40 60" stroke-dashoffset="0"></circle>
</svg>
   				Porcentaje de nacimientos en la región metropolitana (INE, diciembre 2024)
   			
   			</div>
		</div>
     	</main>
     	<footer> Valentina Flores Clase 1
     		</footer>
    </body>
</html>
