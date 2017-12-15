


<h1>DataTable</h1>

The dataTable widget is a jquery plugin with a materialize style to allow build data grid components

<h1>Configuration</h1>




<table>
<table border="1" cellpadding="15" cellspacing="0" width="75%">
       
<th width="10%"scope="col"><i><h2>Attribute</i></th></h2>
 <th width="10%"scope="col"><i><h2>Type</th></i></h2>
 <th width="10%"scope="col"><i><h2>Description</th></i></h2>

 <tr>
    
 <th>height</th>
 <th>int</th>
 <th>Altura de la tabla</th>
            
 </tr>
 
<tr>
    
 <th><a href="#headerOptions">headerOptions</th></a>
 <th>json</th>
 <th>Configura el encabezado de la tabla</th>
            
 </tr>
 
 <tr>
    
 <th>loadingIndicator</th>
 <th>boolean</th>
 <th>Muestra el indicador de la carga de datos</th>
            
 </tr>
 
 <tr>
    
 <th><a href="#selectableRows">selectableRows</th></a>
 <th>json</th>
 <th>Configura la seleccion de filas de la tabla</th>
            
 </tr>
 
 <tr>
    
 <th><a href="#actionsRows">actionsRows</th><a/>
 <th>json</th>
 <th>Configura las posibles acciones sobre cada fila de la tabla</th>
            
 </tr>
 
 <tr>
    
 <th><a href="#columnsDefinition">columnsDefinition</th></a>
 <th>json</th>
 <th>Configura las columnas de la tabla</th>
            
 </tr>
 
 <tr>
    
 <th><a href="#rowsDefinition">rowsDefinition</th></a>
 <th>json</th>
 <th>Configura las filas de la tabla</th>
            
 </tr>
 
 <tr>
    
 <th><a href="#paginationOptions">paginationOptions</th>
 <th>json</th>
 <th>Opciones de la paginacion en la tabla</th>
            
 </tr>
 
 <tr>
    
 <th><a href="#data">data</th></a>
 <th>json</th>
 <th>Fuente de datos de la tabla</th>
            
 </tr>
</table>





           
  <h2 id="headerOptions">headerOptions</h2>
    <table>
   <table border="1" cellpadding="15" cellspacing="0" width="75%">
                 

 <th width="10%"scope="col"><i><h2>Attribute</i></th></h2>
 <th width="10%"scope="col"><i><h2>Type</th></i></h2>
 <th width="10%"scope="col"><i><h2>Description</th></i></h2>
                   
<tr>
 <th>title </th>
 <th>string</th>
 <th>Muestra el titulo en el encabezado de la tabla</th>
            
 </tr>
            
 <tr>
 <th>showColumnsOption</th>
 <th>boolean</th>
 <th>Permite mostrar / ocultar las columnas de la tabla</th>
  </tr>
            
  <tr>
  <th> showSearchOption</td>
  <th>boolean</th>
  <th>En construcción </th>
  </tr>
  
  <tr>
  <th> showRemoveFiltersOption</th>
  <th>boolean</th>
  <th>Permite eliminar los filtros creados</th>
  </tr>
  
  
  </table>
  
<h2 id="selectableRows">selectableRows</h2>
<table>
<table border="1" cellpadding="15" cellspacing="0" width="75%">
       
 <th width="10%"scope="col"><i><h2>Attribute</i></th></h2>
 <th width="10%"scope="col"><i><h2>Type</th></i></h2>
 <th width="10%"scope="col"><i><h2>Description</th></i></h2>

 <tr>
 <th>show</th>
 <th>boolean</th>
 <th>Activa la opción de selección de filas </th>
 </tr>
 
 <tr>
 <th>multiSelect</th>
 <th>boolean</th>
 <th>Permite seleccionar varias filas al mismo tiempo o una por una</th>
 </tr>
 
<tr>
 <th> allowSelectableAll</th>
 <th>boolean</th>
 <th>Permite seleccionar todas las filas depende de la propiedad multiselecc</th>
 </tr>
 </table>
            

 <h2 id="actionsRows">actionsRows</h2>  
 <table>
 <table border="1" cellpadding="15" cellspacing="0" width="75%">
               
<th width="10%"scope="col"><i><h2>Attribute</i></th></h2>
 <th width="10%"scope="col"><i><h2>Type</th></i></h2>
 <th width="10%"scope="col"><i><h2>Description</th></i></h2>
 </tr>

 
 <tr>
<th>show</th>
<th>boolean</th>
<th>Muestra como funcionan las filas</th>
</tr>
            
  <tr>
