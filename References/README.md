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