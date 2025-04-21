# Ex.07 Restaurant Website
# Date:21-04-2025
# AIM:
To develop a static Restaurant website to display the food items and services provided by them.

# DESIGN STEPS:
## Step 1:
Requirement collection.

## Step 2:
Creating the layout using HTML and CSS.

## Step 3:
Updating the sample content.

## Step 4:
Choose the appropriate style and color scheme.

## Step 5:
Validate the layout in various browsers.

## Step 6:
Validate the HTML code.

## Step 7:
Publish the website in the given URL.

# PROGRAM:

```
index.html

<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Z&J RESTAURANT - Home</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <div class="logo">
            <img src="logo.png" alt="Z&J RESTAURANT Logo">
            <h1>Z&J RESTAURANT</h1>
        </div>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="administration.html">Administration</a></li>
                <li><a href="contact.html">Contact Us</a></li>
            </ul>
        </nav>
    </header>

    <section class="banner">
        <h2>30% Off This Weekend</h2>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse et congue massa, eu fringilla mauris.</p>
    </section>

    <section class="features">
        <div class="card">
            <h3>Our New Menu</h3>
            <img src="menu.jpg" alt="New Menu">
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse et congue massa.</p>
            <a href="menu.html">See our new menu</a>
        </div>
        <div class="card">
            <h3>Book a table</h3>
            <img src="table.jpg" alt="Book a Table">
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse et congue massa.</p>
            <a href="#">Book your table now</a>
        </div>
        <div class="card">
            <h3>Opening Hours</h3>
            <img src="chef.jpg" alt="Chef">
            <p>Mon - Fri: 2pm - 10pm<br>Sat: 2pm - 11pm<br>Sun: 2pm - 9pm</p>
        </div>
    </section>

    <footer>
        <img src="logo.png" alt="Z&J RESTAURANT Icon" class="footer-logo">
        <p>Designed and Developed by Mohamed Zabir Khan A (24900623) </p>
    </footer>
</body>
</html>

```

```

menu.html

<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Menu - Z7J RESTAURANT</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>Z&J RESTAURANT</header>
    <main class="menu">
        <h2>Our Menu</h2>
        <br>
        <div class="menu-grid">
            <div class="menu-item"><img src="item1.jpg"><h4>Grilled Chicken</h4><p>With herbs</p></div>
            <div class="menu-item"><img src="item2.jpg"><h4>Spaghetti Bolognese</h4><p>Classic Italian</p></div>
            <div class="menu-item"><img src="item3.jpg"><h4>Cheese Pizza</h4><p>Stone-baked</p></div>
            <div class="menu-item"><img src="item4.jpg"><h4>Caesar Salad</h4><p>Fresh & crunchy</p></div>
            <div class="menu-item"><img src="item5.jpg"><h4>Burger</h4><p>Grilled to perfection</p></div>
            <div class="menu-item"><img src="item6.jpg"><h4>Fish Tacos</h4><p>With lime crema</p></div>
            <div class="menu-item"><img src="item7.jpg"><h4>Butter Chicken</h4><p>Indian classic</p></div>
            <div class="menu-item"><img src="item8.jpg"><h4>Sushi Platter</h4><p>Assorted rolls</p></div>
            <div class="menu-item"><img src="item9.jpg"><h4>Steak</h4><p>Medium-rare</p></div>
            <div class="menu-item"><img src="item10.jpg"><h4>Pancakes</h4><p>With maple syrup</p></div>
            <div class="menu-item"><img src="item11.jpg"><h4>Ice Cream</h4><p>3 scoops variety</p></div>
            <div class="menu-item"><img src="item12.jpg"><h4>Fruit Bowl</h4><p>Seasonal mix</p></div>
        </div>
    </main>
    <footer>
        <img src="logo.png" alt="Z&J RESTAURANT Icon" class="footer-logo">
        Developed by Mohamed Zabir Khan A (24900623)
    </footer>
</body>
</html>

```

```

administration.html

<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Administration - Z&J RESTAURANT</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>Z&J RESTAURANT</header>
    <main class="admin">
        <h2>Meet Our Team</h2>
        <div class="admin-grid">
            <div class="admin-card"><img src="admin1.jpg"><h4>Gordon Ramsay</h4><p>Head Chef</p></div>
            <div class="admin-card"><img src="admin2.jpg"><h4>Thomas Keller</h4><p>Restaurant Manager</p></div>
            <div class="admin-card"><img src="admin3.jpg"><h4>Jamie Oliver</h4><p>Pastry Chef</p></div>
            <div class="admin-card"><img src="admin4.jpg"><h4>Andres Caminada</h4><p>Marketing Head</p></div>
            <div class="admin-card"><img src="admin5.jpg"><h4>Pierre Gagnaire</h4><p>Customer Relations</p></div>
            <div class="admin-card"><img src="admin6.jpg"><h4>Vicky Lau</h4><p>Finance Officer</p></div>
        </div>
    </main>
    <footer>
        <img src="logo.png" alt="Z&J RESTAURANT Icon" class="footer-logo">
        Developed by Mohamed Zabir Khan A (24900623)
    </footer>
</body>
</html>

```

```

contact.html

<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact Us - Z&J RESTAURANT</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>Z&J RESTAURANT</header>
    <main class="contact">
        <h2>Contact Us</h2>
        <p><strong>Address:</strong> 123 Main Street, Chennai, India</p>
        <p><strong>Phone:</strong> +91 8754447744</p>
        <p><strong>Email:</strong> contact@Z&Jrestaurant.com</p>
    </main>
    <footer>
        <img src="logo.png" alt="Z&J RESTAURANT Icon" class="footer-logo">
        Developed by Mohamed Zabir Khan A (24900623)
    </footer>
</body>
</html>

```
# OUTPUT:

![alt text](<index page.png>)

![alt text](<menu page.png>)

![alt text](<administration page.png>)

![alt text](<contact page.png>)

# RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
