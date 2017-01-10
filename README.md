

@import url(http://fonts.googleapis.com/css?family=PT+Sans:400,700);

@import 'https://fonts.googleapis.com/css?family=Indie+Flower';
.devunit {
  font-family: 'Indie Flower', cursive;
}
.love {
  display: inline-block;
  position: relative;
  top: .2em;
  font-size: 1.5em;
  color: #e74c3c;
  -webkit-transform: scale(.9);
  -moz-transform: scale(.9);
  transform: scale(.9);
  -webkit-animation: love .5s infinite linear alternate-reverse;
  -moz-animation: love .5s infinite linear alternate-reverse;
  animation: love .5s infinite linear alternate-reverse;
}
@-webkit-keyframes love {
  to {-webkit-transform: scale(1.2);}
}
@-moz-keyframes love {
  to {-moz-transform: scale(1.2);}
}
@keyframes love {
  to {transform: scale(1.2);}
}

body {
	background: #fff;
	margin:0;
	padding:0;
	font-family: 'PT Sans', 'sans-serif';
	font-size: 1.0em;
	color: #666;
	font-weight: 200;
}

* {
	margin:0;
	padding:0;
}

/** element defaults **/
table {
	width: 100%;
	text-align: left;
}

th, td {
	padding: 10px 10px;
}

th {
	color: #666;
	background: #ccc none repeat-x scroll left top;
}

td {
	border-bottom: 1px solid #ccc;
}

code, blockquote {
	display: block;
	border-left: 5px solid #222;
	padding: 10px;
	margin-bottom: 20px;
}
code {
	background-color: #222;
	color:#ccc;
	border: none;
}
blockquote {
	border-left: 5px solid #222;
}

blockquote p {
	font-style: italic;
	font-family: Georgia, "Times New Roman", Times, serif;
	margin: 0;
	color: #333;
	height: 1%;
}

p {
	line-height: 1.9em;
	margin-bottom: 20px;
}

a {
	color: #4297D8;
	border-bottom: 1px solid #4297D8;
	text-decoration: none;
}

a:hover {
	border-bottom-color: #D63843;
	color: #D63843;
}

a:focus {
	outline: none;
}


a.button { 
  
    background: linear-gradient(#78B5E3, #3892D6);
    background-color: #62A9DF;
    color: #FFFFFF;
    display: inline-block;
    font-weight: bold;
    padding: 8px 15px;
	border: none;
    text-decoration: none;
    text-transform: uppercase;
}

a.button:hover {
	background:#3892D6;
}

a.button-reversed { 
	background: linear-gradient(#333, #111);
	background-color: #222;
	color: #fff;
}

a.button-reversed:hover {
	background: #111;
}

fieldset {
	display: block;
	border: none;
	border-top: 1px solid #ccc;
}

fieldset legend {
	font-weight: bold;
	font-size: 0.9em;
	padding-right: 10px;
	color: #333;
}

fieldset form {
	padding-top: 15px;
}

fieldset p label {
	float: left;
	width: 150px;
}

form input, form select, form textarea {
	padding: 5px;
	color: #333333;
	border: 1px solid #ddd;
	border-right:1px solid #ccc;
	border-bottom:1px solid #ccc;
	background-color:#fff;
	font-family: Arial, Helvetica, sans-serif;
	font-size: 0.9em;
}

form input.formbutton {
	border: none;
	background: #4498D8;
	color: #ffffff;
	font-weight: bold;
	padding: 6px 10px;
	font-size: 0.8em;
	letter-spacing: 1px;
	width: auto;
	overflow: visible;
}

form.searchform input {
  font-size: 0.9em;
    padding: 6px;
}

form.searchform p {
	margin: 5px 0;
}


span.required {
	color: #ff0000;
}

h1 {
	color: #000;
	font-size: 2.7em;
	text-transform: uppercase;
}

h2 {
	color: #222;
	font-size: 2.2em;
	letter-spacing: -1px;
	font-weight: bold;
	padding: 0 0 5px;
	margin: 0;
}

h3 {
	color: #3892D6;
	font-size: 1.9em;
	margin-bottom: 10px;
	letter-spacing: -1px;
}

h4 {
    color: #555;
    font-size: 1.2em;
    text-transform: uppercase;
    font-weight: bold;
    padding-bottom: 10px;
}

h5 {
	padding-bottom: 10px;
	font-size: 1.1em;
	color: #999;
}

ul, ol {
	margin: 0 0 35px 35px;
}

li {
	padding-bottom: 5px;
}

li ol, li ul {
	font-size: 1.0em;
	margin-bottom: 0;
	padding-top: 5px;
}

.width {
	max-width: 1100px;
	margin: 0 auto;
}


#container {
	background-color: #fff;
	width: auto;
	margin: 0 auto;
}

header {
	padding: 0px 0px 0px;
	margin: 0 auto;
    	background: linear-gradient(#333, #111);
    	background-color: #222;
	text-align: left;
	border-top: 8px solid #77B5E3;
	box-shadow: 0px 4px 5px #DDD;
}

header h1 {
	float: left;
}

header h1 a, header h1 a:hover {
    background: linear-gradient(#78B5E3, #3892D6);
    background-color: #62A9DF;
    color: #eee;
    font-size: 1.4em;
    padding: 10px 25px;
    letter-spacing: -2px;
    border-bottom: none;

}


nav {
	height: 80px;
	margin-bottom: 30px;
	float: right;
}

nav ul {
	list-style: none;
	padding: 0;
	margin: 20px 0 0 20px;
	text-align: left;
}

nav ul ul { 
	margin: 0 5px;
}

nav ul li {
	display: block;
	float: left;
	padding: 0px 5px;
}

nav ul li li {
	padding: 0;
	border-top: 1px solid #55A2DC;
}


nav ul li a {
	display: block;
	float: left;
	padding: 10px 20px;
    color: #666;
    font-size: 1.0em;
    letter-spacing: 0;
     border-bottom: none;
text-transform: uppercase;
font-weight: bold;
letter-spacing: 0.5px;
}

nav ul li li a {
	float: none;
}

nav ul li a:hover {
	color: #A2CCEC;
	text-decoration: none;
}

nav ul li.selected a {
	background: linear-gradient(#78B5E3, #3892D6);
	background-color: #62A9DF;
	color: #fff;
}


nav ul li a:hover, nav ul li.sfHover a {
	background: linear-gradient(#78B5E3, #3892D6);
	background-color: #62A9DF;
	color: #fff;
}

 nav ul li.sfHover ul a, nav ul ul {
	background: #3892D6;
	color: #fff;
}

nav ul li li a:hover, nav ul li.sfHover li a:hover {
	background: #2A85CB;
}

/*** ESSENTIAL STYLES ***/
.sf-menu, .sf-menu * {
	list-style:		none;
}
.sf-menu {
	line-height:	1.0;
}
.sf-menu ul {
	position:		absolute;
	top:			-999em;
	width:			200px; /* left offset of submenus need to match (see below) */
	margin-top: 	10px;
	padding-top:	0;
}
.sf-menu ul li {
	width:			100%;
}
.sf-menu li:hover {
	visibility:		inherit; /* fixes IE7 'sticky bug' */
}
.sf-menu li {
	float:			left;
	position:		relative;
}
.sf-menu a {
	display:		block;
	position:		relative;
}
.sf-menu li:hover ul,
.sf-menu li.sfHover ul {
	left:			0;
	top:			26px; /* match top ul list item height */
	z-index:		99;
}
ul.sf-menu li:hover li ul,
ul.sf-menu li.sfHover li ul {
	top:			-999em;
}
ul.sf-menu li li:hover ul,
ul.sf-menu li li.sfHover ul {
	left:			200px; /* match ul width */
	top:			0;
}
ul.sf-menu li li:hover li ul,
ul.sf-menu li li.sfHover li ul {
	top:			-999em;
}
ul.sf-menu li li li:hover ul,
ul.sf-menu li li li.sfHover ul {
	left:			10em; /* match ul width */
	top:			0;
}


/* front page slider styles */
div#jFlowSlide {
	margin:0 auto;
}
div#slides-static {
	padding: 40px 55px 0;
	height:auto;
}
div.slides-container {
	height: 271px;
	overflow: hidden; 
	padding: 20px 20px 30px;
}
div.slides-container div#jFlowSlide {
	height: 315px;
	margin: 0 50px;
}

div.static-slide div { 
	margin: 0 25px; 
}

div.slides-container div.jFlowSlideContainer {
}

span.jFlowPrev, span.jFlowNext {
	background-image:url('images/slide-prev.gif');
	background-repeat:no-repeat;
	display:block;
	height:41px;
	width:24px;
	float:left;
	margin:0;
	cursor:pointer;
}
span.jFlowPrev span, span.jFlowNext span { display:none; }
span.jFlowNext {
	background-image:url('images/slide-next.gif');
	float:right;
}
div.slides-container div.controls {
	position:relative;
	top:-220px;
	margin:0 auto;
}
div.slides-container p {
	padding-top: 10px;
	font-size: 1.2em;
	color: #eee;
}
div.slides-container a {
	color: #eee;
}
div.slides-container h2, div#sub-header h2 {
	color: #eee;
	text-shadow: 2px 2px #000;
	font-weight: bold;
}
div.slide-text {
	padding-top: 10px;
}
a.button-slider {
	padding: 15px 20px;
	font-size: 1.2em;
	text-align: center;
	box-shadow: 2px 2px 1px #000;
}

}
.hidden { display:none;  }

img {
	max-width: 100%;
	height: auto;
}

#body {
	background: none;
	margin: 5px auto 0;
 	padding: 0;
	clear: both;
}

