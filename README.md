<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<title>Module2_assingment</title>
<style>
	*{
		box-sizing: border-box;
	}
	h1{
		text-align: center;
		font-family: sans-serif;
		border-bottom: 20px solid black;
	}
	h2{
		text-align: right;
	}
	div{
		float: left;
		width: 60%;
		margin: 2px;
		border-top: 2px solid black;
		border-bottom: 2px solid black;
		border-right: 2px solid black;
		border-left: 2px solid black;
		background: seashell;
	}
    @media (max-width:1090px){
		div{
		width:32%;
	    }
		
	}	@media (min-width:992px){
		div{
		width:33%;
	    }
		
	}
	@media  (min-width : 768px) and (max-width: 991px){
		.col_sd_12{
		width:49%;
	    }
	    .col{
	    	width:100%;
	    }
	}
	@media (max-width:767px){
		div{
			width:100%;
		}
	}
	
</style>
</head>
<body>
	<h1>Restaurant special</h1>
	<section class="row">
	<div class="col_sd_12"><h2><a href="https://en.wikipedia.org/wiki/Chicken" target="_blank">Chicken</a></h2>TLorem ipsum dolor sit amet, consectetur adipiscing elit. Integer nec odio. Praesent libero. Sed cursus ante dapibus diam. Sed nisi. Nulla quis sem at nibh elementum imperdiet. Duis sagittis ipsum. Praesent mauris. Fusce nec tellus sed augue semper porta. Mauris massa. Vestibulum lacinia arcu eget nulla.
    </div>
	<div class="col_sd_12"><h2><a href="https://en.wikipedia.org/wiki/Sushi" target="_blank">Sushi</a></h2>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer nec odio. Praesent libero. Sed cursus ante dapibus diam. Sed nisi. Nulla quis sem at nibh elementum imperdiet. Duis sagittis ipsum. Praesent mauris. Fusce nec tellus sed augue semper porta. Mauris massa. Vestibulum lacinia arcu eget nulla.</div>
	<div class="col"><h2><a href="https://en.wikipedia.org/wiki/Beef" target="_blank">Beef</a></h2>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer nec odio. Praesent libero. Sed cursus ante dapibus diam. Sed nisi. Nulla quis sem at nibh elementum imperdiet. Duis sagittis ipsum. Praesent mauris. Fusce nec tellus sed augue semper porta. Mauris massa. Vestibulum lacinia arcu eget nulla.
    </div>
    </section>
</body>
</html>
