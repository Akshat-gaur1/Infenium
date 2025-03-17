<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Infenium Media | Elevate Your Brand</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@300;600&family=Playfair+Display:wght@400;700&display=swap');
        
        body {
            font-family: 'Montserrat', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f1ec;
            color: #333;
            text-align: center;
        }
        .container {
            width: 80%;
            margin: auto;
            padding: 50px 0;
        }
        .hero {
            padding: 100px 20px;
            background: linear-gradient(135deg, #252422, #403d39);
            color: #f4f1ec;
            font-weight: bold;
            border-bottom: 5px solid #ff8303;
            box-shadow: 6px 6px 0px #403d39;
        }
        .hero h1 {
            font-size: 3.5rem;
            font-family: 'Playfair Display', serif;
            text-transform: uppercase;
        }
        .hero p {
            font-size: 1.4rem;
        }
        .btn {
            display: inline-block;
            margin-top: 20px;
            padding: 14px 28px;
            background-color: #ff8303;
            color: #fff;
            text-decoration: none;
            font-weight: bold;
            border-radius: 8px;
            transition: all 0.3s;
        }
        .btn:hover {
            background-color: #e67e22;
        }
        .section {
            padding: 60px 20px;
            border-bottom: 2px dashed #403d39;
        }
        .toggle-content {
            display: none;
            margin-top: 10px;
        }
        .toggle-btn {
            background: none;
            border: none;
            color: #ff8303;
            font-size: 1.2rem;
            cursor: pointer;
            font-weight: bold;
        }
        .services {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 20px;
        }
        .service-box {
            background: #fff;
            padding: 20px;
            border-radius: 10px;
            width: 300px;
            text-align: center;
            cursor: pointer;
            box-shadow: 6px 6px 0px #403d39;
            border: 2px solid #403d39;
            transition: all 0.3s;
        }
        .service-box:hover {
            transform: scale(1.05);
            background: #ffe8d6;
        }
        .service-desc {
            display: none;
            font-size: 0.9rem;
            margin-top: 10px;
        }
        .footer {
            padding: 20px;
            background-color: #252422;
            color: white;
        }
        .contact {
            padding: 40px 20px;
            background-color: #ffe8d6;
        }
        .contact a {
            color: #403d39;
            text-decoration: underline;
            font-weight: bold;
        }
    </style>
    <script>
        function toggleDescription(id) {
            var desc = document.getElementById(id);
            desc.style.display = desc.style.display === "none" || desc.style.display === "" ? "block" : "none";
        }
        function toggleAbout() {
            var content = document.getElementById("about-content");
            content.style.display = content.style.display === "none" || content.style.display === "" ? "block" : "none";
        }
    </script>
</head>
<body>
    <div class="hero">
        <h1>Infenium Media</h1>
        <p>We turn attention into opportunity.</p>
        <a href="#contact" class="btn">Work With Us</a>
    </div>

    <div class="container">
        <div class="section">
            <h2>About Us</h2>
            <button class="toggle-btn" onclick="toggleAbout()">Learn More</button>
            <p id="about-content" class="toggle-content">In a world where attention is the new currency, we make sure you’re always in demand. We create connections that matter, helping brands and influencers cut through the noise and make a lasting impact.</p>
        </div>

        <div class="section">
            <h2>Our Services</h2>
            <div class="services">
                <div class="service-box" onclick="toggleDescription('service1')">
                    <h3>Brand Collaborations</h3>
                    <p id="service1" class="service-desc">We connect brands with the right influencers for impactful collaborations.</p>
                </div>
                <div class="service-box" onclick="toggleDescription('service2')">
                    <h3>Influencer Growth</h3>
                    <p id="service2" class="service-desc">We help influencers grow their brand presence and reach wider audiences.</p>
                </div>
                <div class="service-box" onclick="toggleDescription('service3')">
                    <h3>Creative Campaigns</h3>
                    <p id="service3" class="service-desc">We craft unique marketing campaigns that drive engagement and conversions.</p>
                </div>
            </div>
        </div>

        <div class="section contact" id="contact">
            <h2>Contact Us</h2>
            <p>Let's create something extraordinary together.</p>
            <p>Email: <a href="mailto:infeniummedia@gmail.com">infeniummedia@gmail.com</a></p>
            <p>Instagram: <a href="https://instagram.com/infeniummedia" target="_blank">@infeniummedia</a></p>
        </div>
    </div>

    <div class="footer">
        <p>© 2025 Infenium Media. All rights reserved.</p>
    </div>
</body>
</html>
