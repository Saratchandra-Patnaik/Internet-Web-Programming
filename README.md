# Internet-Web-Programming
<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<title>Assaignment</title>
	<style>
		/**********Base Styles*********/
		* {
			box-sizing: border-box;
			margin: 5px;
			padding: 5px;
		}
		h1 {
			margin-bottom: 15px;
		}
		h2 {
				color: blue;
				font-size: 40px;
				font-style: italic;
				text-align: right;
			}
		#par{
			font-size: 30px;	  
			font-family: Helvetica;
			font-style: italic;
			color: blue;
			text-align: right;
		}
		p {
			border: 3px solid black;
			background-color: green;
			width: 90%;
			height: 200px;
			margin-right: auto;
			margin-left: auto;
			font-family: Helvetica;
			font-style: italic;
			color: white;
		}
		h1 {
				color: red;
				font-size: 50px;
				font-style: italic;
				text-align: center;
			}
		.row {
			width: 100%;
		}
		/*********Large Devices**********/
		@media (min-width: 1200px) {
			.col-lg-1, .col-lg-2, .col-lg-3, .col-lg-4, .col-lg-5, .col-lg-6, .col-lg-7, .col-lg-8, .col-lg-9, .col-lg-10, .col-lg-11, .col-lg-12 {
				float: left;
				border: 5px solid red;
			}
			.col-lg-1 {
				width: 8.33%;
			}
			.col-lg-2 {
				width: 16.66%;
			}
			.col-lg-3 {
				width: 32%;
			}
			.col-lg-4 {
				width: 33%;
			}
			.col-lg-5 {
				width: 41.66%;
			}
			.col-lg-6 {
				width: 50%;
			}
			.col-lg-7 {
				width: 58.33%;
			}
			.col-lg-8 {
				width: 66.66%;
			}
			.col-lg-9 {
				width: 74.99%;
			}
			.col-lg-10 {
				width: 83.33%;
			}
			.col-lg-11 {
				width: 91.66%;
			}
			.col-lg-12 {
				width: 100%;
			}
		}

		/*********Medium Size***********/
		@media (min-width: 950px) and (max-width: 1199px) {
			.col-md-1, .col-md-2, .col-md-3, .col-md-4, .col-md-5, .col-md-6, .col-md-7, .col-md-8, .col-md-9, .col-md-10, .col-md-11, .col-md-12 {
				float: left;
				border: 5px solid red;
			}
			.col-md-1 {
				width: 8.33%;
			}
			.col-md-2 {
				width: 16.66%;
			}
			.col-md-3 {
				width: 25%;
			}
			.col-md-4 {
				width: 33%;
			}
			.col-md-5 {
				width: 45.33%;
			}
			.col-md-6 {
				width: 50%;
			}
			.col-md-7 {
				width: 58.33%;
			}
			.col-md-8 {
				width: 66.66%;
			}
			.col-md-9 {
				width: 74.99%;
			}
			.col-md-10 {
				width: 83.33%;
			}
			.col-md-11 {
				width: 91.66%;
			}
			.col-md-12 {
				width: 100%;
			}
		}

	</style>
</head>
<body>
	<h1>Introduction To Html</h1>

	<div class="row">
		<section class="col-lg-3 col-md-11"><p>HTML stands for Hyper Text Markup Language.Hypertext Markup Language (HTML) is the standard markup language for documents designed to be displayed in a web browser. It can be assisted by technologies such as Cascading Style Sheets (CSS) and scripting languages such as JavaScript.</p></section>
		
		<section class="col-lg-3 col-md-5"><p>Web browsers receive HTML documents from a web server or from local storage and render the documents into multimedia web pages. HTML describes the structure of a web page semantically and originally included cues for the appearance of the document.</p></section>
		
		<section class="col-lg-3 col-md-5"><p>HTML can embed programs written in a scripting language such as JavaScript, which affects the behavior and content of web pages. Inclusion of CSS defines the look and layout of content. The World Wide Web Consortium (W3C), former maintainer of the HTML and current maintainer of the CSS standards, has encouraged the use of CSS over explicit presentational HTML since 1997.</p></section>
		</div>
		<h2 id="par">Prepared By</h2>
		<div id="par">MPV Saratchandra</div>
		<div id="par">1860441</div>
		<div id="par">5 BTCS C</div>
</body>
</html>
