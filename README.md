# Ex.07 Restuarant Website
## Date: 29-10-2025

## AIM:
To develop a static Resturant website to display the menu and services provided by the resturant.

## DESIGN STEPS:

### Step 1:
Requirement collection.

### Step 2:
Creating the layout using HTML and CSS.

### Step 3:
Updating the sample content.

### Step 4:
Choose the appropriate style and color scheme.

### Step 5:
Validate the layout in various browsers.

### Step 6:
Validate the HTML code.

### Step 7:
Publish the website in the given URL.

## PROGRAM:
## restaurant.html:
```html
{% load static %}

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Delicious Bites</title>
    <link rel="stylesheet" href="{% static 'app.css' %}">

</head>

<body>
    <header>
        <h1>🍔 Delicious Bites</h1>
        <nav>
            <a href="#home">Home</a>
            <a href="#menu">Menu</a>
            <a href="#about">About</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>

    <section id="home" class="hero">
        <h2>Welcome to Delicious Bites</h2>
        <p>Serving happiness on your plate since 2000!</p>
    </section>

    <section id="menu">
        <h2>Our Menu</h2>
        <div class="menu-items">
            <div class="item">
                <h3>🍕 Margherita Pizza</h3>
                <p>Classic cheese pizza with fresh basil.</p>
            </div>
            <div class="item">
                <h3>🍝 Pasta Alfredo</h3>
                <p>Creamy Alfredo sauce with soft fettuccine.</p>
            </div>
            <div class="item">
                <h3>🍔 Cheeseburger</h3>
                <p>Juicy beef patty with melted cheese.</p>
            </div>
        </div>
    </section>

    <section id="about">
        <h2>About Us</h2>
        <p>We are a family-run restaurant focused on serving fresh, flavorful meals made with love ❤️</p>
    </section>

    <section id="contact">
        <h2>Contact Us</h2>
        <p>📍 123 Food Street, Chennai, India</p>
        <p>📞 +91 98765 43210</p>
    </section>

    <footer>
        <p>© 2025 Delicious Bites | All rights reserved.</p>
    </footer>
</body>

</html>
```

## app.css:
```css
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #fff8f0;
    color: #333;
}

header {
    background-color: #ff914d;
    color: white;
    text-align: center;
    padding: 15px 0;
}

nav a {
    color: white;
    margin: 0 15px;
    text-decoration: none;
    font-weight: bold;
}

nav a:hover {
    text-decoration: underline;
}

.hero {
    text-align: center;
    padding: 60px 20px;
    background-color: #ffe5b4;
}

section {
    padding: 30px;
    text-align: center;
}

.menu-items {
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
}

.item {
    background-color: white;
    border: 1px solid #ddd;
    margin: 10px;
    padding: 15px;
    width: 200px;
    border-radius: 8px;
}

footer {
    background-color: #ff914d;
    color: white;
    text-align: center;
    padding: 10px 0;
}
```

## OUTPUT:
<img width="1919" height="1157" alt="Restaurant-png" src="https://github.com/user-attachments/assets/8cadcc83-a69a-40ec-b5d7-2f348a1249d7" />


## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
