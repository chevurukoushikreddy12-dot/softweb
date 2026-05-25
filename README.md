# Ex.06 Restuarant Website
## Date:24-05-2026

## AIM:
To develop a static Resturant website to display the menu and services provided by the resturant.

## DESIGN STEPS:

### Step 1:
Requirement collection.

### Step 2:
Creating the layout using HTML and CSS.

### Step 3:
Updating the sample content.

### Step 4:
Choose the appropriate style and color scheme.

### Step 5:
Validate the layout in various browsers.

### Step 6:
Validate the HTML code.

### Step 7:
Publish the website in the given URL.

## PROGRAM:
## index.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Spice Garden Restaurant</title>

    <style>

        *{
            margin:0;
            padding:0;
            box-sizing:border-box;
            font-family:Arial, Helvetica, sans-serif;
        }

        body{
            background:#fff8f0;
            color:#333;
        }

        header{
            background:#8b0000;
            color:white;
            padding:20px;
            text-align:center;
        }

        nav{
            background:#ff914d;
            padding:15px;
            text-align:center;
        }

        nav a{
            color:white;
            text-decoration:none;
            margin:20px;
            font-size:18px;
            font-weight:bold;
        }

        nav a:hover{
            color:yellow;
        }

        .banner{
            width:100%;
            height:500px;
            background:url('banner.jpg');
            background-size:cover;
            background-position:center;
        }

        .welcome{
            text-align:center;
            padding:50px;
        }

        .welcome h2{
            color:#8b0000;
            margin-bottom:20px;
            font-size:40px;
        }

        .welcome p{
            font-size:20px;
            line-height:35px;
        }

        .special{
            display:flex;
            justify-content:center;
            gap:30px;
            padding:40px;
            flex-wrap:wrap;
        }

        .card{
            width:300px;
            background:white;
            border-radius:10px;
            overflow:hidden;
            box-shadow:0 0 10px gray;
            text-align:center;
        }

        .card img{
            width:100%;
            height:220px;
        }

        .card h3{
            padding:15px;
            color:#8b0000;
        }

        footer{
            background:#8b0000;
            color:white;
            text-align:center;
            padding:20px;
            margin-top:30px;
        }

    </style>
</head>

<body>

    <header>
        <h1>SPICE GARDEN RESTAURANT</h1>
        <p>Delicious Food | Great Ambience | Fresh Ingredients</p>
    </header>

    <nav>
        <a href="index.html">HOME</a>
        <a href="menu.html">MENU</a>
        <a href="administration.html">ADMINISTRATION</a>
        <a href="contact.html">CONTACT US</a>
    </nav>

    <div class="banner"></div>

    <section class="welcome">
        <h2>Welcome to Spice Garden</h2>

        <p>
            Spice Garden Restaurant offers a variety of delicious Indian,
            Chinese, and Continental dishes prepared with fresh ingredients.
            Enjoy a wonderful dining experience with your friends and family.
        </p>
    </section>

    <section class="special">

        <div class="card">
            <img src="c:\Users\acer\Downloads\vecteezy_indian-style-chicken-biryani-photo-served-on-a-restaurant-plate_66821320.jpg">
            <h3>Chicken Biryani</h3>
        </div>

        <div class="card">
            <img src="c:\Users\acer\Downloads\hyderabadi chicken dum biryani.jpeg">
            <h3>HYDERABADI CHICKEN DUM BIRYANI</h3>
        </div>

        <div class="card">
            <img src="c:\Users\acer\Downloads\tandoori chicken.jpeg">
            <h3>TANDOORI CHICKEN</h3>
        </div>

        <div class="card">
            <img src="c:\Users\acer\Downloads\andhra chilli chicken.jpeg">
            <h3>ANDHRA CHILLI CHICKEN</h3>
        </div>


    </section>

    <footer>
        KOUSHIK
    </footer>

</body>
</html>
```
## menu.html
```


