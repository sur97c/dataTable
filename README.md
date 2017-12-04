


<h1>DataTable</h1>

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
    
 <th><a href="#headerOptions">headerOptions</th></a>
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
    
 <th><a href="#actionsRows">actionsRows</th><a/>
 <th>json</th>
 <th></th>
            
 </tr>
 
 <tr>
    
 <th><a href="#columnsDefinition">columnsDefinition</th></a>
 <th>json</th>
 <th></th>
            
 </tr>
 
 <tr>
    
 <th><a href="#rowsDefinition">rowsDefinition</th></a>
 <th>json</th>
 <th></th>
            
 </tr>
 
 <tr>
    
 <th><a href="#paginationOptions">paginationOptions</th>
 <th>json</th>
 <th></th>
            
 </tr>
 
 <tr>
    
 <th><a href="#data">data</th></a>
 <th>json</th>
 <th></th>
            
 </tr>
</table>


<h1>Configuration</h1>


           
  <h2 id="headerOptions">headerOptions</h2>
    <table>
   <table border="1" cellpadding="15" cellspacing="0" width="75%">
                 

 <th width="10%"scope="col">Attribute</th>
 <th width="10%"scope="col">Type</th>
 <th width="10%"scope="col">Description</th>
                   
<tr>
 <th>title </th>
 <th>string</th>
 <th>Muestra el titulo en el encabezado de la tabla</th>
            
 </tr>
            
 <tr>
 <th>showColumnsOption</th>
 <th>boolean</th>
 <th>configura las columnas</th>
  </tr>
            
  <tr>
  <th> showSearchOption</td>
  <th>boolean</th>
  <th></th>
  </tr>
  
  <tr>
  <th> showRemoveFiltersOption</th>
  <th>boolean</th>
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
 <th>boolean</th>
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

 
 <tr>
<th>show</th>
<th>boolean</th>
<th></th>
</tr>
            
  <tr>
<th>actions</th>
<th>array</th>
<th></th>
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
 <th>string</th>
 <th></th>
 </tr>
   
 <tr>
<th><a href="#displayName">displayName</th></a>
 <th>string</th>
 <th> </th> 
</tr> 

<tr>
 <th>format</th>
 <th>string</th>
 <th></th>
 </tr> 
 
 <tr>
 <th>show</th>
 <th>boolean</th>
 <th></th>
 </tr>
 
 <tr>
 <th>columnFilter</th>
 <th><a href="https://docs.angularjs.org/guide/di">Inline Array Annotation</th></a>
 <th></th>
 </tr> 
 
  <tr>
 <th>cellTemplate</th>
 <th>array</th>
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
 <th>show</th>
 <th>boolean</th>
 <th></th>   
 </tr>
 
<tr>  
<th>currentPage</th>
<th>entire</th>
<th></th>    
</tr>

<tr>  
<th><a href="#itemsByPage">itemsByPage</th>
<th>json</th>
<th></th>    
</tr>   
 </table>
 
<h2 id="data">data</h2>  
<table>
                                                  
<table border="1" cellpadding="15" cellspacing="0" width="75%">
 <th width="10%"scope="col">Attribute</th>
 <th width="10%"scope="col">Type</th>
 <th width="10%"scope="col">Description</th>
                                                                   
 <tr>
<th>infoFieldName</th>
<th>string</th>
<th></th>
</tr>

<tr>   
<th>totalItemsFieldName</th>
<th>string</th>
<th></th>   
</tr>           

<tr>
<th>info</th>
<th>null</th>
<th></th>
</tr>



<tr>    
<th>columnFilter</th>
<th><a href="https://docs.angularjs.org/guide/di">Inline Array Annotation</th></a></th>
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

<h2 id="displayName">displayName</h2>
 <table>

  <table border="1" cellpadding="15" cellspacing="0" width="75%">
                                                               
 <th width="10%"scope="col">Attribute</th>
 <th width="10%"scope="col">Type</th>
 <th width="10%"scope="col">Description</th>


 <tr>
    <th>NT</th>
    <th>string</th>
    <th></th>
    </tr>

 <tr>
    <th>handler</th>
    <th><a href="https://docs.angularjs.org/guide/di">Inline Array Annotation</th></a></th>
    <th></th>
    </tr>
    </table>
    
<h2 id=" itemsByPage">itemsByPage</h2>
 <table>

  <table border="1" cellpadding="15" cellspacing="0" width="75%">
                                                               
 <th width="10%"scope="col">Attribute</th>
 <th width="10%"scope="col">Type</th>
 <th width="10%"scope="col">Description</th>


 <tr>
    <th>displayText</th>
    <th>string</th>
    <th></th>
    </tr>

 <tr>
    <th>value</th>
    <th>enterier</th>
    <th></th>
    </tr>
<tr>
    <th>active</th>
    <th>boolean</th>
    <th></th>
    </tr>
</table>


























                     
        
        
               
                        
        
        
        











     



