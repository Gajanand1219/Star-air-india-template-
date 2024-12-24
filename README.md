
<!DOCTYPE html>
<HTML>
  <head>
  
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
  <script src='https://kit.fontawesome.com/a076d05399.js' crossorigin='anonymous'></script>

  <!-- <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.6.0/css/all.min.css" integrity="sha512-Kc323vGBEqzTmouAECnVceyQqyqdsSiqLQISBL29aUW4U/M7pSPA/gEUZQqv1cwx4OnYxTxve5UMg5GT6L4JJg==" crossorigin="anonymous" referrerpolicy="no-referrer" /> -->
  <meta charset="UTF-8">
  
  
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Document</title>


  <style >

html {
  scroll-behavior: smooth;
}

nav {
  display: flex;
  justify-content: space-between;
  height: 90px;
  align-items: center;
  background-color: white;
  font-family: sans-serif;
  width: 100%;
  position: fixed;
  top: 0px;
}
nav a {
  text-decoration: none;
  padding: 10px 20px;
  margin: 10px;
  color: black;
}
nav a:hover {
  color: #dfe2d8;
  background-color: #9caccb;
  border-radius: 20px;
  box-shadow: -3px 4px 24px 12px rgb(179, 161, 161);
}

.container {
  background: url(https://images4.alphacoders.com/286/286536.jpg);
  background-repeat: no-repeat;
  background-size: cover;
  min-height: 100vh;
  width: 100%;
  padding-top: 20px;
}
.container .container1 {
  width: 80%;
  height: 170px;
  background-color: white;
  box-shadow: -3px 4px 24px 12px rgb(179, 161, 161);
  margin: 7%;
  margin-left: 200px;
  border-radius: 10px;
}

.main1 {
  padding: 20px;
}

.main {
  display: flex;
}

select {
  width: 150px;
  height: 50px;
  border: none;
  font-size: large;
  cursor: pointer;
}

.main2 {
  margin-left: 10px;
  border-right: 1px solid black;
  width: 200px;
  cursor: pointer;
}

.main3 {
  padding-left: 15px;
  cursor: pointer;
}

input[type=date] {
  border: none;
  padding: 10px;
  font-size: large;
  cursor: pointer;
}

.main5 {
  border-left: 1px solid black;
  margin-left: 10px;
  width: 200px;
  cursor: pointer;
}

button {
  /* width: 80px; */
  height: 50px;
  width: 100px;
  margin-top: 20px;
  margin-left: 20px;
  background-color: blueviolet;
  border-radius: 10px;
  color: white;
  cursor: pointer;
}

h1 {
  padding-left: 90px;
}

h3 {
  color: hsl(131, 85%, 5%);
  text-align: end;
  margin-right: 190px;
}

.card {
  background-color: white;
  width: 100%;
  height: 200px;
  display: flex;
  align-items: center;
  margin-top: 20px;
}
.card .card1 {
  background-color: white;
  box-shadow: -3px 4px 24px 12px rgba(198, 195, 216, 0.48);
  width: 30%;
  height: 100px;
  margin-left: 20px;
  border-radius: 20px;
  text-align: center;
  padding-top: 40px;
  font-size: x-large;
}
.card .card1:hover {
  transform: scale(0.9);
}

.section1 {
  display: flex;
  padding-left: 20px;
}
.section1 .section2 img {
  display: grid;
  border: 5px solid rgb(239, 234, 234);
  margin-right: 10px;
  box-shadow: -3px 4px 24px 12px rgba(198, 195, 216, 0.48);
}
.section1 .section2 img:hover {
  border-radius: 50px 10px;
  box-shadow: -3px 4px 24px 12px rgba(196, 8, 26, 0.48);
}

.section3 {
  display: grid;
  grid-template-columns: auto auto;
  grid-column-gap: 20px;
  padding-left: 10px;
  box-shadow: -3px 4px 24px 12px rgba(183, 181, 193, 0.48);
  background-color: none;
}

.section3 img {
  border: 9px solid aqua;
  border-radius: 20px 30px;
}

.section3 img:hover {
  border: 5px solid rgb(10, 229, 211);
  border-radius: 50px 10px;
  box-shadow: -3px 4px 24px 12px rgba(31, 11, 146, 0.48);
  margin: 5px;
}

.WHY_STAR_AIR {
  padding-left: 80px;
  color: rgb(178, 101, 39);
}

.card2 {
  background-color: white;
  min-width: 30%;
  min-height: 400px;
  margin-left: 40px;
  border-radius: 20px;
  margin-top: 200px;
  padding-top: 10px;
  font-size: x-large;
  box-shadow: -1px 1px 24px 2px rgb(149, 135, 135);
}
.card2 .card2:hover {
  box-shadow: -3px 4px 24px 12px rgba(71, 13, 196, 0.48);
}
.card2 span {
  float: inline-end;
}
.card2 .logo {
  margin-left: 50px;
}
.card2 img:hover {
  transform: rotateY(360deg);
  transition: 2s;
}
.card2 h2 {
  padding-left: 60px;
}
.card2 h4 {
  padding-left: 40px;
}

.h5 {
  padding-top: 15%;
  font-size: larger;
  color: goldenrod;
  text-align: center;
}

.update {
  text-align: center;
}

.mango {
  display: flex;
  border-bottom: 1px solid black;
  margin-left: 1px;
}
.mango .mango1 {
  margin: 20px;
  width: 220px;
  height: 180px;
}
.mango .mango1:hover {
  box-shadow: -3px 4px 24px 12px rgba(100, 85, 180, 0.48);
}

.footer1 {
  display: flex;
  justify-content: space-around;
  margin-top: 66px;
  background-color: rgb(11, 76, 76);
  color: white;
  height: 2%;
  box-shadow: -3px 4px 24px 12px rgb(126, 122, 122);
}
.footer1 .text a {
  text-decoration: none;
  color: white;
  font-size: larger;
  display: block;
  margin: 10px;
  margin-left: 80px;
}
.footer1 .text a:hover {
  color: #76c90a;
  scale: 1.1;
  text-align: start;
}
.footer1 .icon a {
  border: 2px solid white;
  color: rgb(169, 209, 241);
  background-color: rgb(124, 100, 100);
  border-radius: 50%;
  display: inline-flex;
  justify-content: center;
  align-items: center;
  margin: 3%;
  height: 20px;
  width: 20px;
  padding: 10px;
  text-decoration: none;
}
.footer1 .icon a.facebook:hover {
  color: white;
  background-color: #4267B2;
  border: 1px solid rgb(189, 249, 253);
  box-shadow: -3px 4px 24px 12px rgba(198, 195, 216, 0.48);
  scale: 1.1;
}
.footer1 .icon a.instragram:hover {
  color: #5B51D8;
  background-color: white;
  border: 2px solid yellowgreen;
  box-shadow: -3px 4px 24px 12px rgba(198, 195, 216, 0.48);
  scale: 1.1;
}
.footer1 .icon a.whatsapp:hover {
  color: white;
  background-color: #1cee42;
  border: 2px solid white;
  box-shadow: -3px 4px 24px 12px rgba(198, 195, 216, 0.48);
}
.footer1 .icon a.linkedin:hover {
  color: white;
  background-color: #4267B2;
  border: 2px solid blue;
  box-shadow: -3px 4px 24px 12px rgba(198, 195, 216, 0.48);
  transform: scale(1.1);
}

.number {
  font-size: xx-large;
  margin-top: 0px;
}

.email {
  color: yellow;
  margin: 0px;
  padding: 0px;
}

h5 {
  font-size: x-large;
}

footer {
  width: 100%;
  background-color: rgb(37, 34, 34);
  height: 100px;
  color: white;
  display: flex;
  justify-content: space-between;
  height: 90px;
  align-items: center;
}
footer .nav a {
  font-family: sans-serif;
  text-decoration: none;
  padding: 10px 20px;
  margin: 10px;
  color: #1cee42;
}
footer .footer2 span {
  color: yellow;
  margin-right: 200px;
}/*# sourceMappingURL=animation.css.map */


    
  </style>  </head>
<body>
  <!-- ===================================================================================================================================== -->
  <header>   
    <nav>
      <div>
      <img src="https://upload.wikimedia.org/wikipedia/commons/d/dd/Star_Air_Logo.png">
      </div>
          <div class="navbar">
              <a href="#">Home</a>
              <a href="#">About</a> 
              <a href="#">Information</a>
              <a href="#">Careers</a>
              <a href="#">Charters</a>
              <a href="#">Login</a>
              <a hre=""> INR <img src="
              "></a>
              </div>
              </nav>              
  </header>
  <!-- ========================================================================================================================================= -->
  <div class="container">
              <div class="container1">
        <div class="main1">
        <input type="radio">
        <label> One Way</label>
        <input type="radio">
        <label> Round Trip</label>
    </div> 
    <div class="main">
    <div class="main2">
      <label> Origin</label><br>
      <select>
       <option>ORG</option>
       <option>ORG</option>
       <option>ORG</option>
       <option>ORG</option>
       <option>ORG</option>
      </select>
  </div>
  <div class="main2">
    <label> Origin</label><br>
    <select>
     <option>ORG</option>
     <option>ORG</option>
     <option>ORG</option>
     <option>ORG</option>
     <option>ORG</option>
    </select>
</div>
<div class="main3">
  <label>Depart</label><br>
  <input type="date">
  <label> - </label>
</div>
<div class="main2">
  <label>Return Datet</label><br>
  <input type="date">
</div>

<div class="main2">
  <label>Passenger</label><br>
  <select class="select3">
      <option>Adult /Child </option>
      <option> </option>
  </select>
</div>
<div class="main3">
  <label>class</label><br>
  <select class="select4">
      <option>Select</option>
      <option> </option>
  </select>
</div>
<div class="main5">
<button value="submit">Flights<i class="fa-regular fa-plane-departure"></i></button>
</div>
</div>
</div>
</div>
<!-- ======================================================================================================================================= -->
<div class="card">
  <div class="card1">
    Web Check-in
  </div>
  <div class="card1">
    Flite Status
  </div>
  <div class="card1">
      Manage Booking
  </div>
</div>
<!-- ======================================================================================================================================= -->
<h1>Flight Offer Deals</h1>
<h3> <span><input type="radio"></span>Best Prise Guarantee</h3>
<!-- ======================================================================================================================================== -->
<div class="section1">
  <div class="section2">
  <img src="https://starair.in/Content/images/Tiles/S5_Tile_1.jpg">
    </div>
      <div class="section3">
      <img src="https://starair.in/Content/images/Tiles/S5_Tile_2.jpg">
      <img src="https://starair.in/Content/images/Tiles/S5_Tile_3.jpg">
      <img src="https://starair.in/Content/images/Tiles/S5_Tile_4.jpg">
      <img src="https://starair.in/Content/images/Tiles/S5_Tile_5.jpg">
    </div>
 </div>
<!--  ====================================================================================================================================-->
 <h4 class="WHY_STAR_AIR">WHY STAR AIR</h4>
 <h1 class="h1">Our Products</h1>
<!-- ================================================================================================================================== -->
 <div class="card">
  <div class="card2">
    <a href=""> <img src="https://starair.in/Content/images/icon/service_icon02.png" class="logo"></a>
    <h2> Business FLex! </h2>
    <h4>First Date change free*   <span>   &#10003;   </span> </h4>
    <h4>Complimentary seat selection  <span>   &#10003;   </span></h4>
    <h4>20 KG baggage allowance   <span>&#10003;</span></h4>
    <h4>Complimentaxy meals & beverage   <span>&#10003;</span></h4>
  </div>
  <div class="card2">
    <a href="">
    <img src="https://starair.in/Content/images/icon/service_icon03.png" class="logo"></a>
   <h2> Business Regular</h2>
   <h4>Complimentary seat selection  <span>&#10003;</span></h4>
   <h4>20 KG baggage allowance   <span>&#10003;</span></h4>
    <h4> Priority check-in and bording <span>&#10003;</span></h4>
    <h4> Complimentary meais & beverag <span>&#10003;</span></h4>
  </div>
   <div class="card2">
    <a href="">
   <img src="https://starair.in/Content/images/icon/service_icon01.png" class="logo"></a>
    <h2>Star Confort</h2>
    <h4> Complimentary Meal <span>&#10003;</span></h4>
    <h4> Free Reserved Seat<span>&#10003;</span></h4>
    <h4> Priority <span>&#10003;</span></h4>
  </div>
</div>
<!-- ================================================================================================================================== -->
 <h4 class="h5">Our News Feeds</h4>
 <h1 class="update">Latest News Update</h1>
 <!-- ================================================================================================================================= -->
 <div class="section1">
  <div>
    <div class="section2">
    <img src="https://starair.in/Content/images/Press/NDC-9destinations_1.jpg">
        </div>
  </div>
  <div>
    <div class="mango">
         <img src="https://starair.in/content/images/Press/BLR-NAG-Pune.jpg" class="mango1">   
          <div>
           <h1> Star Air Expands its Network with the Inauguration of Bengaluru-Nagpur-Pune Route</h1>
          </div>
      </div>
      <div>
      <div class="mango">
     <img src="https://th.bing.com/th/id/OIP.G5xh4FHFp_WUkw4k0_7E4QHaE8?rs=1&pid=ImgDetMain" class="mango1">    
         <div>
          <h1> Star Air Launches Direct Flights between Kolhapur and Tirupati</h1>
         </div>
     </div>
     <div>
      <div class="mango">
    <img src=" https://starair.in/Content/images/Press/KOL-TIR_sched.jpg" class="mango1">
         <div>
        <h1> Star Air Expands its Network with the Inauguration of Bengaluru-Nagpur-Pune Route</h1>
       </div>
       </div>
    <div class="mango">
   <img src="https://starair.in/Content/images/Press/Star_RQY-GOX.jpg" class="mango1">
     <div>
      <h1> Star Air Expands its Network with the Inauguration of Bengaluru-Nagpur-Pune Route</h1>
   </div>
  </div>
  </div>
  </div>
  </div>
</div>
<!-- ======================================================================================================================================== -->

<div class="footer1">
  <div class="text">
      <h1>Who We Are</h1>
      <a href="#"><li>About US</li></a>
      <a href="">Our Fleet</a>
      <a href=""> Medial Center</a>
      <a href="">Magazine</a>
      <a href="">Blogs</a>
      <a href="">Our Awards</a>
  </div>
  <div class="text">
    <h1>Servies</h1>
    <a href="#"><li>Flite Schedule</li></a>
    <a href="">Group Booking</a>
    <a href=""> Fare Sheet</a>
    <a href="">Flite Status</a>
    <a href="">Customer Tax Involve</a>
    <a href="">Financial Info</a>
</div>
<div class="text">
  <h1>MORE</h1>
  <a href="#"><li>AGENT lOGIN</li></a>
  <a href="">Corporate Login</a>
  <a href="">Travel Agent </a>
  <a href="">Chartars</a>
</div>
<div class="text">
  <h1>Contact Us</h1>
  <a href="#"><li>Airport</li></a>
  <a href="">Careers</a>
  <a href=""> FAQs</a>
</div>
<div class="text">
    <h5 class="number">Star Air - Social Media</h5>
    <div class="icon">
      <a href="https://www.facebook.com/profile.php?id=100083728363365"" class="facebook"><i class="fa fa-facebook"></i></a>
      <a href="https://www.instagram.com/gajanandeshmukh5823/" class="instragram"><i class="fa fa-instagram"></i></a>
      <a href="https://web.whatsapp.com/" class="whatsapp"><i class="fa fa-whatsapp"></i></a>
      <a href="https://www.linkedin.com/search/results/all/?fetchDeterministicClustersOnly=true&heroEntityKey=urn%3Ali%3Afsd_
      profile%3AACoAAD322BsBg4j2WpDbgZRXjKM5dip-dXM-6Ho&keywords=gajanan%20deshmukh&origin=RICH_QUERY_SUGGESTION&position=0&
      searchId=4602c0cd-dba8-4493-8566-5e2fddf421be&sid=%3B(*&spellCorrectionEnabled=false" class="linkedin"><i class="fa fa-linkedin"></i></a>
      </div>
      <h5 class="number">+91 9359458009</h5>
      <h5 class="email">gajanan1902200@gmail.com</h5>
      <h5>For refund, please write to<br> refunds@starair.in</h5>
  </div>
  </div>
  <!-- ====================================================================================================================================== -->
  <footer>
    <div class="nav">
      <a href="#">Privacy Policy </a>
      <a href="#"> Terms & Conditions</a>
      <a href="">Disclaimer</a>
      <a href="#">Contact us</a>
      </div>
      <div class="footer2">
        <p>
      Copyright © 2024.All Rights Reserved By <span>Star Air</span>
      </p>
      </div>
  </footer>
  <!-- ======================================================================================================================================= -->
</body>
</html>
