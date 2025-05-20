<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document </title>
        <style>
             header{
                display: flex;
                flex-wrap:wrap;
                justify-content: space-between;
                padding: 1rem;
                align-items: center;
                color:black;
                background-color: #f0f0f0;
            }
            .home {
                 display: flex;
                flex-wrap: wrap;
                color: #f77f00;
                 justify-content: space-between;
                background-color: beige;
                padding: 0.7rem 1.5rem;
                border-radius: 10px;
                border: 1px solid #ddd;
                margin: 0;
            }
            .pizza-images{
                display: flex;
                flex-wrap:wrap; 
                gap: 20px;
                justify-content: center;
            }
            .pizza-images img{
                width: 400px;
                height: 400px;
                object-fit: cover;
                border-radius:10px;
            }
            .pizza-images img:hover{
               transform: scale(1.05);
               filter: brightness(1.1);
            }
            .slider{
                position: relative;
                width: 400;
                height: 400;
                margin: 0 auto;
            }
            .slides{
                display: flex;
                 width: max-content;
                transition: transform 0.5s ease-in-out;
            }
            .prev, .next{
                position: absolute;
                top: 50%;
                padding: 10px;
                cursor:pointer;
                font-size: 18px;
                border-radius: 50%;
                border: none;
                padding: 10px;

            }
            .about-us{
                color: #f77f00;
                background-color: beige;
                padding: 0.7rem 1.5rem ;
                margin-top: 1rem;
                text-align: center;
                margin-left: auto;
                margin-right: auto;
                box-shadow: 0 2px 6px rgba(0,0,0,0.1); 
            }
            .menu{
                display: flex;
                align-items: center;
                background-color: #fff8dc;
                border: 1px solid #ddd;
                border-radius: 10px;
                box-shadow: 0 2px 8px rgba(0,0,0,0.1);
                padding: 1rem;
                margin: 1rem auto;
                max-width: auto;
                gap: 20px;
                transition: transform 0.3s ease, box-shadow 0.3s ease;
            }


            
            .menu-items{
                display: flex;
                width: 150px;
                height: 300px;
                background-color: #fff8dc;
                transition: transform 0.3s ease, box-shadow 0.3s ease;
                margin: 0;
                text-align: left;
               }
            .items-images {
                margin-left: 100px;
            }

            .items-images img{
                width: 200px;
                height: 200px;
                object-fit: cover;
                border-radius:10px;
                gap: 20px;
                transition: transform 0.3s ease, box-shadow 0.3s ease;
            }
            .menu-items img:hover {
                transform: scale(1.02);
                box-shadow: 0 4px 12px rgba(0,0,0,0.2);
            }
                        
            .ul-container{
                display: flex;
                color:black;
                font-size: 32px;
                padding: 0.7rem 1.5rem;
                justify-content:flex-end;
                border-radius: 5px;
                align-items: center;
                margin-top: 1rem;
                gap: 30px;
            }
            nav ul{
                display:flex ;
                gap: 16px;
                justify-content:flex-end;
                align-items: center;
            }
            nav ul li a{
                display:flex;
                color: black;
                font-weight: 200;
            }
            .profile-img{
                position: fixed;
                transition: transform 0.3s linear;
            }
            .profile-img.hover{
                transform: scale(1.1);
            }

            .profile-PizzaRush{
                font-weight: bold;
                color: black;
            }
            .toggle-mode{
                cursor: pointer;
                user-select: none;
                display: inline-block;      
            }
            .btn {
                display: inline-block;
                background: #f77f00;
                padding: 0.7rem 1.5rem;
                color: white;
                border-radius: 5px;
                margin-top: 1rem;
                text-decoration: none;
                font-weight: bold;
            }
            .items{
                font-size: 16px;
            }
           
            .order {
                display: block;
                background-color: whitesmoke;
                color: black;
                padding: 1rem;
                justify-content: space-between;
                align-items: center;
            }
            .footer {
                display: block;
                background-color: whitesmoke;
                color:#333;
                padding: 1rem;
                font-size: 32px;
                margin-top: 2rem;
                text-align: center;
            }
           
        </style>
    
</head>
<body>
    <header>
    <div class="ul-container"> 
         <img src="https://img.icons8.com/color/48/000000/pizza.png" alt="Pizza image" />
         <a href="#PizzaRush"> PizzaRush</a></div> 
     <nav>  
        <ul>
            <li><a href="#Home">Home</a></li>
            <li><a href="#About-Us">About Us</a></li>
            <li><a href="#Menu">Menu</a></li>
            <li><a href="#Contact / Order-Now">Contact / Order Now</a></li>
        </ul>
    </nav>

    <div class="toggle-mode"> day/night</div>
</header>

