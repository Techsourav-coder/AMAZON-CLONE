# AMAZON-CLONE
AMAZON clone site using HTML,CSS,JS
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Amazon</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.2/css/all.min.css">
    <style>
        * {
             margin: 0;
             font-family: Arial;
             border: border-box;
        }
        .navbar{
            height: 60px;
            background-color: #0f1111;
            color: white;
            display: flex;
            align-items: center;
            justify-content: space-evenly;
        }
        .nav-logo{
            height: 50px;
            width: 100px;
        }
        .logo{
            background: url("../Desktop/amazon_logo.png");
            background-size: cover;
            height: 50px;
            width: 100%;
        }
        .border{
            border: 1.5px solid transparent;
        }
        .add-first{
            color: #cccccc;
            font-size: 0.85rem;
        }
        .add-sec{
            font-size: 1rem;
        }
        .add-icon{
            display: flex;
            align-items: center;
        }
        .nav-search{
            display: flex;
            background-color: #febd68;
            width: 620px;
            height: 40px;
            border-radius: 4px;
            justify-content: space-evenly;
        }
        .search-select{
            background-color: #f3f3f3;
            border-top-left-radius: 4px;
            border-bottom-left-radius: 4px;
            width: 50px;
            text-align: center;
            border: none;
        }
        .search-input{
            width: 100%;
            font-size: 1rem;
            border: none;
        }
        .search-icon{
            width: 45px;
            display: flex;
            justify-content: center;
            align-items: center;
            font-size: 1.2rem;
            border-top-right-radius: 4px;
            border-bottom-right-radius: 4px;
            color: #0f1111;
        }
        .nav-search:hover{
            border: 2px solid orange;
        }
        span{
            font-size: 0.7rem;
        }
        .nav-sec{
            font-size: 0.85rem;
            font-weight: 700;
        }
        .nav-cart i{
            font-size: 30px;
        }
        .nav-cart{
            font-size: 0.85rem;
            font-weight: 700;
        }
        .panel{
            height: 40px;
            background-color: #222f3d;
            display: flex;
            color: white;
            align-items: center;
            justify-content: space-evenly;
        }
        .panel-ops p{
            display: inline;
            margin-left: 10px;
        }
        .panel-ops{
            width: 70%;
            font-size: 0.85rem;
        }
        .panel-deals{
            font-size: 0.9rem;
            font-weight: 700;
        }
        .hero-section{
            background-image: url("../Downloads/hero_image.jpg");
            height: 400px;
            background-size: cover;
            display: flex;
            justify-content: center;
            align-items: flex-end;
        }
        .hero-msg{
            background-color: #cccccc;
            color: #0f1111;
            height: 40px;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 0.85rem;
            width: 80%;
            margin-bottom: 25px;
        }
        .hero-msg a{
            color: #007185;
        }
        .shop-section{
            display: flex;
            justify-content: space-evenly;
            background-color: #cccccc;
            flex-wrap: wrap;
        }
        .box{
            height: 400px;
            width: 23%;
            background-color:#e2e7e6;
            padding: 20px 0px 15px;
            margin-top: 15px;
        }
        .box-img{
            height: 300px;
            background-size: cover;
            margin-top: 1rem;
            margin-bottom: 1rem;
        }
        .box-content{
            margin-left: 10px;
            margin-right: 10px;
        }
        .box-content p{
        color: #007185;
        }
        .foot-panel1{
            background-color: #37475a;
            color: #cccccc;
            height: 50px;
            display: flex;
            justify-content: center;
            align-items: center;
            font-size: 0.85rem;
        }
        .footer{
            margin-top: 15px;
        }
        .foot-panel1{
            background-color: #37475a;
            color: white;
            height: 50px;
            display: flex;
            justify-content: center;
            font-size: 0.85rem;
        }
        .foot-panel2{
            background-color: #222f3d;
            color:white;
            height: 300px;
            display: flex;
            justify-content: space-evenly;
        }
        ul{
           margin-top: 10px;
        }
        ul a {
            display: block;
            font-size: 0.85rem;
            margin-top: 10px;
            color:#dddddd;
        }
        .foot-panel3{
            background-color: #222f3d;
            color:white;
            border-top: 0.5px solid white;
            height: 70px;
            display: flex;
            justify-content: center;
            align-items: center;
        }
        .logo1{
            background-image: url("amazon_logo.png");
            background-size: cover;
            height: 50px;
            width: 100%;
        }
        .foot-panel4{
            background-color: #0f1111;
            color: #dddddd;
            display: flex;
            justify-content: center;
            align-items: center;
        }

    </style>
