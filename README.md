
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Infenium Media | Authentic Growth for Brands & Influencers</title>
    <style>
        body {
            font-family: 'Poppins', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #111;
            color: #fff;
            text-align: center;
        }
        .container {
            width: 80%;
            margin: auto;
            padding: 50px 0;
        }
        .hero {
            padding: 100px 20px;
            background: linear-gradient(135deg, #1a1a1a, #222);
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
            background-color: #ff4500;
            color: #fff;
            text-decoration: none;
            font-weight: bold;
            border-radius: 8px;
            transition: background 0.3s;
        }
        .btn:hover {
            background-color: #e03d00;
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
            background: #222;
            padding: 20px;
            border-radius: 10px;
            width: 300px;
            text-align: center;
            transition: transform 0.3s;
            cursor: pointer;
        }
        .service-box:hover {
            transform: translateY(-5px);
        }
        .service-description {
            display: none;
            background: #1a1a1a;
            padding: 20px;
            margin-top: 10px;
            border-radius: 10px;
        }
        .footer {
            padding: 20px;
            background-color: #222;
            opacity: 0.8;
        }
        .contact {
            padding: 40px 20px;
            background-color: #1a1a1a;
        }
        .contact a {
            color: #ff4500;
            text-decoration: none;
            font-weight: bold;
        }
        .cta-icon {
            position: fixed;
            bottom: 20px;
            right: 20px;
            background: #ff4500;
            color: white;
            padding: 15px;
            border-radius: 50%;
            cursor: pointer;
            font-size: 24px;
            text-align: center;
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
        <h1>Infenium Media</h1>
        <p>Bridging brands & influencers for authentic collaborations.</p>
        <a href="#contact" class="btn">Let's Work Together</a>
    </div>

    <div class="container">
        <div class="section">
            <h2>About Us</h2>
            <p>An extension to your marketing team—Infenium Media seamlessly integrates with your brand to drive authentic collaborations and impactful campaigns.</p>
        </div>

        <div class="section">
            <h2>Our Services</h2>
            <div class="services">
                <div class="service-box" onclick="toggleServiceDescription('service1')">Influencer Marketing</div>
                <div class="service-description" id="service1">[Brief description here]</div>
                <div class="service-box" onclick="toggleServiceDescription('service2')">UGC Creators</div>
                <div class="service-description" id="service2">[Brief description here]</div>
                <div class="service-box" onclick="toggleServiceDescription('service3')">End-to-End Campaign Management</div>
                <div class="service-description" id="service3">[Brief description here]</div>
                <div class="service-box" onclick="toggleServiceDescription('service4')">Creative Ads</div>
                <div class="service-description" id="service4">[Brief description here]</div>
                <div class="service-box" onclick="toggleServiceDescription('service5')">Performance Marketing</div>
                <div class="service-description" id="service5">[Brief description here]</div>
                <div class="service-box" onclick="toggleServiceDescription('service6')">Brand Partnerships & Sponsorships</div>
                <div class="service-description" id="service6">[Brief description here]</div>
                <div class="service-box" onclick="toggleServiceDescription('service7')">Social Media Growth & Consulting</div>
                <div class="service-description" id="service7">[Brief description here]</div>
            </div>
        </div>

        <div class="section">
            <h2>Why Choose Us?</h2>
            <p>Proven results, innovative strategies, and a commitment to real growth.</p>
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