<!DOCTYPE html>
<html>
<head>
    <title>Menu - Spice Garden</title>

    <style>

        body{
            font-family:Arial;
            background:#fff8f0;
            margin:0;
        }

        header{
            background:#8b0000;
            color:white;
            text-align:center;
            padding:20px;
        }

        nav{
            background:#ff914d;
            padding:15px;
            text-align:center;
        }

        nav a{
            color:white;
            text-decoration:none;
            margin:20px;
            font-size:18px;
            font-weight:bold;
        }

        .menu-container{
            display:grid;
            grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
            gap:25px;
            padding:40px;
        }

        .menu-item{
            background:white;
            border-radius:10px;
            overflow:hidden;
            box-shadow:0 0 10px gray;
            text-align:center;
        }

        .menu-item img{
            width:100%;
            height:220px;
        }

        .menu-item h3{
            color:#8b0000;
            padding:10px;
        }

        .menu-item p{
            padding-bottom:15px;
            font-size:18px;
            font-weight:bold;
        }

        footer{
            background:#8b0000;
            color:white;
            text-align:center;
            padding:20px;
        }

    </style>

</head>

<body>

<header>
    <h1>OUR MENU</h1>
</header>

<nav>
    <a href="index.html">HOME</a>
    <a href="menu.html">MENU</a>
    <a href="administration.html">ADMINISTRATION</a>
    <a href="contact.html">CONTACT US</a>
</nav>

<div class="menu-container">

    <div class="menu-item">
        <img src="c:\Users\acer\Downloads\vecteezy_indian-style-chicken-biryani-photo-served-on-a-restaurant-plate_66821320.jpg">
        <h3>Chicken Biryani</h3>
        <p>₹250</p>
    </div>

    <div class="menu-item">
        <img src="c:\Users\acer\Downloads\pbm.jpeg">
        <h3>Paneer Butter Masala</h3>
        <p>₹220</p>
    </div>

    <div class="menu-item">
        <img src="c:\Users\acer\Downloads\vfr.jpeg">
        <h3>Veg Fried Rice</h3>
        <p>₹180</p>
    </div>

    <div class="menu-item">
        <img src="c:\Users\acer\Downloads\pizza.jpeg">
        <h3>Pizza</h3>
        <p>₹300</p>
    </div>

    <div class="menu-item">
        <img src="c:\Users\acer\Downloads\burger.jpeg">
        <h3>Burger</h3>
        <p>₹150</p>
    </div>

    <div class="menu-item">
        <img src="c:\Users\acer\Downloads\ff.jpeg">
        <h3>French Fries</h3>
        <p>₹120</p>
    </div>

    <div class="menu-item">
        <img src="c:\Users\acer\Downloads\ic.jpeg">
        <h3>Ice Cream</h3>
        <p>₹90</p>
    </div>

    <div class="menu-item">
        <img src="c:\Users\acer\Downloads\c65.jpeg">
        <h3>Chicken 65</h3>
        <p>₹240</p>
    </div>

    <div class="menu-item">
        <img src="c:\Users\acer\Downloads\d.jpeg">
        <h3>Masala Dosa</h3>
        <p>₹100</p>
    </div>

    <div class="menu-item">
        <img src="c:\Users\acer\Downloads\pasta.jpeg">
        <h3>Pasta</h3>
        <p>₹210</p>
    </div>

    <div class="menu-item">
        <img src="c:\Users\acer\Downloads\sandwich.jpeg">
        <h3>Sandwich</h3>
        <p>₹130</p>
    </div>

    <div class="menu-item">
        <img src="c:\Users\acer\Downloads\momos.jpeg">
        <h3>Momos</h3>
        <p>₹160</p>
    </div>

</div>

<footer>
    KOUSHIK
</footer>

</body>
</html>
```
## administration.html
```

<!DOCTYPE html>
<html>
<head>
    <title>Administration</title>

    <style>

        body{
            margin:0;
            font-family:Arial;
            background:#fff8f0;
        }

        header{
            background:#8b0000;
            color:white;
            text-align:center;
            padding:20px;
        }

        nav{
            background:#ff914d;
            padding:15px;
            text-align:center;
        }

        nav a{
            color:white;
            text-decoration:none;
            margin:20px;
            font-size:18px;
            font-weight:bold;
        }

        .team{
            display:grid;
            grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
            gap:25px;
            padding:40px;
        }

        .member{
            background:white;
            border-radius:10px;
            overflow:hidden;
            text-align:center;
            box-shadow:0 0 10px gray;
        }

        .member img{
            width:100%;
            height:250px;
        }

        .member h3{
            color:#8b0000;
            margin-top:10px;
        }

        .member p{
            padding-bottom:15px;
            font-size:18px;
        }

        footer{
            background:#8b0000;
            color:white;
            text-align:center;
            padding:20px;
        }

    </style>

