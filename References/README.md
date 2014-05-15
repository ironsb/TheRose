TheRose
=======

Site for The Rose restaurant.

Photo Gallery Backup:

HTML-<divclass="gallery" align="center">
		<h3>Simple and Effective Photo Gallery with HTML and JavaScript</h3>
		<div class="thumbnails">
			<img onmouseover="preview.src=img1.src" name="img1" src="http://bit.ly/2rz3hy" alt="" />
			<img onmouseover="preview.src=img2.src" name="img2" src="http://bit.ly/1ug1e6" alt="" />
			
		</div>
		<div class="preview" align="center">
			<img name="preview" src="http://bit.ly/2rz3hy" alt=""/>
		</div>
		
		</div>
CSS-.thumbnails img {
		height: 80px;
		border: 4px solid #555;
		padding: 1px;
		margin: 0 10px 10px 0;
	}

	.thumbnails img:hover {
		border: 4px solid #00ccff;
		cursor:pointer;
	}

	.preview img {
		border: 4px solid #444;
		padding: 1px;
		height: 500px;
	}
	
Color Scheme
	#B5333B
	#486FAD
	#D4D86A
	#BDBB64
	#B2CAC7
	#find{
				
				background:none;
				border:none;
				color:#000000;
				text-decoration: none;
				font-family: Verdana, helvetica, sans-serif;
				font-size:inherit;
				padding:0;
			}
			#find:hover{
				cursor: pointer;
				background-color:#BDBB64;
				text-decoration: none;
				font-family: Arial, Helvetica, sans-serif;
			}
		<form action="http://maps.google.com/maps" method="get" target="_blank">
						   <input type="hidden" name="saddr" value="current location" />
						   <input type="hidden" name="daddr" value="408 Main St. Pagosa Springs Colorado" />
						   <input id="find" type="submit" value="Find Us" />
						</form>
