# Ex.10 Responsive Web Design using Bootstrap
## Date:

## AIM:
To design a responsive website for a Pharmaceutical Company using Bootstrap.


## DESIGN STEPS:

### Step 1:
Clone the repository from GitHub.

### Step 2:
Create Django Admin project.

### Step 3:
Create a New App under the Django Admin project.

### Step 4:
Insert the necessary CSS and JavaScript files as external in order to use Bootstrap.

### Step 5:
Create a HTML file and include the needed Bootstrap components.

### Step 6:
Publish the website in the LocalHost.

## PROGRAM :
# home.html
```

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>HOME</title>
  <!-- Bootstrap CSS -->
  <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
  <!-- Custom CSS -->
  <style>
    body {
      background-image: url("");
      background-size: cover;
      background-repeat: no-repeat;
      font-size: 19px;
    }
    footer{
      position: fixed;
      left: 0;
      bottom: 0;
      width: 100%;
      background-color: #000000; 
      color: white;
      text-align: center;
      padding: 10px 0; 
    }
  </style>
</head>
<body>

  <!-- Navbar -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-success">
    <a class="navbar-brand" href="#">HM PHARMACEUTICALS</a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>

    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav mr-auto">
        <li class="nav-item active">
          <a class="nav-link" href="home.html">Home <span class="sr-only">(current)</span></a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="about.html">About</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="products.html">Products</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="contact.html">Contact</a>
        </li>
      </ul>
      <ul class="navbar-nav ml-auto">
        <li class="nav-item">
          <a class="nav-link" href="#">Login</a>
        </li>
        
      </ul>
    </div>
  </nav>

  <!-- Page Content -->
  <div class="container mt-5">
    <div class="row">
      <div class="col-md-8">
        <h1>WELCOME TO HM PHARMACEUTICALS</h1>
        <p>Welcome to AM Pharmaceuticals.We provide you the best quality of Medicines.Customers well being is what we wish for.</p>
        <p>At Our Pharmaceuticals, we provide you all kind of medicines.</p>
        <p>Thank you for choosing and trusting AM Pharmaceuticals.</p>
      </div>
      <div class="col-md-5">
        <img src="abimg.jpeg" class="img-fluid" alt="Pharmacy Image" width="2000" height="2000">
      </div>
      </div>
    </div>
  </div>

  <!-- Footer -->
  <footer class="bg-dark text-white text-center py-4 mt-5">
    <p>&copy; 2024 PharmaCompany-Kiritk Roshan G R(212221043002).All rights reserved.</p>
  </footer>

  <!-- Bootstrap JS -->
  <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js"></script>
  <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>
```
# products.html
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Products</title>
  <!-- Bootstrap CSS -->
  <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
  <!-- Custom CSS -->
  <style>
    body {
      background-image: url("pr.jpg");
      background-size: cover;
      background-repeat: no-repeat;
      font-size: 19px;
    }
    footer{
      position: fixed;
      left: 0;
      bottom: 0;
      width: 100%;
      background-color: #000000; 
      color: white;
      text-align: center;
      padding: 10px 0; 
    }
  </style>
