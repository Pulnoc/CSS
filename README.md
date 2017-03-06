/*
Mono What.CD Stylesheet

Author:  Callum Jefferies (callumj)
Contact: callum.jefferies@gmail.com
Date:    23/01/2011

All icons Copyright (c) Callum Jefferies 2011
*/

* {
	margin: 0;
	padding: 0;
}

body {
	padding: 79px 20px 60px 20px;
	background: #eee !important;
	font: 9pt/14pt 'Lucida Grande', Helvetica, Arial, sans-serif;
}

table {
	border-collapse: collapse;
	border-spacing: 0;
}

a {
	text-decoration: none;
	color: #3b7ab0;
}

a img {
	border: none;
}

a:hover {
	color: #448cc8;
}

h1,h2,h3 {
	font-family: Helvetica, Arial, sans-serif;
	font-weight: bold;
	color: #444 !important;
}

h2 {
	margin-bottom: 20px;
	font-size: 16pt;
	line-height: 16pt;
}

h3 {
	margin-bottom: 10px;
	font-size: 14pt;
	line-height: 14pt;
}

#logo a {
	position: absolute;
	top: -41px;
	left: 6px;
	width: 241px;
	height: 32px;
}

#wrapper {
	width: 960px;
	margin: 0 auto;
}

#header {
	width: 960px;
	margin: 0 auto;
}

#header ul li {
	display: inline;
	margin-right: 10px;
}

#header ul li:last-child {
	margin-right: 0;
}

#footer {
	width: 960px;
	margin: 0 auto;
	margin-top: 20px;
	padding-top: 20px;
	text-align: center;
	border-top: 2px solid #ddd;
	color: #666;
}

.r00 {color: #F00;}
.r01 {color: #FF1300;}
.r02 {color: #FF1300;}
.r03 {color: #FF2600;}
.r04 {color: #FF4C00;}
.r05 {color: #FF5E00;}
.r06 {color: #FF5E00;}
.r07 {color: #FF7100;}
.r08 {color: #fd4337;}
.r09 {color: #FA0;}
.r10 {color: #74C42E;}
.r20 {color: #418B00;}
.r50 {color: #418B00;}
.r99 {color: #418B00;}

.size1 { font-size: 0.75em; line-height: normal; }
.size2 { font-size: 1em; line-height: normal; }
.size3 { font-size: 1.25em; line-height: normal; }
.size4 { font-size: 1.5em; line-height: normal; }
.size5 { font-size: 1.75em; line-height: normal; }
.size6 { font-size: 2em; line-height: normal; }
.size7 { font-size: 2.25em; line-height: normal; }
.size8 { font-size: 2.5em; line-height: normal; }
.size9 { font-size: 2.75em; line-height: normal; }
.size10 { font-size: 3em; line-height: normal; }

#discog_table.torrent_table .colhead_dark td:nth-child(4) {
	width: 15%;
}

#userinfo_username {
	position: absolute;
	top: -130px;
	right: 0;
	-webkit-border-bottom-left-radius: 5px;
	-moz-border-radius-bottomleft: 5px;
	border-radius-bottomleft: 5px;
	-webkit-border-bottom-right-radius: 5px;
	-moz-border-radius-bottomright: 5px;
	border-radius-bottomright: 5px;
	padding: 15px 8px 15px 15px;
	background: #ddd !important;
}

#alerts {
	position: absolute;
	top: -100px;
}

#searchbars,#userinfo_stats {
	margin-top: 55px;
}

#userinfo_major,#userinfo_minor {
	position: absolute;
	padding: 10px 15px;
	-webkit-box-sizing: border-box;
	-moz-box-sizing: border-box;
}

#userinfo_minor {
	width: 100%;
	left: 0;
	z-index: 0;
	-webkit-border-bottom-left-radius: 4px;
	-webkit-border-bottom-right-radius: 4px;
	-moz-border-radius-bottomleft: 4px;
	-moz-border-radius-bottomright: 4px;
	border-radius-bottomleft: 4px;
	border-radius-bottomright: 4px;
	background: #f4f4f4;
}

#userinfo_major {
	width: 265px;
	right: 0;
	z-index: 1;
	text-align: right;
}

#userinfo_major a,#userinfo_minor a {
	color: #777;
}

#userinfo_major a:hover,#userinfo_minor a:hover {
	color: #444;
}

#userinfo_major a {
	font-size: 13px;
	color: #666;
}

/* #searchbars ul li:nth-child(3),#searchbars ul li:nth-child(5) {
	display: none;
} */

h1.hidden {
	width: 940px;
	margin: 0 auto;
	padding: 15px 10px;
	display: block;
	text-transform: lowercase;
	color: #2a2a2a;
	font-family: Helvetica;
	font-size: 18pt;
	border-bottom: 2px solid #dfdfdf;
}

#header {
	position: relative;
	height: 112px;
	margin-bottom: 40px;
}

#userinfo_stats {
	position: relative;
	float: right;
	width: 217px;
	height: 62px;
	padding: 10px 14px;
	-webkit-border-radius: 4px;
	-moz-border-radius: 4px;
	border-radius: 4px;
	background: #5e5e5e;
	color: #fff;
}

#userinfo_stats li {
	display: block !important;
	position: absolute;
	width: 117px;/*Sasha edit: 105 to 117 to accommodate stat change script spacing*/
	border-bottom: 1px solid #777;
	font-size: 7.5pt;
}

#userinfo_stats span {
	color: #fff !important;
}

