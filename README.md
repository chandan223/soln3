<!DOCTYPE html>
<html>
<head>

<title>Module 3</title>
<style >.container-fluid{
  margin: 0;
  padding: 0;
}

.navbar{
  border-radius: 0px;
  background-color: rgba(142, 68, 173);
}

.navbar-brand{
  font-size: 35px;
  color: white;
  padding-left: 25px;
}

.navbar-brand:hover{
  color: yellow;
}

.nav{
  margin: 0;
  padding: 0;
}

.navbar-nav{
  font-size: 25px;
  text-align: center;
  margin: 0;
  padding: 0;
}

.navbar-toggle{
  border: 2px solid yellow;
  margin-right: 25px;
}

.icon-bar{
  background-color: yellow;
}


.main-title{
  margin-bottom: 15px;
  text-align: center;
  color:#78281F ;
  font-size: 50px;
  font-family: "Comic Sans MS", cursive, sans-serif;
  font-weight: bold;
}

li{
  box-sizing: border-box;
  width: 100%;
}

.menu-item{
  padding: 0;
  margin: 0;
  width: 100%;
  background-color: orange;
  border-bottom: 1px solid black;
  color:black;
  display: block;
}

.menu-item:hover{
  background-color: rgba(255, 87, 51);
  color: rgba(255, 87, 51);
}



.row{
  margin: 20px;
}

.content-box1{
  margin: 20px;
  width: auto;
  height: auto;
  color: black;
  background-color: rgba(241, 148, 138 );
  font-family: "Comic Sans MS", cursive, sans-serif;
  padding: 25px;
}
.content-box2{
  margin: 20px;
  width: auto;
  height: auto;
  color: black;
  background-color: rgba(241, 196, 15 );
  font-family: "Comic Sans MS", cursive, sans-serif;
  padding: 25px;
}
.content-box3{
  margin: 20px;
  width: auto;
  height: auto;
  color: black;
  background-color: rgba(231, 76, 60 );
  font-family:  "Times New Roman", Times, serif;
  padding: 25px;
}

.item-name{
  text-align: center;
  font-size: 25px;
  font-weight: bold;
}

#top{

}
</style>

  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.3.1/jquery.min.js"></script>
  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js"></script>

</head>

<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" type="text/css" href="style.css">



<body>


<nav class="navbar" id="top">
  <div class="container-fluid">

    <div class="navbar-header">
      <button type="button" class="navbar-toggle" data-toggle="collapse" data-target="#myNavbar">
        <span class="icon-bar"></span>
        <span class="icon-bar"></span>
        <span class="icon-bar"></span> 
      </button>
      <a class="navbar-brand" href="#">Food, LLC</a>
    </div>

    <div class="collapse" id="myNavbar">
      <ul class="nav navbar-nav visible-xs">
        <li><a class="menu-item" href="#">Chicken</a></li>
        <li><a class="menu-item" href="#">Palak Paneer</a></li> 
        <li><a class="menu-item" href="#">Shahi paneer</a></li> 
      </ul>
    </div>

  </div>
</nav>

<h1 class="main-title">Our Menu</h1>



<div class="row">

  <div class="col-lg-4 col-md-6 col-sm-12">
    <div class="content-box1">
      <p class="item-name">Chicken</p>
      <p>Chicken cooked in fiery desi flavors is a dream come true for all non-vegetarians. Apart from being a very versatile meat when it comes to cooking, chicken also promises great health benefits. Did you know that the human body can derive about 30 different nutritional substances from just 100 grams of chicken? Apart from that there are other lesser-known benefits of Chicken like:<a href="#top">(Back to Top)</a></p>
    </div>
  </div>

  <div class="col-lg-4 col-md-6 col-sm-12">
    <div class="content-box2">
      <p class="item-name">Palak Paneer</p>
      <p>Palak Paneer is a popular Indian dish of soft cottage cheese cubes in a mild, spiced smooth spinach sauce. This delicious creamy dish is made with fresh spinach leaves, paneer (cottage cheese), onions, herbs and spices.

This vegetarian recipe can be made vegan by using tofu in place of paneer and using cashew or coconut cream in place of regular cream, or just skipping the cream altogether.<a href="#top">(Back to Top)</a></p>
    </div>
  </div>


  <div class="col-lg-4 col-md-6 col-sm-12">
    <div class="content-box3">
      <p class="item-name">Shahi paneer</p>
      <p>Shahi paneer recipe with step by step photos. This Restaurant Style Mughlai Shahi Paneer is a delicious and rich creamy gravy made with cottage cheese.

The creaminess comes from onions, nuts and curd. This is one of the popular and rich cottage cheese recipes from the Mughlai cuisine.<a href="#top">(Back to Top)</a></p>
    </div>
  </div>

</div>


</body>
</html>
