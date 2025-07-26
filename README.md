# cake-delight

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Live Bakery - Cafe Delight</title>
    <style>
    body {
        margin: 0;
        font-family: 'Segoe UI', sans-serif;
        background-image: url('https://images.unsplash.com/photo-1600891964599-f61ba0e24092?auto=format&fit=crop&w=1950&q=80');
        background-size: cover;
        background-position: center;
        background-repeat: no-repeat;
        background-attachment: fixed;
        position: relative;
    }

    body::before {
        content: '';
        position: fixed;
        top: 0;
        left: 0;
        right: 0;
        bottom: 0;
        background-color: rgba(255, 255, 255, 0.65); 
        z-index: 0;
    }

    .menu {
        display: flex;
        align-items: center;
        justify-content: space-between;
        background-color: rgba(109, 76, 65, 0.9);
        padding: 10px 30px;
        position: relative;
        z-index: 1;
    }

    .menu h1 {
        color: white;
        font-size: 28px;
        margin: 0;
    }

    .menu ul {
        list-style: none;
        display: flex;
        margin: 0;
        padding: 0;
    }

    .menu ul li {
        margin-left: 20px;
        color: white;
        font-size: 18px;
        cursor: pointer;
        transition: color 0.3s ease;
    }

    .menu ul li:hover {
        color: #ffc107;
    }

    .content {
        display: flex;
        justify-content: center;
        align-items: center;
        padding: 40px;
        gap: 30px;
        background-color: rgba(255, 255, 255, 0.9);
        margin: 30px;
        border-radius: 10px;
        position: relative;
        z-index: 1;
    }

    .text {
        max-width: 500px;
    }

    .text h2 {
        color: #6d4c41;
        font-size: 32px;
        margin-bottom: 15px;
    }

    .text p {
        font-size: 18px;
        line-height: 1.6;
        color: #333;
    }

    .btn {
        background-color: #6d4c41;
        color: white;
        border: none;
        padding: 10px 20px;
        font-size: 16px;
        margin-top: 20px;
        cursor: pointer;
        border-radius: 5px;
        transition: 0.3s ease;
    }

    .btn:hover {
        background-color: #ffc107;
        color: #6d4c41;
    }

    img {
        width: 500px;
        height: 350px;
        border-radius: 10px;
        box-shadow: 0px 4px 10px rgba(0,0,0,0.1);
    }

    @media screen and (max-width: 768px) {
        .content {
            flex-direction: column;
            text-align: center;
        }
        img {
            width: 70%;
        }
    }
    </style>
</head>
<body>

    <!-- Menu Bar -->
    <div class="menu">
        <h1>Cafe Delight</h1>
        <ul>
            <li>Home</li>
            <li>About</li>
            <li>Menu</li>
            <li>Contact</li>
        </ul>
    </div>

    <!-- Main Content -->
    <div class="content">
        <div class="text">
            <h2>Welcome to Cafe Delight</h2>
            <p>
                A bakery is an establishment that produces and sells flour-based baked goods such as bread, cookies, cakes, doughnuts, bagels, pastries, and pies. Some bakeries also serve coffee and tea, allowing you to enjoy your treats in a cozy setting.
            </p>
            <button class="btn">Contact Us</button>
        </div>
        <img src="https://images.edrawmax.com/article2023/coffee-shop-org-chart/organizational-structure-of-coffee-shop.jpg" alt="Delicious Cake">
    </div>

</body>
</html>


