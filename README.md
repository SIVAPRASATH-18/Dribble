# Project Responsive Web Design using Bootstrap
## Date:15-10-2025

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
drib.html


<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>phones</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
  <link href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.1/font/bootstrap-icons.css" rel="stylesheet">
</head>
<body class="bg-light">

  <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
    <div class="container">
      <a class="navbar-brand fw-bold" href="#">DRIBBLE  &nbsp;  &nbsp;  &nbsp;</a>
      <a class="navbar-brand fw-bold" href="#">   shots &nbsp; designers &nbsp; teams &nbsp; community &nbsp; jobs &nbsp; ...</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse justify-content-end" id="navbarNav">
        <ul class="navbar-nav">
          <li class="nav-item"><a class="nav-link" href="#">Sign up</a></li>
          <li class="nav-item"><a class="nav-link" href="#">Sign in</a></li>
        </ul>
      </div>
    </div>
  </nav>
  <div class="bg-red text-center py-3 border-bottom">
    <b>What are you working on ?</b>Dribble is show and tell for designers
    <div class="collapse navbar-collapse justify-content-end bg-dark" id="navbarNav">
      <ul class="navbar-nav">
        <li class="nav-item navbar-right"><a class="nav-link" href="#">LOGIN</a></li>
        <li class="nav-item navbar-right"><a class="nav-link" href="#">Sign in</a></li>
      </ul>
    </div>
  </div>
  <div class="container py-0">
    <div class="row g-0">

      <div class="col-md-2 col-sm-0">
        <div class="card border-0 shadow-sm">
          <img src="google.jpeg" class="card-img-top" alt="">
          <div class="card-body">
            <h6 class="card-title">GOOGLE PIXEL</h6>
            <small class="text-muted">
              <i class="bi bi-eye"></i> 40044
              <i class="bi bi-chat ms-2"></i> 1114
              <i class="bi bi-heart ms-2 text-danger"></i> 29078
            </small>
          </div>
        </div>
      </div>

      <div class="col-md-2 col-sm-0">
        <div class="card border-0 shadow-sm">
          <img src="iphone 15.jpg" class="card-img-top" alt="">
          <div class="card-body">
            <h6 class="card-title">I PHONE</h6>
            <small class="text-muted">
              <i class="bi bi-eye"></i> 76404
              <i class="bi bi-chat ms-2"></i> 1013
              <i class="bi bi-heart ms-2 text-danger"></i> 20456
            </small>
          </div>
        </div>
      </div>

      <div class="col-md-2 col-sm-0">
        <div class="card border-0 shadow-sm">
          <img src="samsung.jpeg" class="card-img-top" alt="">
          <div class="card-body">
            <h6 class="card-title">SAMSUNG</h6>
            <small class="text-muted">
              <i class="bi bi-eye"></i> 79859
              <i class="bi bi-chat ms-2"></i> 917
              <i class="bi bi-heart ms-2 text-danger"></i> 26445
            </small>
          </div>
        </div>
      </div>

      <div class="col-md-2 col-sm-0">
        <div class="card border-0 shadow-sm">
          <img src="vivo.jpg" class="card-img-top" alt="">
          <div class="card-body">
            <h6 class="card-title">VIVO</h6>
            <small class="text-muted">
              <i class="bi bi-eye"></i> 76024
              <i class="bi bi-chat ms-2"></i> 723
              <i class="bi bi-heart ms-2 text-danger"></i> 18656
            </small>
          </div>
        </div>
      </div>

      <div class="col-md-2 col-sm-0">
        <div class="card border-0 shadow-sm">
          <img src="redmi.jpeg" class="card-img-top" alt="">
          <div class="card-body">
            <h6 class="card-title">REDMI</h6>
            <small class="text-muted">
              <i class="bi bi-eye"></i> 44859
              <i class="bi bi-chat ms-2"></i> 881
              <i class="bi bi-heart ms-2 text-danger"></i> 20445
            </small>
          </div>
        </div>
      </div>

      <div class="col-md-2 col-sm-0">
        <div class="card border-0 shadow-sm">
          <img src="infinix.jpeg" class="card-img-top" alt="">
          <div class="card-body">
            <h6 class="card-title">INFINIX GT</h6>
            <small class="text-muted">
              <i class="bi bi-eye"></i> 48909
              <i class="bi bi-chat ms-2"></i> 678
              <i class="bi bi-heart ms-2 text-danger"></i> 23545
            </small>
          </div>
        </div>
      </div>

      <div class="col-md-2 col-sm-0">
        <div class="card border-0 shadow-sm">
          <img src="oppo.jpeg" class="card-img-top" alt="">
          <div class="card-body">
            <h6 class="card-title">OPPO</h6>
            <small class="text-muted">
              <i class="bi bi-eye"></i> 37059
              <i class="bi bi-chat ms-2"></i> 661
              <i class="bi bi-heart ms-2 text-danger"></i> 15045
            </small>
          </div>
        </div>
      </div>

      <div class="col-md-2 col-sm-0">
        <div class="card border-0 shadow-sm">
          <img src="nokia.jpeg" class="card-img-top" alt="">
          <div class="card-body">
            <h6 class="card-title">NOKIA</h6>
            <small class="text-muted">
              <i class="bi bi-eye"></i> 39059
              <i class="bi bi-chat ms-2"></i> 981
              <i class="bi bi-heart ms-2 text-danger"></i> 14445
            </small>
          </div>
        </div>
      </div>

      <div class="col-md-2 col-sm-0">
        <div class="card border-0 shadow-sm">
          <img src="sony.webp" class="card-img-top" alt="">
          <div class="card-body">
            <h6 class="card-title">SONY</h6>
            <small class="text-muted">
              <i class="bi bi-eye"></i> 67059
              <i class="bi bi-chat ms-2"></i> 1281
              <i class="bi bi-heart ms-2 text-danger"></i> 23445
            </small>
          </div>
        </div>
      </div>

      <div class="col-md-2 col-sm-0">
        <div class="card border-0 shadow-sm">
          <img src="huawei.jpeg" class="card-img-top" alt="">
          <div class="card-body">
            <h6 class="card-title">HUAWEI</h6>
            <small class="text-muted">
              <i class="bi bi-eye"></i> 49059
              <i class="bi bi-chat ms-2"></i> 1087
              <i class="bi bi-heart ms-2 text-danger"></i>19045
            </small>
          </div>
        </div>
      </div>

      <div class="col-md-2 col-sm-0">
        <div class="card border-0 shadow-sm">
          <img src="realme.png" class="card-img-top" alt="">
          <div class="card-body">
            <h6 class="card-title">REALME</h6>
            <small class="text-muted">
              <i class="bi bi-eye"></i> 39959
              <i class="bi bi-chat ms-2"></i> 781
              <i class="bi bi-heart ms-2 text-danger"></i> 17445
            </small>
          </div>
        </div>
      </div>

      <div class="col-md-2 col-sm-0">
        <div class="card border-0 shadow-sm">
          <img src="motor.jpg" class="card-img-top" alt="">
          <div class="card-body">
            <h6 class="card-title">MOTOROLA</h6>
            <small class="text-muted">
              <i class="bi bi-eye"></i> 49059
              <i class="bi bi-chat ms-2"></i> 974
              <i class="bi bi-heart ms-2 text-danger"></i> 14845
            </small>
          </div>
        </div>
      </div>

<footer class="bg-dark text-center text-light py-1">
   PRIME PHONES 2025 © SIVAPRASATH B-25016007
</footer>

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
```


## OUTPUT:

![alt text](<Screenshot 2025-10-17 150435.png>)

## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