#userinfo_stats li:last-child {
	border: none !important;
}

#stats_leeching,#stats_required {
	top: 32px;
}

#stats_ratio,#stats_required {
	left: 128px;
}

#fl_tokens {
	top: 5.4em;
	left: 128px;
}

#userinfo_stats {
	font-weight: bold;
}

#userinfo_stats .stat {
	font-weight: normal;
}

#userinfo_stats a {
	color: #f4f4f4;
}

#discog_table.torrent_table .colhead_dark td:first-child {
	width: 50px !important;
}

button,
input[type="button"],
input[type="submit"],
#userinfo_username .brackets a {
	cursor: pointer;
	padding: 6px 8px;
	font: 12pt Helvetica,Arial,sans-serif;
	text-decoration: none;
	text-transform: lowercase;
	color: #fff;
	text-shadow: 0 1px 0 rgba(0,0,0,0.15);
	-webkit-border-radius: 4px;
	-moz-border-radius: 4px;
	border-radius: 4px;
	-webkit-box-shadow: 0 1px 2px rgba(0,0,0,0.15),inset -1px 1px 0 rgba(255,255,255,0.18);
	-moz-box-shadow: 0 1px 2px rgba(0,0,0,0.15),inset -1px 1px 0 rgba(255,255,255,0.18);
	background: -webkit-gradient(linear,left 40%,left 120%,from(#5f5f5f),to(#575757));
	background: -moz-linear-gradient(center bottom,#575757,#5f5f5f);
	border: 1px solid #4d4d4d;
}

button:active,
input[type="button"]:active,
input[type="submit"]:active,
#userinfo_username .brackets a:active {
	background: -webkit-gradient(linear,left 40%,left 120%,from(#575757),to(#5f5f5f));
	background: -moz-linear-gradient(center bottom,#5f5f5f,#575757);
}

#userinfo_username a {
	font-size: 11pt;
	color: #555;
}

#userinfo_username .brackets {
	margin: -2px;
}

#userinfo_username .brackets a {
	-webkit-border-top-right-radius: 0;
	-moz-border-radius-topright: 0;
	border-top-right-radius: 0;
	-webkit-border-bottom-right-radius: 0;
	-moz-border-radius-bottomright: 0;
	border-bottom-right-radius: 0;
}

#userinfo_username .brackets:last-child a {
	border-left: none;
	-webkit-border-top-right-radius: 4px;
	-moz-border-radius-topright: 4px;
	border-top-right-radius: 4px;
	-webkit-border-bottom-right-radius: 4px;
	-moz-border-radius-bottomright: 4px;
	border-bottom-right-radius: 4px;
	-webkit-border-top-left-radius: 0;
	-moz-border-radius-topleft: 0;
	border-top-left-radius: 0;
	-webkit-border-bottom-left-radius: 0;
	-moz-border-radius-bottomleft: 0;
	border-bottom-left-radius: 0;
}

input[type="submit"]:active {
	-webkit-box-shadow: 0 1px 2px rgba(0,0,0,0.15),inset 0 0 5px rgba(0,0,0,0.02),inset -1px 1px 0 rgba(255,255,255,0.12);
	-moz-box-shadow: 0 1px 2px rgba(0,0,0,0.15),inset 0 0 5px rgba(0,0,0,0.02),inset -1px 1px 0 rgba(255,255,255,0.12);
}

a,textarea,input {
	outline: none;
}

form textarea,form input {
	max-width: 80%;
}

form#quickpostform textarea {
	height: 160px;
	margin: 0 auto;
}

div.thin br+h3,
div.thin > h3:first-child {
	margin: 0 0 15px 15px;
}

textarea,
input[type="text"],
input[type="email"],
input[type="search"],
input[type="password"],
.select {
	width: 195px;
	padding: 8px;
	background: #fff;
	-webkit-border-radius: 4px;
	-moz-border-radius: 4px;
	border-radius: 4px;
	border: 1px solid #adadad;
	font: 12pt 'Lucida Grande',Helvetica,Arial,sans-serif;
	color: #444;
	-webkit-box-shadow: inset -1px 1px 3px rgba(0,0,0,0.15);
	-moz-box-shadow: inset -1px 1px 3px rgba(0,0,0,0.15);
	-webkit-background-clip: padding-box;
}

