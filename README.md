<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0"/>
<title>AS Restaurant & Bakery</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:Arial, sans-serif;
}

body{
    background:#fff8f0;
    color:#222;
}

header{
    background:url('https://images.unsplash.com/photo-1504674900247-0877df9cc836?q=80&w=1400') center/cover;
    height:90vh;
    color:white;
    display:flex;
    align-items:center;
    justify-content:center;
    text-align:center;
}

header .content{
    background:rgba(0,0,0,0.6);
    padding:40px;
    border-radius:20px;
}

header h1{
    font-size:60px;
    margin-bottom:15px;
}

header p{
    font-size:22px;
    margin-bottom:20px;
}

.btn{
    display:inline-block;
    padding:12px 25px;
    background:#ff9800;
    color:white;
    text-decoration:none;
    border-radius:8px;
    font-weight:bold;
}

nav{
    background:#111;
    padding:15px;
    text-align:center;
    position:sticky;
    top:0;
}

nav a{
    color:white;
    margin:0 15px;
    text-decoration:none;
    font-weight:bold;
}

section{
    padding:60px 10%;
}

.section-title{
    text-align:center;
    margin-bottom:40px;
    font-size:40px;
    color:#ff6f00;
}

.menu-grid{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
    gap:25px;
}

.card{
    background:white;
    border-radius:15px;
    overflow:hidden;
    box-shadow:0 5px 15px rgba(0,0,0,0.1);
    transition:0.3s;
}

.card:hover{
    transform:translateY(-8px);
}

.card img{
    width:100%;
    height:220px;
    object-fit:cover;
}

.card-content{
    padding:20px;
}

.card-content h3{
    margin-bottom:10px;
    color:#ff6f00;
}

.special{
    background:#fff0d9;
    padding:20px;
    border-left:6px solid #ff9800;
    margin-bottom:20px;
    border-radius:10px;
}

.booking{
    background:#222;
    color:white;
    border-radius:20px;
    padding:40px;
}

.booking form{
    display:grid;
    gap:15px;
}

.booking input,
.booking textarea{
    padding:12px;
    border:none;
    border-radius:8px;
}

.booking button{
    padding:14px;
    border:none;
    background:#ff9800;
    color:white;
    font-size:18px;
    border-radius:8px;
    cursor:pointer;
}

.features{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
    gap:25px;
}

.feature-box{
    background:white;
    padding:30px;
    border-radius:15px;
    text-align:center;
    box-shadow:0 5px 12px rgba(0,0,0,0.1);
}

footer{
    background:#111;
    color:white;
    text-align:center;
    padding:20px;
    margin-top:40px;
}
</style>
</head>

<body>

<header>
    <div class="content">
        <h1>AS Restaurant & Bakery</h1>
        <p>Fast Foods • Desserts • Cold Coffee • Birthday Parties</p>
        <a href="#booking" class="btn">Book Now</a>
    </div>
</header>

<nav>
    <a href="#menu">Menu</a>
    <a href="#special">Special Dishes</a>
    <a href="#combo">Combos</a>
    <a href="#services">Services</a>
    <a href="#booking">Booking</a>
</nav>

<section id="menu">
    <h2 class="section-title">Fast Food Menu</h2>

    <div class="menu-grid">

        <div class="card">
            <img src="https://images.unsplash.com/photo-1568901346375-23c9450c58cd?q=80&w=1200">
            <div class="card-content">
                <h3>Cheese Burger</h3>
                <p>Loaded burger with cheese and crispy fries.</p>
            </div>
        </div>

        <div class="card">
            <img src="https://images.unsplash.com/photo-1513104890138-7c749659a591?q=80&w=1200">
            <div class="card-content">
                <h3>Italian Pizza</h3>
                <p>Hot cheesy pizza with fresh toppings.</p>
            </div>
        </div>

        <div class="card">
            <img src="https://images.unsplash.com/photo-1626082927389-6cd097cdc6ec?q=80&w=1200">
            <div class="card-content">
                <h3>French Fries</h3>
                <p>Crispy fries with spicy seasoning.</p>
            </div>
        </div>

        <div class="card">
            <img src="https://images.unsplash.com/photo-1571091718767-18b5b1457add?q=80&w=1200">
            <div class="card-content">
                <h3>Chicken Wrap</h3>
                <p>Soft wraps filled with spicy chicken.</p>
            </div>
        </div>

    </div>