</head>
<body>

  <!-- Navbar -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-success">
    <a class="navbar-brand" href="#">HM PHARMACEUTICALS</a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>

    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav mr-auto">
        <li class="nav-item">
          <a class="nav-link" href="home.html">Home</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="about.html">About</a>
        </li>
        <li class="nav-item active">
          <a class="nav-link" href="products.html">Products <span class="sr-only">(current)</span></a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="contact.html">Contact</a>
        </li>
      </ul>
      <ul class="navbar-nav ml-auto">
        <li class="nav-item">
          <a class="nav-link" href="#">Login</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Register</a>
        </li>
      </ul>
    </div>
  </nav>

  <!-- Page Content -->
  <div class="container mt-5">
    <div class="row">
      <div class="col-md-12">
        <h1>Our Products</h1>
        <div class="card-deck">
          <div class="card">
            <img src="i1.jpeg" class="card-img-top" alt="Product 1">
            <div class="card-body">
              <h5 class="card-title">Product 1</h5>
              <p class="card-text">Pankajakasthuri Cough Syrup with Tulsi 100ml</p>
              <a href="#" class="btn btn-primary">Buy Now</a>
            </div>
          </div>
          <div class="card">
            <img src="i2.jpeg" class="card-img-top" alt="Product 2">
            <div class="card-body">
              <h5 class="card-title">Product 2</h5>
              <p class="card-text">Health Veda Organics Natural Immunity Booster Capsules for Men & Women I Immunity blend of Amla, Giloy, Tulsi, Neem & Ashwagandha I 60 Veg Capsules</p>
              <a href="#" class="btn btn-primary">Buy Now</a>
            </div>
          </div>
          <div class="card">
            <img src="i3.jpeg" class="card-img-top" alt="Product 3">
            <div class="card-body">
              <h5 class="card-title">Product 3</h5>
              <p class="card-text">Amway Tulsi Tablet Supports Immunity 60N (Tablets) for Immunity</p>
              <a href="#" class="btn btn-primary">Buy Now</a>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>

  <!-- Footer -->
  <footer class="bg-dark text-white text-center py-4 mt-5">
    <p>&copy; 2024 PharmaCompany-Kirtik Roshan G R(212221043006). All rights reserved.</p>
  </footer>

  <!-- Bootstrap JS -->
  <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js"></script>
  <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>
```
# about.html
```<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>About Us</title>
  <!-- Bootstrap CSS -->
  <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
  <!-- Custom CSS -->
  <style>
    body {
      background-image: url("");
      background-size: cover;
      background-repeat: no-repeat;
      font-size: 19px;
    }
    footer{
    position: fixed;
      left: 0;
      bottom: 0;
      width: 100%;
      background-color: #000000; 
      color: white;
      text-align: center;
      padding: 10px 0; 
    }
  </style>
</head>
<body>

  <!-- Navbar -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-success">
    <a class="navbar-brand" href="#">HM PHARMACEUTICALS</a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>

    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav mr-auto">
        <li class="nav-item">
          <a class="nav-link" href="home.html">Home</a>
        </li>
        <li class="nav-item dropdown active">
          <a class="nav-link dropdown-toggle" href="about.html" id="navbarDropdownAbout" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
            About
          </a>
          <div class="dropdown-menu" aria-labelledby="navbarDropdownAbout">
            <a class="dropdown-item" href="#vision">Vision</a>
            <a class="dropdown-item" href="#mission">Mission</a>
            <a class="dropdown-item" href="#values">Values</a>
            <!-- Add more subheadings as needed -->
          </div>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="products.html">Products</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Contact</a>
        </li>
      </ul>
    </div>
  </nav>

  <!-- Page Content -->
  <div class="container mt-5">
    <div class="row">
      <div class="col-md-12">
        <h1>About HM PHARMACEUTICALS</h1>
        <div id="vision">
          <h2>Vision</h2>
          <p>Our vision is to become a global leader in providing groundbreaking healthcare solutions that enhance the well-being of individuals worldwide. We aspire to pioneer innovations that redefine healthcare standards, empowering people to lead healthier, more fulfilling lives.</p>
        </div>
        <div id="mission">
          <h2>Mission</h2>
          <p>Our mission is to develop and deliver a comprehensive range of safe, effective, and affordable healthcare solutions that cater to the diverse needs of our customers. Through relentless dedication to research, development, and collaboration, we aim to address unmet medical needs and contribute positively to the health and vitality of communities globally.</p>
        </div>
        <div id="values">
          <h2>Values</h2>
          <p>Quality lies at the core of everything we do, as we uphold the highest standards of excellence in all aspects of our operations. Integrity forms the foundation of our business practices, guiding us to conduct ourselves with unwavering honesty, transparency, and ethical conduct. Innovation fuels our quest for progress, driving us to continually push boundaries and improve our products and services to better serve our customers. With a relentless focus on customer needs, we strive to understand and anticipate their requirements, ensuring their satisfaction and trust. Through teamwork and collaboration, we harness the collective talents and strengths of our diverse workforce to achieve our shared objectives and deliver exceptional results that make a meaningful difference in the lives of individuals and communities.





          </p>
        </div>
        <!-- Add more subheadings as needed -->
      </div>
    </div>
  </div>

  <!-- Footer -->
  <footer class="bg-dark text-white text-center py-4 mt-5">
    <p>&copy; 2024 PharmaCompany-Kirtik Roshan G R(212221043002). All rights reserved.</p>
  </footer>

  <!-- Bootstrap JS -->
  <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js"></script>
  <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>