textarea:focus,
input[type="text"]:focus,
input[type="email"]:focus,
input[type="search"]:focus,
input[type="password"]:focus {
	-webkit-box-shadow: inset -1px 1px 3px rgba(0,0,0,0.15),0 0 5px rgba(0,140,180,0.5);
	-moz-box-shadow: inset -1px 1px 3px rgba(0,0,0,0.15),0 0 5px rgba(0,140,180,0.5);
}

textarea {
	resize: none;
	display: block;
	width: 550px;
	height: 120px;
	font-size: 10pt;
}

.sidebar input[type="text"],
.sidebar input[type="email"],
.sidebar input[type="search"],
.sidebar textarea {
	width: 202px;
}

.sidebar select,.sidebar input {
	margin-bottom: 10px;
}

.sidebar ol {
	margin-left: 20px;
}

#content,.thin {
	/*overflow: hidden;*/
	clear: both;
}

#content:after,
.thin:after {
	visibility: hidden;
	display: block;
	font-size: 0;
	content: " ";
	clear: both;
	height: 0;
}

#searchbars {
	float: left;
	width: 667px;
	padding: 15px;
	background: #e4e4e4;
	-webkit-border-radius: 6px;
	-moz-border-radius: 6px;
	border-radius: 6px;
}

#searchbars input {
	width: 92px;
	padding: 5px;
	font-size: 9pt;
	color: #555;
}

#searchbars ul,#searchbars form {
	display: flex;
}

#menu {
	position: absolute;
	top: -35px;
	right: -5px;
}

#menu a {
	color: #4e4e4e;
}

#menu ul {
	width: 665px;
}

#menu ul li {
	padding-right: 15px;
	border-right: 1px solid #ccc;
}

#menu ul li:last-child {
	margin-right: 0;
	padding-right: 0;
	border-right: none;
}

#content {
	width: 960px;
	margin: 0 auto !important;
	/*overflow: hidden;*/
}

#content .main_column,#content .sidebar {
	position: relative;
}

#content .main_column {
	float: left;
	width: 695px;
}

#content .sidebar {
	float: right;
	width: 245px;
}

ul.collage_images {
	width: 700px !important;
}

ul.collage_images li {
	height: 135px !important;
	width: 135px !important;
}

ul.collage_images li a {
	height: 135px !important;
	width: 135px !important;
}

ul.collage_images li a img {
	height: 135px !important;
	width: 135px !important;
}

ul.collage_images li a:hover {
	position: relative;
	overflow: visible !important;
}

ul.collage_images li a:hover img {
	position: absolute;
	margin: -80px;
	z-index: 4;
	width: 300px !important;
	height: 300px !important;
}

#collages,#personal_collages,#collage_table,.forum_index,.torrent_table,.forum_post.box,.recent,table.border,.torrent_table.grouping,#userhistory table {
	width: 100% !important;
}

table[width="100%"],.box,.box2,.torrent_table,#log_table,#request_table,#collages,.forum_index,table.border,.linkbox+table,form#messageform table ,.main_column table ,form[action="user.php"] table,table.staff,#userhistory table {
	margin-bottom: 20px;
	padding: 10px;
	background: #fff;
	border: 1px solid #aeaeae;
	-webkit-box-shadow: 0 2px 3px rgba(0,0,0,0.1);
	-moz-box-shadow: 0 2px 3px rgba(0,0,0,0.1);
	color: #565656;
}

.search_form .box {
	margin-bottom: 0;
	background: inherit;
	border: 0;
	padding: 0;
	-webkit-box-shadow: none;
	-moz-box-shadow: none;
}

.box.pad {
	padding: 0 !important;
	background: transparent;
	border: none;
	-webkit-box-shadow: none;
	-moz-box-shadow: none;
}

.head,.colhead td,.recent .colhead td,.colhead th,.colhead_dark td {
	margin: -11px;
	margin-bottom: 10px;
	padding: 8px !important;
	background: -webkit-gradient(linear,left top,left bottom,from(#ddd),to(#ccc));
	background: -moz-linear-gradient(center bottom,#ccc,#ddd);
	border: 1px solid #aeaeae !important;
	border-bottom-color: #bbb !important;
	-webkit-box-shadow: inset 0 1px 0 rgba(255,255,255,0.4);
	-moz-box-shadow: inset 0 1px 0 rgba(255,255,255,0.4);
	font: bold 10pt Helvetica,Arial,sans-serif !important;
	color: #575757 !important;
	text-shadow: 0 1px 0 rgba(255,255,255,0.5);
}

table[width="100%"] td,.torrent_table td,#requests td,#collages td,.forum_index td,table.border td,.linkbox+table td,form#messageform table td,form[action="user.php"] table td,table.staff td.nobr,#inbox form table td {
	padding: 8px;
	border: 1px solid #ccc;
	border-bottom: none;
}

table[width="100%"] .colhead td,table[width="100%"] .colhead_dark td,.torrent_table .colhead_dark td,#requests .colhead_dark td,#collages .colhead td,.forum_index .colhead td,#torrent_table .colhead td,table.border .colhead td,.linkbox+table .colhead td,form#messageform .colhead table td,#inbox form table .colhead td {
	border: 1px solid #aeaeae !important;
}

#bookmarks .torrent_table .colhead_dark td:nth-child(3) {
	width: 60%;
}

