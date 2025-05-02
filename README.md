# Ex.07 Restaurant Website
# Date:02.05.2025
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
contact.html
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact Us - veggies spot</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>veggies spot</header>
    <main class="contact">
        <h2>Contact Us</h2>
        <p><strong>Address:</strong> 123 Main Street, Chennai, India</p>
        <p><strong>Phone:</strong> +91 8754447744</p>
        <p><strong>Email:</strong> contact@veggies spot.com</p>
    </main>
    <footer>
        <img src="download.jpg" alt="veggies spot" class="footer-logo">
        Developed by P Manasa (212224230149)
    </footer>
</body>
</html>
```
```
index.html
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>veggies spot- Home</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <div class="logo">
            <img src="download.jpg" alt="">
            <h1>VEGGIES spot</h1>
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
            <img src="menu.png" alt="New Menu">
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse et congue massa.</p>
            <a href="menu.html">See our new menu</a>
        </div>
        <div class="card">
            <h3>Book a table</h3>
            <img src="rename.png" alt="Book a Table">
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse et congue massa.</p>
            <a href="#">Book your table now</a>
        </div>
        <div class="card">
            <h3>Opening Hours</h3>
            <img src="admin6.jpg" alt="Chef">
            <p>Mon - Fri: 2pm - 10pm<br>Sat: 2pm - 11pm<br>Sun: 2pm - 9pm</p>
        </div>
    </section>

    <footer>
        <img src="download.jpg" alt="veggies spot" class="footer-logo">
        <p>Designed and Developed by P Manasa (212224230149) </p>
    </footer>
</body>
</html
```
```
menu .html
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Menu - veggies spot</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>Veggies spot</header>
    <main class="menu">
        <h2>Our Menu</h2>
        <br>
        <div class="menu-grid">
            <div class="menu-item"><img src="item1.jpg"><h4>Grilled Panner Tikka</h4><p>With herbs</p></div>
            <div class="menu-item"><img src="item2.jpg"><h4>Spaghetti squash</h4><p>Classic Italian</p></div>
            <div class="menu-item"><img src="item3.jpg"><h4>Cheese Pizza</h4><p>Stone-baked</p></div>
            <div class="menu-item"><img src="item4.jpg"><h4>Caprese Salad</h4><p>Fresh & crunchy</p></div>
            <div class="menu-item"><img src="item5.jpg"><h4>Burger</h4><p>Grilled to perfection</p></div>
            <div class="menu-item"><img src="item6.jpg"><h4>vegan Tacos</h4><p>With lime crema</p></div>
            <div class="menu-item"><img src="item7.jpg"><h4>Chilly garlic Mushroom</h4><p>Indian classic</p></div>
            <div class="menu-item"><img src="item8.jpg"><h4> veg Sushi Platter</h4><p>Assorted rolls</p></div>
            <div class="menu-item"><img src="item9.jpg"><h4> vegan Steak</h4><p>Medium-rare</p></div>
            <div class="menu-item"><img src="item10.jpg"><h4>Pancakes</h4><p>With maple syrup</p></div>
            <div class="menu-item"><img src="item11.jpg"><h4>Ice Cream</h4><p>3 scoops variety</p></div>
            <div class="menu-item"><img src="item12.jpg"><h4>Fruit Bowl</h4><p>Seasonal mix</p></div>
        </div>
    </main>
    <footer>
        <img src="download.jpg" alt="veggies spot" class="footer-logo">
        Developed by P Manasa (212224230149)
    </footer>
</body>
</html>
```
```
admin.html
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Administration - veggies spot</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>Veggies spot</header>
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
        <img src="download.jpg" alt="veggies spot" class="footer-logo">
        Developed by P Manasa(212224230149)
    </footer>
</body>
</html>
```
```
style.html
/* General Reset */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
  }
  
  body {
    background-color: #b890aa;
    color: #333;
  }
  
  header {
    background-color: #444;
    color: white;
    padding: 20px;
    display: flex;
    align-items: center;
    justify-content: space-between;
    flex-wrap: wrap;
  }
  
  .logo {
    display: flex;
    align-items: center;
  }
  
  .logo img {
    height: 50px;
    margin-right: 10px;
  }
  
  nav ul {
    display: flex;
    list-style: none;
  }
  
  nav ul li a {
    color: white;
    text-decoration: none;
    margin: 0 15px;
    font-weight: bold;
    font-size: 18px;
  }
  
  .banner {
    background-image: url('banner.png');
    background-size: cover;
    background-position: center;
    padding: 60px 20px;
    color: white;
    text-align: left;
  }
  
  .banner h2 {
    font-size: 36px;
    margin-bottom: 10px;
  }
  
  .banner p {
    font-size: 18px;
  }
  
  .features {
    display: flex;
    justify-content: space-around;
    padding: 40px 20px;
    gap: 20px;
    background-color: #697b86;
    flex-wrap: wrap;
  }
  
  .card {
    background-color: white;
    border-radius: 10px;
    padding: 20px;
    width: 300px;
    text-align: center;
    box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
  }
  
  .card img {
    width: 100%;
    height: 200px;
    object-fit: cover;
    margin-bottom: 10px;
    border-radius: 8px;
  }
  
  footer {
    background-color: #f5f5f5;
    padding: 20px;
    text-align: center;
    margin-top: 40px;
  }
  
  .footer-logo {
    height: 40px;
    display: block;
    margin: 0 auto 10px;
  }
  
  /* Menu Page */
  .menu {
    padding: 40px 20px;
  }
  
  .menu-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 20px;
  }
  
  .menu-item {
    background-color: white;
    padding: 15px;
    border-radius: 8px;
    box-shadow: 0 2px 6px rgba(0, 0, 0, 0.1);
    text-align: center;
  }
  
  .menu-item img {
    width: 100%;
    height: 180px;
    object-fit: cover;
    border-radius: 8px;
    margin-bottom: 10px;
  }
  
  /* Admin Page */
  .admin {
    padding: 40px 20px;
  }
  
  .admin-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
    gap: 20px;
    margin-top: 20px;
  }
  
  .admin-card {
    text-align: center;
    background-color: white;
    padding: 15px;
    border-radius: 10px;
    box-shadow: 0 2px 8px rgba(0,0,0,0.1);
  }
  
  .admin-card img {
    width: 100%;
    height: 200px;
    object-fit: cover;
    border-radius: 8px;
    margin-bottom: 10px;
  }
  
  /* Contact Page */
  .contact {
    padding: 40px 20px;
    background-color: #bf699f;
    font-size: 18px;
    line-height: 1.6;
  }
  
  /* Color Scheme: Warm and welcoming palette */
  /* #fffaf1 background, #fcefd8 feature blocks, #444 nav bar, white content blocks */
```

# OUTPUT:
![Screenshot 2025-05-02 085110](https://github.com/user-attachments/assets/2befcfa6-71f3-4296-8b37-600165aef7b0)
![Screenshot 2025-05-02 085126](https://github.com/user-attachments/assets/39fa243c-ca44-4814-b891-d57ef6108a78)
![Screenshot 2025-05-02 085239](https://github.com/user-attachments/assets/0b3c8cc5-2021-468c-a105-42cc49d393cf)
![Screenshot 2025-05-02 085313](https://github.com/user-attachments/assets/7e866e9b-5c73-4f43-b554-21a759909ebd)




# RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
