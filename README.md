<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="stylesheet" href="https://fonts.googleapis.com/icon?family=Material+Icons">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.2/css/all.min.css">
  <link rel="stylesheet" href="day34.1,2a.css">
  <link rel="stylesheet" href="responsive.css">
</head>

<body>
  <nav class="header-clr">
    <div class="wrapper">
      <div class="header-area d-flex jcb">
        <div class="header-left">
          <a href="#"><img src="https://www.google.com/images/branding/googlelogo/2x/googlelogo_color_272x92dp.png"
              alt=""></a>
        </div>
        <div class="header-right">
          <ul>
            <li><a href="#">Home</a></li>
            <li><a href="#">About</a></li>
            <li><a href="#">Service</a></li>
            <li><a href="#">Product</a></li>
            <li><a href="#">Blog</a></li>
            <li><a href="#">Contact</a></li>
          </ul>
        </div>
      </div>
    </div>
  </nav>
  <section class="banner">
    <div class="wrapper">
      <div class="banner-text tc">
        <h2>Welcome to our website</h2>
        <h1>Lorem ipsum dolor sit amet consectetur.</h1>
      </div>
    </div>
  </section>
  <section class="myself">
    <div class="wrapper d-flex">
      <div class="me-img">
        <img src="https://images2.imgbox.com/73/8b/ehprnLmR_o.jpg" alt="">
      </div>
      <div class="me-describe">
        <h2>About Me</h2>
        <h3>My life style is totally simple</h3>
        <p>But I must explain to you how all this mistaken idea of denouncing pleasure and praising pain was born and I will give you a complete account of the system, and expound the actual teachings of the great explorer of the truth, the master-builder of human happiness. No one rejects, dislikes, or avoids pleasure itself, because plasure.</p>
      </div>
    </div>
  </section>
  <section class="service">
    <div class="wrapper">
      <div class="service-box d-flex">
        <div class="s-box-inner tc">
          <span class="material-icons">travel_explore</span>
          <h2>Web Design</h2>
          <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Laborum?</p>
        </div>
        <div class="s-box-inner tc">
          <span class="material-icons">travel_explore</span>
          <h2>Graphics Design</h2>
          <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Laborum?</p>
        </div>
        <div class="s-box-inner tc">
          <span class="material-icons">travel_explore</span>
          <h2>Web Development</h2>
          <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Laborum?</p>
        </div>
      </div>
    </div>
  </section>
  <footer>
    <div class="wrapper">
      <div class="f-wrap d-flex jcb">
        <div class="f-left">
          <p>&copy; Isa Ahmed - All Right Reserved</p>
        </div>
        <div class="f-right">
          <ul>
            <li><a href="#"><i class="fab fa-facebook"></i></a></li>
            <li><a href="#"><i class="fab fa-twitter"></i></a></li>
            <li><a href="#"><i class="fab fa-instagram"></i></a></li>
            <li><a href="#"><i class="fab fa-youtube"></i></a></li>
          </ul>
        </div>
      </div>
    </div>
  </footer>
</body>

</html>

* {
  margin: 0;
  padding: 0;
  outline: 0;
  box-sizing: border-box;
}
img{
  max-width: 100%;
}
ul{
  list-style: none;
}
a, span{
  display: inline-block;
  text-decoration: none;
}
.wrapper{
  max-width: 1270px;
  margin: auto;
}
.tc{
  text-align: center;
}
.tr{
  text-align: right;
}
.d-flex{
	display: flex;
}
.jcb{
	justify-content: space-between;
}
/*  */
.header-clr{
  background: #f5deb3;
}
.header-area{
	align-items: center;
}
.header-left img {
	width: 125px;
	height: auto;
	/* box-shadow: 0 0 4px 4px #444; */
}
.header-right ul{
  text-align: right;
}
.header-right ul li{
  display: inline-block;
  margin-left: -4px;
}
.header-right ul li a {
	color: #fff;
	font-size: 21px;
	padding: 6px 30px;
	line-height: 51px;
	border-right: 1px solid #fff;
	transition: .6s;
}
.header-right ul li a:hover{
 background: #26819f; 
}
/* banner */
.banner {
	background: url(https://images2.imgbox.com/27/2e/KbZWsqP3_o.jpg) no-repeat center 43%;
	background-size: cover;
	padding: 164px 0;
}
.banner-text h2 {
	color: #3498db;
	font-size: 30px;
	margin-bottom: 13px;
}
.banner-text h1 {
	color: #3498db;
	font-size: 38px;
}
/* introduce */
.myself .wrapper{
	display: flex;
	justify-content: space-evenly;
	column-gap: 8%;
	padding: 0 7em;
}
.myself {
	padding:80px 0;
}
.me-img {
	width:22em;
}
.me-describe {
	width:79%;
}
.me-describe h2 {
	font-size:25px;
	margin-top:16px;
}
.me-describe h3 {
	margin: 30px 0;
	font-weight:bold;
	font-size:21px;
}
.me-describe p {
	line-height:1.7;
	font-size:18px;
	padding-right:50px;
}
/* .service */
span.material-icons{
	user-select: none;
}
.service{
	background: #fffaf0;
	padding: 100px 0;
}
.service-box{
	column-gap: 2%;
}
.s-box-inner {
	border:3px dashed #ddd;
	padding: 29px 30px;
	border-radius:70px 0;
}
.s-box-inner span {
	font-size:40px;
	color:#3498db;
	width: 60px;
	height: 60px;
	line-height: 60px;
	border:2px solid #3498db;
	border-radius:15px 0;
}
.s-box-inner h2 {
	margin:15px 0;
}
.s-box-inner p {
	font-size: 18px;
font-weight: bold;
}
/* footer */
footer{
	background: #2c3e50;
	color: #fff;
	padding: 20px 0;
}
.f-left p{
	font-size: 20px;
}
.f-right{}
.f-right li{
	display: inline-block;
}
.f-right li a{
	color: #fff;
	padding: 0 5px;
	font-size: 20px;
}
