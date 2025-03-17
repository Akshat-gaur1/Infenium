
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
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Infenium Media | Authentic Growth for Brands & Influencers</title>
    <style>
        body {
            font-family: 'Montserrat', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
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
            background: linear-gradient(135deg, #0077b6, #0096c7);
            color: white;
            font-weight: bold;
            position: relative;
        }
        .hero img {
            max-width: 150px;
            position: absolute;
            top: 20px;
            left: 20px;
        }
        .hero h1 {
            font-size: 3.5rem;
            animation: fadeIn 1.5s ease-in-out;
        }
        .hero p {
            font-size: 1.3rem;
            opacity: 0.9;
        }
        .btn {
            display: inline-block;
            margin-top: 20px;
            padding: 12px 24px;
            background-color: #0096c7;
            color: #fff;
            text-decoration: none;
            font-weight: bold;
            border-radius: 8px;
            transition: background 0.3s;
        }
        .btn:hover {
            background-color: #0077b6;
        }
        .section {
            padding: 60px 20px;
            transition: transform 0.3s;
        }
        .section:hover {
            transform: scale(1.02);
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
            transition: transform 0.3s;
            cursor: pointer;
            box-shadow: 0 4px 8px rgba(0,0,0,0.1);
            display: flex;
            flex-direction: column;
            align-items: center;
        }
        .service-box:hover {
            transform: translateY(-5px);
            background: #caf0f8;
        }
        .service-box img {
            width: 50px;
            margin-bottom: 10px;
        }
        .service-description {
            display: none;
            background: #e0f7fa;
            padding: 20px;
            margin-top: 10px;
            border-radius: 10px;
        }
        .footer {
            padding: 20px;
            background-color: #0096c7;
            color: white;
            opacity: 0.9;
        }
        .contact {
            padding: 40px 20px;
            background-color: #caf0f8;
        }
        .contact a {
            color: #0096c7;
            text-decoration: none;
            font-weight: bold;
        }
        .cta-icon {
            position: fixed;
            bottom: 20px;
            right: 20px;
            background: #0096c7;
            color: white;
            padding: 15px;
            border-radius: 50%;
            cursor: pointer;
            font-size: 24px;
            text-align: center;
            box-shadow: 0 4px 8px rgba(0,0,0,0.2);
        }
        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }
    </style>
    <script>
        function toggleServiceDescription(id) {
            var element = document.getElementById(id);
            if (element.style.display === "none" || element.style.display === "") {
                element.style.display = "block";
            } else {
                element.style.display = "none";
            }
        }
    </script>
</head>
<body>
    <div class="hero">
        <img src=""C:\Users\aksha\Pictures\Screenshots\Screenshot 2025-03-17 143655.png"" alt="Infenium Media Logo">
        <h1>Infenium Media</h1>
        <p>Bridging brands & influencers for authentic collaborations.</p>
        <a href="#contact" class="btn">Let's Work Together</a>
    </div>

    <div class="container">
        <div class="section">
            <h2>Our Services</h2>
            <div class="services">
                <div class="service-box" onclick="toggleServiceDescription('service1')">
                    <img src="influencer-icon.png" alt="Influencer Marketing">
                    Influencer Marketing
                </div>
                <div class="service-description" id="service1">We have a network of 100+ nano and micro-influencers ready to work with your brand, ensuring targeted and authentic audience engagement.</div>
                <div class="service-box" onclick="toggleServiceDescription('service2')">
                    <img src="ugc-icon.png" alt="UGC Creators">
                    UGC Creators
                </div>
                <div class="service-description" id="service2">Our professional UGC creators deliver high-quality content tailored for maximum engagement and brand trust.</div>
                <div class="service-box" onclick="toggleServiceDescription('service3')">
                    <img src="campaign-icon.png" alt="End-to-End Campaign Management">
                    End-to-End Campaign Management
                </div>
                <div class="service-description" id="service3">We handle everything from strategy to execution, ensuring seamless campaign delivery and success.</div>
                <div class="service-box" onclick="toggleServiceDescription('service4')">
                    <img src="ads-icon.png" alt="Creative Ads">
                    Creative Ads
                </div>
                <div class="service-description" id="service4">Innovative and high-converting ad creatives that grab attention and drive sales.</div>
            </div>
        </div>
    </div>

    <div class="contact" id="contact">
        <h2>Contact Us</h2>
        <p>Email: <a href="mailto:infeniummedia@gmail.com">infeniummedia@gmail.com</a></p>
        <p>Instagram: <a href="https://instagram.com/infeniummedia" target="_blank">@infeniummedia</a></p>
    </div>

    <div class="footer">
        <p>© 2025 Infenium Media. All rights reserved.</p>
    </div>

    <div class="cta-icon" onclick="location.href='#contact'">📩</div>
</body>
</html>
