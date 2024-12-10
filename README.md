# Ex.07 Restaurant Website
## Date:

## AIM:
To develop a static Restaurant website to display the food items and services provided by them.

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
```
rest.html

<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Le Petit Café</title>
</head>
<body>

    <div style="font-size: 40px; font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif; text-align: center; background-color: rgb(207, 160, 107); padding: 20px;">
        <h1>Le Petit Café</h1>
        <img src="pl logo.png" alt="Le Petit Café" style="width: 300px; height: auto; margin-top: 1px;">
    </div>

    <nav style="background-color: #4c3720; padding: 10px; text-align: center;">
        <ul style="list-style-type: none; padding: 0; margin: 0;">
            <li style="display: inline; margin-right: 20px;"><a href="#home" style="text-decoration: none; color: white;">Home</a></li>
            <li style="display: inline; margin-right: 20px;"><a href="#about" style="text-decoration: none; color: white;">About</a></li>
            <li style="display: inline; margin-right: 20px;"><a href="#menu" style="text-decoration: none; color: white;">Menu</a></li>
            <li style="display: inline; margin-right: 20px;"><a href="#ourcrew" style="text-decoration: none; color: white;">Administration</a></li>
            <li style="display: inline; margin-right: 20px;"><a href="#query" style="text-decoration: none; color: white;">Query</a></li>
            <li style="display: inline; margin-right: 20px;"><a href="#contact" style="text-decoration: none; color: white;">Contact</a></li>
        </ul>
    </nav>

    <section id="home" style="padding: 20px; text-align: center; background-color: rgb(243, 213, 178);">
        <h2>Bonjour Le Petit Café</h2>
        <p>Step into the fresh french cultured cafe</p>
        <p>Whether you're here for a peaceful moment with a latte or a lively gathering over fresh pastries, we’re delighted to have you. </p>
        <p>Relax, savor, and let us make your day a little brighter. </p>
        <p>Experience the french style cuisine at your place</p>
        <p>Bienvenue! 🌸☕</p>
    </section>

    <section id="about" style="padding: 20px; text-align: center; background-color: rgb(219, 160, 115);">
        <h2>About Us</h2>
        <p>Welcome to Le Petit Café, where the charm of France meets the warmth of home. </p>
        <p>We're a cozy haven for those seeking delicious coffee, delectable pastries, and a dash of joie de vivre. </p>
        <p>Come for the coffee, stay for the community.</p>
    </section>

    <section id="about" style="padding: 20px; text-align: center; background-color: rgb(196, 168, 104);">
        <h2>The Origin</h2>
        <p>Le Petit Café has been a charming haven for coffee enthusiasts and lovers of fine pastries. </p>
        <p>Established in 1973, it has consistently offered a blend of traditional recipes and contemporary flavors, creating a unique culinary experience. </p>
        <p>Known for its cozy atmosphere, impeccable service, and thoughtfully crafted menu, Le Petit Café continues to be a go-to destination for those seeking a delightful retreat in the heart of the city.</p>
    </section>

    <section id="menu" style="padding: 20px; text-align: center; background-color: #b88d49;">
        <h2>A Taste of Paris</h2>
        <div style="display: flex; justify-content: center; gap: 20px; flex-wrap: wrap;">
            <div style="text-align: center;">
                <img src="croissant.jpg" alt="Flaky, buttery pastry often enjoyed for breakfast." style="width: 150px; height: 150px;">
                <p>Croissant - $2.00</p>
            </div>
            <div style="text-align: center;">
                <img src="Mille-Feuille.jpg" alt="Layered pastry made with puff pastry, pastry cream, and fruit preserves." style="width: 150px; height: 150px;">
                <p>Mille-Feuille - $5.25</p>
            </div>
            <div style="text-align: center;">
                <img src="Soupe à l'Oignon.jpg" alt="French onion soup with caramelized onions, beef broth, and a cheesy gratin topping." style="width: 150px; height: 150px;">
                <p>Soupe à l'Oignon - $9.75</p>
            </div>
            <div style="text-align: center;">
                <img src="Crème Brûlée.jpg" alt="Rich custard topped with a caramelized sugar crust." style="width: 150px; height: 150px;">
                <p>Crème Brûlée - $6.99</p>
            </div>
            <div style="text-align: center;">
                <img src="Quiche Lorraine.jpg" alt="Savory tart with a filling of cream, eggs, and bacon or lardons." style="width: 150px; height: 150px;">
                <p>Quiche Lorraine - $4.99</p>
            </div>
            <div style="text-align: center;">
                <img src="Moules Marinières.avif" alt="Mussels cooked in white wine, shallots, and parsley." style="width: 150px; height: 150px;">
                <p>Moules Marinières - $8.60</p>
            </div>
            <div style="text-align: center;">
                <img src="Choucroute Garnie (Alsace).jpg" alt="Sauerkraut with sausage, ham, and potatoes." style="width: 150px; height: 150px;">
                <p>Choucroute Garnie - $11.00</p>
            </div>
        </div>
    </section>

    <section id="ourcrew" style="padding: 20px; text-align: center;">
        <h2>Our Crew</h2>
        <div style="display: flex; justify-content: center; gap: 20px; flex-wrap: wrap;">
            <div style="text-align: center;">
                <img src="Akshay.jpg" alt="CEO" style="width: 150px; height: 150px;">
                <p>Akshay Karthick - Our CEO</p>
            </div>
            <div style="text-align: center;">
                <img src="Alain Ducasse.jpg" alt="Investor" style="width: 150px; height: 150px;">
                <p>Alain Ducasse - Our Investor</p>
            </div>
            <div style="text-align: center;">
                <img src="Sanjeev_kapoor.jpg" alt="Chief Chef" style="width: 150px; height: 150px;">
                <p>Sanjeev Kapoor - Our Chief Chef</p>
            </div>
            <div style="text-align: center;">
                <img src="Garima Arora.jpg" alt="Executive Chef" style="width: 150px; height: 150px;">
                <p>Garima Arora - Our Executive Chef</p>
            </div>
            <div style="text-align: center;">
                <img src="ey-dilip-shangvi.webp" alt="Exclusive Partner" style="width: 150px; height: 150px;">
                <p>Dilip Shanghvi - Our Exclusive Partner</p>
            </div>
            <div style="text-align: center;">
                <img src="Mr.-Varun-Jaipuria.png" alt="Leading Supplier" style="width: 150px; height: 150px;">
                <p>Varun Jaipuria - Our Leading Supplier</p>
            </div>
        </div>
    </section>


    <section id="query" style="padding: 20px; text-align: center; background-color: #4a3d26; color: white;">
        <h2>Any Query</h2>
        <p>Inform us your feedback and queries here</p>
        <form action="#" style="text-align: center;">
            <input type="name" placeholder="Your Name" style="padding: 5px; margin: 5px;"><br>
            <textarea placeholder="Your Query" rows="4" style="padding: 5px; margin: 5px;"></textarea><br>
            <button type="submit" style="padding: 10px 20px; background-color: #b88d49; color: white; border: none; cursor: pointer;">Submit</button>
        </form>
    </section>

    <section id="contact" style="padding: 20px; text-align: center; background-color: #06111B; color: white;">
        <h2>Contact Us</h2>
        <p>Get in touch with us or Have questions or want to book a table? </p>
        <form action="#" style="text-align: center;">
            <p>Our email - lepetitfrancais@gmail.com</p>
            <p>Our telephone - +33 6 12 34 56 78</p>
        </form>
    </section>

    <div style="font-size: 15xpx; text-align: bottom; background-color: rgb(207, 160, 107); padding: 20px;">
        <p>Designed and Developed by Akshay Karthick ASR</p>
    </div>

</body>
</html>


```

## OUTPUT:
![alt text](<Screenshot (54).png>)
![alt text](<Screenshot (55).png>)
![alt text](<Screenshot (56).png>)
![alt text](<Screenshot (57).png>)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