#bookmarks .torrent_table .colhead_dark td:first-child, #bookmarks .torrent_table .colhead_dark td:nth-child(2) {
	width: 5%;
}
/*
.torrent_table .colhead_dark td:first-child {
	width: 70%;
}
*/
table[width="100%"] td:first-child,.torrent_table td:first-child,#requests td:first-child,#collages td:first-child,.forum_index td:first-child,#torrent_table td:first-child,table.border td:first-child,.linkbox+table td:first-child,form#messageform table td:first-child,#inbox form table td:first-child {
	border-left: 1px solid #aeaeae;
}

table[width="100%"] td:last-child,.torrent_table td:last-child,#requests td:last-child,#collages td:last-child,.forum_index td:last-child,#torrent_table td:last-child,table.border td:last-child,.linkbox+table td:last-child,form#messageform table td:last-child,#inbox form table td:last-child {
	border-right: 1px solid #aeaeae;
}

#inbox form table tr:last-child td {
	border-bottom: 1px solid #aeaeae !important;
}

#inbox form table td:first-child {
	border-left: 1px solid #aeaeae !important;
}

#inbox form table td:last-child {
	border-right: 1px solid #aeaeae !important;
}

.torrent_table.sign {
	text-align: center;
}

table.staff td.nobr {
	border-right: 1px solid #ccc !important;
}

table.staff td.nobr:last-child {
	border-right: 1px solid #aeaeae !important;
}

.torrent_table .group {
	background: -webkit-gradient(linear,left top,left bottom,from(#f3f3f3),to(#eee));
	background: -moz-linear-gradient(center bottom,#eee,#f3f3f3);
}

.torrent_table .group strong {
	font-size: 12pt;
}

.torrent_table .group strong a {
	color: #444;
}

.recent {
	margin-bottom: 20px !important;
	padding: 0;
	-webkit-box-shadow: 0 2px 3px rgba(0,0,0,0.1);
	-moz-box-shadow: 0 2px 3px rgba(0,0,0,0.1);
}

.recent td {
	padding: 10px;
	background: #fff;
	border: 1px solid #aeaeae;
	border-right: 1px solid #ccc;
	border-left: none;
	border-top: none;
	word-break: break-all;
}

.recent td:first-child {
	border-left: 1px solid #aeaeae;
}

.recent td:last-child {
	border-right: 1px solid #aeaeae;
}

.recent td img {
	width: 118px;
	height: 118px;
}

.cats_col {
	width: 25px;
}

.cats_music,.cats_comics,.cats_audiobooks,.cats_elearningvideos,.cats_comedy,.cats_applications,.cats_ebooks {
	width: 25px !important;
	height: 25px !important;
	margin: 0 !important;
}

.cats_music {
	background: url('https://ptpimg.me/kucx34.png'); /* music.png */
}

.cats_comics {
	background: url('https://ptpimg.me/s9g3f4.png'); /* comics.png */
}

.cats_audiobooks {
	background: url('https://ptpimg.me/89f40q.png'); /* audiobooks.png */
}

.cats_elearningvideos {
	background: url('https://ptpimg.me/rtkqt7.png'); /* elearning.png */
}

.cats_comedy {
	background: url('https://ptpimg.me/4tc69u.png'); /* comedy.png */
}

.cats_applications {
	background: url('https://ptpimg.me/jpz392.png'); /* applications.png */
}

.cats_ebooks {
	background: url('https://ptpimg.me/ur96f4.png'); /* ebooks.png */
}

body#index #recommended .head {
	margin-bottom: -11px !important;
	border-bottom-color: #aeaeae !important;
}

body#index #recommended #vanityhouse {
	margin-top: 21px;
	margin-bottom: 0px;
	width: 100%;
}

.hide_torrents a,.show_torrents a {
	display: block;
	width: 25px;
	height: 25px;
	background-image: url('https://ptpimg.me/xt7xf9.png'); /* show-hide.png */
	background-repeat: no-repeat;
}

.hide_torrents a {
	background-position: center top;
}

.show_torrents a {
	background-position: center bottom;
}

#torrent_table .colhead td[width="100%"] {
	width: 50% !important;
}

