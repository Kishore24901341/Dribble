# Project Responsive Web Design using Bootstrap
## Date:24:12:2024

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
main.html:

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dribbble Clone</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/css/bootstrap.min.css" rel="stylesheet">
    <style>
        body {
            font-family: 'Arial', sans-serif;
            background: linear-gradient(135deg, #2c3e50, #34495e, #5d6d7e);
            color: white;
        }
        .navbar {
            background-color: #2c3e50;
        }
        .navbar-brand {
            color: #e74c3c;
        }
        .navbar-brand:hover {
            color: #f39c12;
        }
        .btn-custom {
            background-color: #e74c3c;
            border: none;
            color: white;
        }
        .btn-custom:hover {
            background-color: #f39c12;
        }
        .portfolio-item img {
            border-radius: 10px;
            transition: transform 0.3s;
        }
        .portfolio-item img:hover {
            transform: scale(1.05);
        }
        .portfolio-stats {
            font-size: 0.9rem;
            color: #bdc3c7;
        }
        .card-title {
            color: #34495e;
        }
        .card-title:hover {
            color: #2c3e50;
        }
        .custom-footer {
            background: #2c3e50;
            color: #bdc3c7;
        }
        .main-heading {
            text-align: center;
            font-size: 2rem;
            font-weight: bold;
            color: #fff;
            background-color: #34495e;
            padding: 20px;
            margin-bottom: 25px;
            border-radius: 12px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.3);
        }
        .sub-heading {
            text-align: center;
            font-size: 1.1rem;
            font-weight: 500;
            color: #bdc3c7;
            margin-top: -8px;
        }
    </style>
</head>
<body>
    
    <nav class="navbar navbar-expand-lg navbar-dark">
        <div class="container-fluid">
            <a class="navbar-brand" href="#">Dribbble Clone</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <form class="d-flex ms-auto me-3">
                    <input class="form-control me-2" type="search" placeholder="Search creative works" aria-label="Search">
                    <button class="btn btn-outline-light" type="submit">Search</button>
                </form>
                <ul class="navbar-nav">
                    <li class="nav-item">
                        <a class="nav-link" href="#">Log in</a>
                    </li>
                    <li class="nav-item">
                        <a class="btn btn-custom" href="#">Join now</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>

    <header class="main-heading">
        Showcase your creativity. Connect with like-minded designers.
        <p class="sub-heading">Explore creative works and discover new trends</p>
    </header>

    <div id="portfolio" class="container py-5">
        <h2 class="text-center mb-4">Trending Designs</h2>
        <div class="row g-4">
            <div class="col-md-4 portfolio-item">
                <div class="card">
                    <img src="ai.jpg" class="card-img-top" alt="Portfolio Item">
                    <div class="card-body">
                        <h5 class="card-title">AI Innovation</h5>
                        <p class="portfolio-stats">5,012 views | 350 likes</p>
                    </div>
                </div>
            </div>
            <div class="col-md-4 portfolio-item">
                <div class="card">
                    <img src="art.jpg" class="card-img-top" alt="Portfolio Item">
                    <div class="card-body">
                        <h5 class="card-title">Colorful Abstracts</h5>
                        <p class="portfolio-stats">4,500 views | 290 likes</p>
                    </div>
                </div>
            </div>
            <div class="col-md-4 portfolio-item">
                <div class="card">
                    <img src="civ.jpg" class="card-img-top" alt="Portfolio Item">
                    <div class="card-body">
                        <h5 class="card-title">Architectural Wonders</h5>
                        <p class="portfolio-stats">3,200 views | 250 likes</p>
                    </div>
                </div>
            </div>
            <div class="col-md-4 portfolio-item">
                <div class="card">
                    <img src="ece.jpg" class="card-img-top" alt="Portfolio Item">
                    <div class="card-body">
                        <h5 class="card-title">Tech Innovations</h5>
                        <p class="portfolio-stats">2,500 views | 200 likes</p>
                    </div>
                </div>
            </div>
            <div class="col-md-4 portfolio-item">
                <div class="card">
                    <img src="mec.jpg" class="card-img-top" alt="Portfolio Item">
                    <div class="card-body">
                        <h5 class="card-title">Mechanical Design Mastery</h5>
                        <p class="portfolio-stats">3,000 views | 220 likes</p>
                    </div>
                </div>
            </div>
            <div class="col-md-4 portfolio-item">
                <div class="card">
                    <img src="OIP.jpg" class="card-img-top" alt="Portfolio Item">
                    <div class="card-body">
                        <h5 class="card-title">Visual Creativity</h5>
                        <p class="portfolio-stats">2,000 views | 150 likes</p>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <footer class="custom-footer text-center py-3">
        <p>&copy; 2024 Dribbble Clone. Designed by Kishore.</p>
    </footer>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>

```

## OUTPUT:
![Uploading Screenshot 2024-12-24 094548.png…]()


## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
