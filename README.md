<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC" crossorigin="anonymous">
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.bundle.min.js" integrity="sha384-MrcW6ZMFYlzcLA8Nl+NtUVF0sA7MsXsP1UyJoMp4YLEuNSfAP+JcXn/tWtIaxVXM" crossorigin="anonymous"></script>
    <title>Food Mart</title>
</head>
<body>
  <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
    <div class="container-fluid">
      <a class="navbar-brand" href="#">FOOD MART</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNavAltMarkup" aria-controls="navbarNavAltMarkup" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
        <div class="navbar-nav">
          <a class="nav-link active" aria-current="page" href="#">Home</a>
          <a class="nav-link" href="#">About</a>
          <a class="nav-link" href="#">Contact</a>
          <li class="nav-item dropdown">
            <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-bs-toggle="dropdown" aria-expanded="false">
              EXPLORE
            </a>  
            <ul class="dropdown-menu" aria-labelledby="navbarDropdown">
              <li><a class="dropdown-item" href="#">Features</a></li>
              <li><a class="dropdown-item" href="#">Pricing</a></li>
              <li><hr class="dropdown-divider"></li>
              <li><a class="dropdown-item" href="#">More info about our  MART</a></li>
            </ul>
          </li>
          <a class="nav-link disabled" href="#" tabindex="-1" aria-disabled="true">GOOD LUCK</a>
        </div>
      </div>
    </div>
    <form class="d-flex">
      <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
      <button class="btn btn-outline-success" type="submit">Search</button>
    </form>
  </nav>
  <div class="banner">
    <div class="Content">
      <h1>Welcome to Foodmart </h1>
      <p> Your One-Stop Shop for Freshness and Quality. your ultimate destination for the freshest and highest-quality groceries. </p>
      <button>CLICK HERE!</button>
    </div>
  </div>
<main> 
  <header>
    Categories
</header>
    <div class="class card-container" >
      <div class="class card" style="height: 150px;">
        <img src="./cat-1.png" alt="Card image 1" >
        <h5>Fruits</h5>
        <p id="price">Rs-500</p>
      </div>

      <div class="class card" style="height: 150px;">
        <img src="./cat-2.png" alt="Card image 2">
        <h5>Meat</h5>
        <p id="price">Rs-200</p>
      </div>

      <div class="class card" style="height: 150px;">
        <img src="./cat-3.png" alt="Card image 3">
        <h5>Vegetable</h5>
        <p id="price">Rs-600</p>
      </div>

      <div class="class card" style="height: 150px;">
        <img src="./cat-4.png" alt="Card image 3">
        <h5>Fish</h5>
        <p id="price">Rs-900</p>
      </div>

      <div class="class card" style="height: 150px;">
        <img src="./cat-5.png" alt="Card image 3">
        <h5>Fish</h5>
        <p id="price">Rs-900</p>
      </div>

      <div class="class card" style="height: 150px;">
        <img src="./cat-6.png" alt="Card image 3">
        <h5>Fish</h5>
        <p id="price">Rs-900</p>
      </div>
    </div>
</main>

</body>
</html>
<style>
  .banner{
    width: 100%;
    height: 100vh;
    background-image:url(./home-bg.jpg);
    background-repeat: no-repeat;
    background-size: cover;
    height: 560px; ;
}
.Content{
    display:grid;
    width: 85%;
    margin: auto;
    padding: 35px 0;
    text-align: end;
    justify-content: space-around;
    float: left;
}
.Content h1{
    font-size: 40px;
    color: black;
    font-weight: 700;
    margin-right: 450px;
    text-align: center;
    margin-top: 100px;
}

.Content p{
    font-size: 18px;
    color: black;
    font-weight: 400;
    margin-bottom: 20px;
    margin-right: 500px;
}
div button{
    background-color: gray;
    color: white;
    margin: 20px;
    margin-top: 30px;
    padding: 20px;
    width: 140px;
    font-size: 15px;
    border-radius: 10px;
    border: 2px solid black;
}
div button:hover{
    background-color: ghostwhite;
    color: cadetblue;
    transition: all 0.5s;
}
/* --------------CARDS----------------- */

header{
    color: black;
    padding: 10px 0;
    font-size: 20px;
    font-weight: bold;

}

.card-container{
    background-color: blanchedalmond;
    display: flex;
    gap: 20px;
}
.card {
    background-color: whitesmoke;
    border-radius: 00px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    padding: 20px;
    width: 100px;
    text-align: center;
    transition: transform 0.2s ease-in-out;
    border: 2px solid black;
    margin-right: 30px;
    margin-left: 30px;
    height: 100px;
    border-radius: 20px;

}
.card img {
    max-width: 100%;
    border-radius: 10px;
    height: 100%;

}
.card h5 {
    margin: 15px 0;
    font-size: 12px;
    color: black;
}
.card p {
    color: black;
}
#price {
    font-size: 15px;
    margin-top: 0px;
    font-weight: bold;
    color: black;
}
.card:hover {
    background-color: gainsboro;
}
</style>
