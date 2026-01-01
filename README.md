<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Toko Hamster - Jual Diamond Game & Top Up</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #ffffff; /* Putih */
            color: #001f3f; /* Biru laut */
        }
        header {
            background-color: #001f3f; /* Biru laut */
            color: #ffffff; /* Putih */
            padding: 20px;
            text-align: center;
        }
        header h1 {
            margin: 0;
            font-size: 2.5em;
        }
        header p {
            margin: 5px 0;
        }
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }
        .slide {
            display: none;
            background-color: #f0f8ff; /* Biru muda untuk kontras */
            border-radius: 10px;
            padding: 20px;
            margin: 20px 0;
            box-shadow: 0 4px 8px rgba(0,0,0,0.1);
            transition: all 0.3s ease;
        }
        .slide.active {
            display: block;
        }
        .slide img {
            max-width: 100px;
            height: auto;
            margin-bottom: 10px;
        }
        .slide h2 {
            color: #001f3f;
            border-bottom: 2px solid #001f3f;
            padding-bottom: 10px;
        }
        .product-list {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
        }
        .product {
            background-color: #ffffff;
            border: 1px solid #001f3f;
            border-radius: 8px;
            padding: 15px;
            width: calc(33% - 20px);
            box-sizing: border-box;
            text-align: center;
            transition: transform 0.2s;
        }
        .product:hover {
            transform: scale(1.05);
            box-shadow: 0 4px 12px rgba(0,0,0,0.2);
        }
        .product p {
            margin: 5px 0;
            font-weight: bold;
        }
        .nav-buttons {
            text-align: center;
            margin: 20px 0;
        }
        .nav-buttons button {
            background-color: #001f3f;
            color: #ffffff;
            border: none;
            padding: 10px 20px;
            margin: 0 10px;
            border-radius: 5px;
            cursor: pointer;
            font-size: 1em;
            transition: background-color 0.3s;
        }
        .nav-buttons button:hover {
            background-color: #003366;
        }
        footer {
            background-color: #001f3f;
            color: #ffffff;
            text-align: center;
            padding: 10px;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
        @media (max-width: 768px) {
            .product {
                width: calc(50% - 20px);
            }
        }
        @media (max-width: 480px) {
            .product {
                width: 100%;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>Toko Hamster</h1>
        <p>WA: 085933068430 | IG: @hamsterkiosgaming</p>
    </header>

    <div class="container">
        <div class="nav-buttons">
            <button onclick="showSlide(0)">Diamond Free Fire</button>
            <button onclick="showSlide(1)">Paket Gacor</button>
            <button onclick="showSlide(2)">Diamond Mobile Legend</button>
            <button onclick="showSlide(3)">Top Up OVO</button>
            <button onclick="showSlide(4)">Top Up DANA</button>
            <button onclick="showSlide(5)">Top Up GO PAY</button>
            <button onclick="showSlide(6)">Top Up SHOOPE PAY</button>
            <button onclick="showSlide(7)">Pulsa XL</button>
            <button onclick="showSlide(8)">Pulsa Indosat/IM3</button>
            <button onclick="showSlide(9)">Pulsa Telkomsel</button>
        </div>

        <!-- Slide 0: Diamond Free Fire -->
        <div class="slide active" id="slide0">
            <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/5/5a/Free_Fire_logo.svg/1200px-Free_Fire_logo.svg.png" alt="Free Fire Logo">
            <h2>LIST PEMBELIAN DIAMOND FREE FIRE</h2>
            <div class="product-list">
                <div class="product"><p>💎 5 DM = 1K</p></div>
                <div class="product"><p>💎 12 DM = 2K</p></div>
                <div class="product"><p>💎 20 DM = 4K</p></div>
                <div class="product"><p>💎 50 DM = 6K</p></div>
                <div class="product"><p>💎 70 DM = 8K</p></div>
                <div class="product"><p>💎 100 DM = 15K</p></div>
                <div class="product"><p>💎 140 DM = 18K</p></div>
                <div class="product"><p>💎 210 DM = 28K</p></div>
                <div class="product"><p>💎 355 DM = 48K</p></div>
                <div class="product"><p>💎 510 DM = 78K</p></div>
                <div class="product"><p>💎 720 DM = 95K</p></div>
                <div class="product"><p>💎 1450 DM = 180K</p></div>
                <div class="product"><p>💎 2180 DM = 270K</p></div>
                <div class="product"><p>💎 3640 DM = 475K</p></div>
            </