</head>

<body>

<header>
    <h1>ADMINISTRATION</h1>
</header>

<nav>
    <a href="index.html">HOME</a>
    <a href="menu.html">MENU</a>
    <a href="administration.html">ADMINISTRATION</a>
    <a href="contact.html">CONTACT US</a>
</nav>

<div class="team">

    <div class="member">
        <img src="c:\Users\acer\Downloads\RS.jpeg">
        <h3>ROHITH SHARMA</h3>
        <p>Manager</p>
    </div>

    <div class="member">
        <img src="c:\Users\acer\Downloads\VK.jpeg">
        <h3>VIRAT KOHLI</h3>
        <p>Head Chef</p>
    </div>

    <div class="member">
        <img src="c:\Users\acer\Downloads\KLR.jpeg">
        <h3>KL RAHUL</h3>
        <p>Assistant Chef</p>
    </div>

    <div class="member">
        <img src="c:\Users\acer\Downloads\AR.jpeg">
        <h3>ANASWARA RAJAN</h3>
        <p>Receptionist</p>
    </div>

    <div class="member">
        <img src="c:\Users\acer\Downloads\JB.jpeg">
        <h3>JOS BUTTLER</h3>
        <p>Food Supervisor</p>
    </div>

    <div class="member">
        <img src="c:\Users\acer\Downloads\PZ.jpeg">
        <h3>PREITY ZINTA</h3>
        <p>Service Manager</p>
    </div>

</div>

<footer>
    KOUSHIK
</footer>

</body>
</html>
```
## contact.html
```

!DOCTYPE html>
<html><
<head>
    <title>Contact Us</title>

    <style>

        body{
            margin:0;
            font-family:Arial;
            background:#fff8f0;
        }

        header{
            background:#8b0000;
            color:white;
            text-align:center;
            padding:20px;
        }

        nav{
            background:#ff914d;
            padding:15px;
            text-align:center;
        }

        nav a{
            color:white;
            text-decoration:none;
            margin:20px;
            font-size:18px;
            font-weight:bold;
        }

        .contact-box{
            width:70%;
            margin:auto;
            background:white;
            margin-top:50px;
            padding:40px;
            border-radius:10px;
            box-shadow:0 0 10px gray;
            line-height:40px;
            font-size:22px;
        }

        h2{
            color:#8b0000;
            margin-bottom:20px;
        }

        footer{
            background:#8b0000;
            color:white;
            text-align:center;
            padding:20px;
            margin-top:50px;
        }

    </style>

</head>

<body>

<header>
    <h1>CONTACT US</h1>
</header>

<nav>
    <a href="index.html">HOME</a>
    <a href="menu.html">MENU</a>
    <a href="administration.html">ADMINISTRATION</a>
    <a href="contact.html">CONTACT US</a>
</nav>

<div class="contact-box">

    <h2>Spice Garden Restaurant</h2>

    <p><b>Address:</b> Beach Road, Visakhapatnam, Andhra Pradesh</p>

    <p><b>Phone:</b> +91 6303033151</p>

    <p><b>Email:</b> spicegarden@gmail.com</p>

    <p><b>Working Hours:</b> 10 AM to 11 PM</p>

</div>

<footer>
    KOUSHIK
</footer>

</body>
</html>
```


## OUTPUT:
<img width="1303" height="961" alt="{319C3A81-8B7B-4A9E-A439-E1674F953E6D}" src="https://github.com/user-attachments/assets/52b185b0-29d6-4438-927c-b39771773bb8" />
<img width="1306" height="767" alt="{A369FC5B-11B3-4DB4-91C8-A54B0D136351}" src="https://github.com/user-attachments/assets/ee5aa283-354f-4009-8827-150de97c879d" />
<img width="1295" height="969" alt="{F5EC4195-54DA-47E3-9517-EB097ECAEE54}" src="https://github.com/user-attachments/assets/b936a786-b674-4533-9b16-2bf153d4e5bb" />
<img width="1289" height="1048" alt="{D17A3D4B-75FB-4539-AB73-D416B2160BA7}" src="https://github.com/user-attachments/assets/82ddba5e-4eb4-4134-96da-1a0d694a82ca" />





## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
