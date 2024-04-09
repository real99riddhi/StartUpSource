# StartUpSource
# Welcome to Our Website

## About Us

We are a team dedicated to providing quality content and services to our users. Our goal is to create a seamless experience for our visitors.

## Services

- Startup ideas
- Guidance
- Connections
- Basics to advanced
- P.S. We're still updating our website for better user experience..
- <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HOME PAGE</title>
    <style>
        body {
            font-family: 'Times New Roman', Times, serif; /* Change font-family to a formal serif font */
            margin: 0;
            padding: 0;
            background-color: #333;
            color: #f0f0f0; /* Light pastel font color */
        }

        header {
            background-color: #222; /* Slightly darker background for header */
            color: #f0f0f0;
            text-align: center;
            padding: 20px;
        }

        main {
            padding: 20px;
        }

        .image-links {
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
        }

        .image-links a {
            text-decoration: none;
            color: #f0f0f0;
            text-align: center;
            margin: 20px;
            flex: 0 0 calc(30% - 40px);
        }

        .image-links a:hover {
            transform: scale(1.1);
            transition: transform 0.3s ease-in-out;
        }

        .image-links img {
            max-width: 100%;
            height: auto;
            border-radius: 10px;
        }

        .learn-options {
            text-align: center;
            margin-top: 40px;
        }

        .learn-options h2 {
            font-size: 24px;
            margin-bottom: 20px;
        }

        .category-links {
            display: flex;
            justify-content: center;
        }

        .category-links a {
            text-decoration: none;
            color: #f0f0f0;
            background-color: #555;
            padding: 10px 20px;
            margin: 0 10px;
            border-radius: 5px;
        }

        .category-links a:hover {
            background-color: #777;
        }

        footer {
            background-color: #222; /* Slightly darker background for footer */
            color: #f0f0f0;
            text-align: center;
            padding: 10px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to StartUp Source</h1>
    </header>
    <main>
        <section class="image-links">
            <a href="about.html">
                <img src="C:\Users\MRIDUL KHANDELWAL\Downloads\_a50e2429-bf2d-452b-a3a7-c9092dddd946.jpg" alt="About Us">
                <h2>About Us</h2>
            </a>
            <a href="services.html">
                <img src="C:\Users\MRIDUL KHANDELWAL\Downloads\_4865b362-d8b0-4610-9f24-77b5d3845b67.jpg" alt="Our Services">
                <h2>Our Services</h2>
            </a>
            <a href="contact.html">
                <img src="C:\Users\MRIDUL KHANDELWAL\Downloads\_b3a71d2c-8edf-4549-a99f-68e841fc80dc.jpg" alt="Contact Us">
                <h2>Contact Us</h2>
            </a>
        </section>
        
        <section class="learn-options">
            <h2>What would you like to learn today?</h2>
            <div class="category-links">
                <a href="#">Tech</a>
                <a href="#">Non-Tech</a>
                <a href="#">Others</a>
            </div>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 StartUp Source
           thanks for visting our website!</p>
    </footer>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>About Us</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #000; /* Black background */
            color: #fff; /* White text */
        }

        .container {
            max-width: 800px;
            margin: 0 auto;
            padding: 20px;
        }

        h1, h2 {
            text-align: center;
        }

        p {
            line-height: 1.6;
        }

        .team-member {
            margin-bottom: 40px;
        }

        .team-member img {
            max-width: 100%;
            height: auto;
            border-radius: 50%;
            display: block;
            margin: 0 auto 10px;
        }

        .team-member h3 {
            text-align: center;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>About Us</h1>
        <p>Welcome to our company! We are a team of passionate individuals dedicated to creating a place where everyone can find resources for their startup idea</p>
        <h2>Our Team</h2>
           
            <h3>Riddhi Sharma</h3>
       
            <h3>Riddhima Bisht</h3>

            <h3>Rishika Khandelwal</h3>

            
               <p>If you have any questions or inquiries, feel free to <a href="contact.html">contact us</a>.</p>
    </div>
</body>
</html>
