


<h1>DataTable</h1>

The dataTable widget is a jquery plugin with a materialize style to allow build data grid components

<h1>Configuration</h1>

<table>
<table border="1" cellpadding="15" cellspacing="0" width="75%">
       
<th width="10%"scope="col"><i>Attribute</i></th>
 <th width="10%"scope="col"><i>Type</th></i>
 <th width="10%"scope="col"><i>Description</th></i>

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
                 

<th width="10%"scope="col"><i>Attribute</i></th>
 <th width="10%"scope="col"><i>Type</th></i>
 <th width="10%"scope="col"><i>Description</th></i>
                   
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
       
<th width="10%"scope="col"><i>Attribute</i></th>
 <th width="10%"scope="col"><i>Type</th></i>
 <th width="10%"scope="col"><i>Description</th></i>

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
               
<th width="10%"scope="col"><i>Attribute</i></th>
 <th width="10%"scope="col"><i>Type</th></i>
 <th width="10%"scope="col"><i>Description</th></i>
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
                                                               
<th width="10%"scope="col"><i>Attribute</i></th>
 <th width="10%"scope="col"><i>Type</th></i>
 <th width="10%"scope="col"><i>Description</th></i>
 
 <tr>
 <th>name</th>
 <th>string</th>
 <th>Nombre de la columna</th>
 </tr>
   
 <tr>
<th>displayName</th>
 <th>string</th>
 <th>Texto a desplegar en la columna</th> 
</tr> 

<tr>
 <th>format</th>
 <th>string</th>
 <th>Formato de la columna</th>
 </tr> 
 
 <tr>
 <th>show</th>
 <th>boolean</th>
 <th>Mostrar / ocultar la columna</th>
 </tr>
 
 <tr>
 <th>columnFilter</th>
 <th><a href="https://docs.angularjs.org/guide/di">Inline Array Annotation</th></a>
 <th>Habilitar filtrado por columna</th>
 </tr> 
 
  <tr>
 <th>cellTemplate</th>
 <th>array</th>
 <th>Plantilla para mostrar los valores de la columna</th>
 </tr> 
 
  </table>
 
 
 <h2 id="paginationOptions">paginationOptions</h2>  
     <table>
         
 <table border="1" cellpadding="15" cellspacing="0" width="75%">
                    
<th width="10%"scope="col"><i>Attribute</i></th>
 <th width="10%"scope="col"><i>Type</th></i>
 <th width="10%"scope="col"><i>Description</th></i>
 
  <tr> 
 <th>show</th>
 <th>boolean</th>
 <th>Permite usar paginación en la tabla </th>   
 </tr>
 
<tr>  
<th>currentPage</th>
<th>int</th>
<th>Pagina actual</th>    
</tr>

<tr>  
<th><a href="#itemsByPage">itemsByPage</th>
<th>json</th>
<th>Registros por pagina</th>    
</tr>   
 </table>
 
 <h2 id="itemsByPage">itemsByPage</h2>
 <table>

  <table border="1" cellpadding="15" cellspacing="0" width="75%">
                                                               
<th width="10%"scope="col"><i>Attribute</i></th>
 <th width="10%"scope="col"><i>Type</th></i>
 <th width="10%"scope="col"><i>Description</th></i>


 <tr>
    <th>displayText</th>
    <th>string</th>
    <th>Etiqueta para el valor de elementos por pagina</th>
    </tr>

 <tr>
    <th>value</th>
    <th>int</th>
    <th>Número de elementos por pagina</th>
    </tr>
<tr>
    <th>active</th>
    <th>boolean</th>
    <th>Pagina activa</th>
    </tr>
</table>

 
<h2 id="data">data</h2>  
<table>
                                                  
<table border="1" cellpadding="15" cellspacing="0" width="75%">
<th width="10%"scope="col"><i>Attribute</i></th>
 <th width="10%"scope="col"><i>Type</th></i>
 <th width="10%"scope="col"><i>Description</th></i>
                                                                   
 <tr>
<th></th>
<th></th>
<th> </th>
</tr>

 <tr>
<th></th>
<th></th>
<th> </th>
</tr>        

 <tr>
<th></th>
<th></th>
<th> </th>
</tr>


 <tr>
<th></th>
<th></th>
<th> </th>
</tr>

 <tr>
<th></th>
<th></th>
<th> </th>
</tr>  
             
 <tr>
<th></th>
<th></th>
<th> </th>
</tr>

 <tr>
<th></th>
<th></th>
<th> </th>
</tr>
</table>

<h2 id="actions structure">actions structure</h2>
 <table>

  <table border="1" cellpadding="15" cellspacing="0" width="75%">
                                                               
<th width="10%"scope="col"><i>Attribute</i></th>
 <th width="10%"scope="col"><i>Type</th></i>
 <th width="10%"scope="col"><i>Description</th></i>

 <tr>
    <th>handler</th>
    <th><a href="https://docs.angularjs.org/guide/di">Inline Array Annotation</th></a>
    <th>manejador</th>
    </tr>
    </table>
    

<h2 id="rowsDefinition">rowsDefinition</h2>

<table>
<table border="1" cellpadding="15" cellspacing="0" width="75%">
       
<th width="10%"scope="col"><i>Attribute</i></th>
 <th width="10%"scope="col"><i>Type</th></i>
 <th width="10%"scope="col"><i>Description</th></i>

 <tr>
    
 <th>stripedTable</th>
 <th>boolean</th>
 <th>permite estilo a rayas de la tabla</th>
            
 </tr>























                     
        
        
               
                        
        
        
        











     



