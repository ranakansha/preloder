# preloder
this repo contain preloder code with fadeout time in javascript,html,css.

working code



```
<!DOCTYPE html> 
<html lang="en"> 

<head> 
	<meta charset="utf-8" /> 
	<meta name="viewport"
		content="width=device-width, initial-scale=1.0" /> 
	<meta http-equiv="X-UA-Compatible" content="ie=edge" /> 
	<title>Loader Demo</title> 
	<style> 
		#loader { 
			width: 100%; 
			height: 100vh;
			position:fixed;
			z-index:99999; 
			background: #fff url('loader.gif') no-repeat center;
		} 
	
	</style> 
</head> 

<body> 
	<div id="loader" class="center"></div> 
	<h1>GeeksforGeeks</h1> 
	<h2>A computer science portal for geeks</h2> 
	<img src="https://i.imgur.com"
		alt="GeeksforGeeks logo" /> 
	<script> 
		document.onreadystatechange = function() { 
			if (document.readyState !== "complete") { 
				document.querySelector( 
				"body").style.visibility = "hidden"; 
				document.querySelector( 
				"#loader").style.visibility = "visible"; 
			} else { 
				document.querySelector( 
				"#loader").style.display = "none"; 
				document.querySelector( 
				"body").style.visibility = "visible"; 
			} 
		}; 
	</script> 
</body> 

</html> 

```
