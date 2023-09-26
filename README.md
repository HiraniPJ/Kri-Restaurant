<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
<link rel="stylesheet" href="assets/css/style.css">
    <title>Krishna Restaurant</title>
</head>


<!-- Header Section -->
<body>
    <header>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="book.html">Booking</a></li>
            </ul>
        </nav>
        <div class="search-bar">
            <input type="text" placeholder="Search...">
            <button>Search</button>
        </div>
    </header>


    <!-- Hero Section -->
    <section class="hero">
        <img src="samosa.png" alt="Restaurant's ambiance image" class="hero-image">
        <div class="hero-content">
        <h1>Welcome to Krishna Restaurant</h1>
        <p>Delight in the Authentic Flavors of Vegetarian Indian Cuisine</p>
        <a href="menu.html" class="cta-button">Explore our Menu</a>
        </div>
    </section>

    <!-- About Section with Video -->
    <section class="about">
        <h2>About Us</h2>
        <video controls width="500">
            <source src="path_to_video.mp4" type="video/mp4">
            Your browser does not support the video tag.
        </video>
        <p>We are a family-owned restaurant dedicated to bringing you the authentic flavors of India. Our culinary experts
            craft each dish with love and care, using the finest ingredients and traditional recipes.</p>
    </section>


<!-- Menu Section -->
<section class="menu">
    <h2>Our Menu</h2>
    <!-- Sample menu items -->
    <div class="menu-item">
        <img src="paneer-tikka.png" alt="Paneer Tikka">
        <h3>Paneer Tikka</h3>
        <p>Grilled paneer cubes marinated in spices, served with mint chutney. A true North Indian delight.</p>
        <span>$12.99</span>
    </div>

    <!-- Contact Section -->
        <section class="contact">
            <h2>Contact Us</h2>
            <p>For reservations, please use the form below:</p>
            <form id="reservation-form">
                <div class="form-group">
                    <label for="reservation-date">Date:</label>
                    <input type="date" id="reservation-date" required>
                </div>
                <div class="form-group">
                    <label for="reservation-time">Time:</label>
                    <select id="reservation-time" required>
                        <option value="12:00 PM">12:00 PM</option>
                        <option value="1:00 PM">1:00 PM</option>
                        <option value="2:00 PM">2:00 PM</option>
                        
                    </select>
                </div>
                <div class="form-group">
                    <label for="party-size">Party Size:</label>
                    <select id="party-size" required>
                        <option value="1">1 person</option>
                        <option value="2">2 people</option>
                        <option value="3">3 people</option>
                        <option value="4">4 people</option>
                        <option value="5">5 people</option>
                        <option value="6">6 people</option>
                    </select>
                </div>
                <button type="submit">Make Reservation</button>
            </form>
        </section>


    <!-- Footer -->
    <section class="footer">
        <ul class="social-icons">
            <li><a href="https://www.facebook.com/" target="_blank" rel="noopener" aria-label="Visit our Facebook page "><i class="fa-brands fa-facebook"></i></a></li>
            <li><a href="https://www.instagram.com/" target="_blank" rel="noopener" aria-label="Visit our Instagram page "><i class="fa-brands fa-instagram"></i></a></li>
            <li><a href="https://www.twitter.com/" target="_blank" rel="noopener" aria-label="Visit our Twitter page "><i class="fa-brands fa-twitter"></i></a></li>
        </ul>
        <script src="https://kit.fontawesome.com/6ed4674fb0.js" crossorigin="anonymous"></script>
        <p>&copy; 2023 Krishna Restaurant</p>
    </section>
</body>
</html>





css style

/* Reset some default styles */
body,
ul,
li {
    margin: 0;
    padding: 0;
    list-style: none;
}

/* Global Styles */
body {
    font-family: Arial, sans-serif;
    background-color: #f5f5f5;
}

header {
    background-color: #333;
    color: #fff;
    padding: 10px 0;
    display: flex;
    justify-content: space-between;
    align-items: center;
    position: sticky;
    top: 0;
    z-index: 999;
}

nav ul {
    text-align: center;
}

nav li {
    display: inline;
    margin: 0 20px;
}

nav a {
    text-decoration: none;
    color: #fff;
    font-weight: bold;
}


/* Menu Section */
.menu {
    display: flex;
    flex-wrap: wrap;
    justify-content: space-between;
}

.menu-item {
    flex: 0 0 calc(25% - 20px);
    /* 4 items in a row, accounting for 20px of margin */
    margin: 10px;
    background-color: #fff;
    border-radius: 5px;
    box-shadow: 0 3px 15px rgba(0, 0, 0, 0.1);
    text-align: center;
    padding: 20px;
}

.menu-item img {
    max-width: 100%;
    height: auto;
    border-radius: 5px;
}

.menu-item h3 {
    margin: 15px 0 10px;
}

.menu-item p {
    font-size: 14px;
    color: #666;
}

.menu-item span {
    display: block;
    font-weight: bold;
    margin-top: 10px;
}

