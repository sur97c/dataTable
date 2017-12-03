

<h3>Configuration</h3>

The dataTable widget is a jquery plugin with a materialize style to allow build data grid components


<table>
<table border="1" cellpadding="15" cellspacing="0" width="75%">
       
 <th width="10%"scope="col">Attribute</th>
 <th width="10%"scope="col">Type</th>
 <th width="10%"scope="col">Description</th>

 <tr>
    
 <th>height</th>
 <th>entire</th>
 <th>altura de la tabla</th>
            
 </tr>
 
<tr>
    
 <th><a href="#heightOptions">headerOptions</a></th>
 <th>json</th>
 <th>configura el encabezado de la tabla</th>
            
 </tr>
 
 <tr>
    
 <th>loadingIndicator</th>
 <th>bolean</th>
 <th></th>
            
 </tr>
 
 <tr>
    
 <th><a href="#selectableRows">selectableRows</th></a>
 <th>json</th>
 <th></th>
            
 </tr>
 
 <tr>
    
 <th>actionsRows</th>
 <th>json</th>
 <th></th>
            
 </tr>
 
 <tr>
    
 <th>columnsDefinition</th>
 <th>json</th>
 <th></th>
            
 </tr>
 
 <tr>
    
 <th>rowsDefinition</th>
 <th>json</th>
 <th></th>
            
 </tr>
 
 <tr>
    
 <th>paginationOptions</th>
 <th>json</th>
 <th></th>
            
 </tr>
 
 <tr>
    
 <th>data</th>
 <th>json</th>
 <th></th>
            
 </tr>
</table>


<h1>DataTable</h1>


<ul>
        <li><a href="#height">height</li></a>
        <li><a href="#headerOptions">headerOptions</li></a> 
        <li><a href="#loadingIndicator">loadingIndicator</li></a>
        <li><a href="#selectableRows">selectableRows</li></a>
        <li><a href="#actionsRows">actionsRows</li></a>
        <li><a href="#columnsDefinition">columnsDefinition</li></a>
        <li><a href="#rowsDefinition">rowsDefinition</li></a>
        <li><a href="#paginationOptions">paginationOptions</li></a>
        <li><a href="#data">data</li></a>
         <ul>
           
  <h2 id="headerOptions">headerOptions</h2>
    <table>
   <table border="1" cellpadding="15" cellspacing="0" width="75%">
                 

 <th width="10%"scope="col">Attribute</th>
 <th width="10%"scope="col">Type</th>
 <th width="10%"scope="col">Description</th>
                   
<tr>
 <th>title </th>
 <th>boolean</th>
 <th>Muestra el titulo en el encabezado de la tabla  "Error en parámetro 'tipo Bandeja'"</th>
            
 </tr>
            
 <tr>
 <th>showColumnsOption</th>
 <th>boolean</th>
 <th>configura las columnas</th>
  </tr>
            
  <tr>
  <th> showSearchOption: false,  </td>
  <th>boolean</th>
  <th></th>
  </tr>
  
  <tr>
  <th> showRemoveFiltersOption: false,  </th>
  <th>boolean</th>
  <th></th>
  </tr>
  
  <tr>
  <th> headerOptions.title </th>
  <th></th>
  <th></th>
  </tr>
  
  </table>
  
<h2 id="selectableRows">selectableRows</h2>
<table>
<table border="1" cellpadding="15" cellspacing="0" width="75%">
       
 <th width="10%"scope="col">Attribute</th>
 <th width="10%"scope="col">Type</th>
 <th width="10%"scope="col">Description</th>

 <tr>
 <th>show</th>
 <th>boolean</th>
 <th></th>
 </tr>
 
 <tr>
 <th>multiSelect</th>
 <th>boolean</th>
 <th></th>
 </tr>
 
<tr>
 <th> allowSelectableAll</th>
 <th></th>
 <th></th>
 </tr>
 </table>
            

 <h2 id="actionsRows">actionsRows</h2>  
 <table>
 <table border="1" cellpadding="15" cellspacing="0" width="75%">
               
 <th width="10%"scope="col">Attribute</th>
 <th width="10%"scope="col">Type</th>
 <th width="10%"scope="col">Description</th>
 </tr>
 </table>                 
                     

 <h2 id="columnsDefinition">columnsDefinition</h2>
 <table>

  <table border="1" cellpadding="15" cellspacing="0" width="75%">
                                                               
 <th width="10%"scope="col">Attribute</th>
 <th width="10%"scope="col">Type</th>
 <th width="10%"scope="col">Description</th>
 <tr>
 <th>name</th>
 <th></th>
 <th></th>
 </tr>
   
 <tr>
 <th>displayName</th>
 <th></th>
 <th> </th> 
</tr> 

<tr>
 <th>format</th>
 <th></th>
 <th></th>
 </tr> 
 
 <tr>
 <th>show</th>
 <th></th>
 <th></th>
 </tr>
 
 <tr>
 <th></th>
 <th></th>
 <th></th>
 </tr> 
  </table>
 
 
 <h2 id="paginationOptions">paginationOptions</h2>  
     <table>
         
 <table border="1" cellpadding="15" cellspacing="0" width="75%">
                    
 <th width="10%"scope="col">Attribute</th>
 <th width="10%"scope="col">Type</th>
 <th width="10%"scope="col">Description</th>
 
  <tr> 
 <th>Show</th>
 <th></th>
 <th></th>   
 </tr>
 
<tr>  
<th>currentPage</th>
<th></th>
<th></th>    
</tr>

<tr>  
<th> itemsByPage</th>
<th></th>
<th></th>    
</tr>   
 </table>
 
<h2 id="self.data">self.data</h2>  
<table>
                                                  
<table border="1" cellpadding="15" cellspacing="0" width="75%">
 <th width="10%"scope="col">Attribute</th>
 <th width="10%"scope="col">Type</th>
 <th width="10%"scope="col">Description</th>
                                                                   
 <tr>
<th>infoFieldName</th>
<th></th>
<th></th>
</tr>
             
<tr>
<th>info</th>
<th></th>
<th></th>
</tr>

<tr>   
<th>totalItemsFieldName</th>
<th></th>
<th></th>   
</tr>

<tr>    
<th>columnFilter</th>
<th></th>
<th></th>
</tr> 

<tr>    
<th>cellTemplate</th>
<th></th>
<th></th>
</tr>    
             
<tr>    
<th>return self</th>
<th></th>
<th></th>
</tr> 

<tr>
<th>console.log(parameters)</th>
<th></th>
<th></th>
</tr>   
</table>

<h2 id="Data">Data</h2>
 <table>

  <table border="1" cellpadding="15" cellspacing="0" width="75%">
                                                               
 <th width="10%"scope="col">Attribute</th>
 <th width="10%"scope="col">Type</th>
 <th width="10%"scope="col">Description</th>
 <tr>
    <th></th>
    <th></th>
    <th></th>
    </tr>
  </table>
  
<h2 id="pagination">pagination</h3>
<table>
    
  <table border="1" cellpadding="15" cellspacing="0" width="75%">
                                                               
 <th width="10%"scope="col">Attribute</th>
 <th width="10%"scope="col">Type</th>
 <th width="10%"scope="col">Description</th>
 
<tr>
    <th></th>
    <th></th>
    <th></th>
    </tr>



</table>


























                     
        
        
               
                        
        
        
        











     



