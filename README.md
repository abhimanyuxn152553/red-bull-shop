<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Red Bull </title>
    <style>
        /* General styles */
        body {
            font-family: Arial, sans-serif;
            background-color: #f0f0f0;
            margin: 0;
            padding: 0;
            color: #333;
        }
        .container {
            width: 100%;
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }
        /* Header styles */
        header {
            background-color: #D70010;
            color: white;
            padding: 10px 0;
            text-align: center;
            font-size: 1.5rem;
            font-weight: bold;
            display: flex;
            justify-content: space-between;
            align-items: center;
            position: relative;
        }
        header .login-btn {
            background-color: #fff;
            color: #D70010;
            border: 2px solid #D70010;
            padding: 8px 20px;
            border-radius: 4px;
            text-decoration: none;
            transition: background-color 0.3s ease, color 0.3s ease;
        }
        header .login-btn:hover {
            background-color: #D70010;
            color: white;
        }
        /* Main content styles */
        .main-content {
            display: flex;
            justify-content: space-between;
            flex-wrap: wrap;
        }
        .article {
            flex: 1 1 calc(33% - 20px);
            background-color: #fff;
            padding: 20px;
            margin-bottom: 20px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
            border-radius: 5px;
        }
        .article h2 {
            color: #D70010;
            font-size: 1.2rem;
            margin-bottom: 10px;
        }
        .article p {
            color: #555;
            line-height: 1.6;
        }
        /* Product styles */
        .products {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-between;
        }
        .product {
            flex: 1 1 calc(33% - 20px);
            background-color: #fff;
            padding: 20px;
            margin-bottom: 20px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
            border-radius: 5px;
            text-align: center;
        }
        .product img {
            max-width: 100%;
            border-radius: 5px;
            margin-bottom: 10px;
        }
        .product h3 {
            color: #D70010;
            font-size: 1.2rem;
            margin-bottom: 10px;
        }
        .product p {
            color: #555;
            line-height: 1.6;
        }
        .product a {
            display: inline-block;
            background-color: #D70010;
            color: white;
            text-decoration: none;
            padding: 8px 20px;
            border-radius: 4px;
            transition: background-color 0.3s ease;
        }
        .product a:hover {
            background-color: #A30000;
        }
        /* Footer styles */
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px 0;
            position: absolute;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>

<header>
    <div>
     Red Bull
    </div>
    <div>
        <!--login and registration button-->
        <a href="C:\Users\abhim\OneDrive\Pictures\Desktop\html\login.html" class="login-btn">Login</a>
    </div>
</header>

<div class="container main-content">
    <div class="article">
        <h2>Extreme Sports</h2>
        <p>Explore the adrenaline-pumping world of extreme sports with Red Bull. From skydiving to mountain biking, find out how athletes push their limits.</p>
    </div>
    <div class="article">
        <h2>Events</h2>
        <p>Discover the latest Red Bull events happening worldwide. Get tickets, watch live streams, and be part of the action.</p>
    </div>
    <div class="article">
        <h2>
            <!--REVEIWS-->
        <a href="C:\Users\abhim\OneDrive\Pictures\Desktop\html\reveiws.html"class="Reveiw-btn">Reveiw</a>
        </h2>
        <p> click to veiw reveiws by customers </p>
    </div>
</div>

<div class="container products">
    <div class="product">
        <!--prodects  page -->
        <img src="https://imgs.search.brave.com/dAnk6RK7EeWSLHvTWlg7Ica9W0wJu2dDZV_EaMEOjZU/rs:fit:500:0:0:0/g:ce/aHR0cHM6Ly9tZWRp/YS5nZXR0eWltYWdl/cy5jb20vaWQvNDU4/NzE2ODI5L3Bob3Rv/L3JlZC1idWxsLmpw/Zz9zPTYxMng2MTIm/dz0wJms9MjAmYz0w/Q3NCVnNYZHJBN1BW/MWdrVUY0VkhCa1BH/aDRWdHlxOXVOSkFN/VFFPYkJBPQ" alt="Product 1">
        <h3>Red Bull Energy Drink</h3>
        <p>The original Red Bull energy drink.</p>
        <a href="C:\Users\abhim\OneDrive\Pictures\Desktop\html\product.html">View Product</a>
    </div>
    <div class="product">
        <img src="https://imgs.search.brave.com/jeTH_nGfpXf7NlljLp4CxKRpyrcq7VaiuUGFzwXVwZQ/rs:fit:500:0:0:0/g:ce/aHR0cHM6Ly9hc3Nl/dHMucmVkYnVsbHNo/b3AuY29tL2ltYWdl/cy9mX2F1dG8scV9h/dXRvL3RfcHJvZHVj/dC1saXN0LTNieTQv/cHJvZHVjdHMvUkJS/LzIwMjQvUkJSMjQw/NzJfMUNfMS9OZXct/RXJhLTlGb3J0eS1Z/b3V0aC1WZXJzdGFw/cGVuLUNhcC5qcGc" alt="Product 2">
        <h3>Red Bull Racing Cap</h3>
        <p>Official Red Bull Racing merchandise.</p>
        <a href="#">View Product</a>
    </div>
    <div class="product">
        <img src="https://imgs.search.brave.com/FnWHWKW5MGA-OJetMFCaT7kvMQre81FTFouB_9550Rk/rs:fit:500:0:0:0/g:ce/aHR0cHM6Ly9mYW5z/YnJhbmRzLmNvbS9j/ZG4vc2hvcC9maWxl/cy83MDEyMjQxMDUw/MDEyMjBYRkIuanBn/P3Y9MTcxMjU2NDAy/NCZ3aWR0aD00NjA" alt="Product 3">
        <h3>Red Bull Athlete T-Shirt</h3>
        <p>Celebrate Red Bull athletes with this exclusive t-shirt.</p>
        <a href="#">View Product</a>
    </div>
</div>


</body>
</html>