#discog_table .box.center {
	background: #f8f8f8;
	border: none;
	padding: 10px;
	text-align: center;
	-webkit-box-shadow: none;
	-moz-box-shadow: none;
	-webkit-border-radius: 5px;
	-moz-border-radius: 5px;
	border-radius: 5px;
}

#discog_table .box.center a {
	color: #666;
	font-weight: bold;
	margin-right: 5px;
	line-height: 18pt;
}

.group_torrent td span {
	float: right;
}

.linkbox {
	margin-bottom: 20px;
	text-align: center;
}

.linkbox.notify_filter_links {
	margin-bottom: 5px;
}

.head a {
	color: #3e3e3e;
}

.main_column .box {
	width: 675px;
}

.main_column .head {
	width: 679px;
}

.sidebar .box {
	width: 220px;
}

.sidebar .head {
	width: 224px;
}

.sidebar .box ul li {
	list-style: none;
}

td.unread,td.read,td.read_locked,td.unread_sticky,td.read_locked_sticky,td.unread_locked_sticky,td.read_sticky {
	width: 3.5%;
	background-repeat: no-repeat;
	background-position: center center;
}

td.unread {
	background-image: url('https://ptpimg.me/dmzsgr.png'); /* unread.png */
}

td.read {
	background-image: url('https://ptpimg.me/19r3o8.png'); /* read.png */
}

td.read_locked {
	background-image: url('https://ptpimg.me/lkb1bc.png'); /* read-locked.png */
}

td.unread_sticky {
	background-image: url('https://ptpimg.me/2d5pzu.png'); /* sticky-unread.png */
}

td.read_sticky {
	background-image: url('https://ptpimg.me/jj31yx.png'); /* sticky-read.png */
}

td.read_locked_sticky {
	background-image: url('https://ptpimg.me/s70yv7.png'); /* sticky-read-locked.png */
}

td.unread_locked_sticky {
	background-image: url('https://ptpimg.me/271sw6.png'); /* sticky-unread-locked.png */
}

table.forum_index tr td:nth-child(3) .last_topic a,td.unread+td >h4 a,td.unread+td >span.last_topic strong a,td.unread_locked+td >span.last_topic strong a,td.unread_sticky+td >span.last_topic strong a,td.unread_locked_sticky+td >span.last_topic strong a {
	color: #626262;
}

td.read+td >h4 a,td.read+td >span.last_topic strong a,td.read_locked+td >span.last_topic strong a,td.read_sticky+td >span.last_topic strong a,td.read_locked_sticky+td >span.last_topic strong a {
	color: #888;
}

span.last_read a {
	display: block;
	width: 12px;
	height: 12px;
	margin: 2px 0 0 5px;
	background: url('https://ptpimg.me/70ll39.png') no-repeat center -4px; /* goto.png */
}

span.last_read a:hover {
	background-position-y: -24px;
}

.forum_post .avatar {
	padding: 10px;
	width: 100px !important;
	background: #f6f6f6;
	border-right: 1px solid #ddd;
}

.forum_post .avatar img {
	width: 120px !important;
}

.forum_post .body {
	padding: 15px;
}

body#forums table.forum_post td.body > div, body#userhistory table.forum_post td.body > div { /* Wide main column (forums, user history) */
	width: 787px;
}

table.forum_post td.body > div { /* Narrow main column (torrent comments, request comments) */
	width: 522px;
}

.forum_post ul,.forum_post ol {
	margin-left: 25px;
}

strong.quoteheader{
	color: #626262;
}

.forum_post blockquote, #inbox div.body>blockquote {
	padding: 10px;
	background: #fafafa url('https://ptpimg.me/29sxun.png') no-repeat 98% 5px; /* quote-mark.png */
	border: 1px solid #ddd;
	-webkit-border-radius: 3px;
	-moz-border-radius: 3px;
	border-radius: 3px;
}

#torrents .filter_torrents .box.pad,#torrents div.thin form.search_form,#requests div.thin form.search_form,#collage div.thin form.search_form,#inbox #searchbox {
	padding: 15px !important;
	background: #e4e4e4;
	border: none;
	-webkit-border-radius: 5px;
	-moz-border-radius: 5px;
	border-radius: 5px;
}

#collage div.thin form table {
	background: none;
	border: none;
	-webkit-box-shadow: none;
	-moz-box-shadow: none;
}

#requests form.search_form table:nth-child(6) td {
	padding-top: 13px !important;
	padding: 13px 0 0 0 !important;
	border-bottom: 0 !important;
}

#torrents form.search_form div.submit,#collage div.thin form div.submit {
	padding-top: 13px;
}

