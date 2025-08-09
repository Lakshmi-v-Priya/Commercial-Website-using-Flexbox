## Ex02 Commercial Website
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

## PROGRAM:
index.html
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>My Business</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>

  <header>
    <div class="logo">MyBusiness</div>
    <nav>
      <ul class="nav-links">
        <li><a href="#home">Home</a></li>
        <li><a href="#products">Products</a></li>
        <li><a href="#about">About</a></li>
        <li><a href="#contact">Contact</a></li>
        <li><a href="#account">Account</a></li>
      </ul>
    </nav>
  </header>

  <section id="home" class="hero">
    <h1>Welcome to MyBusiness</h1>
    <p>Your one-stop shop for quality products.</p>
  </section>

  <section id="products" class="products">
    <h2>Our Products</h2>
    <div class="product-grid">
      <div class="product-card">
        <img src="pexels-harper-sunday-2866796.jpg" alt="Product 1" />
        <p>Product 1</p>
      </div>
      <div class="product-card">
        <img src="pexels-madebymath-90946.jpg" alt="Product 2" />
        <p>Product 2</p>
      </div>
      <div class="product-card">
        <img src="pexels-polina-tankilevitch-3735149.jpg" alt="Product 3" />
        <p>Product 3</p>
      </div>
    </div>
  </section>

  <section id="about" class="about">
    <h2>About Us</h2>
    <p>We are committed to quality and customer satisfaction.</p>
  </section>

  <section id="contact" class="contact">
    <h2>Contact Us</h2>
    <p>Email: contact@mybusiness.com</p>
    <p>Phone: +123 456 7890</p>
  </section>

  <section id="account" class="account">
    <h2>User Account</h2>
    <p>Sign in or register to manage your orders.</p>
  </section>

  <footer>
    <div class="social-links">
      <a href="#">Facebook</a>
      <a href="#">Instagram</a>
      <a href="#">LinkedIn</a>
    </div>
    <p>&copy; 2025 MyBusiness. All rights reserved.</p>
  </footer>

</body>
</html>
```
style.css
```
/* STEP 6: Global Styles */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: 'Segoe UI', sans-serif;
  line-height: 1.6;
  background: #f5f5f5;
  color: #333;
}

a {
  text-decoration: none;
  color: inherit;
}

/* STEP 7: Header and Navigation */
header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 20px;
  background-color: #003366;
  color: white;
}

.logo {
  font-size: 1.5rem;
  font-weight: bold;
}

.nav-links {
  display: flex;
  list-style: none;
  gap: 20px;
}

.nav-links li a {
  color: white;
  transition: color 0.3s ease;
}

/* STEP 9: Hover Effects */
.nav-links li a:hover {
  color: #ffcc00;
}

/* STEP 8: Flexbox Layouts */
.hero,
.about,
.contact,
.account {
  padding: 60px 20px;
  text-align: center;
  background-color: white;
}

.products {
  padding: 60px 20px;
  background-color: #e8f4fa;
}

.product-grid {
  display: flex;
  flex-wrap: wrap;
  gap: 20px;
  justify-content: center;
}

.product-card {
  background: white;
  border: 1px solid #ccc;
  padding: 20px;
  width: 200px;
  transition: transform 0.3s ease;
}

.product-card img {
  width: 100%;
  height: auto;
  object-fit: cover;
}

/* STEP 9: Hover Effects */
.product-card:hover {
  transform: scale(1.05);
}

/* STEP 5: Footer Styles */
footer {
  background: #003366;
  color: white;
  padding: 20px;
  text-align: center;
}

.social-links {
  display: flex;
  justify-content: center;
  gap: 15px;
  margin-bottom: 10px;
}

.social-links a {
  color: #fff;
  transition: color 0.3s;
}

.social-links a:hover {
  color: #ffcc00;
}

```


## OUTPUT:
<img width="1920" height="1080" alt="Screenshot (2)" src="https://github.com/user-attachments/assets/7e1374bc-3699-4ade-9c42-e2cb52dedabc" />

## RESULT
The program for creating commercial website using CSS Flexbox is executed successfully.
