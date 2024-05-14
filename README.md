# Ex.10 Responsive Web Design using Bootstrap
## Date:13/05/2024

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
```
<home.html>
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>INDIANA PHARMA</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-1BmE4kWBq78iYhFldvKuhfTAU6auU8tT94WrHftjDbrCEXSU1oBoqyl2QvZ6jIW3" crossorigin="anonymous">
</head>
<body>

  <nav class="navbar navbar-expand-lg navbar-light bg-warning">
    <div class="container-fluid">
      <a class="navbar-brand" href="#"><B><font face="Perpetua Titling MT" size="4" >INDIANA PHARMA</font></a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNavAltMarkup" aria-controls="navbarNavAltMarkup" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
        <div class="navbar-nav">
          <a class="nav-link active" aria-current="page" href="home.html">Home</a>
          <a class="nav-link" href="about.html">About</a>
          <a class="nav-link" href="products.html">Products</a>
          <a class="nav-link" href="contact.html">Contact</a>
          <div class="nav-item dropdown">
            <a class="nav-link dropdown-toggle" href="#" id="navbarDropdownMenuLink" role="button" data-bs-toggle="dropdown" aria-expanded="false">
              Register
            </a>
            <ul class="dropdown-menu" aria-labelledby="navbarDropdownMenuLink">
              <li><a class="dropdown-item" href="#">Login</a></li>
              <li><a class="dropdown-item" href="#">Sign Up</a></li>
            </ul>
          </div>
        </div>
      </div>
    </div>
  </nav>
  <section class="container mt-2">
    <div class="row">
      <div class="col-md-5">
        <div class="col-md-5" >
          <body>
          <img src="T8.png" align="left" border="3" class="img-fluid"></body>
        </div>
        <br>
        <h1>Welcome to <b><font face="Harlow Solid Italic" size="9" color= "darkpink">INDIANA PHARMA COMPANY</font></h1>
          <br>
        <p>We are dedicated to developing and delivering high-quality pharmaceutical products to improve people's lives.</p>
        <br>
        <p>INDIANA is one of the world’s premier biopharmaceutical companies. It has a rich history of scientific innovation spanning 175 years. INDIANA continues to develop innovative therapies that impact healthcare globally, particularly in areas like cancer treatment3</p>
        <p>Founded in 1983,INDIANA Pharma is a leading multinational pharmaceutical company in India. It offers products to treat in various therapeutic areas.INDIANA revenue in 2023 was INR 44,520 crore.</p>
        <br>
        <a href="about.html" class="btn btn-warning">LOGIN<br></a>
        <a href="about.html" class="btn btn-light">SIGNUP<br></a>
        <br>
        <br>
        <a href="about.html" class="btn btn-dark">Learn More<br></a> 
      </div>
      
    </div>
    <body background="t5 - Copy.jpg" style="background-repeat: no-repeat; background-size: cover;">
  </section>

  <footer class="text-center p-2 bg-success mt-5">
  
    <p>Copyright &copy; <?php echo date("Y"); ?> INDIANA PHARMA COMPANY - STA INDUSTRIES</p>
  </footer>

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-ka7Sk0Gln4gmtz2MlQnikT1wXgYsOg+OMhuP+IlRH9sENBO0LRn5q+8nbTov4+1p" crossorigin="anonymous"></script>
</body>
</html>
```
```
<about.html>
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>INDIANA PHARMA</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-1BmE4kWBq78iYhFldvKuhfTAU6auU8tT94WrHftjDbrCEXSU1oBoqyl2QvZ6jIW3" crossorigin="anonymous">
</head>
<body>

    <nav class="navbar navbar-expand-lg navbar-light bg-warning">
        <div class="container-fluid">
          <a class="navbar-brand" href="#"><B><font face="Perpetua Titling MT" size="4" >INDIANA PHARMA</font></a>
          <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNavAltMarkup" aria-controls="navbarNavAltMarkup" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
          </button>
          <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
            <div class="navbar-nav">
              <a class="nav-link active" aria-current="page" href="home.html">Home</a>
              <a class="nav-link" href="about.html">About</a>
              <a class="nav-link" href="products.html">Products</a>
              <a class="nav-link" href="contact.html">Contact</a>
              <div class="nav-item dropdown">
                <a class="nav-link dropdown-toggle" href="#" id="navbarDropdownMenuLink" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                  Register
                </a>
                <ul class="dropdown-menu" aria-labelledby="navbarDropdownMenuLink">
                  <li><a class="dropdown-item" href="#">Login</a></li>
                  <li><a class="dropdown-item" href="#">Sign Up</a></li>
                </ul>
              </div>
            </div>
          </div>
        </div>
      </nav>

  <!-- Page Content -->
  <div class="container mt-5">
    <div class="row">
      <div class="col-md-12">
        <h1><font face="Perpetua Titling MT" size="10" ><b>About INDIANA PHARMA</h1></font>
        <div id="vision">
          <h2><b>Vision</h2>
          <p>Our vision is to be a leading pharmaceutical company in India and to become a significant global player by providing high quality, affordable and innovative solutions in medicine and treatment.</p>
        </div>
        <BODY>
            <IMG src="t9.jpeg" 
            height="150" width="400" align="center" border="5">
        </BODY>
        <div id="mission">
          <h2><b>Mission</h2>
          <p> To discover, develop, and successfully market pharmaceutical products that prevent, diagnose, alleviate, and cure diseases. They aim for total customer satisfaction and leadership in chosen markets worldwide through excellence in technology and research1.</p>
         <p>Consistently deliver high-quality, safe, and effective pharmaceutical products and services globally. They achieve this through good manufacturing practices, state-of-the-art technology, a competent workforce, and efficient management</p>
        </div>
        <div id="values">
          <h2><b>Values</h2>
          <ul>
            <li>Quality:From the very beginning, Quality has been the core of our existence. Unimarckens are persistently putting efforts in manufacturing high-quality products for society.</li>
            <li>Commitment to Excellence:We believe commitment drives the force for achieving excellence for products to stand at par in the pharmaceutical industry. We pursue </li>
          </ul>
        </div>
      </div>
    </div>
  </div>
  <body background="t6 - Copy.jpg" style="background-repeat: no-repeat; background-size: cover;"></body>
  <footer class="text-center p-3 bg-success mt-5">
    <p>Copyright &copy; <?php echo date("Y"); ?> INDIANA PHARMA COMPANY - STA INDUSTRIES</p>
  </footer>

  <!-- Bootstrap JS -->
  <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js"></script>
  <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>
```
```
<products.html>
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>INDIANA PHARMA</title>
  <!-- Bootstrap CSS -->
  <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>

  <!-- Navbar -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-warning">
    <a class="navbar-brand" href="#"><B><font face="Perpetua Titling MT" size="4" >INDIANA PHARMA</font></a>
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
        <li class="nav-item dropdown">
          <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
            Products
          </a>
          <div class="dropdown-menu" aria-labelledby="navbarDropdown">
            <a class="dropdown-item" href="#">Over-the-counter (OTC) Medications</a>
            <a class="dropdown-item" href="#">Prescription Drugs</a>
            <a class="dropdown-item" href="#">Vaccines</a>
            <a class="dropdown-item" href="#">Supplements</a>
          </div>
        </li>
        <li class="nav-item active">
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
  <div class="container mt-3">
    <div class="row">
      <div class="col-md-12">
        <h5>Our Product Categories</h5>
        <div class="card-deck">
          <div class="card">
            <img src="t10.jpg" class="card-img-top" alt="Product 1" width="200" height="200">
            <div class="card-body">
              <h5 class="card-title">Over-the-counter (OTC)</h5>
              <p class="card-text">These drugs you can buy without a prescription. Some OTC medicines relieve aches, pains, and itches.</p>
              <a href="#" class="btn btn-primary">Buy Now</a>
            </div>
          </div>
          <div class="card">
            <img src="t11.jpeg" class="card-img-top" alt="Product 2" width="200" height="200">
            <div class="card-body">
              <h5 class="card-title"> Prescription Drug</h5>
              <p class="card-text">A pharmaceutical drug that is permitted to be dispensed only to those with a medical prescription.</p>
              <a href="#" class="btn btn-primary">Buy Now</a>
            </div>
          </div>
          <div class="card">
            <img src="t12.jpg" class="card-img-top" alt="Product 2" width="200" height="200">
            <div class="card-body">
              <h5 class="card-title">Vaccine</h5>
              <p class="card-text">A vaccine is a biological preparation that provides active acquired immunity to a particular infectious or malignant disease.</p>
              <a href="#" class="btn btn-primary">Buy Now</a>
            </div>
          </div>
          <div class="card">
            <img src="t14.jpg" class="card-img-top" alt="Product 3" width="200" height="200">
            <div class="card-body">
              <h5 class="card-title">Supplements</h5>
              <p class="card-text">These include vitamins, minerals, herbs and botanicals, probiotics, and more.</p>
              <a href="#" class="btn btn-primary">Buy Now</a>
            </div>
          </div>
          <div class="card">
            <img src="t16.png" class="card-img-top" alt="Product 3" width="220" height="200">
            <div class="card-body">
              <h5 class="card-title">Health care</h5>
              <p class="card-text"> They can include a variety of ingredients such as vitamins, minerals, herbs, amino acids, enzymes, and botanicals</p>
              <a href="#" class="btn btn-primary">Buy Now</a>
            </div>
        </div>
        </div>
      </div>
    </div>
  </div>
<br>
<br>
<br>
<br>
<br><br>
  <!-- Footer -->
  <footer class="text-center p-3 bg-success mt-5">
    <p>Copyright &copy; <?php echo date("Y"); ?> INDIANA PHARMA COMPANY - STA INDUSTRIES</p>
  </footer>
  <body background="t13.jpeg" {% widthratio this_value max_value 200 %}>


  <!-- Bootstrap JS -->
  <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js"></script>
  <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>
```
```
<contact.html>
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>INDIANA PHARMA</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-1BmE4kWBq78iYhFldvKuhfTAU6auU8tT94WrHftjDbrCEXSU1oBoqyl2QvZ6jIW3" crossorigin="anonymous">
</head>
<body>

    <nav class="navbar navbar-expand-lg navbar-light bg-warning">
        <div class="container-fluid">
          <a class="navbar-brand" href="#"><B><font face="Perpetua Titling MT" size="4" >INDIANA PHARMA</font></a>
          <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNavAltMarkup" aria-controls="navbarNavAltMarkup" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
          </button>
          <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
            <div class="navbar-nav">
              <a class="nav-link active" aria-current="page" href="home.html">Home</a>
              <a class="nav-link" href="about.html">About</a>
              <a class="nav-link" href="products.html">Products</a>
              <a class="nav-link" href="contact.html">Contact</a>
              <div class="nav-item dropdown">
                <a class="nav-link dropdown-toggle" href="#" id="navbarDropdownMenuLink" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                  Register
                </a>
                <ul class="dropdown-menu" aria-labelledby="navbarDropdownMenuLink">
                  <li><a class="dropdown-item" href="#">Login</a></li>
                  <li><a class="dropdown-item" href="#">Sign Up</a></li>
                </ul>
              </div>
            </div>
          </div>
        </div>
      </nav>

  <!-- Page Content -->
  <div class="container mt-5">
    <div class="row">
      <div class="col-md-8">
        <h5><font face="Harlow Solid Italic" size="9" color= "white"><b>Contact Us</h5></font>
            <font face="Harlow Solid Italic" size="3" color= "white"><p>For any inquiries or feedback, please fill out the form below and we will get back to you as soon as possible.</p>
        <form>
          <div class="form-group">
            <label for="name">Your Name</label>
            <input type="text" class="form-control" id="name" placeholder="Enter your name">
          </div>
          <div class="form-group">
            <label for="email">Your Email</label>
            <input type="email" class="form-control" id="email" placeholder="Enter your email">
          </div>
          <div class="form-group">
            <label for="message">Message</label>
            <textarea class="form-control" id="message" rows="3" placeholder="Enter your message"></textarea>
          </div>
          <button type="submit" class="btn btn-primary">Submit</button>
        </form>
      </div>
      <div class="col-md-4">
        <h2>PharmaPlus</h2>
        <address>
          <strong>Address:</strong><br>
          STA INDUSTRIES,MOUNT POONAMALLEE RD,CHENNAI
          TAMILNADU, 600089<br><BR>
          <strong>Email:</strong><br>
          pharmaindiana@gmail.com<br>
          <strong>Phone:</strong><br>
          +91 6684145735
        </address>
      </div>
    </div>
  </div>
</font>
 
  <body background="t7.jpg" style="background-repeat: no-repeat; background-size: cover;">

    <br>
    <br>
  <footer class="text-center p-3 bg-success mt-5">
    <p>Copyright &copy; <?php echo date("Y"); ?> INDIANA PHARMA COMPANY - STA INDUSTRIES</p>
  </footer>

  <!-- Bootstrap JS -->
  <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js"></script>
  <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>
```

## OUTPUT:
![image](https://github.com/aishaishwaryav/Pharma/assets/151565589/7e283d10-b288-497a-ab4d-9bfa2fa9edc0)

![image](https://github.com/aishaishwaryav/Pharma/assets/151565589/2de242cd-c76c-48c5-8fc6-4f2d6201c683)

![image](https://github.com/aishaishwaryav/Pharma/assets/151565589/be8f8be4-1360-4ef8-bd4a-a9546fc1835b)

![image](https://github.com/aishaishwaryav/Pharma/assets/151565589/609ecf18-06ce-4607-b7eb-9a8c13e344da)


## RESULT:
The program for responsive web design using Bootstrap is completed successfully.