div.thin .header+form,div.thin .header+div>form,div.thin .header+.linkbox+div {
	margin-bottom: 20px;
}

div.thin form.search_form table,div.thin .header+.linkbox+div table,.filter_torrents table {
	width: 100%;
}

div.thin .header+.linkbox+div table {
	border: none;
	background: none;
	-webkit-box-shadow: none;
	-moz-box-shadow: none;
}

div.thin form.search_form table td, div.thin .header+.linkbox+div table td,.filter_torrents table td {
	padding: 10px 0;
	border: none !important;
	border-bottom: 1px solid #d1d1d1 !important;
}

div.thin .header+.linkbox+div td {
	padding-left: 10px !important;
}

td.label {
	font-size: 10pt;
}

#torrents .filter_torrents .box.pad table:nth-child(1) tr:first-child td,#requests div.thin form.search_form table:nth-child(3) tr:first-child td,#collage div.thin form table:nth-child(2) tr:first-child td {
	padding-top: 0 !important;
}

.filter_torrents table.cat_list td {
	width: 8% !important;
	text-align: center !important;
}

.filter_torrents table:nth-child(2) td {
	padding: 17px 0 15px 0 !important;
	background: #e0e0e0;
}

.filter_torrents .cat_list[width="100%"] {
	background: #e4e4e4;
	border: none;
	-webkit-box-shadow: none;
	-moz-box-shadow: none;
}

div.thin form.search_form table td.label,.filter_torrents table td:first-child {
	width: 20%;
	padding-right: 10px;
	text-align: right;
}

.filter_torrents .submit {
	position: relative;
	padding-top: 15px;
}

.filter_torrents .submit input[value="Reset"] {
	display: none;
}

.filter_torrents .submit span {
	position: absolute;
	left: 120px;
	font-size: 12pt;
	color: #444;
	line-height: 24pt;
}

.filter_torrents .submit span:before {
	content: "(";
}

.filter_torrents .submit span:after {
	content: ")";
}

.filter_torrents .submit input[name="setdefault"],.filter_torrents .submit input[name="cleardefault"] {
	float: right;
	margin-left: 8px;
}

.filter_torrents .cat_list {
	border: none !important;
}

ul#artistcomplete {
	position: absolute;
	left: 185px;
	top: 98px;
	z-index: 1;
	list-style: decimal;
	-webkit-border-radius: 4px;
	-moz-border-radius: 4px;
	border-radius: 4px;
	-webkit-box-shadow: 0 1px 2px rgba(0,0,0,0.1);
	-moz-box-shadow: 0 1px 2px rgba(0,0,0,0.1);
	box-shadow: 0 1px 2px rgba(0,0,0,0.1);
	border: 1px solid #bbb;
	background: #fff;
	color: #444;
}

#artistcomplete li:first-child {
	-webkit-border-top-left-radius: 4px;
	-moz-border-radius-topleft: 4px;
	border-top-left-radius: 4px;
	-webkit-border-top-right-radius: 4px;
	-moz-border-radius-topright: 4px;
	border-top-right-radius: 4px;
}

#artistcomplete li:last-child {
	-webkit-border-bottom-left-radius: 4px;
	-moz-border-radius-bottomleft: 4px;
	border-bottom-left-radius: 4px;
	-webkit-border-bottom-right-radius: 4px;
	-moz-border-radius-bottomright: 4px;
	border-bottom-right-radius: 4px;
}

#artistcomplete li {
	display: block !important;
	-webkit-box-sizing: border-box;
	padding: 5px 10px;
}

#artistcomplete li.highlight {
	background: #f5f5f5;
	width: 100%;
}

#lightbox {
	z-index: 1;
	position: fixed;
	top: 10%;
	left: 50%;
	width: 800px;
	height: 80%;
	margin-left: -400px;
	text-align: center;
}

#lightbox img {
	max-width: 800px;
	max-height: 100%;
	padding: 10px;
	background: #fff;
	-webkit-box-shadow: 0 2px 5px #222;
	-moz-box-shadow: 0 2px 5px #222;
}

#curtain {
	z-index: 0;
	position: fixed;
	top: 0;
	left: 0;
	width: 100%;
	height: 100%;
	background: rgba(0,0,0,0.75);
}

#torrents h2+div.linkbox+h3+table.border >tbody >tr td:nth-child(2) {
	width: 55% !important;
}

form[action="user.php"] table textarea,
form[action="user.php"] table input[type="text"],
form[action="user.php"] table input[type="email"],
form[action="user.php"] table input[type="search"] {
	-webkit-box-sizing: border-box;
	-moz-box-sizing: border-box;
}

h3#irc+div.box.pad,body#rules .header+div.box.pad,h3#forums+div.box.pad {
	padding: 30px !important;
	background: #f8f8f8;
	-webkit-border-radius: 5px;
	-moz-border-radius: 5px;
	border-radius: 5px;
}