</head>
<body>
    <header>
        <div class="navbar">
            <div class="nav-logo border">
                <div class="logo"></div>
            </div>
            <div class="nav-address border">
                <p class="add-first"> Deliver to </p>
                <div class="add-icon">
              <i class="fa-solid fa-location-dot"></i>
              <p class="add-sec"> India </p>
                </div>
            </div>
            <div class="nav-search">
                <select class="search-select">
                    <option>All</option>
                </select>
                <input placeholder="search Amazon" class="search-input">
                <div class="search-icon">
                    <i class="fa-solid fa-magnifying-glass"></i>
                </div>
            </div>
            <div class="nav-signin border">
                <p><span>Hello, sign in</span></p>
                <p class="nav-sec">Account & Lists</p>
            </div>
            <div class="nav-return border">
                <p><span>Returns</span></p>
                <p class="nav-sec">& Orders</p>
            </div>
            <div class="nav-cart border">
                <i class="fa-solid fa-cart-shopping"></i>
                Cart
            </div>
        </div>
            <div class="panel">
                <div class="panel-all">
                    <i class="fa-solid fa-bars"></i>
                   All 
                </div>
                <div class="panel-ops">
                    <p>Today's Deals</p>
                    <p>Customer Service</p>
                    <p>Registry</p>
                    <p>Gift Cards</p>
                    <p>Sell</p>
                </div>
                <div class="panel-deals">
                    Shop deals in electronics
                </div>
            </div>
    </header>
    <div class="hero-section">
        <div class="hero-msg">
            <p> You are on Amazon.com. You can also Shop on Amazon India for millions of products with fast local delivery. <a>Click here to go Amazon.in</a></p>
        </div>
    </div>
    <div class="shop-section">
        <div class="box1 box">
           <div class="box-content">
            <h2>Health & Personal Care</h2>
            <div class="box-img" style="background-image: url('../Downloads/box1_image.jpg');"></div>
            <p>See more</p>
           </div>
        </div>
        <div class="box2 box">
            <div class="box-content">
                <h2>Cloths</h2>
                <div class="box-img" style="background-image: url('../Downloads/box2_image.jpg');"></div>
                <p>See more</p>
               </div>
        </div>
        <div class="box3 box">
            <div class="box-content">
                <h2>Furniture</h2>
                <div class="box-img" style="background-image: url('../Downloads/box3_image.jpg');"></div>
                <p>See more</p>
               </div>
        </div>
        <div class="box4 box">
            <div class="box-content">
                <h2>Electronics</h2>
                <div class="box-img" style="background-image: url('../Downloads/box4_image.jpg');"></div>
                <p>See more</p>
               </div>
        </div>
        <div class="box1 box">
            <div class="box-content">
             <h2>Makeup</h2>
             <div class="box-img" style="background-image: url('../Downloads/box5_image.jpg');"></div>
             <p>See more</p>
            </div>
         </div>
         <div class="box2 box">
             <div class="box-content">
                 <h2>Pet Care</h2>
                 <div class="box-img" style="background-image: url('../Downloads/box6_image.jpg');"></div>
                 <p>See more</p>
                </div>
         </div>
         <div class="box3 box">
             <div class="box-content">
                 <h2>New Ariival in Toys</h2>
                 <div class="box-img" style="background-image: url('../Downloads/box7_image.jpg');"></div>
                 <p>See more</p>
                </div>
         </div>
         <div class="box4 box">
             <div class="box-content">
                 <h2>Fashion & Trends</h2>
                 <div class="box-img" style="background-image: url('../Downloads/box8_image.jpg');"></div>
                 <p>See more</p>
                </div>
         </div>
    </div>
    <footer>
        <div class="foot-panel1">
            Back to Top
        </div>
        <div class="foot-panel2">
            <ul>
                <p>Get to Know us</p>
                <a>Careers</a>
                <a>Blog</a>
                <a>About Amazon</a>
                <a>Investor Relations</a>
                <a>Amazon Devices</a>
                <a>Amazon Science</a>
            </ul>
            <ul>
                <p>Get to Know us</p>
                <a>Careers</a>
                <a>Blog</a>
                <a>About Amazon</a>
                <a>Investor Relations</a>
                <a>Amazon Devices</a>
                <a>Amazon Science</a>
            </ul>
            <ul>
                <p>Get to Know us</p>
                <a>Careers</a>
                <a>Blog</a>
                <a>About Amazon</a>
                <a>Investor Relations</a>
                <a>Amazon Devices</a>
                <a>Amazon Science</a>
            </ul>
            <ul>
                <p>Get to Know us</p>
                <a>Careers</a>
                <a>Blog</a>
                <a>About Amazon</a>
                <a>Investor Relations</a>
                <a>Amazon Devices</a>
                <a>Amazon Science</a>
            </ul>
        </div>
        <div class="foot-panel3">
            <div class="logo1"></div>
        </div>
        <div class="foot-panel4">
            <div class="pages">
                <a>Conditions of Use</a>
                <a>privacy Policy</a>
                <a>Your Ads Privacy Choices</a>
            </div>
        <div class="copyright">
            1996-2023, Amazon.com, Inc. or its affiliates
        </div>
        </div>
    </footer>   
</body>
</html>
