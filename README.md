# Ex02 Commercial Website
## Date: 11.08.25

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

index.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Fashion Trend</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>Fashion Trend</h1>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#collections">Collections</a></li>
                <li><a href="#about">About Us</a></li>
                <li><a href="#contact">Contact</a></li>
                <li><a href="#account">User Account</a></li>
            </ul>
        </nav>
    </header>

    <section id="home">
        <h2>Welcome to Fashion Trend</h2>
        <p>Discover the latest trends in fashion and style.</p>
    </section>

    <section id="collections">
        <h2>Our Collections</h2>
        <p>Explore our latest fashion collections.</p>
    </section>

    <section id="about">
        <h2>About Us</h2>
        <p>Fashion Trend is a leading fashion brand bringing you the latest styles.</p>
    </section>

    <section id="contact">
        <h2>Contact Us</h2>
        <p>Email: support@fashiontrend.com | Phone: +1234567890</p>
    </section>

    <section id="account">
        <h2>User Account</h2>
        <p>Login to explore exclusive fashion deals.</p>
    </section>

    <footer>
        <p>&copy; 2025 Your Name | Reg No: 123456</p>
        <div class="social-links">
            <a href="#">Facebook</a> |
            <a href="#">Instagram</a> |
            <a href="#">Twitter</a>
        </div>
    </footer>
</body>
</html>
```
style.css
```
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Arial', sans-serif;
}

body {
    background-color: #f7f1e3;
    color: #333;
    text-align: center;
}

/* Header & Navigation */
header {
    background-color: #222;
    color: white;
    padding: 20px;
    font-size: 24px;
}

nav ul {
    display: flex;
    justify-content: center;
    list-style: none;
    margin-top: 10px;
}

nav ul li {
    margin: 0 15px;
}

nav ul li a {
    color: rgb(242, 150, 233);
    text-decoration: none;
    font-weight: bold;
    transition: color 0.3s;
}

nav ul li a:hover {
    color: #ff9f43;
}

/* Sections */
section {
    padding: 50px 20px;
    margin: 20px auto;
    width: 80%;
    background: rgb(242, 150, 233);
    border-radius: 10px;
    box-shadow: 0px 4px 10px rgba(0, 0, 0, 0.2);
}

/* Footer */
footer {
    background-color: #222;
    color: white;
    padding: 15px;
    margin-top: 20px;
}

.social-links a {
    color: #ff9f43;
    text-decoration: none;
    margin: 0 10px;
}

.social-links a:hover {
    text-decoration: underline;
}
```

## OUTPUT
<img width="1919" height="896" alt="image" src="https://github.com/user-attachments/assets/50913c2c-813e-4ed7-9e55-90c25bfbd9a5" />

<img width="1919" height="1008" alt="image" src="https://github.com/user-attachments/assets/9439a22d-6dc7-4713-945e-79d3f2ee1529" />

## RESULT
The program for creating commercial website using CSS Flexbox is executed successfully.
