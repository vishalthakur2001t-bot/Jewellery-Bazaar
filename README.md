<!DOCTYPE html>  <html lang="en">  
<head>  
    <meta charset="utf-8">  
    <meta name="viewport" content="width=device-width, initial-scale=1">  
    <title>The Jewellery Bazaar India</title>  
    <style>  
        :root {  
            --primary: #4b1f1f;  
            --accent: #b8860b;  
            --bg: #faf7f2;  
            --text: #2d2d2d;  
            --white: #ffffff;  
        }  
        body {  
            font-family: 'Segoe UI', Arial, sans-serif;  
            margin: 0;  
            background: var(--bg);  
            color: var(--text);  
            line-height: 1.6;  
        }  
        header {  
            background: var(--primary);  
            color: var(--white);  
            text-align: center;  
            padding: 40px 20px;  
            box-shadow: 0 4px 15px rgba(0,0,0,0.1);  
        }  
        .logo-placeholder {  
            font-size: 2.5rem;  
            font-weight: bold;  
            letter-spacing: 2px;  
            text-transform: uppercase;  
            margin-bottom: 5px;  
            color: var(--white);  
        }  
        header p {  
            font-style: italic;  
            margin: 5px 0 0;  
            opacity: 0.9;  
            font-size: 1.1rem;  
        }  
        .hero {  
            padding: 50px 20px;  
            text-align: center;  
            max-width: 800px;  
            margin: 0 auto;  
        }  
        .hero h2 {  
            font-size: 2.2rem;  
            color: var(--primary);  
            margin-bottom: 10px;  
        }  
        .hero p {  
            font-size: 1.2rem;  
            color: #666;  
            margin-bottom: 25px;  
        }  
        .btn-container {  
            display: flex;  
            justify-content: center;  
            gap: 15px;  
            flex-wrap: wrap;  
        }  
        .btn {  
            display: inline-flex;  
            align-items: center;  
            background: var(--accent);  
            color: var(--white);  
            padding: 14px 28px;  
            text-decoration: none;  
            border-radius: 30px;  
            font-weight: bold;  
            transition: all 0.3s ease;  
            box-shadow: 0 4px 6px rgba(0,0,0,0.1);  
        }  
        .btn:hover {  
            transform: translateY(-2px);  
            box-shadow: 0 6px 12px rgba(0,0,0,0.15);  
            background: #a3760a;  
        }  
        .btn-wa {  
            background: #25D366;  
        }  
        .btn-wa:hover {  
            background: #20ba5a;  
        }  
        .section-title {  
            text-align: center;  
            font-size: 2rem;  
            color: var(--primary);  
            margin: 40px 0 10px;  
            position: relative;  
        }  
        .section-title::after {  
            content: '';  
            display: block;  
            width: 50px;  
            height: 2px;  
            background: var(--accent);  
            margin: 8px auto 0;  
        }  
        .grid {  
            display: grid;  
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));  
            gap: 25px;  
            padding: 20px;  
            max-width: 1200px;  
            margin: 0 auto;  
        }  
        .card {  
            background: var(--white);  
            border-radius: 16px;  
            overflow: hidden;  
            box-shadow: 0 4px 15px rgba(0,0,0,0.05);  
            transition: transform 0.3s ease;  
            display: flex;  
            flex-direction: column;  
        }  
        .card:hover {  
            transform: translateY(-5px);  
        }  
        .card-img {  
            width: 100%;  
            height: 280px;  
            object-fit: cover;  
            background: #eee;  
        }  
        .card-content {  
            padding: 20px;  
            text-align: center;  
            flex-grow: 1;  
            display: flex;  
            flex-direction: column;  
            justify-content: space-between;  
        }  
        .card h3 {  
            margin: 0 0 10px 0;  
            color: var(--primary);  
            font-size: 1.3rem;  
        }  
        .card p {  
            margin: 0 0 15px 0;  
            color: #666;  
            font-size: 0.95rem;  
        }  
        .card .btn-sm {  
            padding: 8px 16px;  
            font-size: 0.9rem;  
            border-radius: 20px;  
            align-self: center;  
        }  
        .features {  
            background: #f0eae1;  
            padding: 40px 20px;  
            margin-top: 50px;  
        }  
        .features-grid {  
            display: grid;  
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));  
            gap: 20px;  
            max-width: 1000px;  
            margin: 0 auto;  
            text-align: center;  
        }  
        .feature-item h4 {  
            color: var(--primary);  
            margin: 10px 0 5px;  
            font-size: 1.2rem;  
        }  
        footer {  
            background: var(--primary);  
            color: var(--white);  
            text-align: center;  
            padding: 30px 20px;  
            font-size: 0.95rem;  
        }  
        footer a {  
            color: #f7d070;  
            text-decoration: none;  
        }  
    </style>  
</head>  
<body>  <header>  
    <div class="logo-placeholder">TJB</div>  
    <h1>The Jewellery Bazaar India</h1>  
    <p>Premium Artificial Jewellery Collection</p>  