#content {
    float: left;
}

.two-column {
	width: 66%;
}

.three-column {
	width: 46%;
	margin: 0 2%;
}

.with-right-sidebar {
	margin-right: 2%;
}

.with-left-sidebar {
	margin-left: 2%;
}


article {
    padding: 10px 10px 20px 5px;
 }

article h2 {
    padding-bottom: 0;
}

article .article-info {
    color: #c0c0c0;
    font-size: 0.9em;
    letter-spacing: -0.5px;
    padding: 0 0 10px 0;
}

article .article-info a { 
	color: #c0c0c0;
	border-bottom-color: #c0c0c0;
}

.sidebar {
	margin-top: 10px;
}

.small-sidebar { 
   width: 25%;
}

.big-sidebar {
	width: 30%;
}

.left-sidebar { 
	float: left;
}

.right-sidebar {
	float: right;
}



.sidebar h4 {
	padding-bottom: 0;
	font-size: 1.4em;
	color: #333;
	letter-spacing: -1px;
	padding: 6px 0;
}

.sidebar ul {
	margin: 0;
	padding: 0;
	list-style: none;
}

.sidebar ul li {
	margin-bottom: 20px;
	line-height: 1.9em;
	padding: 10px;
}

.sidebar ul li.bg {
	background-color: #f0f0f0;
}

