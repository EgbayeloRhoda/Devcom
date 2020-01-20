<!DOCTYPE html>
<html>
<head>
	<title> DevCom </title>
	<style>
		body {
			background-color: #b5a789;
			font-family: georgia, serif;
			margin:	10px;
			
		}

		header {
			background-color: #675c47;
			margin: 10px;
		}

		label {
			color: #efe5d0;
			font-weight: bolder;
			font-size: 330%;
		
		}

		h1 {
			color: #b76666;
		}

		#container{
			display: table;
			border-spacing: 15px;

		}

		ul {
			background-color: #675c47;
			padding: 5px 0px 5px 0px;
			margin: 10px 10px 10px 10px;
			list-style-type: none;
			text-align: center;
		}

		ul li {
			display: inline;
			padding: 5px 10px 5px 10px;
		}

		ul li a:link, ul li a:visited {
			color: #b76666;
			font-weight: bold;
		}

		footer {
			background-color: #675c47;
			text-align: center;
			padding: 15px;
			margin: 10px;
		}
	</style>
		
</head>
<body>
	<header>
			<label> WebDev </label>
	</header>
			<ul>
				<li> <a href="#"> Home </a> 
				<li> <a href="#"> Register </a>
				<li> <a href="#"> Our Services </a>
				<li> <a href="#"> Contact </a>
				<li> <a href="#"> Help </a> 
			</ul>

	<div id="container">
			<form>
						<h1> Registration Form </h1>
				<marquee> Make your Registrations </marquee>
				
				<h4> Surname: 	  <input type="text" name="box" placeholder="e.g David">
				<h4> First-Name:  <input type="text" name="box" placeholder="e.g Grace"> 
				<h4> Middle-Name: <input type="text" name="box" placeholder="e.g Efe">
				<h4> Sex: <input type="radio" name="sex"> Male
						  <input type="radio" name="sex"> Female
				<h4> Date Of Birth: <input type="Date">
				<h4> Relationship Status: <input type="text" name="box">
				<h4> Address: <textarea rows="10" cols="50"></textarea>
				<h4> Favorite Colour: <input type="color" name="color"><br><br>
					<input type="button" name="submit" value="Sign Up">
					<input type="button" name="reset" value="Refresh">
					<input type="button" name="back" value="Back">
				
			</form>
	
	</div>
			<footer> Copyright ©  2019 </footer>
</body>
</html>
