# Ex02 Commercial Website
## Date:14/03/2025

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
    <header>
        <h1>My Business</h1>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#services">Services</a></li>
                <li><a href="#about">About Us</a></li>
                <li><a href="#contact">Contact</a></li>
                <li><a href="#account">Account</a></li>
            </ul>
        </nav>
    </header>

    <section id="home" class="section">
        <h2>Welcome to Our Business<p><sub>Providing quality services to our customers.</sub></p></h2>
    
        
    </section>

    <section id="services" class="section">
        <h2>Our Services<p><sub>We offer a range of high-quality services tailored to your needs<p><sub>Instant Discount<p><sub>Exchange old devices<p><sub>No Cost EMIs<p><sub>Online coupons</sub></p></h2>
        
        
    </section>

    <section id="about" class="section">
        <h2>About Us<p><sub>We are dedicated to excellence and customer satisfaction and bring a goodness of health and wellness products to reach the customers,we aim to curate all-natural quality products to enrich your lifestyle.</sub></p></h2>
        
    </section>

    <section id="contact" class="section">
        <h2>Contact Us<p><sub>Email: contact@mybusiness.com<p><sub>Phone NO: 1234567890<p><sub>Address: Saveetha Block,saveetha Nagar,Thandalam,Chennai<p><sub>Pincode: 602105</sub></p></h2>
        
    </section>

    <section id="account" class="section">
        <h2>User Account<p><sub>Login to manage your account and preferences.</sub></p></h2>
    </section>

    <footer>
        <p>&copy; 2025 My Business. All Rights Reserved.</p>
        
    </footer>
</body>
</html>

```
##Style.CSS
```
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    
}

header {
    background: #333;
    color: white;
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 10px 20px;
}

nav ul {
    list-style: none;
    display: flex;
    gap: 15px;
}

nav ul li a {
    color: white;
    text-decoration: none;
    padding: 10px;
    transition: 0.3s;
}

nav ul li a:hover {
    background: #555;
    border-radius: 5px;
}

.section {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 50vh;
    text-align: center;
    background: #f4f4f4;
    margin: 10px;
    padding: 20px;
    border-radius: 10px;
    background-color:pink;
}

footer {
    background: #333;
    color: white;
    text-align: center;
    padding: 10px;
    position: relative;
}

.social-links a {
    color: white;
    margin: 0 10px;
    text-decoration: none;
    transition: 0.3s;
}

.social-links a:hover {
    text-decoration: underline;
}
```


## OUTPUT
![Screenshot (219)](https://github.com/user-attachments/assets/af600526-554e-4f3b-8cff-6c9b50d6b21a)
![Screenshot (220)](https://github.com/user-attachments/assets/8cbc0c17-ffef-4975-88c1-4dc8e148ec29)
![Screenshot (221)](https://github.com/user-attachments/assets/d266fb72-9c33-4fdf-b54f-91641712d596)
![Screenshot (222)](https://github.com/user-attachments/assets/60dd60cf-a566-406c-a6d9-f0e994ca39e1)
![Screenshot (223)](https://github.com/user-attachments/assets/4d64aeda-7ed3-4d49-8a93-94af97b807ce)







## RESULT
The program for creating commercial website using CSS Flexbox is executed successfully.