h3#irc+div.box.pad ul,h3#forums+div.box.pad ul,body#rules .header+div.box.pad ul,#drag_drop_textnote ul {
	list-style: none;
}

h3#irc+div.box.pad ul li,h3#forums+div.box.pad ul li,body#rules .header+div.box.pad ul li,#drag_drop_textnote ul li {
	margin-bottom: 8px;
	padding-bottom: 8px;
	border-bottom: 1px solid #ddd;
}

h3#irc+div.box.pad ul li:last-child,h3#forums+div.box.pad ul li:last-child,body#rules .header+div.box.pad ul li:last-child,#drag_drop_textnote ul li:last-child {
	margin-bottom: 0;
	padding-bottom: 0;
	border-bottom: none;
}

table.border[width="100%"] {
	margin-bottom: 0;
}

#collage form > table.border[width="100%"] tbody tr:nth-child(5) td {
	padding-bottom: 0;
	border-bottom: none !important;
}

#threadpoll p {
	margin-bottom: 20px;
	font-size: 16px;
}

ul.nobullet {
	list-style-type: none;

}

li.graph {
	width: 100%;
	height: 20px;
	margin-bottom: 10px;
	padding: 5px;
	background: #f4f4f4;
	-webkit-border-radius: 8px;
	-moz-border-radius: 8px;
	border-radius: 8px;
	-webkit-box-sizing: border-box;
	-moz-box-sizing: border-box;
}

li.graph .center_poll {
	display: block;
	height: 8px;
	background: #666;
	border: 1px solid #5a5a5a;
	-webkit-border-radius: 5px;
	-moz-border-radius: 5px;
	border-radius: 5px;
	-webkit-box-shadow: inset 0 -2px 3px #555;
	-moz-box-shadow: inset 0 -2px 3px #555;
}

#index .graph .center_poll {
	margin-top: 0;
}

#inbox form table {
	margin-top: 20px;
}

#inbox form table td {
	border: 1px solid #ccc !important;
}

#inbox form table td:nth-child(1) {
	width: 3%;
}

#inbox form table td:nth-child(3) {
	width: 15%;
}

#inbox form table td:nth-child(4) {
	width: 20%;
}

#inbox #searchbox {
	margin-top: -20px;
}

#inbox #searchbox input[type="text"],
#inbox #searchbox input[type="search"] {
	margin-top: 10px;
}

#manage_collage_table input[type="text"],
#manage_collage_table input[type="search"] {
	width: 40px;
}

td {
	border: 1px solid #BBB;
	padding: 5px;
	text-align: left;
}

td.colhead {
	margin: -11px;
	margin-bottom: 10px;
	padding: 8px !important;
	background: -webkit-gradient(linear,left top,left bottom,from(#ddd),to(#ccc));
	background: -moz-linear-gradient(center bottom,#ccc,#ddd);
	border: 1px solid #aeaeae !important;
	border-bottom-color: #bbb !important;
	-webkit-box-shadow: inset 0 1px 0 rgba(255,255,255,0.4);
	-moz-box-shadow: inset 0 1px 0 rgba(255,255,255,0.4);
	font: bold 10pt Helvetica,Arial,sans-serif !important;
	color: #575757 !important;
	text-shadow: 0 1px 0 rgba(255,255,255,0.5);
}

div.permission_container {
	float: left;
	width: 32%;
}

div.permission_container:nth-child(2) {
	padding: 0px 2%;
}

div.permission_container table.layout {
	width: 100%;
}

div.pad ul,div.body ul,table.torrent_table blockquote>ul,div.pad ol,div.body ol,.setting_description ul {
	padding-left: 15px;
}

#debug_report {
	white-space: pre-wrap;
}

table.debug_table td.debug_data {
	padding: 0;
}

table.debug_table td.debug_data>div, table.debug_table td.debug_data>pre {
	overflow: auto;
	padding: 8px;
	max-height: 400px;
}

table.debug_table td.debug_query_data>div {
	width: 796px;
}

.nobr {
	white-space: nowrap;
}

tr.torrent .bookmark > a:before { content:""; }
tr.torrent .bookmark > a:after { content:""; }

/* Fixes by Trico beyond here. All credit for the style sheet goes to callumj */

/* General fixes */
/* Give dropdowns a bit of style */
/*select {
	padding: 7px;
	background: #fff;
	color: #565656;
	border: 1px solid #aeaeae;
}
*/

/* Fix for upload.php, the "Do not upload" section */
#dnulist tr {
	/* Previously unstyled */
	background: #fff;
}

/* Fixes for friends.php */
form.manage_form[name=friends] table tr {
	/* Previously unfinished */
	border: 1px solid #aeaeae !important;
	background: #fff;
}

form.manage_form[name=friends] {
	margin-bottom: 20px;
}

form.manage_form[name=friends] .left input[type=submit] {
	margin-bottom: 10px;
}

/* Fixes for staffpm.php, wiki.php, user.php?action=edit and inbox.php, when composing new message/wiki, and some other stuff */
#compose h3,
[class="create_form"][name=wiki_article] h3,
#messageform #quickpost h3 {
	margin: 20px 0 10px 0;
}

