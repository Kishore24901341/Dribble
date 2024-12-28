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
<html>
<head>
    <title>Dribbble Clone</title>
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
</head>
<body>
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
        <a class="navbar-brand" href="#">Dribbble</a>
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
            <ul class="navbar-nav ml-auto">
                <li class="nav-item"><a class="nav-link" href="#">Shots</a></li>
                <li class="nav-item"><a class="nav-link" href="#">Designers</a></li>
                <li class="nav-item"><a class="nav-link" href="#">Teams</a></li>
                <li class="nav-item"><a class="nav-link" href="#">Community</a></li>
                <li class="nav-item"><a class="nav-link" href="#">Jobs</a></li>
                <li class="nav-item"><a class="btn btn-primary" href="#">Sign Up</a></li>
            </ul>
        </div>
    </nav>

    <div class="container mt-4">
        <div class="text-center mb-4 header-section">
            <h3>What are you working on?</h3>
            <p class="lead">Dribbble is show and tell for designers.</p>
        </div>

        <div class="row gallery-section">
            <div class="col-md-3 col-sm-6 mb-4">
                <div class="card shadow gallery-item">
                    <img src="ai.jpg" class="card-img-top gallery-img" alt="Design Thumbnail" width="250" height="250">
                    <div class="card-body text-center">
                        <p class="card-title">AetherIntellect</p>
                        <small class="text-muted">AIKish</small>
                    </div>
                </div>
            </div>
            <div class="col-md-3 col-sm-6 mb-4">
                <div class="card shadow gallery-item">
                    <img src="art.jpg" class="card-img-top gallery-img" alt="Design Thumbnail" width="250" height="250">
                    <div class="card-body text-center">
                        <p class="card-title">Visionary
                        </p>
                        <small class="text-muted">Creations
                        </small>
                    </div>
                </div>
            </div>
            <div class="col-md-3 col-sm-6 mb-4">
                <div class="card shadow gallery-item">
                    <img src="civ.jpg" class="card-img-top gallery-img" alt="Design Thumbnail" width="250" height="250">
                    <div class="card-body text-center">
                        <p class="card-title">Civil</p>
                        <small class="text-muted">CivTech</small>
                    </div>
                </div>
            </div>
            <div class="col-md-3 col-sm-6 mb-4">
                <div class="card shadow gallery-item">
                    <img src="ece.jpg" class="card-img-top gallery-img" alt="Design Thumbnail" width="250" height="250">
                    <div class="card-body text-center">
                        <p class="card-title">ElectroLab</p>
                        <small class="text-muted">ECE Vision</small>
                    </div>
                </div>
            </div>
            <div class="col-md-3 col-sm-6 mb-4">
                <div class="card shadow gallery-item">
                    <img src="mec.jpg" class="card-img-top gallery-img" alt="Design Thumbnail" width="250" height="250">
                    <div class="card-body text-center">
                        <p class="card-title">MechWorks</p>
                        <small class="text-muted">PrecisionMech
                        </small>
                    </div>
                </div>
            </div>
            <div class="col-md-3 col-sm-6 mb-4">
                <div class="card shadow gallery-item">
                    <img src="OIP.jpg" class="card-img-top gallery-img" alt="Design Thumbnail" width="250" height="250">
                    <div class="card-body text-center">
                        <p class="card-title">Discovery</p>
                        <small class="text-muted">Research</small>
                    </div>
                </div>
            </div>
            <div class="col-md-3 col-sm-6 mb-4">
                <div class="card shadow gallery-item">
                    <img src="ARTI.jpg" class="card-img-top gallery-img" alt="Design Thumbnail" width="250" height="250">
                    <div class="card-body text-center">
                        <p class="card-title"> Design Studio</p>
                        <small class="text-muted">ArchiVision</small>
                    </div>
                </div>
            </div>
            <div class="col-md-3 col-sm-6 mb-4">
                <div class="card shadow gallery-item">
                    <img src="CYBS.jpg" class="card-img-top gallery-img" alt="Design Thumbnail" width="250" height="250">
                    <div class="card-body text-center">
                        <p class="card-title">LogicWorks</p>
                        <small class="text-muted">CyberSphere</small>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <footer class="bg-dark text-white text-center py-3">
        <p>All rights reserved by Kishore.V</p>
    </footer>
    <script src="https://code.jquery.com/jquery-3.5.1.min.js"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.bundle.min.js"></script>
</body>
</html>


```

## OUTPUT:
![image](https://github.com/user-attachments/assets/06b36831-33e8-4770-a493-8b988eb911cc)


## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
