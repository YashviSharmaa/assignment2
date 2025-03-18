#working with html and css
#This is a form that is created using html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0"
    <title>forms</title>
</head>
<body>
    <div>
        <h1>travel form for our trip</h1>
        <form>
        <!-- input element = can be of type text , checkbox , radio button , submit -->
         <input type="text" placeholder="enter ur name"><br>
         <label for="sectionida">
            <!-- id is unique identifier of html element -->
          <input type="radio" value="section a" name="section" id="sectionid">yes<br>
          <input type="radio" value="section b" name="section" id="sectionid">no<br>
</label>
<label for="sectionidb">
    <input type="radio" value="section c" name="section" id="sectionidc">section b<br>
    <input type="checkbox" name="library card" id="lib" class="red">hey buddy wanna card<br>
    <!-- class can be of two also not unique -->
     <input type="color"><br>
     <textarea name="explain" id="explain" cols="30" rows="14" placeholder="explain urself"></textarea><br>
     <select name="car" id="cars" > select your car
        <option value="nocar">select car</option>
        <option value="punch">punch</option>
        <option value="scorpio">scorpio</option>
        <option value="nexon">nexon</option>
     </select>
</form></div>


</body>
</html>
