# Project Responsive Web Design using Bootstrap
## Date: 

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

### boot.html:
```
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dribbble Clone</title>
    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
    <!-- Custom Styles (optional) -->
    <link rel="stylesheet" href="styles.css">
</head>

<body style="background-color:rgb(220, 174, 150)">
    <!-- Navigation Bar -->
    <nav class="navbar navbar-expand-lg navbar-light bg-light">
        <div class="container">
            <a class="navbar-brand" href="#">Dribbble Clone</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item"><a class="nav-link" href="#">Inspiration</a></li>
                    <li class="nav-item"><a class="nav-link" href="#">Work</a></li>
                    <li class="nav-item"><a class="nav-link" href="#">Designers</a></li>
                    <li class="nav-item"><a class="nav-link" href="#">Learn</a></li>
                    <li class="nav-item"><a class="nav-link" href="#">Sign Up</a></li>
                </ul>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <header class="bg-light text-center py-5">
        <div class="container">
            <h1 class="display-4">Discover the World's Top Designers & Creatives</h1>
            <p class="lead">Join the community to showcase your work, find inspiration, and connect with designers.</p>
            <a href="#" class="btn btn-primary btn-lg">Join Us Today</a>
        </div>
    </header>

    <!-- Featured Content Section -->
    <section class="container py-5">
        <div class="row g-4">
            <div class="col-md-4">
                <div class="card">
                    <img src="C:\Users\admin\Downloads\uiiii.jpg" class="card-img-top" alt="Sample Design 1">
                    <div class="card-body">
                        <h5 class="card-title">Design Concept 1</h5>
                        <p class="card-text">User Interface (UI) Design is the process of designing the visual layout
                             and interactive elements of digital products, such as websites, mobile apps, software, 
                             and other digital interfaces. UI design focuses on how users interact with a product and 
                             aims to create a visually appealing, intuitive, and efficient experience. It includes everything 
                             from buttons, icons, color schemes, and typography to spacing, navigation, and overall layout.A beautiful UI design
                              concept to inspire your next project.</p>
                        <a href="#" class="btn btn-outline-secondary">View More</a>
                    </div>
                </div>
            </div>
            <div class="col-md-4">
                <div class="card">
                    <img src="C:\Users\admin\Downloads\port.jpg" class="card-img-top" alt="Sample Design 2">
                    <div class="card-body">
                        <h5 class="card-title">Design Concept 2</h5>
                        <p class="card-text">A portfolio is an essential tool for showcasing your skills, experience, and creativity, 
                            especially in fields like UI/UX design, web development, graphic design,
                             and other creative industries. Your portfolio serves as a visual resume, demonstrating your abilities to potential employers, 
                             clients, or collaborators.Modern and clean design examples for your portfolio.</p>
                        <a href="#" class="btn btn-outline-secondary">View More</a>
                    </div>
                </div>
            </div>
            <div class="col-md-4">
                <div class="card">
                    <img src="C:\Users\admin\Downloads\dss.png" class="card-img-top" alt="Sample Design 3">
                    <div class="card-body">
                        <h5 class="card-title">Design Concept 3</h5>
                        <p class="card-text">Creative design is at the heart of any visually impactful project, whether it’s for branding, websites, apps, packaging, 
                            or marketing campaigns. It’sthe process of transforming ideas and concepts
                             into engaging visuals that tell a story, evoke emotions, and capture attention.Explore creative UI ideas and concepts for designers.</p>
                        <a href="#" class="btn btn-outline-secondary">View More</a>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Newsletter Section -->
    <section class="bg-dark text-white text-center py-5">
        <div class="container">
            <h2>Stay Updated</h2>
            <p>Sign up for our newsletter to get the latest updates.</p>
            <form class="row g-2 justify-content-center">
                <div class="col-md-6">
                    <input type="email" class="form-control" placeholder="Enter your email">
                </div>
                <div class="col-md-auto">
                    <button type="submit" class="btn btn-primary">Subscribe</button>
                </div>
            </form>
        </div>
    </section>

    <!-- Bootstrap JavaScript Bundle with Popper -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>

</html>
```
### style.css:

```
body {
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    b

}
header{
     background-color: darkkhaki;
}

.card {
    transition: transform 0.2s ease-in-out;
}

.card:hover {
    transform: translateY(-10px);
}
```

## OUTPUT:
![386055525-d3d074f6-94de-44c2-b6bd-3a4246051116](https://github.com/user-attachments/assets/36671bbd-f41e-4a8f-a8ef-2b7e123b1c3b)


## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
