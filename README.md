<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>AK Graphic Studio</title>

    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: Arial, sans-serif;
        }

        /* Header */
        header {
            background: #111;
            color: white;
            display: flex;
            justify-content: space-between;
            padding: 10px 20px;
            align-items: left-down;
        }

        header .logo {
            font-size: 28px;
            font-weight: bold;
        }

        nav a {
            color: white;
            margin: 0 15px;
            text-decoration: none;
            font-weight: 600;
        }

        /* Hero Section */
        .hero {
            background: url("") no-repeat center/cover;
            color: rgb(235, 23, 23);
            text-align: center;
            padding: 150px 20px;
        }

        .hero h1 {
            font-size: 50px;
            margin-bottom: 10px;
        }

        .hero p {
            font-size: 20px;
            margin-bottom: 20px;
        }

        .btn {
            background: #ff5722;
            padding: 12px 25px;
            color: white;
            border-radius: 5px;
            text-decoration: none;
            font-size: 18px;
        }

        /* Products */
        .products, .services {
            padding: 60px 40px;
            text-align: center;
        }

        .product-container, .service-container {
            display: flex;
            justify-content: center;
            gap: 30px;
            margin-top: 40px;
            flex-wrap: wrap;
        }

        .product-card, .service-card {
            background: #f1f1f1;
            padding: 20px;
            width: 280px;
            border-radius: 10px;
            box-shadow: 0 2px 10px rgba(0,0,0,0.2);
        }

        .product-card img {
            width: 100%;
            border-radius: 10px;
        }

        .product-card button {
            margin-top: 10px;
            background: #111;
            color: white;
            padding: 10px;
            border: none;
            width: 100%;
            border-radius: 5px;
            cursor: pointer;
        }

        /* Footer */
        footer {
            background: #111;
            color: white;
            text-align: center;
            padding: 30px;
            margin-top: 40px;
        }
    </style>

</head>
<body>

    <!-- Header -->
    <header>
        <div class="logo">AK Graphic Studio</div>
        
        <nav>
            <a href="#contact">Contact</a>
            <a href="https://www.instagram.com/cinematic_ak_00/"><img src="https://img.icons8.com/ios7/1200/instagram-new--v1.jpg" width="20"  alt=""></a>
        </nav>
        
       
    </header>

    <!-- Hero Section -->
    <section class="hero">
        <img src="https://i.ibb.co/8Ld22SQd/Whats-App-Image-2025-12-15-at-09-22-01-a1271890.jpg" alt="Whats-App-Image-2025-12-15-at-09-22-01-a1271890"  width="300" height="300" />
        
       
    </section>

    <!-- Products Section -->
    <section id="products" class="products">
        <h2>Our Products</h2>

        <div class="product-container">

            

            <div class="product-card">
                <img src="https://i.ibb.co/4gd6y6z4/Whats-App-Image-2025-12-15-at-09-10-34-fbc8e08e.jpg" alt="Whats-App-Image-2025-12-15-at-09-10-34-fbc8e08e" border="0"></a>
                 <a href="RELL.html"><button>See Now</button></a>
                <h3>SOCIAL MEDIA VIDEO CREATOR</h3>
                
                
            </div>

            <div class="product-card">
                <img src="https://i.ibb.co/8Ld22SQd/Whats-App-Image-2025-12-15-at-09-22-01-a1271890.jpg" alt="Whats-App-Image-2025-12-15-at-09-22-01-a1271890" border="0" /></a>
                <h3>LAGNA PATRIKA</h3>
                <p> High Quality.</p>
                <a href="LAGNA PATRIKA.html"><button>See Now</button></a>
            </div>

            <div class="product-card">
                <img src="https://i.ibb.co/MkJ4mbm2/Whats-App-Image-2025-12-15-at-09-10-34-4fdc46ec.jpg" alt="Whats-App-Image-2025-12-15-at-09-10-34-4fdc46ec" border="0" /></a>
                <h3>CINEMATIC RELL</h3>
                <p> High Quality .</p>
                <a href="RELL.html"><button>See Now</button></a>
            </div>

            <div class="product-card">
               <img src="https://i.ibb.co/jCd1Pyj/Whats-App-Image-2025-12-15-at-09-22-00-c0cab982.jpg" alt="Whats-App-Image-2025-12-15-at-09-22-00-c0cab982" border="0"></a>
                <h3>Graphic</h3>
                <p> High Quality.</p>
                
            </div>


        </div>
    </section>

   

    <!-- Footer -->
    <footer id="contact">
        <h3>Contact Us</h3>
        <p>Email: adityakolpe4312@gmail.com  </p>
        <p>Phone: +919099917506</p>
        <p>© 2025 AK Graphic Studio. All Rights Reserved.</p>
    </footer>

</body>
</html>
