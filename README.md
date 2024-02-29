# PROBLEM NO - CBP40

Creating a Virtual zoo can provide educational and entertaining experience for people world wide, promoting wild life conservation awearness and accessability,
especially for those unable to vist traditional zoo's 
# Virtual Zoo Flow Chart

## Start
1. User accesses the Virtual Zoo website.

## Main Menu
2. User is presented with the main menu options:
   - Home Page
   - About
   - Gallery
   - Animals
   - Pricing
   - Contact Us

## Home Page
3. If user selects "Home Page":
   - It contains the login information.
   - And hat you are getting to know.

### About
4. Show details about the selected exhibit:
   - Price to visit the zoo
   - It contains Time to Visit and leave the zoo
   - You can Find all the most popular species

## Gallery
5. If user selects "Gallery":
   - Display a list of all animals photos in the virtual zoo.
   - User selects a specific animal to visit it.

### Animal Details
6. Show details about the selected animal:
   - Price to visit the specific animal
   - About the animal that you want to visit
   - Facts about the animal

## Pricing
7. If user selects "Pricing":
   - It contains all the pricing of the animals which are present in the zoo.
   - User selects a tour to visit the specific animal.

### Contact us
8. Simulate a virtual tour:
   - Navigate through different sections of the zoo.

## Events and Shows
9. If user selects "Events and Shows":
   - Display a calendar of upcoming events.
   - User selects an event.

### Event Details
10. Provide details about the selected event:
    - Date
    - Time
    - Description

## Contact Us
11. If user selects "Contact Us":
    - Display contact information.
    - User can send inquiries or feedback to the the zoo which they visited.

## End
12. User exits the Virtual Zoo website with the full satisfaction.


# SOURCE CODE

# HTML code;
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="inline.css">
</head>
<body>
    <header class="header">
        <a href="#" class="logo"><i class="fas fa-paw"></i></a>
        <nav class="navbar">
            <a href="#home">home</a>
            <a href="#about">about</a>
            <a href="#gallery">gallery</a>
            <a href="#animal">animal</a>
            <a href="pricing">princing</a>
            <a href="#contact">contact</a>
        </nav>
        <div class="icon">
            <div id="login-btn" class="fas fa-user"></div>
            <div id="menu-btn" class="fas fa-bars5"></div> 
        </div>
    </header>
    <form action="" class="login">
        <h3>login form</h3>
        <input type="email" placeholder="Enter your email" class="box">
        <input type="password" placeholder="Enter your password" class="box">
        <div class="='remember">
            <input type="checkbox" name="" id="remember-me">
            <label for="remember-me">remember me</label>
        </div>
        <a href="#" class="btn">login</a>
    </form>
    <section class="home" id="home">

        <div class="contact">
            <h3>enjoy the wonderful<br>
            adventure of the <br> animals</h3>
            <a href="#" class="btn">meet the zoo</a> 
        </div>
        <img src=".png">
    </section>    
</section>    
<section class="about" id="about">
    <h2 class="deco-title">About us</h2>
    <div class="box-container">
        <div class="image">
            <img src="" alt="">
        </div>
         <div class="content">
            <h3 class="title">you can find all the most popular species</h3>
            <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit.
                Totam velit nihil exercitationem aut nostrum debitis, ea aliquam nesciunt, possimus nulla voluptatum repellendus? Dolorum natus quis rem optio, explicabo ipsam aperiam.
                
            </p>
            <div class="icon-container">
                <div class="icons">
                    <i class="fas fa-graduation-cap"></i>
                    <h3>we educate</h3>
                </div>
                <div class="icons">
                    <i class="fas fa-bull-horn" ></i>
                    <h3>we play</h3>
                </div>
                <div class="icons">
                    <i class="fas fa-book-opn"></i>
                    <h3>Getting to know</h3>
                </div>
            </div>
        </div>