[class="create_form"][name=wiki_article] input[type=submit],
#messageform input[type=submit],
.preview_submit input[type=button],
#newthreadform #buttons input[type=button],
#newthreadform #poll_answers input[type=text] {
	margin-top: 10px;
}

.torrent_table .filelist_table {
	width: 100%;
}

/* Fix for artist.php sidebar layout */
[class="box box_search"] #filelist, [class="box box_addartists box_addartists_similar"] #artistsimilar {
	width: 150px;
}

/* Fix for artist.php artist map margin */
#similar_artist_map {
	margin-top: 20px;
}


/* Fix for requests.php, search section */
[class="layout border"] #search_terms input[name=search] {
	margin-top: 10px;
}

/* Fix for forums.php?action=search, search section */
[class="search_form"] table tr > td > strong {
	padding-left: 10px;
}

/* Fix for wiki.php, sidebar details section */
.sidebar [class="box box_info pad"] > ul {
	/* Previously unstyled */
	margin-bottom: 20px;
	padding: 10px;
	background: #fff;
	border: 1px solid #aeaeae;
	-webkit-box-shadow: 0 2px 3px rgba(0,0,0,0.1);
	-moz-box-shadow: 0 2px 3px rgba(0,0,0,0.1);
	color: #565656;
}

/* Fix for index.php, more news section at the very bottom of the page */
#more_news.box {
	height: 0;
}

/* Fix for forums.php, search specific forum */
.search_form[action="forums.php"] td > strong {
	margin-right: 10px;
}

#userinfo .brackets:before, #userinfo .brackets:after {
	content: "";
}

.linkbox .brackets:before,
.linkbox .brackets:after,
.top10_quantity_links .brackets:before,
.top10_quantity_links .brackets:after {
	color: #444;
}

.group_image + .group_info { margin: 0; padding: 0 5px; display: table-cell; vertical-align: middle; height: 90px; }
#torrents .group_image + .group_info { width: 450px; }
#top10 .group_image + .group_info { width: 585px; }

.field_div {
	margin-bottom: 10px;
}

.edit_changelog textarea {
	width: 600px;
}

div[class~=tooltipster-base] {
	background-color: #FFFFFF;
	border-color: #ABABAB;
	color: #565656;
}

#settings_sections h2 {
	font-size: 12pt;
}

#settings_sections input {
	max-width: 100%;
}

table[width="100%"].user_options {
	margin-bottom: 20px;
}

.user_options .label {
	width: 200px;
}

.user_options .box {
	width: auto;
}

.user_options .textarea_wrap textarea {
	width: 400px;
	max-width: 100%;
}

.forum_post td img {
	max-width: 785px;
}

#collage #reply_box img,
#forums #reply_box img {
	max-width: 787px;
}

#artistcomments #reply_box img,
#request_comments #reply_box img,
#torrent_comments #reply_box img {
	max-width: 520px;
}

#artistcomments img,
#torrent_comments img {
	max-width: 527px;
}

#request_comments img {
	max-width: 539px;
}

#artist_information img,
.box_request_desc img,
.profileinfo img,
.news_post img,
.torrent_description img,
.torrentdetails img,
.wiki_article img {
	max-width: 675px;
}

.blog_post img,
#inbox .body img,
#inbox #preview img,
#wiki .create_form img,
#wiki .edit_form img {
	max-width: 939px;
}

#staff .preview_wrap img,
#staffpm #reply_box img {
	max-width: 938px;
}

#userform img {
	max-width: 438px;
}

#reportsv2 .manage_form img {
	max-width: 646px;
}

/*
Consistent .box and .pad
TODO: Make these rules apply globally and add exceptions where needed
*/
#reportsv2 .pad, #reports .pad, .two_columns.pad { padding: 10px !important; }
#reportsv2 .box, #reports .box { margin-bottom: 10px; background-color: rgb(255,255,255); border: 1px solid #aaa; color: #777; }


/* Randy's Additions */
#userinfo_major { width: 271px; }
#menu ul { width: 620px; }
#menu ul li {
	padding-right: 11px;
	margin-right: 15px;
}
#userinfo_major, #userinfo_minor { padding: 10px 15px 10px 15px; }
#userinfo_stats { height: 60px; }
#userinfo_stats li:last-child { border-bottom: 1px solid #777 !important; }
