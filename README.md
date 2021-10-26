# homepage_exp3
<!DOCTYPE html>
<html lang="en">
<head>
  <title>Home Page </title>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.1/dist/css/bootstrap.min.css" rel="stylesheet">
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.1/dist/js/bootstrap.bundle.min.js"></script>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
   <nav class="navbar navbar-expand-sm bg-dark navbar-dark ">
    <div class="container-fluid">
      <a class="navbar-brand" href="#">
        <img src="2logo.jpg" alt="Logo" style="width:40px;" class="rounded-pill"> Mobile Shopee
      </a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#mynavbar">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="mynavbar">
        <ul class="navbar-nav me-auto">
          <li class="nav-item">
            <a class="nav-link" href="javascript:void(0)"> Home </a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="javascript:void(0)"> Cart </a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="javascript:void(0)">Contact Us</a>
          </li>
        </ul>
        <form class="d-flex">
          <input class="form-control me-2" type="text" placeholder="Search">
          <button class="btn btn-primary" type="button">Search</button>
        </form>
       
      </div>
    </div>
    </div>
  </nav>
  <div id="demo" class="carousel slide" data-bs-ride="carousel">

    <!-- Indicators/dots -->
    <div class="carousel-indicators">
      <button type="button" data-bs-target="#demo" data-bs-slide-to="0" class="active"></button>
      <button type="button" data-bs-target="#demo" data-bs-slide-to="1"></button>
      
    </div>
    
    <!-- The slideshow/carousel -->
    <div class="carousel-inner">
      <div class="carousel-item active">
        <img src="12pro.jpg" alt="iphone13" class="d-block" style="width:100%">
        <div class="carousel-caption">
          <h3>Iphone 13 </h3>
          <button type="button" class="btn btn-outline-primary"> BUY NOW </button>
        </div>
      </div>
      <div class="carousel-item">
        <img src="oneplus2.jpg" alt="Chicago" class="d-block" style="width:100%">
        <div class="carousel-caption">
          <h3>One Plus 10 </h3>
          <button type="button" class="btn btn-outline-primary"> BUY NOW </button>
        </div> 
      </div>
      
      </div>
    </div>
    
    <!-- Left and right controls/icons -->
    <button class="carousel-control-prev" type="button" data-bs-target="#demo" data-bs-slide="prev">
      <span class="carousel-control-prev-icon"></span>
    </button>
    <button class="carousel-control-next" type="button" data-bs-target="#demo" data-bs-slide="next">
      <span class="carousel-control-next-icon"></span>
    </button>
  </div>
  <div class=".container-fluid pt-5 align-middle bg-dark text-white">
    <h1>MORE PRODUCTS</h1>
  </div>
  <br>
  <br>
  <main>
  <section>
  <div class="box">
    <img src="Images/Budget/6i.jpeg" class="float-start" alt="6i" width="150" height="236">
   <br>
    <p><b>Samsung a4 </b></p>
    <p>
      <em style="text-decoration: line-through"> Rs. 12999/- </em>
      <em style="color: blue"> Rs. 11499/- </em>
    </p>
    <button type="button" class="btn btn-primary btn-sm">Add to cart </button>
  </div>
  <div class="box">
    <img src="Images/Budget/c11.jpeg" class="float-end" alt="c11" width="150" height="236"> 
    <br>
    <p style="color: rgb(0, 0, 0);"><b>lenovo </b></p>
    <p>
      
      <em style="color: rgb(0, 0, 0)"> Rs. 11499/- </em>
    </p>
    <button type="button" class="btn btn-primary btn-sm">Add to cart </button>
  </div>
  <div class="box">
    <img src="Images/Budget/F12.jpeg" class="mx-auto d-block" width="150" height="236"> 
    <br>
    <p style="color: rgb(0, 0, 0);"><b>F12 </b></p>
    <p>
      
      <em style="color: rgb(0, 0, 0)"> Rs. 20,499/- </em>
    </p>
    <button type="button" class="btn btn-primary btn-sm">Add to cart </button>
  </div>
  </div>
  </section>
</main>
  

  </div>
</body>
