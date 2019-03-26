<template>
	<div>
		<div class="top_bar">
			<div class="nav">
				<div class="logo"></div>
				<div class="tab">
					<div class="hx_1"></div>
					<div class="hx_2"></div>
					<div class="hx_3"></div>
				</div>
			</div>
		</div>
		<div class="home_banner">
			<div class="mb"></div>
			<div class="mb1"></div>
			<div class="mb2"></div>
			<div class="title_area">
				<div class="zs"></div>
				<div class="yx"></div>
				<div class="zpj">作品集</div>
				<div class="zpj2">MY WORKS</div>
				<div class="yq_img"></div>
			</div>
			<div class="enter">
				<a href="#">点击进入</a>
			</div>
			<div class="sb">
				<div class="sb_sx"></div>
			</div>
		</div>
		<div class="wrap">
			<div class="sjx sjx1"></div>
			<div class="yq yq1"></div>
			<div class="zfx zfx1"></div>
			<div class="sjx sjx2"></div>
			<div class="yq yq2"></div>
			<div class="zfx zfx2"></div>
			<div class="sjx sjx3"></div>
			<div class="yq yq3"></div>
			<div class="zfx zfx3"></div>
			<div class="zfx zfx4"></div>
			<div class="zfx zfx5"></div>
			<div class="container">
				<div class="wdzp">这是标题</div>
				<div class="box_area">
					<div class="box1"></div>
					<div class="box2"></div>
					<div class="box3"></div>
					<div class="box4"></div>
					<div class="box5"></div>
					<div class="box6"></div>
					<div class="box7"></div>
					<div class="box8"></div>
				</div>
				<div class="more"><a href="">进入更多</a></div>
				
			</div>
		</div>
		<div class="footer">
			<div class="container">
				<div class="logo2"></div>
				<div class="tab2">
					<ul>
						<li><a class="tab2_active"  href="">home</a></li>
						<li><a href="">works</a></li>
						<li><a href="">about me</a></li>
						<li><a href="">contact</a></li>
					</ul>
				</div>
				<div class="send">
					<input type="text" placeholder="189@189.com">
					<button type="submit">send</button>
				</div>
				
				<div class="clearfix"></div>
			</div>
		</div>
	</div>
	
</template>

<script>
	export default {
		data(){
			return {
				tabs:['1','2','3']
			}
		}
	}
</script>

