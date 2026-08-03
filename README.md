# Ex02 Commercial Website
## Date:

## AIM
To create a commercial website using CSS Flexbox.

## ALGORITHM
### STEP 1
Create an HTML file (index.html)

### STEP 2
Create a CSS file (style.css)

### STEP 3
Include a navigation bar with links to different sections.

### STEP 4
Add structured sections for Homepage, Products / Services, About Us, Contact Details and User Account.

### STEP 5
Include social media links at the footer with copyright information.

### STEP 6
Define global styles for fonts, colors, and layout.

### STEP 7
Style the header, navigation bar, and sections.

### STEP 8
Use Flexbox for layout design.

### STEP 9
Add hover effects and transitions for interactivity.

### STEP 10
Add Images and Media.

### STEP 11
Use optimized images for a professional look.

### STEP 12
Open the HTML file in a browser to check layout and functionality.

### STEP 13
Fix styling issues and refine content placement.

### STEP 14
Deploy the website.

### STEP 15
Upload to GitHub Pages for free hosting.

## PROGRAM
## index.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Commercial Website</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <!-- Navigation -->
    <header>
        <nav>
            <h1>ShopEasy</h1>

            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#products">Products</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <!-- Home -->
    <section id="home" class="hero">

        <div class="hero-text">
            <h2>Welcome to ShopEasy</h2>
            <p>Your one-stop shop for quality products.</p>
            <a href="#products" class="btn">Shop Now</a>
        </div>

    </section>

    <!-- Products -->
    <section id="products">

        <h2>Our Products</h2>

        <div class="product-container">

            <div class="product-card">
                <h3>Laptop</h3>
                <p>High-performance laptop for students and professionals.</p>
                <button>Buy Now</button>
            </div>

            <div class="product-card">
                <h3>Smartphone</h3>
                <p>Latest smartphone with advanced camera features.</p>
                <button>Buy Now</button>
            </div>

            <div class="product-card">
                <h3>Headphones</h3>
                <p>Wireless headphones with crystal-clear sound.</p>
                <button>Buy Now</button>
            </div>

        </div>

    </section>

    <!-- About -->
    <section id="about">

        <h2>About Us</h2>

        <p>
            ShopEasy is an online shopping website that provides quality
            products at affordable prices. We aim to provide the best
            shopping experience for our customers.
        </p>

    </section>
```
## style.css:
```
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:Arial, sans-serif;
}

html{
    scroll-behavior:smooth;
}

body{
    background:#f4f4f4;
    color:#333;
}

/* Navigation */

header{
    background:#222;
    color:white;
    position:sticky;
    top:0;
}

nav{
    display:flex;
    justify-content:space-between;
    align-items:center;
    padding:20px 50px;
}

nav ul{
    display:flex;
    list-style:none;
}

nav ul li{
    margin-left:25px;
}

nav ul li a{
    color:white;
    text-decoration:none;
    font-weight:bold;
}

nav ul li a:hover{
    color:orange;
}

/* Hero */

.hero{
    display:flex;
    justify-content:center;
    align-items:center;
    text-align:center;
    height:80vh;
    background:#e8f4ff;
}

.hero-text h2{
    font-size:45px;
    margin-bottom:20px;
}

.hero-text p{
    font-size:20px;
    margin-bottom:30px;
}

.btn{
    background:#0077ff;
    color:white;
    text-decoration:none;
    padding:12px 25px;
    border-radius:5px;
}

.btn:hover{
    background:#0055cc;
}

/* Products */

#products{
    padding:70px;
}

#products h2{
    text-align:center;
    margin-bottom:40px;
}

.product-container{
    display:flex;
    justify-content:center;
    gap:30px;
    flex-wrap:wrap;
}

.product-card{
    background:white;
    width:280px;
    padding:20px;
    border-radius:10px;
    text-align:center;
    box-shadow:0 0 10px rgba(0,0,0,0.2);
}

.product-card h3{
    margin-bottom:15px;
}

.product-card p{
    margin-bottom:20px;
}

.product-card button{
    background:#0077ff;
    color:white;
    border:none;
    padding:10px 20px;
    cursor:pointer;
    border-radius:5px;
}

.product-card button:hover{
    background:#0055cc;
}

/* About */

#about{
    padding:70px;
    text-align:center;
}

#about h2{
    margin-bottom:20px;
}

/* Contact */

#contact{
    padding:70px;
    text-align:center;
}

#contact h2{
    margin-bottom:20px;
}

/* Footer */

footer{
    background:#222;
    color:white;
    text-align:center;
    padding:20px;
}
```
    

## OUTPUT:
<img width="1877" height="866" alt="Screenshot 2026-08-03 205017" src="https://github.com/user-attachments/assets/89d43bff-19fe-46c1-81f1-eca9226d0d96" />

<img width="1852" height="981" alt="Screenshot 2026-08-03 205033" src="https://github.com/user-attachments/assets/1311d157-a194-44d2-b0f3-8384852b50d9" />


## RESULT
The program for creating commercial website using CSS Flexbox is executed successfully.
