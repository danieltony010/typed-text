<!doctype html>
<html>
	<head>
		<title>Scrolling Typed Text</title>
		<meta charset="utf-8" />
		<link rel="stylesheet" type="text/css" href="scrolling_typed_text.css">
		<script type="text/javascript" src="jquery-3.2.1.js"></script>
		<script src="typed.js"></script>
	</head>
	<body>
		<div class="center">
			<span class="type"></span>
		</div>

		<script>
			$(function(){
				$(".type").typed({
					strings:[
						"HELLO WORLD",
						"I am an up and coming web designer and developer"
					],
					backDelay: 100,
					typeSpeed: 70,
					loop: true,
				})
			})
		</script>		
	</body>
</html>
