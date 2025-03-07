<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mobile Apps Showcase</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #F5EEF5;
        }
        .container {
            display: grid;
            gap: 20px;
            padding: 20px;
        }
        .section {
            padding: 20px;
            border-radius: 8px;
        }
        .section-1 {
            background-color: #F5EEF5;
            text-align: center;
            font-size: 24px;
            font-weight: bold;
        }
        .grid {
            display: grid;
            grid-template-columns: repeat(2, 1fr);
            gap: 20px;
        }
        .box {
            background-color: white;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0px 4px 6px rgba(0, 0, 0, 0.1);
        }
        .section-2 { background-color: #FAF5F3; }
        .section-3 { background-color: #F2F9F8; }
        .section-4 { 
            background-color: #000000; 
            color: white;
            padding: 30px;
            text-align: center;
        }
        .footer-grid {
            display: grid;
            grid-template-columns: repeat(4, 1fr);
            gap: 10px;
            margin-top: 20px;
            text-align: left;
        }
        .footer-box {
            padding: 10px;
        }
        h2, h3 {
            margin: 0;
            color: #333;
        }
        .box p {
            color: gray;
            margin-top: 5px;
        }
    </style>
</head>
<body>

<div class="container">
    <div class="section section-1">
        <p>Mobile development</p>
        <h1>Grow your business with mobile apps</h1>
    </div>

    <div class="grid section section-2">
        <div class="box">
            <h3>Sleepiest</h3>
            <p>Helps millions fall asleep every night</p>
            <p>branding, design, mobile, product</p>
        </div>
        <div class="box">
            <img src="sleepiest.png" alt="Sleepiest App" width="100%">
        </div>
    </div>

    <div class="grid section section-3">
        <div class="box">
            <img src="ulesson.png" alt="ULesson App" width="100%">
        </div>
        <div class="box">
            <h3>uLesson</h3>
            <p>Online platform for distance learning</p>
            <p>web, mobile, product</p>
        </div>
    </div>

    <div class="grid section section-4">
        <div class="box">
            <h3>Genesis Vision</h3>
            <p>Private trust management and trading platform</p>
            <p>branding, design, experience, product</p>
        </div>
        <div class="box">
            <img src="genesis.png" alt="Genesis Vision App" width="100%">
        </div>
    </div>

    <div class="section-4">
        <h2>Have an idea? Tell us about it</h2>
        <div class="footer-grid">
            <div class="footer-box">
                <h4>Product</h4>
                <p>Features</p>
                <p>Security</p>
                <p>Enterprise</p>
                <p>Customer stories</p>
            </div>
            <div class="footer-box">
                <h4>Platform</h4>
                <p>Developer API</p>
                <p>Partners</p>
                <p>Atom</p>
                <p>Electron</p>
            </div>
            <div class="footer-box">
                <h4>Support</h4>
                <p>Help</p>
                <p>Community Forum</p>
                <p>Learning Lab</p>
                <p>Certifications</p>
            </div>
            <div class="footer-box">
                <h4>Company</h4>
                <p>About</p>
                <p>Blog</p>
                <p>Careers</p>
                <p>Press</p>
            </div>
        </div>
    </div>
</div>

</body>
</html>
