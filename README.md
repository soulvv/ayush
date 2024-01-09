# ayush
we know what v8 is

<html>
<head>
    <title>Login Page</title>
	    <script>
        function check()
		{
            var a = document.getElementById("login").value;
            var b = document.getElementById("pass").value;

            if (a === "Web" && b === "Technology")
			{
                alert("Welcome!");
		    }
			else if (a === "GLA" && b === "University")
			{
			    alert ("Welcome!");
			}
			else if (a === "CEA" && b === "Department")
			{
			    alert ("Welcome!");
			}
             else
			{
                alert("Incorrect username or password. Please try again.");
            }
        };
    </script>
</head>
<body>
<form>
Login<input type=text name=t1 id=login><br>
Password<input type=password name=t2 id=pass><br>
<input type=submit value=submit onclick=check()>
</form>

</body>
</html>