<th><a href="#actions structure">actions</th></a>
<th>array[json]</th>
<th>muestra las acciones de las filas</th>
</tr>
 </table> 


 <h2 id="columnsDefinition">columnsDefinition</h2>
 <table>

  <table border="1" cellpadding="15" cellspacing="0" width="75%">
                                                               
<th width="10%"scope="col"><i><h2>Attribute</i></th></h2>
 <th width="10%"scope="col"><i><h2>Type</th></i></h2>
 <th width="10%"scope="col"><i><h2>Description</th></i></h2>
 <tr>
 <th>name</th>
 <th>string</th>
 <th>nombre de la columna</th>
 </tr>
   
 <tr>
<th>displayName</th>
 <th>string</th>
 <th>desplega el nombre</th> 
</tr> 

<tr>
 <th>format</th>
 <th>string</th>
 <th>da formato a la celda</th>
 </tr> 
 
 <tr>
 <th>show</th>
 <th>boolean</th>
 <th>muestra la columna</th>
 </tr>
 
 <tr>
 <th>columnFilter</th>
 <th><a href="https://docs.angularjs.org/guide/di">Inline Array Annotation</th></a>
 <th>filtra la columna</th>
 </tr> 
 
  <tr>
 <th>cellTemplate</th>
 <th>array</th>
 <th>celda</th>
 </tr> 
 
  </table>
 
 
 <h2 id="paginationOptions">paginationOptions</h2>  
     <table>
         
 <table border="1" cellpadding="15" cellspacing="0" width="75%">
                    
 <th width="10%"scope="col"><i><h2>Attribute</i></th></h2>
 <th width="10%"scope="col"><i><h2>Type</th></i></h2>
 <th width="10%"scope="col"><i><h2>Description</th></i></h2>
 
  <tr> 
 <th>show</th>
 <th>boolean</th>
 <th>muestra las opciones de la paginacion</th>   
 </tr>
 
<tr>  
<th>currentPage</th>
<th>int</th>
<th>pagina actual</th>    
</tr>

<tr>  
<th><a href="#itemsByPage">itemsByPage</th>
<th>json</th>
<th>articulos por pagina</th>    
</tr>   
 </table>
 
<h2 id="data">data</h2>  
<table>
                                                  
<table border="1" cellpadding="15" cellspacing="0" width="75%">
<th width="10%"scope="col"><i><h2>Attribute</i></th></h2>
 <th width="10%"scope="col"><i><h2>Type</th></i></h2>
 <th width="10%"scope="col"><i><h2>Description</th></i></h2>
                                                                   
 <tr>
<th>infoFieldName</th>
<th>string</th>
<th> el nombre del campo</th>
</tr>

<tr>   
<th>totalItemsFieldName</th>
<th>string</th>
<th>nombre del campo de elementos</th>   
</tr>           

<tr>
<th>info</th>
<th>null</th>
<th>informacion del campo</th>
</tr>



<tr>    
<th>columnFilter</th>
<th><a href="https://docs.angularjs.org/guide/di">Inline Array Annotation</th></a></th>
<th>filtra la columna</th>
</tr> 

<tr>    
<th>cellTemplate</th>
<th></th>
<th>plantilla de la celda</th>
</tr>    
             
<tr>    
<th>return self</th>
<th></th>
<th>regresa a la celda</th>
</tr> 

<tr>
<th>console.log(parameters)</th>
<th></th>
<th>consola de los parametros</th>
</tr>   
</table>

<h2 id="actions structure">actions structure</h2>
 <table>

  <table border="1" cellpadding="15" cellspacing="0" width="75%">
                                                               
<th width="10%"scope="col"><i><h2>Attribute</i></th></h2>
 <th width="10%"scope="col"><i><h2>Type</th></i></h2>
 <th width="10%"scope="col"><i><h2>Description</th></i></h2>

 <tr>
    <th>handler</th>
    <th><a href="https://docs.angularjs.org/guide/di">Inline Array Annotation</th></a>
    <th>manejador</th>
    </tr>
    </table>
    
<h2 id="itemsByPage">itemsByPage</h2>
 <table>

  <table border="1" cellpadding="15" cellspacing="0" width="75%">
                                                               
 <th width="10%"scope="col"><i><h2>Attribute</i></th></h2>
 <th width="10%"scope="col"><i><h2>Type</th></i></h2>
 <th width="10%"scope="col"><i><h2>Description</th></i></h2>


 <tr>
    <th>displayText</th>
    <th>string</th>
    <th>muestra el texto de la pagina</th>
    </tr>

 <tr>
    <th>value</th>
    <th>entirer</th>
    <th>da valor a la pagina</th>
    </tr>
<tr>
    <th>active</th>
    <th>boolean</th>
    <th>activa la pagina</th>
    </tr>
</table>

























                     
        
        
               
                        
        
        
        











     