</header>  <div class="hero">  
    <h2>Elegance in Every Detail</h2>  
    <p>Discover our curated collections of premium earrings, stunning necklaces, royal bridal sets, bangles, and statement rings designed for every special occasion.</p>  
    <div class="btn-container">  
        <a class="btn" href="https://www.instagram.com/thejewellery_bazaar_india?igsh=MWpkejY2bmtkMmdhdw==" target="_blank">Follow on Instagram</a>  
        <a class="btn btn-wa" href="https://wa.me/919711096978?text=Hello%20The%20Jewellery%20Bazaar,%20I'm%20interested%20in%20your%20collection!" target="_blank">Order on WhatsApp</a>  
    </div>  
</div>  <h2 class="section-title">Our Collections</h2>  <div class="grid">  
    <div class="card">  
        <img src="https://images.unsplash.com/photo-1599643478518-a784e5dc4c8f?auto=format&fit=crop&w=600&q=80" alt="Necklace Collection" class="card-img">  
        <div class="card-content">  
            <div>  
                <h3>Necklace Collection</h3>  
                <p>Elegant and timeless neckpieces crafted for unforgettable celebrations.</p>  
            </div>  
            <a class="btn btn-sm btn-wa" href="https://wa.me/919711096978?text=Hi,%20I%20want%20to%20see%20the%20Necklace%20Collection" target="_blank">Inquire via WhatsApp</a>  
        </div>  
    </div>  <div class="card">  
    <img src="https://images.unsplash.com/photo-1630019852942-f89202989a59?auto=format&fit=crop&w=600&q=80" alt="Premium Earrings" class="card-img">  
    <div class="card-content">  
        <div>  
            <h3>Trendy Earrings</h3>  
            <p>From statement jhumkas to modern studs, discover premium quality styles.</p>  
        </div>  
        <a class="btn btn-sm btn-wa" href="https://wa.me/919711096978?text=Hi,%20I%20want%20to%20see%20the%20Earrings%20Collection" target="_blank">Inquire via WhatsApp</a>  
    </div>  
</div>  

<div class="card">  
    <img src="https://images.unsplash.com/photo-1611591437281-460bfbe1220a?auto=format&fit=crop&w=600&q=80" alt="Bangles Collection" class="card-img">  
    <div class="card-content">  
        <div>  
            <h3>Traditional Bangles</h3>  
            <p>Intricate designs bridging the charm of heritage and contemporary trends.</p>  
        </div>  
        <a class="btn btn-sm btn-wa" href="https://wa.me/919711096978?text=Hi,%20I%20want%20to%20see%20the%20Bangles%20Collection" target="_blank">Inquire via WhatsApp</a>  
    </div>  
</div>  

<div class="card">  
    <img src="https://images.unsplash.com/photo-1602751584552-8ba73aad10e1?auto=format&fit=crop&w=600&q=80" alt="Bridal Jewellery Set" class="card-img">  
    <div class="card-content">  
        <div>  
            <h3>Bridal Jewellery Sets</h3>  
            <p>Make your wedding day grand with our majestic, heavy bridal sets.</p>  
        </div>  
        <a class="btn btn-sm btn-wa" href="https://wa.me/919711096978?text=Hi,%20I%20want%20to%20see%20the%20Bridal%20Jewellery%20Collection" target="_blank">Inquire via WhatsApp</a>  
    </div>  
</div>  

<div class="card">  
    <img src="https://images.unsplash.com/photo-1605100804763-247f67b3557e?auto=format&fit=crop&w=600&q=80" alt="Statement Rings" class="card-img">  
    <div class="card-content">  
        <div>  
            <h3>Statement Rings</h3>  
            <p>Beautiful, adjustable rings featuring high-grade stones and polished finishes.</p>  
        </div>  
        <a class="btn btn-sm btn-wa" href="https://wa.me/919711096978?text=Hi,%20I%20want%20to%20see%20the%20Rings%20Collection" target="_blank">Inquire via WhatsApp</a>  
    </div>  
</div>

</div>  <div class="features">  
    <div class="features-grid">  
        <div class="feature-item">  
            <h4>All India Shipping</h4>  
            <p style="margin:0; font-size: 0.9rem; color:#555;">Fast, safe, and secure delivery right to your doorstep.</p>  
        </div>  
        <div class="feature-item">  
            <h4>Premium Quality</h4>  
            <p style="margin:0; font-size: 0.9rem; color:#555;">Long-lasting shine with premium polish and stones.</p>  
        </div>  
        <div class="feature-item">  
            <h4>Easy Booking</h4>  
            <p style="margin:0; font-size: 0.9rem; color:#555;">Screenshot your favorite design and text us to buy!</p>  
        </div>  
    </div>  
</div>  <footer>  
    <p style="margin: 0 0 10px 0;"><strong>The Jewellery Bazaar India</strong></p>  
    <p style="margin: 5px 0;">Instagram: <a href="https://www.instagram.com/thejewellery_bazaar_india?igsh=MWpkejY2bmtkMmdhdw==" target="_blank">@thejewellery_bazaar_india</a></p>  
    <p style="margin: 5px 0;">WhatsApp Order Support: <a href="https://wa.me/919711096978" target="_blank">+91 9711096978</a></p>  
</footer>  </body>  
