# Project Responsive Web Design using Bootstrap
## Date:26-12-24

## AIM:
To create a simplified clone of Dribbble (https://dribbble.com/) landing page.


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
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Digital Destination</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>
  <nav class="navbar navbar-expand-lg navbar-dark shadow-sm" style="background: linear-gradient(90deg, red, yellow);">
    <div class="container">
      <a class="navbar-brand" href="#">Dribble Website</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item">
            <a class="nav-link active" href="#">Home</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Shop</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Product</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Contact</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>
  <div class="container my-5">
    <h1 class="text-center mb-4 text-danger fw-bold">Explore Our Products</h1>
    <div class="row">
      <div class="col-lg-3 col-md-4 col-sm-6 mb-4">
        <div class="card shadow-sm h-100">
          <img src="hp.jpg" class="card-img-top" alt="Hp Laptop" style="height: 200px; object-fit: cover;">
          <div class="card-body text-center">
            <h6 class="card-title fw-bold">Hp Laptop</h6>
          </div>
        </div>
      </div>
      <div class="col-lg-3 col-md-4 col-sm-6 mb-4">
        <div class="card shadow-sm h-100">
          <img src="dell.jpg" class="card-img-top" alt="Dell Laptop" style="height: 200px; object-fit: cover;">
          <div class="card-body text-center">
            <h6 class="card-title fw-bold">Dell Laptop</h6>
          </div>
        </div>
      </div>
      <div class="col-lg-3 col-md-4 col-sm-6 mb-4">
        <div class="card shadow-sm h-100">
          <img src="lenova.jpg" class="card-img-top" alt="Lenovo Laptop" style="height: 200px; object-fit: cover;">
          <div class="card-body text-center">
            <h6 class="card-title fw-bold">Lenovo Laptop</h6>
          </div>
        </div>
      </div>
      <div class="col-lg-3 col-md-4 col-sm-6 mb-4">
        <div class="card shadow-sm h-100">
          <img src="apple.jpg" class="card-img-top" alt="Apple Laptop" style="height: 200px; object-fit: cover;">
          <div class="card-body text-center">
            <h6 class="card-title fw-bold">Apple Laptop</h6>
          </div>
        </div>
      </div>
      <div class="col-lg-3 col-md-4 col-sm-6 mb-4">
        <div class="card shadow-sm h-100">
          <img src="applep.jpg" class="card-img-top" alt="Apple iPhone" style="height: 200px; object-fit: cover;">
          <div class="card-body text-center">
            <h6 class="card-title fw-bold">Apple iPhone</h6>
          </div>
        </div>
      </div>
      <div class="col-lg-3 col-md-4 col-sm-6 mb-4">
        <div class="card shadow-sm h-100">
          <img src="appleb.jpg" class="card-img-top" alt="Apple Earbuds" style="height: 200px; object-fit: cover;">
          <div class="card-body text-center">
            <h6 class="card-title fw-bold">Apple Earbuds</h6>
          </div>
        </div>
      </div>
      <div class="col-lg-3 col-md-4 col-sm-6 mb-4">
        <div class="card shadow-sm h-100">
          <img src="applew.jpg" class="card-img-top" alt="Apple Watch" style="height: 200px; object-fit: cover;">
          <div class="card-body text-center">
            <h6 class="card-title fw-bold">Apple Watch</h6>
          </div>
        </div>
      </div>
      <div class="col-lg-3 col-md-4 col-sm-6 mb-4">
        <div class="card shadow-sm h-100">
          <img src="applei.jpg" class="card-img-top" alt="Apple Tab" style="height: 200px; object-fit: cover;">
          <div class="card-body text-center">
            <h6 class="card-title fw-bold">Apple Tab</h6>
          </div>
        </div>
      </div>
    </div>
  </div>
  <footer class="text-center py-3" style="background: linear-gradient(90deg, red, yellow); color: #fff;">
    <div class="container">
      <p>© Designed and Developed by Sunil.A</p>
    </div>
  </footer>
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>



```


## OUTPUT:
![alt text](<Screenshot (68).png>)

## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
