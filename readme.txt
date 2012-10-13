60082437, no kyoung jae

main.css
html{
	color:#000; 
	background:#888; 
	padding:20px; 
	font:"맑은고딕","바탕","굴림";
}
#wrap{
	width:960px; 
	margin:0 auto; 
	background-color:#888
}

/*-- top --*/
#top{
	width:950px; 
	color:#eee; 
	padding:0 10px 15px 0; 
	text-align:right; 
	font-weight: bold; 
	font-size: 11px;
}
#top a {color:#eee; text-decoration: none; padding: 5px;}
#top a:hover{background-color: yellow;}

/*-- header--*/
#header {
	width:100%; 
	height:120px; 
	background-color: #03497d;
}

#header_top {height:100px;}

#header_left{ 
	width:500px; 
	float:left; 
	display:inline; 
	color: #FFF; 
	padding:10px; 
	height: 80px;
}
#header_right{ 
	width: 400px; 
	float:right; 
	text-align: right; 
	display:inline; 
	padding: 40px 30px 0 0;
}
#line{
	width:960px; 
	height: 5px; 
	background-color: #94c713;
}

/*--search--*/
#search{
	background: #fff; 
	border: 1px; 
	width: 280px; 
	font-size: 14px;
	line-height: 24px;
	height: 24px; 
	padding-left: 22px; 
	vertical-align: middle;
}

/*--content--*/
#content{ 
	background: #fff; 
	overflow: auto; 
	padding:0;
}
#main_content{
	width:700px; 
	float: left; 
	padding: 10px; 
	background: #fff;
}

#sub_content{
	width:700px; 
	float: right; padding:0; 
	background-color: #ddd; 
	height: 100%;
}

/*--navigation--*/
#navbar{
	width:960;
	height: 30px;
	background-color: #03497d;
}
#navbar ul{ margin: 10px; padding: 0;}
#navbar ul li {float: left;}
#navbar ul li a{
	color: #fff;
	background-color: #4682b4;
	display: block;
	width: 100px;
	text-align: center;
	padding: 0px 10px;
	font: bold 12px/30px Tahoma;
	text-decoration: none;
	margin-right: 1px;
}
#navbar ul li a.selected { background-color: #94c713;}
#navbar ul li a:hover { background-color: #709647;}

/*--footer--*/
#footer{
	background-color: #d5dde2; 
	color:#888; 
	text-align: center; 
	padding: 20px;
}

/*--section--*/
#main_content div.section_2, #main_content div.section_1{
	width:700px; 
	margin-bottom: 20px; 
	border:1px solid #d7e9f9; 
	border-radius: 5px; 
	overflow: auto;
}
#main_content div.section_3 h1, #main_content div.section_1 h1{
	width: 650px;
	padding: 4px 6px 4px 44px;
	background: #d7e9f9;
	border-radius: 5px 5px 0 0;
}
#main_content div.section_3 li {
	width: 220px;
	display: block;
	float: left;
	margin: 5px;
}
div.section_3 li img{ float: left;}

#main_content div.section_1 li{
	width: 690px;
	display: block;
	float: left;
	margin: 5px;
}
div.section_1 li img{ float: left;}