# Project Responsive Web Design using Bootstrap
## Date:25-12-24

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
<html>

<head>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet"
        integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
</head>

<body style="background-image: url('fashion.jpg'); background-size: cover; background-repeat: no-repeat; height: 100vh;">
    <nav class="navbar navbar-expand-lg navbar-dark sticky-top" style="background-color: rgb(9, 235, 81);">
        <div class="container-fluid">
            <a class="navbar-brand fw-bold" href="https://www.google.co.in/" title="Google" style="font-family: fantasy;">Fashion fantacy</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav"
                aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item"><a class="nav-link text-light active" href="#">Home</a></li>
                    <li class="nav-item"><a class="nav-link text-light" href="about.html">About</a></li>
                    <li class="nav-item"><a class="nav-link text-light" href="#">Products</a></li>
                    <li class="nav-item"><a class="nav-link text-light" href="#">Contact</a></li>
                </ul>
            </div>
        </div>
    </nav>

    <div id="carouselExampleCaptions" class="carousel slide" data-bs-ride="carousel">
        <div class="carousel-indicators">
            <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
            <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="1" aria-label="Slide 2"></button>
            <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="2" aria-label="Slide 3"></button>
        </div>
        <div class="carousel-inner">
            <div class="carousel-item active">
               
                <div class="carousel-caption d-none d-md-block">
                    <h1 class="text-warning">WELCOME TO FASHION WORLDS</h1>
                    <p style="color: red;">Explore latest fashion.</p>
                    <a href="service.html" class="btn btn-lg btn-outline-light">Visit Now</a>
                </div>
            </div>
            <div class="carousel-item">
                <div class="carousel-caption d-none d-md-block">
                    <h1 class="text-info">DISCOVER AMAZING FASHIONS</h1>
                    
                </div>
            </div>
            <div class="carousel-item">
                <div class="carousel-caption d-none d-md-block">
                    <h1 class="text-success">EXPERIENCE QUALITY</h1>
                    <p>Your satisfaction is our priority.</p>
                </div>
            </div>
        </div>
        <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide="prev">
            <span class="carousel-control-prev-icon" aria-hidden="true"></span>
            <span class="visually-hidden">Previous</span>
        </button>
        <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide="next">
            <span class="carousel-control-next-icon" aria-hidden="true"></span>
            <span class="visually-hidden">Next</span>
        </button>
    </div>

    <section class="container mt-5">
        <h2 class="text-center text-info mb-4">Our Featured Products</h2>
        <div class="row row-cols-1 row-cols-md-3 g-4">
            <div class="col">
                <div class="card h-100 border-warning shadow">
                    <img src="shirt.jpg" class="card-img-top" alt="Shirt">
                    <div class="card-body">
                        <h5 class="card-title text-warning">SHIRTS</h5>
                        <p class="card-text">100% Cotton Shirts</p>
                        <a href="#" class="btn btn-warning">Buy Now</a>
                    </div>
                </div>
            </div>

            <div class="col">
                <div class="card h-100 border-success shadow">
                    <img src="pant.jpg" class="card-img-top" alt="Pant">
                    <div class="card-body">
                        <h5 class="card-title text-success">Pant</h5>
                        <p class="card-text">latest trending Pant</p>
                        <a href="#" class="btn btn-success">Buy Now</a>
                    </div>
                </div>
            </div>

                    
                
            

            <div class="col">
                <div class="card h-100 border-info shadow">
                    <img src="tshirt.jpg" class="card-img-top" alt="Tshirt">
                    <div class="card-body">
                        <h5 class="card-title text-info">Tshirt</h5>
                        <p class="card-text">Wear Comfort</p>
                        <a href="#" class="btn btn-info">Buy Now</a>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section class="bg-gradient text-light py-5 mt-5" style="background: linear-gradient(45deg, #7a07f5, #2575fc);">
        <div class="container">
            <div class="row text-center">
                <div class="col-md-4">
                    <h4 style="color: rgb(37, 14, 210);">Fast Delivery</h4>
                    <p style="color: rgb(206, 213, 12);">Get your orders delivered quickly and safely.</p>
                </div>
                <div class="col-md-4">
                    <h4 style="color: rgb(157, 16, 133);">Quality Assurance</h4>
                    <p style="color: rgb(15, 181, 67);">Products tested for top-notch quality.</p>
                </div>
    
        </div>
    </section>

    <footer class="bg-dark text-light text-center py-3">
        <div class="container">
            <p>&copy; 2024 Designed and Developed by Sunil.A</p>
        </div>
    </footer>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"
        integrity="sha384-YvpcrYf0tY3lHB60NNkmXc5s9fDVZLESaAA55NDzOxhy9GkcIdslK1eN7N6jIeHz"
        crossorigin="anonymous"></script>
</body>

</html>


```


## OUTPUT:
![alt text](<Screenshot (67).png>)

## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