</section>
<section class="animal" id="animal">
    <h2 class="heading">animals</h2>
    <div class="box-container">
        <div class="box">
            <img src="animal_1.jpg" alt="cameleon">
            <div class="content">
                <h3>cameleon</h3>
                <a href="#" class="btn">see details</a>
            </div>
        </div>
    </div>

        <div class="box">
            <img src="animals_2.jpg" alt="zebra">
            <div class="content">
                <h3>zebra</h3>
                <a href="#" class="btn">see details</a>
            </div>
        </div>
        <div class="box">
            <img src="animals_3.jpg" alt="giraffe">
            <div class="content">
                <h3>giraffe</h3>
                <a href="#" class="btn">see details</a>
            </div>
        </div>
        <div class="box">
            <img src="animals_4.jpg" alt="monkey">
            <div class="content">
                <h3>monkey</h3>
                <a href="#" class="btn">see details</a>
            </div>
        </div>
</section>[10:54 PM, 2/29/2024] RITHVIK: </section>    
    <section class="about" id="about">
        <h2 class="deco-title">About us</h2>
        <div class="box-container">
            <div class="image">
                <img src="about.png" alt="">
            </div>
             <div class="content">
                <h3 class="title">you can find all the most popular species</h3>
                <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit.
                    Totam velit nihil exercitationem aut nostrum debitis, ea aliquam nesciunt, possimus nulla voluptatum repellendus? Dolorum natus quis rem optio, explicabo ipsam aperiam.
                    
                </p>
                <div class="icon-container">
                    <div class="icons">
                        <i class="fas fa-graduation-cap"></i>
                        <h3>we educate</h3>
                    </div>
                    <div class="icons">
                        <i class="fas fa-bull-horn" ></i>
                        <h3>we play</h3>
                    </div>
                    <div class="icons">
                        <i class="fas fa-book-opn"></i>
                        <h3>Getting to know</h3>
                    </div>
                </div>
            </div>
    </section>
    <section class="pricing" id="pricing">
        <h2 class="heading">pricing</h2>
        <div class="box-container">
            <div class="box">
                <img src="" alt="">
                <h3>individuals</h3>
                <h4 class="price">$ 10</h4>
                <p>the entrance is from 8:00 to 14:00</p>
            </div>
        </div>
        <div class="box">
            <img src="" alt="">
            <h3>school</h3>
            <h4 class="price">$ 10</h4>
            <p>the entrance is from 9:00 to 17:00</p>
        </div>
        <div class="box">
            <img src="" alt="">
            <h3>family</h3>
            <h4 class="price">$ 10</h4>
            <p>the entrance is from 10:00 to 18:00</p>
        </div>
[11:49 PM, 2/29/2024] RITHVIK: <section class="footer">
        <div class="box">
            <h3><i class="fas fa-paw"></i>/</h3>
            <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. </p>
            <p class="links"><i class="fas fa-clock"></i>monday-friday</p>
            <p class="days">7:00AM-11:00PM</p>
        </div>
        <div class="box">
            <h3>Contact info</h3>
            <a href="#" class="links"><i class="fas fa-phone"></i>1245-147-2589</a>
            <a href="#" class="links"><i class="fas fa-phone"></i>1245-147-2589</a>
            <a href="#" class="links"><i class="fas fa-envelope"></i>info@zoolife.com</a>
            <a href="#" class="links"><i class="fas fa-marker-all"></i>India delhi</a>
        </div>
        <div class="box">
            <h1>quick links</h1>
            <a href="#" class="links"><i class="fas fa-arrow-right">home</i></a>
            <a href="#" class="links"><i class="fas fa-arrow-right">about</i></a>
            <a href="#" class="links"><i class="fas fa-arrow-right">gallery</i></a>
            <a href="#" class="links"><i class="fas fa-arrow-right"></i>animal</a>
            <a href="#" class="links"><i class="fas fa-arrow-right"></i>pricing/a>
        </div>
        <div class="box">
            <h3>news letter</h3>
            <p>subscribe for latest updates</p>
            <input type="email" placeholder="Your email" class="email">
            <a href="#" class="btn">subscribe</a>
            <div class="share">
                <a href="#" class="fab fa-facebook"></a>
                <a href="#" class="fab fa-twitter"></a>
                <a href="#" class="fab fa-instagram"></a>
                <a href="#" class="fab fa-linkedin"></a>

            </div>
        </div>
        <div class="credit">&copy; 2022 zoolife.All rights reserved by <a href="#" class="link">ninjashub</a></div>
    </section>


</body>
</html>
    <script src="script.js"></script>
</body>
</html>
