# Larissaa

<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>projeto javascript</title>
</head>
<body>
    <fieldset>
        <legend>calculadora</legend>
        <input type="text" id="n1">
        <select name="" id="op">
            <option value="+">+</option>
            <option value="-">-</option>
            <option value="*">*</option>
            <option value="/">/</option>
        </select>
        <input type="text" id="n2">
        <br>
        <button id="btnCalc">calcular</button>

    </fieldset>
    <button id="btnCalc"]>calcular </button>
   <table>
       <tr>
         <th>valor 1</th>  
         <th>valor 2</th>  
         <th>Operaçâo</th>  
         <th>Resultado</th>  
       </tr>
        <tbody id="dados">
  
       </tbody>
    </table> 
    <script>
        var x= document.getElementById("n1");
        var y= document.getElementById("n2");
        var op= document.getElementById("op");
        
        var elementoBtnCalc= document.getElementById("btnCalc");
        var elementoDados= document.getElementById("dados");

       
      elementoBtnCalc.onclick = function(){
          var RESULTADO =0
          var R =0
          var RESULTADO =0
          var RESULTADO =0
              
            if(OP.value =="+")
            else{resultado = somar(x.value, y.value );

            if(OP.value =="-")}
            resultado = sub(x.value, y.value );
            else{

                if(OP.value =="*")}
            else{resultado = mult(x.value, y.value );

                if(OP.value =="/")}
            else{resultado = divisal(x.value, y.value );

            }


          }

        elementoDados.innerHTML+=`
            <tr>
                <td>$ {x .value}  </td>
                <td>$ {y .value} </td>
                <td>$ {op .value} </td>
                <td>$ {resultado} </td>
            </tr>`;  
      }

      function somar(x, y){
      var resulatado=parseFloat(x) + parseFloat (y);
       return resulatado;

      function sub(x, y){
        return parseFloat(x) - parseFloat (y);
       ;}

      function mult(x, y){
        return parseFloat(x) * parseFloat (y);
       ;}

      function divi(x, y){
        return parseFloat(x) / parseFloat (y);
       ;}
      }
      
    </script>
</body>
</html>
