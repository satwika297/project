<!DOCTYPE html>
{% load static %}
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>About Me</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css" />
    <link rel="icon" href="{% static 'vehicle_images/logo.png' %}" type="image/x-icon">
    <link rel="stylesheet" href="{% static 'css/header_footer.css' %}">
    <link rel="stylesheet" href="{% static 'css/contactus_about.css' %}">
</head>
<body>
    <nav>
        <div class="nav-bar">
            <i class="fas fa-bars sidebarOpen"></i>
            <span class="logo navLogo"><a href="/">Bike Rental Management</a></span>
            <div class="menu">
                <div class="logo-toggle">
                    <span class="logo"><a href="/">Bike Rental Management</a></span>
                    <i class="fas fa-xmark siderbarClose"></i>
                </div>
    
                <ul class="nav-links">
                    <li><a href="/">Home</a></li>
                    <li><a href="/customer_login">Customer</a></li>
                    <li><a href="/dealer_login">Dealer</a></li>
                    <li><a href="/about" class="active">About</a></li>
                    <li><a href="/contactus">Contact</a></li>
                    <li>
                        <div class="dark-light">
                            <i class="fas fa-sun sun"></i>
                            <i class="fas fa-moon moon"></i>
                        </div>
                    </li>
                </ul>
            </div>
            <div class="darkLight">
                <div class="dark-light">
                    <i class="fas fa-sun sun"></i>
                    <i class="fas fa-moon moon"></i>
                </div>
            </div>
        </div>
    </nav>
<!--  Header End -->

    <!-- Main Content Start -->
    <div class="aboutp">
        <div class="card">
            <div class="imgBox">
                <img src="{% static 'images/clz_logo.jpg' %}">
                <img src="{% static 'images/college.jpg' %}">
            </div>
            <div class="details">
                <div class="contentp">
                    <h2>Developed by<br><span>SWEC IT 2025</span></h2>
                    <span>( MCA Gradute )</span>
                    <p><i class="fa-solid fa-phone" style="--icon-clr: #1fdfdf;"></i>(+91) 6371202542</p>
                    <p><i class="fa-solid fa-envelope" style="--icon-clr: #df1f1f;"></i>bikesonrent@gmail.com</p>
                    <div class="social-icons">
                        <a href="https://www.instagram.com/satya.brata_panda?igsh=MTNuNHBuMXg4MTUyOQ==" target="_blank" style="--social-clr: #c32aa3;"><i class="fab fa-instagram"></i></a>
                        <a href="https://x.com/__SWEC IT 2025__" target="_blank" style="--social-clr: #000000;"><i class="fab fa-x-twitter"></i></a>
                        <a href="https://www.linkedin.com/in/SWEC IT 2025-panda-a462b5220" target="_blank" style="--social-clr: #0A66C2;"><i class="fab fa-linkedin-in"></i></a>
                        <a href="https://satya-portfolio-web.netlify.app/" target="_blank" style="--social-clr: #0097F9;"><i class="fas fa-globe"></i></a>
                    </div>
                </div>
            </div>
        </div>
        <div class="wrapper">
            <div class="flip-inner-wrapper">
                <div class="flip-front">
                    <img src="{% static 'images/clz_logo.jpg' %}">
                </div>
                <div class="flip-back">
                    <img src="{% static 'images/college.jpg' %}">
                    <h2>Developed by<br><span>SWEC IT 2025</span></h2>
                    <span>( B.Tech Gradute )</span>
                    <p><i class="fa-solid fa-phone" style="--icon-clr: #1fdfdf;"></i>(+91) 6371202542</p>
                    <p><i class="fa-solid fa-envelope" style="--icon-clr: #df1f1f;"></i>bikesonrent@gmail.com</p>
                    <div class="social-icons">
                        <a href="https://www.instagram.com/satya.brata_panda?igsh=MTNuNHBuMXg4MTUyOQ==" target="_blank" style="--social-clr: #c32aa3;"><i class="fab fa-instagram"></i></a>
                        <a href="https://x.com/__SWEC IT 2025__" target="_blank" style="--social-clr: #000000;"><i class="fab fa-x-twitter"></i></a>
                        <a href="https://www.linkedin.com/in/SWEC IT 2025-panda-a462b5220" target="_blank" style="--social-clr: #0A66C2;"><i class="fab fa-linkedin-in"></i></a>
                        <a href="https://www.youtube.com/channel/UCRwqXSEz4xspk1B1z592-fA" target="_blank" style="--social-clr: #ff0000;"><i class="fab fa-youtube"></i></a>
                    </div>
                </div>
            </div>
        </div>
    </div>
    

    <!-- Footer Part start -->
    <footer>
        <div class="main-content">
            <div class="left box">
                <h2>About us</h2>
                <div class="content">
                    <p>A vehicle rental platform for cars and bikes that enables users to browse, book, and pay for rentals online. It features vehicle listings, availability checks, secure payments, and booking management, offering a convenient way to rent vehicles on-demand.</p>
                    <div class="social">
                        <a href="https://www.facebook.com/SWEC IT 2025.panda.3956690?mibextid=ZbWKwL" target="_blank" style="--social-clr: #1877f2;"><i class="fab fa-facebook-f"></i></a>
                        <a href="https://x.com/__SWEC IT 2025__" target="_blank" style="--social-clr: #000000;"><i class="fab fa-x-twitter"></i></a>
                        <a href="https://www.instagram.com/satya.brata_panda?igsh=MTNuNHBuMXg4MTUyOQ==" target="_blank" style="--social-clr: #c32aa3;"><i class="fab fa-instagram"></i></a>
                        <a href="https://www.youtube.com/channel/UCRwqXSEz4xspk1B1z592-fA" target="_blank" style="--social-clr: #ff0000;"><i class="fab fa-youtube"></i></a>
                    </div>
                </div>
            </div>
    
            <div class="center box">
                <h2>Address</h2>
                <div class="content">
                    <div class="place">
                        <span class="fas fa-location-dot icon" style="--all-clr: #1c68b5;"></span>
                        <span class="text">India</span>
                    </div>
                    <div class="phone">
                        <span class="fas fa-phone icon" style="--all-clr: #000080;"></span>
                        <span class="text">+91 9123456789</span>
                    </div>
                    <div class="email">
                        <span class="fas fa-envelope icon" style="--all-clr: #ff0000;"></span>
                        <span class="text">SWEC IT 2025&#64;gmail.com</span>
                    </div>
                </div>
            </div>
    
            <div class="right box">
                <h2>Contact us</h2>
                <div class="content">
                    <form action="#">
                        <div class="email">
                            <div class="text">Email <span style="color: red;">*</span></div>
                            <input type="email" required>
                        </div>
                        <div class="msg">
                            <div class="text">Message <span style="color: red;">*</span></div>
                            <textarea cols="25" rows="2" required></textarea>
                        </div>
                        <div class="contact-us-btn">
                            <button type="submit">Send</button>
                        </div>
                    </form>
                </div>
            </div>
        </div>
        <div class="bottom">
            <div class="center">
                <span class="credit">Created By <a href="#">Satya</a> | &copy; 2024 All rights reserved.</span>
            </div>
        </div>
    </footer>
    <script src="{% static 'js/header.js' %}"></script>
</body>
</html>