</section>

<section id="special">
    <h2 class="section-title">Special Dishes</h2>

    <div class="special">
        <h3>Chef Special Pasta</h3>
        <p>Creamy white sauce pasta with garlic bread.</p>
    </div>

    <div class="special">
        <h3>Special Chocolate Lava Cake</h3>
        <p>Hot chocolate cake with ice cream.</p>
    </div>

    <div class="special">
        <h3>Royal Cold Coffee</h3>
        <p>Cold coffee topped with chocolate and cream.</p>
    </div>
</section>

<section id="combo">
    <h2 class="section-title">Special Combos</h2>

    <div class="menu-grid">

        <div class="card">
            <img src="https://images.unsplash.com/photo-1550317138-10000687a72b?q=80&w=1200">
            <div class="card-content">
                <h3>Family Combo</h3>
                <p>2 Pizza + Fries + Cold Drinks + Dessert</p>
            </div>
        </div>

        <div class="card">
            <img src="https://images.unsplash.com/photo-1528605248644-14dd04022da1?q=80&w=1200">
            <div class="card-content">
                <h3>Birthday Combo</h3>
                <p>Cake + Snacks + Cold Coffee + Decoration</p>
            </div>
        </div>

    </div>
</section>

<section>
    <h2 class="section-title">Desserts & Drinks</h2>

    <div class="menu-grid">

        <div class="card">
            <img src="https://images.unsplash.com/photo-1579954115545-a95591f28bfc?q=80&w=1200">
            <div class="card-content">
                <h3>Chocolate Shake</h3>
                <p>Rich chocolate milkshake with cream.</p>
            </div>
        </div>

        <div class="card">
            <img src="https://images.unsplash.com/photo-1513558161293-cdaf765ed2fd?q=80&w=1200">
            <div class="card-content">
                <h3>Cold Drinks</h3>
                <p>Pepsi, Coca Cola, Sprite and more.</p>
            </div>
        </div>

        <div class="card">
            <img src="https://images.unsplash.com/photo-1488477181946-6428a0291777?q=80&w=1200">
            <div class="card-content">
                <h3>Bakery Cakes</h3>
                <p>Fresh birthday and chocolate cakes.</p>
            </div>
        </div>

    </div>
</section>

<section id="services">
    <h2 class="section-title">Our Services</h2>

    <div class="features">

        <div class="feature-box">
            <h3>Private Dinner Table</h3>
            <p>Enjoy romantic and private dinner arrangements.</p>
        </div>

        <div class="feature-box">
            <h3>Birthday Booking</h3>
            <p>Birthday decoration and cake arrangements available.</p>
        </div>

        <div class="feature-box">
            <h3>Small Party Booking</h3>
            <p>We organize small parties and celebrations.</p>
        </div>

    </div>
</section>

<section id="booking">
    <h2 class="section-title">Book Your Table</h2>

    <div class="booking">

        <form>
            <input type="text" placeholder="Your Name" required>

            <input type="email" placeholder="Your Email" required>

            <input type="tel" placeholder="Phone Number" required>

            <input type="date" required>

            <textarea rows="5" placeholder="Party / Birthday Details"></textarea>

            <button type="submit">Confirm Booking</button>
        </form>

    </div>
</section>

<footer>
    <h3>AS Restaurant & Bakery</h3>
    <p>Fast Food | Bakery | Cold Coffee | Private Dinner</p>
    <p>© 2026 All Rights Reserved</p>
</footer>

</body>
</html>