```
# contact.html
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>About Us</title>
  <!-- Bootstrap CSS -->
  <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
  <!-- Custom CSS -->
  <style>
    body {
      background-image: url("");
      background-size: cover;
      background-repeat: no-repeat;
      font-size: 19px;
    }
    footer{
    position: fixed;
      left: 0;
      bottom: 0;
      width: 100%;
      background-color: #000000; 
      color: white;
      text-align: center;
      padding: 10px 0; 
    }
  </style>
</head>
<body>

  <!-- Navbar -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-success">
    <a class="navbar-brand" href="#">HM PHARMACEUTICALS</a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>

    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav mr-auto">
        <li class="nav-item">
          <a class="nav-link" href="home.html">Home</a>
        </li>
        <li class="nav-item dropdown active">
          <a class="nav-link dropdown-toggle" href="about.html" id="navbarDropdownAbout" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
            About
          </a>
          <div class="dropdown-menu" aria-labelledby="navbarDropdownAbout">
            <a class="dropdown-item" href="#vision">Vision</a>
            <a class="dropdown-item" href="#mission">Mission</a>
            <a class="dropdown-item" href="#values">Values</a>
            <!-- Add more subheadings as needed -->
          </div>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="products.html">Products</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Contact</a>
        </li>
      </ul>
    </div>
  </nav>

  <!-- Page Content -->
  <div class="container mt-5">
    <div class="row">
      <div class="col-md-12">
        <h1>About HM PHARMACEUTICALS</h1>
        <div id="vision">
          <h2>Vision</h2>
          <p>Our vision is to become a global leader in providing groundbreaking healthcare solutions that enhance the well-being of individuals worldwide. We aspire to pioneer innovations that redefine healthcare standards, empowering people to lead healthier, more fulfilling lives.</p>
        </div>
        <div id="mission">
          <h2>Mission</h2>
          <p>Our mission is to develop and deliver a comprehensive range of safe, effective, and affordable healthcare solutions that cater to the diverse needs of our customers. Through relentless dedication to research, development, and collaboration, we aim to address unmet medical needs and contribute positively to the health and vitality of communities globally.</p>
        </div>
        <div id="values">
          <h2>Values</h2>
          <p>Quality lies at the core of everything we do, as we uphold the highest standards of excellence in all aspects of our operations. Integrity forms the foundation of our business practices, guiding us to conduct ourselves with unwavering honesty, transparency, and ethical conduct. Innovation fuels our quest for progress, driving us to continually push boundaries and improve our products and services to better serve our customers. With a relentless focus on customer needs, we strive to understand and anticipate their requirements, ensuring their satisfaction and trust. Through teamwork and collaboration, we harness the collective talents and strengths of our diverse workforce to achieve our shared objectives and deliver exceptional results that make a meaningful difference in the lives of individuals and communities.





          </p>
        </div>
        <!-- Add more subheadings as needed -->
      </div>
    </div>
  </div>

  <!-- Footer -->
  <footer class="bg-dark text-white text-center py-4 mt-5">
    <p>&copy; 2024 PharmaCompany-Kirtik Roshan G R(212221043002). All rights reserved.</p>
  </footer>

  <!-- Bootstrap JS -->
  <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js"></script>
  <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>
```

## OUTPUT:
![image](https://github.com/dilipsanjay/Pharma/assets/155506948/c832d21d-8d5a-4a9d-8122-50a8f1ff6eaf)
![image](https://github.com/dilipsanjay/Pharma/assets/155506948/fc896ccf-2259-48e5-836a-efe33cf14a4b)
![image](https://github.com/dilipsanjay/Pharma/assets/155506948/17d427be-0bd7-4dae-8218-19f556406acb)
![image](https://github.com/dilipsanjay/Pharma/assets/155506948/f6cc6eef-e7ae-4967-92fe-8a1d213ac9be)


## RESULT:
The program for responsive web design using Bootstrap is completed successfully.