<style lang="less">
	/*清除公共样式*/
			html, body, div, ul, li, h1, h2, h3, h4, h5, h6, p, dl, dt, dd, ol, form, input,button, textarea, th, td, select {
			    margin: 0;
			    padding: 0;
			}
			*{
				box-sizing: border-box;
			}
			html, body {
			    min-height: 100%;
			}
			
			body {
			    font-family: "思源宋体";
			    font-size:14px;
			    color:#333;
			}
			h1, h2, h3, h4, h5, h6{font-weight:normal;}
			ul,ol {
			    list-style: none;
			}
			
			img {
			    border: none;
			    vertical-align: middle;
			}
			
			a {
			    text-decoration: none;
			}
			
			table {
			    border-collapse: collapse;
			    table-layout: fixed;
			}
			
			input, button, textarea {
			    outline: none;
			    border: none;
				background-color: transparent;
			}
			
			textarea {
			    resize: none;
			    overflow: auto;
			}
			
			.clearfix {
			    zoom: 1;
			}
			
			.clearfix:after {
			    content: ".";
			    width: 0;
			    height: 0;
			    visibility: hidden;
			    display: block;
			    clear: both;
			    overflow:hidden;
			}
			.ellipse {
			    overflow: hidden;
			    text-overflow: ellipsis;
			    white-space: nowrap;
			}
			.inline{
			    display: inline-block;
			    *display: inline;
			    *zoom: 1;
			}
			
			@font-face{
			     font-family:思源宋体; 
			     src:url('SourceHanSerifCN-ExtraLight.otf') format('opentype'),
			         url('SourceHanSerifCN-ExtraLight.ttf') format('turetype'),
			         url('SourceHanSerifCN-ExtraLight.svg') format('svg');
			}
			/*首页banner*/
			.home_banner{
				width: 100%;
				height: 1080px;
				background: url(img/home_bg.jpg) no-repeat;
				position: relative;
				top: 0;
				left: 0;
			}
			.mb{
				width: 100%;
				height: 1080px;
				background: url(img/home_img01.jpg) no-repeat;
				position: absolute;
				top: 0;
				left: 0;
				mix-blend-mode: soft-light;
			}
			.mb1{
				width: 100%;
				height: 1080px;
				background:rgba(0,0,0,0.5);
				position: absolute;
				z-index: 10;
				top: 0;
				left: 0;
				
			}
			.mb2{
				width: 100%;
				height: 1080px;
				background: url(img/home_img02.png) no-repeat;
				position: absolute;
				top: 0;
				left: 0;
				mix-blend-mode: color-dodge;
			}
			.title_area{
				width: 112px;
				height: 322px;
				position: absolute;
				top: 36%;
				left: 50%;
				transform: translate(-50%,-50%);
				z-index: 30;
			}
			.zs{
				width: 36px;
				height: 36px;
				border-top: 1px solid #FFFFFF;
				border-left: 1px solid #FFFFFF;
				position: absolute;
				left: -1px;
				top: -1px;
			}
			.yx{
				width: 36px;
				height: 36px;
				border-bottom: 1px solid #FFFFFF;
				border-right: 1px solid #FFFFFF;
				position: absolute;
				right: -1px;
				bottom: -1px;
			}
			.zpj{
				width: 36px;
				color: #fff;
				font-size: 38px;
				text-align: inherit;
				position: absolute;
				z-index: 20;
				top: 40%;
				left: 45%;
				transform: translate(-50%,-50%);
				font-family: '思源宋体';
				line-height: 74px;
			}
			.zpj2{
				width: 132px;
				color: #fff;
				font-size: 14px;
				text-align: center;
				position: absolute;
				z-index: 20;
				top: 83%;
				left: 17%;
				font-family: '思源宋体';
				line-height: 20px;
				transform: rotateZ(90deg) translate(-50%,-50%);
				word-spacing: 10px;
				letter-spacing: 4.4px;
				text-decoration:line-through;
			}
			.yq_img{
				width: 26px;
				height: 26px;
				background: url(img/hongquan.png) no-repeat center center;
				position: absolute;
				top: 80%;
				left: 35%;
			}
			.enter{
				width: 200px;
				height: 54px;
				border: 1px solid #FFFFFF;
				position: absolute;
				top: 61%;
				left: 50%;
				transform: translate(-50%,-50%);
				z-index: 30;
			}
			.enter a{
				font-size: 18px;
				color: #FFFFFF;
				text-align: center;
				line-height: 52px;
				display: block;
				letter-spacing: 2px;
			}
			.sb{
				width: 22px;
				height: 32px;
				border: 1px solid #FFFFFF;
				border-radius: 10px;
				position: absolute;
				top: 70%;
				left: 50%;
				transform: translate(-50%,-50%);
				z-index: 30;
			}
			.sb_sx{
				width: 2px;
				height: 7px;
				background: #FFFFFF;
				border: 1px;
				position: absolute;
				top: 10px;
				left: 50%;
				transform: translate(-50%,-50%);
			}
			/*导航栏*/
			.top_bar{
				width: 100%;
				position: fixed;
				top: 0;
				z-index: 100;
			}
			.nav{
				width: 1520px;
				height: 110px;
				position: relative;
				margin: 0 auto;
				top: 0;
			}
			.logo{
				width: 83px;
				height: 23px;
				position: absolute;
				left: 0;
				top: 43.5px;
				background: url(img/logo01.png) no-repeat;
			}
			.tab{
				width: 26px;
				height: 23px;
				position: absolute;
				right: 0;
				top: 43.5px;
				background: url(img/tab_hx.png) no-repeat;
			}	
			.tab>div{
				width: 26px;
				height: 2px;
				background: #FFFFFF;
				margin-top: 8px;
			}
			.tab>div:first-child{
				margin-top: 0;
			}
			
			/* 内容区 */
			.wrap{
				width: 100%;
				background: #fff;
				top: 0;
				position: relative;
			}
			.container{
				width: 1170px;
				margin: 0 auto;
			}
			.wdzp{
				width: 100%;
				height: 240px;
				background: #FFFFFF;
				font-size: 28px;
				color: #222;
				line-height: 240px;
			}
			.box_area{
				width: 100%;
				height: 895px;
				background: #FFFFFF;
				position: relative;
			}
			.box_area>div{
				width: 370px;
				position: absolute;
			}
			.box1{
				height: 360px;
				background: #f6f6f6;
				top: 0;
				left: 0;
			}
			.box2{
				height: 300px;
				background: #f6f6f6;
				top: 0;
				left: 400px;
			}
			.box3{
				height: 360px;
				background: #f6f6f6;
				top: 0;
				left: 800px;
			}
			.box4{
				height: 500px;
				background: #f6f6f6;
				top: 390px;
				left: 0;
			}
			.box5{
				height: 246px;
				background: #f6f6f6;
				top: 330px;
				left: 400px;
			}
			.box6{
				height: 250px;
				background: #f6f6f6;
				top: 390px;
				left: 800px;
			}
			.box7{
				height: 246px;
				background: #f6f6f6;
				top: 606px;
				left: 400px;
			}
			.box8{
				height: 250px;
				background: #f6f6f6;
				top: 670px;
				left: 800px;
			}
			.more{
				width: 154px;
				height: 44px;
				border: 1px solid #d6d6d6;
				margin: 30px auto 75px;
			}
			.more a{
				font-size: 14px;
				display: block;
				line-height: 42px;
				text-align: center;
				color: #222222;
			}
			.sjx{
				
				width: 26px;
				height: 22px;
				background: url(img/sanjiaoxing.png) no-repeat;
				position: absolute;
				z-index: 99999;
			}
			.zfx{
				width: 26px;
				height: 26px;
				background: url(img/zhengfangxing.png) no-repeat;
				position: absolute;
				
				z-index: 99999;
			}
			.yq{
				width: 22px;
				height: 22px;
				background: url(img/yuan.png) no-repeat;
				position: absolute;
				z-index: 99999;
			}
			/* 三角形、圆圈、正方形 */
			.sjx1{
				left: 200px;
				top: 192px;
				transform: rotateZ(30deg);
			}
			.zfx1{
				left: 300px;
				top: 478px;
			}
			.yq1{
				left: 100px;
				top: 720px;
			}
			.sjx2{
				left: 270px;
				top: 992px;
			}
			.zfx2{
				left: -2px;
				top: 1157px;
				transform: rotateZ(60deg);
			}
			.yq2{
				left: 644px;
				top: 626px;
			}
			.sjx3{
				right: 454px;
				top: 233px;
				transform: rotateZ(5deg);
			}
			.zfx3{
				right: 145px;
				top: 265px;
				transform: rotateZ(15deg);
			}
			.yq3{
				right: 138px;
				top: 850px;
			}
			.zfx4{
				right: 275px;
				top: 1137px;
				transform: rotateZ(18deg);
			}
			.zfx5{
				right: 768px;
				top: 788px;
				transform: rotateZ(10deg);
			}
			
			/* footer */
			.footer{
				width: 100%;
				height: 270px;
				background: #FFFFFF;
				border-top: 1px solid #D6D6D6;
				padding: 120px 0;
			}
			.logo2{
				width: 83px;
				height: 30px;
				background: url(img/logo2.png) no-repeat 0 center;
				float: left;
			}
			.tab2{
				width: 460px;
				height: 30px;
				float: left;
				margin-left: 298px;
			
			}
			.tab2 ul{
				display: flex;
			}
			.tab2 ul li{
				padding: 0 32px;
			}
			.tab2 ul li a{
				font-size: 14px;
				color: #666;
				line-height: 29px;
				text-align: center;
			}
			.tab2 ul li:first-child:after{
				content: ' ';
				display: block;
				width: 20px;
				height: 1px;
				background: #000;
				clear: both;
			}
			.tab2 ul li a .tab2_active{
				color: #000;
			}
			.send{
				width: 262px;
				height: 30px;
				float: right;
			}
			.send input{
				width: 160px;
				height: 30px;
				border-bottom: 1px solid #9b9b9b;
				color: #222;
				font-size: 14px;
				line-height: 30px;
				font-family: '思源宋体';
				margin-right: 16px;
				float: left;
			}
			.send button{
				width: 86px;
				height: 30px;
				background: #000000;
				color: #FFFFFF;
				font-size: 14px;
				line-height: 30px;
				text-align: center;
				font-family: '思源宋体';
				cursor: pointer;
			}
</style>