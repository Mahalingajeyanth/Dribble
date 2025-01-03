# Project Responsive Web Design using Bootstrap
## Date:19/12/2024

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
    <title>VMJ Pharmacy Company</title>
    <!-- Bootstrap CSS CDN -->
    <link href="https://maxcdn.bootstrapcdn.com/bootstrap/5.3.0/css/bootstrap.min.css" rel="stylesheet">
</head>

<body>
    <!-- Navigation Bar -->
    <nav class="navbar navbar-expand-lg navbar-dark bg-primary">
        <div class="container-fluid">
            <a class="navbar-brand" href="#">VMJ pharmacy&Co</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item">
                        <a class="nav-link active" href="#home">Home</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#products">Products</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#contact">Contact</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>

    <!-- Home Section -->
    <section id="home" class="p-5 bg-light text-center">
        <div class="container">
            <h1>Welcome to VMJPharmacy&Co</h1>
            <p>Your trusted pharmacy partner for quality medicines and healthcare products.</p>
        </div>
    </section>

    <!-- Products Section -->
    <section id="products" class="p-5">
        <div class="container text-center">
            <h2>Our Products</h2>
            <div class="row mt-4">
                <div class="col-md-4">
                    <div class="card">
                        <img src="m2.png" class="card-img-top" alt="Medicine">
                        <div class="card-body">
                            <h5 class="card-title">Medicines</h5>
                            <p class="card-text">High-quality medicines for all health needs.</p>
                        </div>
                    </div>
                </div>
                <div class="row mt-4">
                    <div class="col-md-4">
                        <div class="card">
                            <img src="medicines.png" class="card-img-top" alt="Supplements">
                            <div class="card-body">
                                <h5 class="card-title">Supplements</h5>
                                <p class="card-text">Boost your health with our range of supplements.</p>
                            </div>
                        </div>
                    </div>
                    <div class="row mt-4">
                        <div class="col-md-4">
                            <div class="card">
                                <img src="boost.png" class="card-img-top" alt="Equipment">
                                <div class="card-body">
                                    <h5 class="card-title">Healthcare Equipment</h5>
                                    <p class="card-text">Reliable medical equipment for healthcare needs.</p>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="p-5 bg-light text-center">
        <div class="container">
            <h2>Contact Us</h2>
            <p>Email: VMJ@pharmaco.com | Phone: +91 7200663404</p>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-dark text-white text-center p-3">
        <p>Designed and Developed by Mahalinga jeyanth V(24900649)</p>
    </footer>

    <!-- Bootstrap JS Bundle with Popper -->
    <script src="https://cdnjs.cloudflare.com/ajax/libs/bootstrap/5.3.0/js/bootstrap.bundle.min.js"></script>
</body>

</html>


```

## OUTPUT :
![alt text](<Screenshot 2024-12-21 160215.png>)
![alt text](<Screenshot 2024-12-21 160247.png>)
![alt text](<Screenshot 2024-12-21 160317.png>)
![alt text](<Screenshot 2024-12-21 160349.png>)


## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
