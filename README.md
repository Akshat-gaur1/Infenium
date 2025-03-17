
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Infenium Media | Elevate Your Brand</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@300;600;800&family=Playfair+Display:wght@400;700&display=swap');
        
        body {
            font-family: 'Montserrat', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f1ec;
            color: #333;
            text-align: center;
            overflow-x: hidden;
        }
        .container {
            width: 90%;
            max-width: 1200px;
            margin: auto;
            padding: 50px 0;
        }
        .hero {
            padding: 150px 20px;
            background: linear-gradient(135deg, #252422, #403d39, #ff8303);
            color: #f4f1ec;
            font-weight: bold;
            position: relative;
            overflow: hidden;
        }
        .hero h1 {
            font-size: 4.5rem;
            font-family: 'Playfair Display', serif;
            text-transform: uppercase;
            margin: 0;
            animation: fadeIn 2s ease-in-out;
        }
        .hero p {
            font-size: 1.6rem;
            margin: 20px 0;
            animation: fadeIn 2.5s ease-in-out;
        }
        .btn {
            display: inline-block;
            margin-top: 30px;
            padding: 16px 32px;
            background-color: #ff8303;
            color: #fff;
            text-decoration: none;
            font-weight: bold;
            border-radius: 8px;
            transition: all 0.3s;
            animation: fadeIn 3s ease-in-out;
        }
        .btn:hover {
            background-color: #e67e22;
            transform: translateY(-5px);
        }
        .section {
            padding: 80px 20px;
            border-bottom: 2px dashed #403d39;
        }
        .section h2 {
            font-size: 2.5rem;
            margin-bottom: 40px;
            font-family: 'Playfair Display', serif;
            color: #403d39;
        }
        .services {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 30px;
        }
        .service-box {
            background: #fff;
            padding: 30px;
            border-radius: 15px;
            width: 280px;
            text-align: center;
            cursor: pointer;
            box-shadow: 6px 6px 0px #403d39;
            border: 2px solid #403d39;
            transition: all 0.3s;
        }
        .service-box:hover {
            transform: scale(1.05);
            background: #ffe8d6;
            box-shadow: 10px 10px 0px #403d39;
        }
        .service-box i {
            font-size: 2.5rem;
            color: #ff8303;
            margin-bottom: 20px;
            animation: float 3s ease-in-out infinite;
        }
        .service-desc {
            display: none;
            font-size: 0.9rem;
            margin-top: 10px;
            color: #666;
        }
        .newsletter {
            background: #ffe8d6;
            padding: 40px 20px;
            border-radius: 15px;
        }
        .newsletter input {
            padding: 10px;
            width: 300px;
            border: 2px solid #403d39;
            border-radius: 8px;
            margin-right: 10px;
        }
        .newsletter .btn {
            padding: 10px 20px;
        }
        .footer {
            padding: 20px;
            background-color: #252422;
            color: white;
        }
        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(20px); }
            to { opacity: 1; transform: translateY(0); }
        }
        @keyframes float {
            0%, 100% { transform: translateY(0); }
            50% { transform: translateY(-10px); }
        }
    </style>
    <script>
        function toggleDescription(id) {
            var desc = document.getElementById(id);
            desc.style.display = desc.style.display === "none" || desc.style.display === "" ? "block" : "none";
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
            <p>In a world where attention is the new currency, we make sure you’re always in demand. We create connections that matter, helping brands and influencers cut through the noise and make a lasting impact.</p>
        </div>

        <div class="section">
            <h2>Our Services</h2>
            <div class="services">
                <div class="service-box" onclick="toggleDescription('service1')">
                    <i class="fas fa-users"></i>
                    <h3>Influencer Marketing</h3>
                    <p id="service1" class="service-desc">We have a network of 200+ nano and micro influencers, carefully selected to authentically showcase your brand's story and connect with your target audience.</p>
                </div>
                <div class="service-box" onclick="toggleDescription('service2')">
                    <i class="fas fa-video"></i>
                    <h3>UGC Creators</h3>
                    <p id="service2" class="service-desc">Our professional UGC creators specialize in crafting high-quality, engaging content tailored to your brand's voice, ensuring maximum impact and authenticity.</p>
                </div>
                <div class="service-box" onclick="toggleDescription('service3')">
                    <i class="fas fa-tasks"></i>
                    <h3>End-to-End Campaign Management</h3>
                    <p id="service3" class="service-desc">From strategy to execution, we handle every aspect of your campaign, ensuring seamless delivery, measurable results, and a stress-free experience for you.</p>
                </div>
                <div class="service-box" onclick="toggleDescription('service4')">
                    <i class="fas fa-ad"></i>
                    <h3>Creative Ads & More</h3>
                    <p id="service4" class="service-desc">We create ads that hook your audience, combining compelling visuals, storytelling, and data-driven strategies to drive engagement and conversions.</p>
                </div>
            </div>
        </div>

        <div class="section newsletter">
            <h2>Subscribe to Our Newsletter</h2>
            <p>Get the latest updates on influencer marketing trends, collaborations, and more.</p>
            <input type="email" placeholder="Enter your email">
            <a href="#" class="btn">Subscribe</a>
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
