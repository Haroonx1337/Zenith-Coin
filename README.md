<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Zenith Coin (ZNC) - The Future of Digital Wealth</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;700&display=swap');

        body {
            font-family: 'Poppins', sans-serif;
            background: #0a0f24;
            color: #fff;
            text-align: center;
            margin: 0;
            overflow-x: hidden;
            animation: fadeIn 1.5s ease-in-out;
        }

        @keyframes fadeIn {
            0% { opacity: 0; }
            100% { opacity: 1; }
        }

        /* 3D Background Animation */
        body::before {
            content: "";
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: radial-gradient(circle, #1a237e, #0a0f24);
            animation: backgroundMove 10s infinite alternate;
            z-index: -1;
        }

        @keyframes backgroundMove {
            0% { background-position: left; }
            100% { background-position: right; }
        }

        /* 3D Floating Hero Section */
        .hero {
            margin-top: 120px;
            padding: 50px;
            background: linear-gradient(135deg, #283593, #1e88e5);
            border-radius: 15px;
            box-shadow: 0 10px 50px rgba(33, 150, 243, 0.9);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
            max-width: 80%;
            margin: auto;
            animation: floatEffect 3s infinite alternate;
        }
        .hero:hover {
            transform: translateY(-10px) scale(1.05);
            box-shadow: 0 15px 60px rgba(33, 150, 243, 1);
        }

        @keyframes floatEffect {
            0% { transform: translateY(0px); }
            100% { transform: translateY(-10px); }
        }

        /* Animated Join Button */
        .btn {
            background: linear-gradient(90deg, #ffcc00, #ff6600);
            color: #000;
            padding: 14px 30px;
            text-decoration: none;
            border-radius: 50px;
            font-size: 22px;
            font-weight: bold;
            display: inline-block;
            transition: transform 0.3s ease, box-shadow 0.3s ease;
            cursor: pointer;
            animation: pulse 1.5s infinite alternate;
        }
        .btn:hover {
            background: linear-gradient(90deg, #ff6600, #ff3300);
            transform: scale(1.1);
            box-shadow: 0 8px 30px rgba(255, 153, 0, 1);
        }

        @keyframes pulse {
            0% { box-shadow: 0 0 10px #ffcc00; }
            100% { box-shadow: 0 0 30px #ff3300; }
        }

        /* X (Twitter) Icon */
        .social a {
            display: inline-block;
            font-size: 24px;
            color: #ffffff;
            text-decoration: none;
            background: linear-gradient(135deg, #000000, #444444);
            padding: 15px 25px;
            border-radius: 50px;
            box-shadow: 0 5px 15px rgba(255, 255, 255, 0.5);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }
        .social a:hover {
            transform: scale(1.2);
            box-shadow: 0 10px 30px rgba(255, 255, 255, 1);
        }
    </style>
</head>
<body>

    <!-- Navigation Bar -->
    

    <!-- Hero Section -->
    <h1>Welcome to <span style="color:#ffcc00;">Zenith Coin (ZNC)</span></h1>
    <p class="animated-text">The Future of Digital Wealth</p>
    <div class="hero">
        <p style="font-size: 22px;">Zenith Coin is designed for peak financial performance, symbolizing innovation, growth, and limitless possibilities in the cryptocurrency world.</p>
        <a href="#" class="btn" onclick="showContract()">Join the Revolution</a>
    </div>

    <!-- Additional Scrollable Section -->
    <div class="extra-section">
        <h2>Why Choose Zenith Coin?</h2>
        <p>Secure, fast, and built for the future. Join a community driving financial innovation forward.</p>
    </div>

    <!-- Social Media Links -->
    <div class="social">
        <p>Follow us on <a href="https://twitter.com/ZenithCoin" target="_blank"><i class="fab fa-x-twitter"></i> X</a></p>
    </div>

    <!-- Footer -->
    <footer>
        &copy; 2025 Zenith Coin. All Rights Reserved.
    </footer>

    <!-- Show Contract Address Script -->
    <script>
        function showContract() {
            alert("Zenith Coin Contract Address: [INSERT ADDRESS HERE]");
        }
    </script>

</body>
</html>
