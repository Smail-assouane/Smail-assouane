<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Skills School</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }
        header {
            background-color: #4CAF50;
            color: white;
            padding: 1rem;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #333;
        }
        nav a {
            color: white;
            padding: 14px 20px;
            text-decoration: none;
            text-align: center;
        }
        nav a:hover {
            background-color: #ddd;
            color: black;
        }
        .container {
            padding: 2rem;
        }
        .section {
            margin-bottom: 2rem;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 1rem;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
        .logo {
            font-size: 2rem;
            font-weight: bold;
        }
        .contact-info {
            list-style: none;
            padding: 0;
        }
        .contact-info li {
            margin: 0.5rem 0;
        }
    </style>
</head>
<body>

<header>
    <div class="logo">Skills School</div>
</header>

<nav>
    <a href="#about">About Us</a>
    <a href="#courses">Courses</a>
    <a href="#contact">Contact</a>
</nav>

<div class="container">
    <div id="about" class="section">
        <h2>About Us</h2>
        <p>Welcome to Skills School, your premier destination for professional training in English, Personal Development, HSE (Health, Safety, and Environment), and Offshore courses. Our mission is to empower individuals and companies with the skills they need to succeed in today's competitive environment.</p>
    </div>

    <div id="courses" class="section">
        <h2>Our Courses</h2>
        <ul>
            <li><strong>English Training:</strong> Enhance your communication skills with our comprehensive English courses.</li>
            <li><strong>Personal Development:</strong> Develop your personal and professional skills to achieve your goals.</li>
            <li><strong>HSE Courses:</strong> Learn essential health, safety, and environmental practices to ensure a safe workplace.</li>
            <li><strong>Offshore Courses:</strong> Specialized training for offshore industry professionals.</li>
        </ul>
    </div>

    <div id="contact" class="section">
        <h2>Contact Us</h2>
        <ul class="contact-info">
            <li>Email: info@skillsschool.com</li>
            <li>Phone: +123 456 7890</li>
            <li>Address: 123 Training Center Ave, Education City, Country</li>
            <li>Follow us on:
                <a href="#">Facebook</a>,
                <a href="#">Twitter</a>,
                <a href="#">LinkedIn</a>
            </li>
        </ul>
    </div>
</div>

<footer>
    &copy; 2024 Skills School. All rights reserved.
</footer>

</body>
</html>