.sidebar li ul {
    list-style: none outside none;
    margin: 0px;
}

.sidebar li ul li {
	display: block;
	border-top: none;
	padding: 7px 2px;
	margin: 0;
	line-height: 1.5em;
	font-size: 0.85em;
}

.sidebar li ul li ul {
	margin-top: 10px;
}

.sidebar li ul li li  {
	font-size: 1.0em;
	padding-left: 15px;
}



.sidebar li ul li.text { 
	border-bottom: none;
}



.sidebar li ul li a {
	 border-bottom-color: #666;
	color: #666;
}

.sidebar li ul li a:hover {
	 border-bottom-color: #4A9CDA;
	color: #4A9CDA;
}


.sidebar li ul li a.readmore {
   font-weight: bold;
}


.sidebar ul.blocklist {
	border-top: 1px solid #ddd;
}

.sidebar ul.blocklist li {
	padding: 0;
}

.sidebar ul.blocklist li a,
.sidebar ul.blocklist li a:hover {
	border-bottom: 0;
	display: block;
	border-bottom: 1px solid #ddd;
	padding: 12px 10px;
}

.sidebar ul.blocklist li a.selected {
	background: linear-gradient(#78B5E3, #3892D6);
	background-color: #62A9DF;
    color: #FFFFFF;
	border-bottom-color: #2577B6;
	font-weight: bold;

}
.sidebar li ul.blocklist li li {
	font-size: 1.0em;
}

.sidebar li ul.blocklist ul {
	margin-top: 0;
}

.sidebar li ul.blocklist li li a,
.sidebar li ul.blocklist li li a:hover {
	padding-left: 25px;
}

.sidebar ul.newslist li {
	padding: 20px 5px;
	border-bottom: 1px solid #ddd;
}

.sidebar ul.newslist p {
	margin-bottom: 0;
}

.sidebar ul.newslist span.newslist-date { 
	background-color: #3892D6;
	border-bottom: 1px solid #2577B6;
	color: #fff;
	padding: 5px 10px;
}




.clear {
	clear: both;
}

footer {
	margin:20px auto 0;
	background: #222;
	border-top: 2px solid #eee;
}

footer p {
	text-align: left;
	color: #ccc;
	font-size: 0.9em;
	margin: 0;
	padding: 0;
}

footer p a {
	color: #ccc;
	font-weight: bold;
}

.footer-content {
	padding: 20px 25px 30px;
}

footer .footer-content ul {
	width: 25%;
	list-style: none;
	margin: 0;
	padding: 0;
	float: left;
}

footer .footer-content li {
	padding: 5px 5px;
}

footer .footer-content li a, footer .footer-content h4 {
}

footer .footer-content li a {
 color: #505050;
	border-bottom-color:#505050;
    
}

footer .footer-content li {
 color: #505050;
	line-height: 1.5em;
font-size: 0.95em;
}

footer .footer-content li a:hover { 
	color: #909090;

	border-bottom-color:#909090;
}

footer .footer-content h4 {
   color: #ddd;
    font-size: 1.6em;
    font-weight: bold;
    padding-bottom: 10px;
}

footer .footer-bottom {
	padding: 10px;
	text-align: center;
	background-color: #000;
}

footer .footer-bottom p {
	text-align: center;
}

footer .footer-bottom p, footer .footer-bottom p a {
	color: #666;
	border-bottom-color: #666;
}



@media screen and (max-width: 740px) {

	body { font-size: 0.8em; }	

	header h1 a, header h1 a:hover { padding: 5px; }

	div#container { width: auto; }

	footer .footer-content ul { margin-bottom: 15px; }

	footer .footer-content ul.endfooter { margin-bottom: 0px; }

	.width { width:auto; padding-left: 10px; padding-right: 10px; }
	
	#content, aside.sidebar { float: none; width: auto; }

	footer .footer-content ul { width: auto; float: none; }
}


@media screen and (max-width: 540px) {


	body { font-size: 0.8em; }

	header { text-align: center; }

	header h1 a, header h1 a:hover { text-align: center;  padding: 10px; font-size: 1.1em; }

	header h1, nav { float: none; }
	
	nav { height: auto; position: relative; }

	nav ul li { margin: 5px; }

	nav ul li li { margin: 0; }

	.sf-menu li:hover ul, .sf-menu li.sfHover ul { top: 22px; }

	div.slides-container p { font-size: 0.9em; }
	
	div.slides-container h2 { font-size: 1.8em; }

	div.slides-container { height: 200px; }

}

@media screen and (max-width: 350px) {
	div.slides-container { height: 275px; }