/* Responsive tweaks */
@media screen and (max-width: 768px) {
    .menu-item {
        flex: 0 0 calc(50% - 20px);
        /* 2 items in a row for smaller screens */
    }
}

/* Menu Section */
.menu {
    display: flex;
    flex-wrap: wrap;
    justify-content: space-between;
}

.menu-item {
    flex: 0 0 calc(25% - 20px);
    /* 4 items in a row, accounting for 20px of margin */
    margin: 10px;
    background-color: #fff;
    border-radius: 5px;
    box-shadow: 0 3px 15px rgba(0, 0, 0, 0.1);
    text-align: center;
    padding: 20px;
}

.menu-item img {
    max-width: 100%;
    height: auto;
    border-radius: 5px;
}

.menu-item h3 {
    margin: 15px 0 10px;
}

.menu-item p {
    font-size: 14px;
    color: #666;
}

.menu-item span {
    display: block;
    font-weight: bold;
    margin-top: 10px;
}

/* Responsive tweaks */
@media screen and (max-width: 768px) {
    .menu-item {
        flex: 0 0 calc(50% - 20px);
        /* 2 items in a row for smaller screens */
    }
}

/* Menu Section */ 

.menu {
    display: flex;
    flex-wrap: wrap;
    justify-content: space-between;
}

.menu-item {
    flex: 0 0 calc(25% - 20px);
    /* 4 items in a row, accounting for 20px of margin */
    margin: 10px;
    background-color: #fff;
    border-radius: 5px;
    box-shadow: 0 3px 15px rgba(0, 0, 0, 0.1);
    text-align: center;
    padding: 20px;
}

.menu-item img {
    max-width: 100%;
    height: auto;
    border-radius: 5px;
}

.menu-item h3 {
    margin: 15px 0 10px;
}

.menu-item p {
    font-size: 14px;
    color: #666;
}

.menu-item span {
    display: block;
    font-weight: bold;
    margin-top: 10px;
}

/* Responsive tweaks */
@media screen and (max-width: 768px) {
    .menu-item {
        flex: 0 0 calc(50% - 20px);
        /* 2 items in a row for smaller screens */
    }
}

/* Page-specific Styles */
.hero {
    background-image: url('images/restaurant.jpg');
    background-size: cover;
    text-align: center;
    padding: 100px 0;
    color: #fff;
}


/* Menu Section */
.menu {
    display: flex;
    flex-wrap: wrap;
    justify-content: space-between;
}

.menu-item {
    flex: 0 0 calc(25% - 20px);
    /* 4 items in a row, accounting for 20px of margin */
    margin: 10px;
    background-color: #fff;
    border-radius: 5px;
    box-shadow: 0 3px 15px rgba(0, 0, 0, 0.1);
    text-align: center;
    padding: 20px;
}

.menu-item img {
    max-width: 100%;
    height: auto;
    border-radius: 5px;
}

.menu-item h3 {
    margin: 15px 0 10px;
}

.menu-item p {
    font-size: 14px;
    color: #666;
}

.menu-item span {
    display: block;
    font-weight: bold;
    margin-top: 10px;
}


.cta-button {
    display: inline-block;
    padding: 10px 20px;
    background-color: #d9534f;
    color: #fff;
    text-decoration: none;
    font-weight: bold;
    margin-top: 20px;
}

.about,
.contact {
    padding: 40px;
    background-color: #fff;
}

.contact h2 {
    margin-top: 30px;
}

.form-group {
    margin: 20px 0;
}

label {
    font-weight: bold;
}

input[type="date"],
select {
    width: 100%;
    padding: 10px;
    margin-top: 5px;
}

button[type="submit"] {
    background-color: #d9534f;
    color: #fff;
    border: none;
    padding: 10px 20px;
    font-weight: bold;
    cursor: pointer;
}

button[type="submit"]:hover {
    background-color: #c9302c;
}

.footer {
    background-color: rgb(77, 77, 77);
    color: #ffffff;
    text-align: center;
    padding: 10px 0;
}

.social-icons {
    list-style: none;
    padding: 0;
    margin: 0;
    display: flex;
    justify-content: center;
}

.social-icons li {
    margin: 0 10px;
}

.social-icons img {
    width: 30px;
    height: 30px;
    transition: transform 0.3s;
}

.social-icons a:hover img {
    transform: scale(1.2);
}

/* Responsive Styles */
@media screen and (max-width: 768px) {
    nav ul {
        text-align: left;
    }

    nav li {
        display: block;
        margin: 10px 0;
    }

    .search-bar {
        display: none;
    }


    .menu-item {
        flex: 0 0 calc(50% - 20px);
        /* 2 items in a row for smaller screens */
    }
}

images

![image](https://github.com/HiraniPJ/Kri-Restaurant/assets/139878937/9d5c3c25-6ddd-4635-8eb9-c8e44ef92a1e)


![image](https://github.com/HiraniPJ/Kri-Restaurant/assets/139878937/0282667f-4fe9-4cfe-adb1-2c5e9a91577c)


