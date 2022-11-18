# asifproject
<!DOCTYPE html>
<html lang="en">
<head>
  <title>developing an home page releted to project asif </title>
  <link rel="stylesheet" href="asif.css">
  <style>
   .anim{
    width:300px;
    height:400px;
    background-color:dodgerblue;
    border-radius:10px;
    box-shadow:1px 2px 10px rgba(0,0,0,0.6),
    5px 21px 10px rgba(0,0,0,0.6),1px 2px -10px rgba(0,0,0,0.6),-1px -2px -10px rgba(0,0,0,0.6);
    animation:anim 2s alternate ;
    @key-farame anim{
     0%{
          transform:parspective(800px),translateZ(0px);
       }
     50%{
        transform:parspective(800px),translateZ(50px);
        }
     100%{
       transform:parspective(800px),translateZ(100px);
         }
     }
    
   }
  </style>
  </head>
  <body>
    <h1>hello world</h1>
    <div class="container">
      <form action="" onsubmit="return validation()">
        <label>user name: </label>
        <input type="text" name="user" id="user">
        <span id='usererror'></span>
         <label>password: </label>
        <input type="text" name="user" id="user">
         <label>email: </label>
        <input type="text" name="user" id="user">
         <label>mobileno: </label>
        <input type="text" name="user" id="user">
        <br>
        <input type="submit" value="submit" name="submit">
  
        </form>
      
    </div>
    <div class="anim">
    </div>
    <script>
        function validation(){
          var user=document.getEelementById('user').value;
         
          if(user==""){
        document.getElementById('usererror').innerHTML="** please fill the user name field.";
      
      }
        }
      
      
      
    </script>
  </body>
  </html>
    
