layout: page
title: "PAGE TITLE"
permalink: /about/

<!DOCTYPE html>
<html>
	<head>
		<title></title>
		<style>
			/* Accomodating layout change for small displays */
			@media screen and (max-width: 839px){
				.subbox1{
					height: 180px;
				}
				.subboxproperties{
					width: 100% !important;
				}
			}
			/* End */
			
			body{
				margin: 0px;
				font-family:system-ui,-apple-system,BlinkMacSystemFont,'Segoe UI','Helvetica Neue',Helvetica,Arial,sans-serif;
				background: green;
			}
			.title{
				font-size: 35px;
				font-weight: 700;
				padding: 0px 20px;
				padding-bottom: 0px;
				margin-bottom: 0px;
				
			}
			.text{
				font-size: 16px;
				padding: 0px 20px;
				line-height: 1.5em;
				margin-top: 10px;
				padding-top: 0px;
			}
			.flexbox{
				display: flex;
				flex-flow: row wrap;
				background: none;
				align-items: center;
				justify-content: center;
				align-content: space-between;
				overflow: hidden !important;
				
			} 
			.boxproperties{
				display: flex;
				flex-flow: row wrap;
				justify-content: center;
				margin: 10px;
				width: 45vw;
				min-width: 400px;
				max-width: 600px;
				min-height: 400px;
				background: white !important;
				border-radius: 20px;
				overflow: hidden !important;
			}
			.subboxproperties{
				width: 50%;
			
				
			}
				
			.box1{
				background: red;
				
			}
			.subbox1{
				background: grey;					
			}
			.subbox2{
				background: none;
			}
			.box2{
				background: orange;
				
			}
			.box3{
				background: yellow;
				
				
			}
		</style>
	</head>
	<body>
		<div class="flexbox">
			<div class="box1 boxproperties">
				<div class="subboxproperties subbox1"></div>
				<div class="subboxproperties subbox2"> 
				<p class="title">Title</p>
				<p class="text">This is some text that will go below the title. Quasi incidunt libero non sed blanditiis. Consectetur dolorem ipsum molestiae dolore commodi id eum ipsum. Eius quis ex temporibus est dolor voluptatibus.<br><br></p>
				</div>
			</div>
			<div class="box2 boxproperties"></div>
			<div class="box3 boxproperties"></div>
		</div>
	</body>
</html>
