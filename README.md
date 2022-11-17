# asifproject
<!DOCTYPE html>
<html lang="en">
<head>
  <title>developing an home page releted to project asif </title>
  <link rel="stylesheet" href="asif.css">
  
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
    
