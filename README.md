# Ex.07 Restaurant Website
# Date:
# AIM:
To develop a static Restaurant website to display the food items and services provided by them.

# DESIGN STEPS:
## Step 1:
Requirement collection.

## Step 2:
Creating the layout using HTML and CSS.

## Step 3:
Updating the sample content.

## Step 4:
Choose the appropriate style and color scheme.

## Step 5:
Validate the layout in various browsers.

## Step 6:
Validate the HTML code.

## Step 7:
Publish the website in the given URL.

# PROGRAM:
admin.html
```<html>
    <head>
        <title>
            admin
        </title>
        <style>
            body {
                background-image: url("homepage.jpg");
                background-position: center;
                background-repeat: no-repeat;
                background-size: contain;
                background-size: cover;
            }
            body h1 {
                color: blanchedalmond;
                font-size: 45;
                padding-left: 60;
                padding-top: 100;
                font-weight: bolder;
            }
            .nav {
                margin-top: 20px;
                text-align: right;
                background-color: rgba(243, 220, 195, 0.8) ;

            }
            .nav a {
                color: white;
                text-decoration: none;
                margin-right: 20px;
                font-family: 'Lora', serif;
                letter-spacing: 2px;
            }

            .nav a:hover {
                text-decoration: underline;
            }
            .team {
                display: flex;
                justify-content: center;
                align-items: flex-start;
                gap: 30px;

                max-width: 1200px;
                margin: 80px auto;

                flex-wrap: wrap;   
            }

            .role {
                background: #fbf7da;
                width: 230px;
                padding: 25px 15px;
                border-radius: 12px;
                text-align: center;
            }

            .role img {
                width: 160px;
                height: 160px;
                border-radius: 50%;
                object-fit: cover;
            }
            .role h3 {
                margin-top: 15px;
            }

            .role span {
                font-size: 14px;
                color: #333;
            }

            footer
            {
                text-align: center;
                background-color: rgba(243, 220, 195, 0.8) ;
            }

            

        </style>

    </head>
    <body>
        <h1>ADMINSTRATION TEAM</h1>
        <div class="nav">
            <a href="menu.html"  >MENU</a>
            <a href="admin.html" >ADMIN </a>
            <a href="contact.html" >CONTACT</a>


        </div>
        <hr>
        <div class="team">

            <div class="role">
                <img src="aj.jpeg">
                <h3>Arunjuthan</h3>
                <span>Founder & CEO</span>
            </div>

            <div class="role">
                <img src="chef.jpg">
                <h3>Sai Abhyankar</h3>
                <span>Executive Chef</span>
            </div>

            <div class="role">
                <img src="v.jpg">
                <h3>Vijay</h3>
                <span>Restaurant Manager</span>
            </div>

            <div class="role">
                <img src="elon.jpg">
                <h3>Elon Musk</h3>
                <span>Marketing Head</span>
            </div>

            <div class="role">
                <img src="pr.jpg">
                <h3>Pradeep Raganathan</h3>
                <span>HR & Staff Manager</span>
            </div>

            <div class="role">
                <img src="mam.jpg">
                <h3>Mamitha Baiju</h3>
                <span>Customer Service Manager</span>
            </div>

            
            </div>
        </div>
        <hr>
        <footer>
            <p>&copy; Arunjuthan.M.A (25016022) </p>
        </footer>

    </body>
</html>```
contact.html
```
<html>
    <head>
        <title>
            contact
        </title>
        <style>
            body{
                background-image: url("z.jpeg");
                background-position: center;
                background-repeat: no-repeat;
                background-size: contain;
                background-size: cover;
            }
            .nav {
                margin-top: 20px;
                text-align: right;

            }
            .nav a {
                color: white;
                text-decoration: none;
                margin-right: 20px;
                font-family: 'Lora', serif;
                letter-spacing: 2px;
                font-weight: bolder;
            }

            .nav a:hover {
                text-decoration: underline;
            }
            body h1{
                font-size: 50;
                color: aliceblue;
                padding-top: 100;
                padding-left: 60;
            }
            .he {
                font-size: 30;
                color:aliceblue;
                line-height: 1;
                padding-left: 60;
                
            }
            .sub {
                font-size: 20;
                padding-left: 80;
                color: aliceblue;
                line-height: 1;
                margin: 0;
                font-weight: bolder;
                
            }
            footer
            {
                text-align: center;
                background-color: rgba(243, 220, 195, 0.8) ;
                margin-top: 190;
            }

        </style>
    </head>
    <body>
        <h1> CONTACT US</h1>
        <div class="nav">
            <a href="rest.html" >HOME</a>

            <a href="menu.html"  >MENU</a>
            <a href="admin.html" >ADMIN </a>
            

        </div>
        <hr>
        <div class="he">
            <h3>Visit Us At:</h3>
        </div>
        
        <p class="sub">'Rue Gourmet</p>
        <p class="sub">Level 1, The Grand Arcade
        <p class="sub">Heritage Main Road, Opp. City Central Mall</p>
        <p class="sub">Mysuru  570001</p>
        <p class="sub">Karnataka, India'</p>
        
        <br>
        <div class="he">
            <h3>Phone:</h3>
        </div>
        <div class="sub">
            <p>+91 98765 43210</p>
        </div>
        <div class="he">
            <h3>Email ID:</h3>
        </div>
        <div class="sub">
            <p>ruegourmet@gmail.com</p>
        </div>
        <hr>

        <footer><p>&copy; (25016022) </p></footer>

    </body>
</html>```
menu.html
```
<html>
    <head>
        <title>
            Menu
        </title>
        <style>
            body
                {
                    background: url("food/food/templates/WhatsApp Image 2025-12-18 at 10.08.19 PM.jpeg") ;
                    background-position: center;
                    background-repeat: no-repeat;
                    background-size: contain;
                    background-size: cover;
                }
            .head 
            {
                padding-left: 50;
                padding-top: 60;
                color: aliceblue;
                font: 'Cormorant Garamond',serif;
                font-size: 23;
            }
            .nav {
                margin-top: 20px;
                text-align: right;

            }
            .nav a {
                color: white;
                text-decoration: none;
                margin-right: 20px;
                font-family: 'Lora', serif;
                letter-spacing: 2px;
            }

            .nav a:hover {
                text-decoration: underline;
            }
            .spe{
                padding-left: 40;
                font-weight: bolder;
                font-size: 26;
                font-family: 'Lora', serif;
                color: aliceblue;
            }
            footer
            {
                text-align: center;
                background-color: rgba(243, 220, 195, 0.8) ;
                margin-top: 60;
                height:15;
            }
            .cont {
                display: flex;
                gap: 80px;
                padding: 0 60px;
            }
            .items {
                background:rgba(243, 220, 195, 0.8);
                width: 250px;
                border-radius: 15px;
                padding: 10px;
                text-align: center;
            }
            .items img {
                width: 100%;
                height: 130px;
                object-fit: cover;
                border-radius: 10px;
            }

            .items h3 {
                margin: 10px 0 5px;
            }

            .items p {
                font-size: 14px;
            }


            
        </style>
    </head>
    <body>
        <div class="head">
            <h1>MENU</h1>
        </div>
        <div class="nav">
            <a href="rest.html"  >HOME</a>
            <a href="admin.html" >ADMIN </a>
            <a href="contact.html" >CONTACT</a>
        </div>
        <hr>
        <div class="spe">
            <p>Today's Special</p>
        </div>
        
        
        <div class="cont">
            <div class="items">
                <img src="food/food/templates/WhatsApp Image 2025-12-18 at 10.08.20 PM (1).jpeg">
                <h3>Lasagna al Forno</h3>
                <p>Rs.210</p>
            </div>
            <div class="items">
                <img src="food/food/templates/WhatsApp Image 2025-12-18 at 10.08.20 PM (2).jpeg">
                <h3>Truffle Risotto</h3>
                <p>Rs.200</p>
            </div>
            <div class="items">
                <img src="food/food/templates/WhatsApp Image 2025-12-18 at 10.08.20 PM (3).jpeg">
                <h3>Margherita Pizza</h3>
                <p>Rs.190</p>
            </div>
            <div class="items">
                <img src="food/food/templates/WhatsApp Image 2025-12-18 at 10.08.20 PM (4).jpeg">
                <h3>Chicken Steak</h3>
                <p>Rs.220</p>
            </div>
            <div class="items">
                <img src="food/food/templates/WhatsApp Image 2025-12-18 at 10.08.20 PM (5).jpeg">
                <h3>Classic Tiramisu</h3>
                <p>Rs.200</p>
            </div>
        

      

        </div>
        <hr>
        <br>
        <div class="spe">
            <p>Most Loved</p>
        </div>
        <div class="cont">
            <div class="items">
                <img src="f.jpg">
                <h3>Pasta</h3>
                <p>Rs.170</p>
            </div>
             <div class="items">
                <img src="food/food/templates/WhatsApp Image 2025-12-18 at 10.08.20 PM (6).jpeg">
                <h3>Focaccia Bread</h3>
                <p>Rs.150</p>
            </div>
             <div class="items">
                <img src="food/food/templates/WhatsApp Image 2025-12-18 at 10.08.20 PM (4).jpeg">
                <h3>Gelato</h3>
                <p>Rs.140</p>
            </div>

        </div>
        <hr>
        <footer>
            <p>&copy; SEJILAN(25008273)</p>
        </footer>
        
    </body>
</html>
```
res.html
```<html>
    <head>
        <title>Home</title>
        <link href="homes.css" rel="stylesheet">


    </head>
    <body>
        <div class="header">
            <h1>RUE GOURMET</h1>
            <div class="sub">
                <p>"The Street of Fine Food"</p>
            </div>
           
        </div>
        <div class="nav">
            <a href="menu.html"  >MENU</a>
            <a href="admin.html" >ADMIN </a>
            <a href="contact.html" >CONTACT</a>


        </div>
        <br>
        <br>

        <div class="content">
            <p>Traditional European techniques, crafted with modern elegance.</p>
            <p>Where classic European flavours meet modern creativity.</p>
        </div>
        <br>
        <br>
        <div class="one">
            <img src="WhatsApp Image 2025-12-18 at 10.08.19 PM (1).jpeg">
            <img src="WhatsApp Image 2025-12-18 at 10.08.19 PM (2).jpeg">
            <img src="WhatsApp Image 2025-12-18 at 10.08.19 PM (3).jpeg">
        </div>
        
        <footer>
            <p>&copy; SEJILAN(25008273) </p>
        </footer>
        

        

    </body>
</html>
```




# OUTPUT:  
<img width="1890" height="1015" alt="Screenshot 2025-12-18 223809" src="https://github.com/user-attachments/assets/d554fc45-5481-40fd-ba86-ebe8ab8c26b1" />

# RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
