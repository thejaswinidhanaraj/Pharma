# Project Responsive Web Design using Bootstrap
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
HOME:
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Home - Merck</title>
  <!-- Bootstrap CSS -->
  <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
  <style>
    .navbar {
      background-color: rgb(160, 35, 176); 
    }
    footer {
      position: fixed;
      bottom: 0;
      width: 100%;
      background-color:rgb(160, 35, 176) ;
      color: rgb(8, 8, 8);
      padding: 10px 0;
    }
  </style>
</head>
<body>

  <!-- Navbar -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-plum">
    <a class="navbar-brand" href="#">Merck</a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>

    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav mr-auto">
        <li class="nav-item active">
          <a class="nav-link" href="web.html">Home <span class="sr-only">(current)</span></a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="about.html">About us</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="product.html">Products</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="contact.html">Contact us</a>
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
      <div class="col-md-8">
        <h1>SUN PHARMA</h1>
        <p>Together, we impact life and health with science. We offer one of the broadest portfolios in the industry for scientists, 
        best-in-class products for pharmaceutical development and manufacturing, and a fully integrated service organization to support CDMO and contract testing 
        across traditional and novel modalities. Our vision is a world where our innovative products, services, and digital offerings help create solutions for people
        globally and a sustainable future for generations to come.
        <p>Thank you for choosing Merck for your healthcare needs. We Are blessed and Happy to Be the reason for your healthier life.</p>
      </div>
      <div class="col-md-4">
        <img src="c:\Users\admin\Downloads\Sun_Pharma_logo.svg.png" class="img-fluid" alt="Pharmacy Image">
      </div>
    </div>
  </div>

  <!-- Footer -->
  <footer class="bg-plum text-black text-center">
    <div class="container">
      <p>&copy; copyrights @2024 Made and Developed by THEJASWINI D (212223110059)</p>
    </div>
  </footer>

  <!-- Bootstrap JS -->
  <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js"></script>
  <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>
```
ABOUT:
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Merck</title>
  <!-- Bootstrap CSS -->
  <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
  <style>
    .navbar {
      background-color:  rgb(160, 35, 176); 
    }
    body {
      display: flex;
      flex-direction: column;
      min-height: 100vh;
    }
    .content {
      flex: 1;
    }
    footer {
      background-color:  rgb(160, 35, 176); /* Dark background color */
      color: black; /* Text color */
      text-align: center;
      padding: 20px 0;
      width: 100%;
    }
  </style>
</head>
<body>

  <!-- Navbar -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-plum">
    <a class="navbar-brand" href="#">Merck</a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>

    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav mr-auto">
        <li class="nav-item">
          <a class="nav-link" href="web.html">Home</a>
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
          <a class="nav-link" href="product.html">Products</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Contact us</a>
        </li>
      </ul>
    </div>
  </nav>

  <!-- Page Content -->
  <div class="container mt-5 content">
    <div class="row">
      <div class="col-md-12">
        <h1>SUN PHARMA</h1>
        <div id="vision">
          <h2>Vision</h2>
          <p>To pioneer innovative healthcare solutions that improve and save lives globally, setting new standards for excellence and accessibility in pharmaceuticals.</p>
        </div>
        <div id="mission">
          <h2>Mission</h2>
          <p>Our mission is to relentlessly pursue breakthroughs in medical science, developing and delivering high-quality, safe, and 
            affordable medications to meet the evolving needs of patients worldwide. We are committed to fostering a culture of integrity, collaboration, and social 
            responsibility, striving to make a positive impact on healthcare outcomes and the communities we serve.</p>
        </div>
        <div id="values">
          <h2>Values</h2>
          <ul>
            <li>Quality: Committing to excellence in the manufacturing and distribution of pharmaceutical products, ensuring rigorous 
                quality control processes to deliver safe and effective medications.</li>
            <li>Integrity: Upholding the highest ethical standards in all our actions and decisions, prioritizing transparency and 
                honesty in our relationships with stakeholders.</li>
            <li>Innovation: Embracing a culture of continuous innovation, investing in research and development to discover novel treatments 
                and technologies that address unmet medical needs.</li>
            <li>Employee Development: Investing in the professional growth and development of our employees, providing opportunities for 
                learning, skill-building, and career advancement.</li>
            <li>Responsibility: Recognizing our responsibility to society and future generations, striving to make a positive impact on global 
                health while conducting our business ethically and responsibly.</li>
          </ul>
        </div>
        <!-- Add more subheadings as needed -->
      </div>
    </div>
  </div>

  <!-- Footer -->
  <footer>
    <div class="bg-plum text-black text-center">
      <p>&copy; Copyrights @2024 Made and Developed by THEJASWINI D (212223110059)</p>
    </div>
  </footer>

  <!-- Bootstrap JS -->
  <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js"></script>
  <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>
```

## OUTPUT:

![Screenshot (30)](https://github.com/thejaswinidhanaraj/Pharma/assets/148514511/9a707e5f-e0b7-49bb-b4c6-ac4c4c20535d)

![Screenshot (31)](https://github.com/thejaswinidhanaraj/Pharma/assets/148514511/6c3befe3-8e65-46f8-80a4-03b79f83ab8d)


## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
