# Lydia-task
HNG
<DOCTYPE html>
<html>
<head>
<style>
h1{ 
		text-align: center;
		font-size:25px;
		padding-top:100px;
		margin-left:50px;
		color:purple;
		letter-spacing:35px;
}
h2{
   text-align:center
   font-size:35px;
   padding-top:200px;
   margin-left:500px;
   letter-spacing:30px;
  color:purple;
bottom:0;

  }
   

body {
    font:normal 12px/1.6em Arial, Helvetica, sans-serif;
	color:#2a3845;
	margin:0;
	padding:0;
	background:yellow;
}
div{	   display:inline-block;
			position:relative;
			height:0px;
			color:white;
			 width:0px;
		     height:0px;
			margin:50px 0;
			border-left:100px solid transparent;
			border-right:100px solid transparent;
			border-bottom:70px solid white;
			-webkit-user-select:none;
			-moz-transform:rotate(37deg);
			-ms-transform:rotate(37deg);
			-o-transform:rotate(37deg);
			-webkit-transform:rotate(37deg);
			transform:rotate(37deg);
	
			}
div:before{
			      display:block;
                  content:"";
				  width:10px;
				  height:0px;
				  position: absolute;
				  border-left:30px solid transparent;
				  border-right: 30px solid transparent;
				  border-bottom:80px solid white;
				  -moz-transform:rotate(-35deg);
				  -ms-transform:rotate(-35deg);
				  -o-transform:rotate(-35deg);
				  transform:rotate(-35deg);
				  -webkit-transform:rotate(-35deg);
				  top:-45px;
				  left:-65px;
	}
div:after{
		    width:0;
			color:white;
			height:0;
			border-left:solid 100px transparent;
			border-right:solid 100px transparent;
			border-bottom: solid 70px white;
			position:absolute;
			display:block;
		    content:"";
			top:3px;
			left:-105px;
			-webkit-transform:rotate(-70deg);
			 -moz-transform:rotate(-70deg);
			-o-transform:rotate(-70deg);
			transform:rotate(-70deg);
	}
	#five{
	      margin-right:900px;
	
	}
</head>

</style>
<body>
<div id="five"></div>
<div>
</div>
<h1> HELLO! MY NAME IS LYDIA</h1>
<h2> <?php
date_default_timezone_set("Africa/Lagos");
echo "TIME:". date("h:ia");
?> </h2>
</body>
</html>
