<!DOCTYPE html>
<html>
  <body>
   <script>
    function Largest2No() {
	  var n1,n2;
	  n1 = parseInt(prompt("enter first number:"));
	  n2 = parseInt(prompt("enter second number:"));
	if(n1>n2)
	{
           document.write(n1+" is Largest number");
	}
	else
	{
	   document.write(n2+" is Largest number");
	}
   }
    </script>
    <form>
      <input type="button" value="LargestNo" onclick="Largest2No()" />
    </form>
  </body>
</html>            
