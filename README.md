PeanutButterJelly
=================

Bootstrap3 HTML WYSIWYG editor in Javascript

# How to use

### include bootstrap3
	<script type="text/javascript" scr="bootstrap.min.js"></script>


### include the js files

	<script type="text/javascript" scr="PeanutButterJelly.js"></script>

### include the CSS file

	<link rel="stylesheet" type="text/css" href="PeanutButterJelly.css">
	
## in your code init PBJ like this:	

	var pbj = new PeanutButterJelly();
	pbj.init();
	
## in your HTML add the PBJ DIVs:

	<!-- Main Canvas Container. Just add class pbj -->
	<div class="pbj">
		<!-- Main Sidebar Container. Just add class pbj-sidebar -->
		<div class="pbj-sidebar"></div>
		<!-- Main Toolbar Container. Just add class pbj-toolbar -->
		<div class="pbj-toolbar"></div>
		<!-- Main Editor Container. Just add class pbj-editor -->
		<div class="pbj-editor"></div>
		<!-- Main Footer Container. Just add class pbj-footer -->
		<div class="pbj-footer"></div>
	</div>
	
	
## Here's a video to get you started ;)
	https://www.youtube.com/watch?v=-VK-VjWbvF4
