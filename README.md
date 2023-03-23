<DOCTYPE html>
<html>
<head><title>form</title></head>
<body bgcolor="khaki">
    <form action="mail to: sirohi2211921@gmail.com" method="post">
        <fieldset>
   <legend> personal Information</legend>
   <label for="firstname">First name:
   <input type="text" name="firstname" name="firstname"/></label><br/>
   <label for="lastname">Last name:
   <input type="text" name="lastname" name="lastname"/></label><br/>
   <label for="email">email:
   <input type="text"name="email" name="email"/></label><br/>
   <label for="male"><input type="radio" name="gender" value="male" id="male"/>
   male</label>
   </br>
   <label for="female"><input type="radio" name="gender" value="female" id="female"/>
   female</label><br/>
   </fieldset>
   <fieldset>
       <legend>Interests</legend>                <input type="checkbox" checked="checked" name="programming" value="yes"id="programming"/>
 <label for="programming"> programming</label><br/>
 <input type="checkbox" name ="graphics" value="yes" id="graphics"/>
 <label for="graphics"> Graphics Design</label><br/>
 <input type="checkbox" checked="checked" name="layout" value="yes" id="layout"/>
<label for="layout">Page Layout</label><br/>
<input type="checkbox"  name="writing" value="yes" id="writing"/>
<label for="writing">Technical writing</label><br/><br/>
<label for="Department-1">college:</label><br/>
<select name="Department-1" name="Department-1">
    <option>Architecture</option>
    <option>Business </option>
    <option> communication</option>
    <option>engineering</option>
    <option>law</option>
    <option>polytechnic</option>
    <option>ITI</option>
    </select>
    </fieldset>
    <input type="submit" value="send"/>
    <input type="reset"/>
    </form>
    </body>
    </html>