<section id="Home">
    <div class="home">
    <h1> Welcome to the PizzaRush</h1>
    <p> Hot | Crispy | Yummy</p>
    <div class="pizza-images">
        <div class="slider">
        <div class="slides">
        <img src="https://media.istockphoto.com/id/153784617/photo/supreme-pizza-slice-lift.jpg?s=612x612&w=0&k=20&c=Et5uDUJYv3sqDitb1jnUbnGrxhn015foBX_BS-1NFxs=">
        <img src="https://hips.hearstapps.com/hmg-prod/images/classic-cheese-pizza-recipe-2-64429a0cb408b.jpg?crop=0.6666666666666667xw:1xh;center,top&resize=1200:*">
        <img src="https://recipesblob.oetker.in/assets/d8a4b00c292a43adbb9f96798e028f01/1272x764/pizza-pollo-arrostojpg.webp">
    
    <button class="prev">&#10095;</button>
  <button class="next">&#10094;</button>
    </div>
    </div>
    </div>
</section>


<section id="About-us">
    <div class="about-us"
    </h1><u> About us</u></h1>
    <p><h4>Welcome to <strong>PizzaRush</strong> – your go-to destination for delicious, hot, and freshly baked pizzas delivered right to your doorstep! At PizzaRush, we blend the art of traditional Italian pizza-making with modern flavors to bring you an unforgettable taste experience.
    Whether you're craving a classic Margherita, a cheesy Pepperoni, or a loaded Veggie Delight, we've got something to satisfy every craving. 
    ingredients are handpicked for quality and freshness, and our dough is made fresh daily for that perfect crunch and chew.
    Fast delivery, easy online ordering, and unbeatable taste – that's the PizzaRush promise. Serving smiles one slice at a time! </h4>
    </p>
</div>
</section>


<section id="Menu">
  <h1>Our Pizza Menu</h1>
  <div class="menu">
  <div class="menu-items">
            <img src="https://media.istockphoto.com/id/1168754685/photo/pizza-margarita-with-cheese-top-view-isolated-on-white-background.jpg?s=612x612&w=0&k=20&c=psLRwd-hX9R-S_iYU-sihB4Jx2aUlUr26fkVrxGDfNg=" alt="Margherita Pizza" />   
            <div class="items-images">
                <h3>Margherita Pizza</h3>
                <p>Ingredients: Tomato sauce, mozzarella cheese, fresh basil</p>
                <span>Price: $10</span>
                <div class="quantity-selector">
                    <button onclick="decreaseQty(this)">-</button> 
                    <input type="text" placeholder="Amount in number">    
                    <button onclick="increaseQty(this)">+</button>   
                </div>
            </div>
    </div>
</div>

<div class="menu">
    <div class="menu-items">
        <img src="https://media.istockphoto.com/id/184928432/photo/pizza-from-the-top-pepperoni-cheese.jpg?s=612x612&w=0&k=20&c=wkC4yrZLcvHqg-9kQtRb1wan_z15eiO1Z297OFSuxpg=" alt="pepperoni Pizza" />
        <div class="items-images">
            <h3>Pepperoni Pizza</h3>
            <p>Ingredients: Tomato sauce, mozzarella cheese, pepperoni slices</p>
            <span>Price: $12</span>
            <div class="quantity-selector">
                <button onclick="decreaseQty(this)">-</button> 
                <input type="text" placeholder="Amount in number">    
                <button onclick="increaseQty(this)">+</button>   
            </div>
        </div>
    </div>
</div>  

<div class="menu">
    <div class="menu-items">
       <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcToOO__2dy9rRO5R-ET7EpfmkFAj8goLau1Pw&s" alt="Veggie Delight Pizza" />
       <div class="items-images">    
            <h3>Veggie Delight</h3>
            <p>Ingredients: Tomato sauce, mozzarella, bell peppers, onions, olives, mushrooms</p>
            <span>Price: $11</span>
            <div class="quantity-selector">
                <button onclick="decreaseQty(this)">-</button> 
                <input type="text" placeholder="Amount in number">    
                <button onclick="increaseQty(this)">+</button>   
            </div>
        </div>
    </div>
</div>

<div class="menu">
    <div class="menu-items">
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcS9Yul0xgVo7md_OA5SQuZEYXLTP2WG4oX18w&s" alt="Cheese Pizza" />
        <div class="items-images">
                <h3>Cheese Pizza</h3>
                <p>Ingredients: Tomato sauce, mozzarella, cheddar, parmesan, blue cheese</p>
                <span>Price: $14</span>
                <div class="quantity-selector">
                    <button onclick="decreaseQty(this)">-</button> 
                    <input type="text" placeholder="Amount in number">    
                    <button onclick="increaseQty(this)">+</button>   
            </div>
        </div>
    </div>
</div>

</section>

   </div>
   </div>
</section>

<section id="Contact / Order-Now" class="order">
    <p class="left"><img src="https://img.icons8.com/?size=100&id=86793&format=png&color=000000.png" width="20px" height="20px"> Order Now:<strong>+91 9876543210</strong></p>
    <p class="right"><img src="https://img.icons8.com/?size=100&id=rUgzXdXFnhmg&format=png&color=000000" width="20px" height="20px"> pizzarush@email.com</p>
</section>

<footer  class="footer">
    <p>&copy;2025 PizzaRush. All rights reserved.</p>
    <div class="Social">
        <a href="#">Facebook</a>
        <a href="#">Instagram</a>
        <a href="#">Twitter</a>
    </div>
</footer>

</body>
</html>
