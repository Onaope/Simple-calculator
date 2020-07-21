
<head> 
  <meta name="viewport" content="width=device-width, initial-scale=1.0"> 
 <style type="text/css" id="dcoder_stylesheet">body {
    background-color:rgb(24, 144, 240)}
table{
    margin:auto;
    background-color:rgb(0, 48, 72);
    width:295px;
    max-width:295px;
    height:325px;
    text-align:center;
    border-radius:4px;
    padding-right:10px;
}
input {
  outline: 0;
  position: relative;
  left: 5px;
  top: 5px;
  border: 0;
  color: #495069;
  background-color: #fff;
  border-radius: 4px;
  width: 60px;
  height: 50px;
  float: left;
  margin: 5px;
  font-size: 20px;
  box-shadow: 0 4px rgba(0,0,0,0.2);
  margin-bottom: 15px;
}
input:hover {
  border: 0 solid #000;
  color: #495069;
  background-color: #fff;
  border-radius: 4px;
  width: 60px;
  height: 50px;
  float: left;
  margin: 5px;
  font-size: 20px;
  box-shadow: 0 4px #b0d2cf;
}
input:active {
  top: 4px;
  border: 0 solid #000;
  color: #495069;
  background-color: #fff;
  border-radius: 4px;
  width: 60px;
  height: 50px;
  float: left;
  margin: 5px;
  font-size: 20px;
  box-shadow: none;
}  
#display {
  width: 293px;
  max-width: 293px;
  font-size: 26px;
  text-align: right;
  background-color:rgb(216 240 255);
  float: left;
  height:120px;
  }
#display:hover {
  width: 270px;
  font-size: 26px;
  text-align: right;
  background-color: #bcbd95;
  box-shadow: 0 4px rgba(0,0,0,0.2);
}
#display:active {
  top: 5px;
  width: 270px;
  font-size: 26px;
  text-align: right;
  background-color: #bcbd95;
  box-shadow: 0 4px rgba(0,0,0,0.2);
  }
.operator {
  background-color:rgb(96 120 216);
  position: relative;
}
.operator:hover {
  background-color: #cee9ea;
  box-shadow: 0 4px #b0d2cf;
}
.operator:active {
  top: 4px;
  box-shadow: none;
}

#clear {
  float: left;
  position: relative;
  display: block;
  background-color: deepSkyBlue;
}
#clear:hover {
  float: left;
  display: block;
  background-color: deepSkyBlue;
  box-shadow:;
 
}

#clear:active {
  float: left;
  top: 4px;
  display: block;
  background-color: deepSkyBlue;
  margin-bottom: 15px;
  box-shadow: none;
}
button{
    text-align: center;
    border-radius: 4px;
    box-shadow: 0 ;
    background-color: rgb(48, 72, 192);
    display: block ;
    height: 40px;
    border-style: none;
    padding: 0 20px 0 20px;
    margin: auto;
    margin-bottom: 15px;
    width: 293px;
    
    
}
button:hover{
 width: 293px;
  text-align: center;
  background-color: blue;
  box-shadow: 0  blue;
   border: 0 solid;
  color: #495069;
  border-radius: 4px;
  height: 40px;
  margin: auto;
  font-size: 20px;
   
}
button:active{
    top: 5px;
  width: 293px;
  text-align:center ;
  background-color: blue;
  box-shadow: 0 blue;
  border-style:none ;
}
hr{
    text-align: center ;
    background color: white;
    width: 293px;
    margin: auto ;
}</style></head> 
 <body> 
  <form name="calculator"> 
   <table> 
    <tbody> 
     <tr> 
      <td colspan="4"> <input type="text" name="display" id="display" disabled> </td> 
     </tr> 
     <tr> 
      <td colspan="4"> 
       <hr></td> 
     </tr> 
     <tr> 
      <td><input type="button" name="seven" value="7" onclick="calculator.display.value += '7'"></td> 
      <td><input type="button" name="eight" value="8" onclick="calculator.display.value += '8'"></td> 
      <td><input type="button" name="nine" value="9" onclick="calculator.display.value += '9'"></td> 
      <td><input type="button" class="operator" name="plus" value="+" onclick="calculator.display.value += '+'"></td> 
     </tr> 
     <tr> 
      <td><input type="button" name="four" value="4" onclick="calculator.display.value += '4'"></td> 
      <td><input type="button" name="five" value="5" onclick="calculator.display.value += '5'"></td> 
      <td><input type="button" name="six" value="6" onclick="calculator.display.value += '6'"></td> 
      <td><input type="button" class="operator" name="minus" value="-" onclick="calculator.display.value += '-'"></td> 
     </tr> 
     <tr> 
      <td><input type="button" name="one" value="1" onclick="calculator.display.value += '1'"></td> 
      <td><input type="button" name="two" value="2" onclick="calculator.display.value += '2'"></td> 
      <td><input type="button" name="three" value="3" onclick="calculator.display.value += '3'"></td> 
      <td><input type="button" class="operator" name="times" value="x" onclick="calculator.display.value += '*'"></td> 
     </tr> 
     <tr> 
      <td><input type="button" name="zero" value="0" onclick="calculator.display.value += '0'"></td> 
      <td><input type="button" name="dot" value="." onclick="calculator.display.value += '.'"></td> 
      <td><input type="button" id="clear" name="clear" value="c" onclick="calculator.display.value = ''"></td> 
      <td><input type="button" class="operator" name="div" value="÷" onclick="calculator.display.value += '/'"></td> 
     </tr> 
     <tr> 
      <td colspan="8"> <button type="button" name="doit" value="=" onclick="calculator.display.value = eval(calculator.display.value)">=</button></td> 
     </tr> 
    </tbody> 
   </table> 
  </form> 
 
</body>


