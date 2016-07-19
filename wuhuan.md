# css3
haha
<!DOCTYPE html>
<html>
<head>
	<title></title>
	<style type="text/css">
	.circle, .circle:after{
		border-radius: 50%;
		border-style: solid;
		border-width: 10px;
		width: 140px;
		height: 140px;
		position: absolute;
	}
	.circle:after{
			content: '';
			left: -10px;
			top: -10px;
		}
	.blue{
		border-color: blue;
	}
	.blue:after{
		border-color: blue;
		border-bottom-color: transparent;
		z-index: 1;
	}
	.yellow{
		border-color: yellow;
		left: 180px;
	}
	.yellow:after{
		border-color: yellow;
		border-left-color: transparent;
		z-index: 1;
	}
	.red{
		border-color:red;
		left: 350px;
	}
	.red:after{
		border-color:red;
		border-left-color: transparent;
		z-index: 1;
	}
	.green{
		border-color:green;
		top: 90px;
		left: 90px;
	}
	.green:after{
		border-color:green;
	}
	.black{
		border-color:black;
		top: 90px;
		left: 270px;
	}
	.black:after{
		border-color:black;
		border-right-color: transparent;
		border-top-color: transparent;
		z-index: 1;
	}
	</style>
</head>
<body>
	<div class="circle blue"></div>
	<div class="circle yellow"></div>
	<div class="circle red"></div>
	<div class="circle green"></div>
	<div class="circle black"></div>
</body>
</html>
