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
    <script src="script.js"></script>
</body>
</html>


# CSS code


@import url('https://fonts.googleapis.com/css2?family=Roboto:wght@100;300;400;500;700&display=swap');

:root{
  --main: #ff6e01;
  --bg: #f1e1d2;
  --black: #000;
  --white: #fff;
  --box-shadow: 0 .5rem 1rem rgba(0, 0, 0, 0.1);
}

*{
  font-family: 'Roboto', sans-serif;
  margin: 0; padding: 0;
  box-sizing: border-box;
  outline: none; border: none;
  text-decoration: none;
  text-transform: capitalize;
  transition: .2s linear;
}

html{
  font-size: 62.5%;
  overflow-x: hidden;
  scroll-behavior: smooth;
  scroll-padding-top: 4rem;
}

html::-webkit-scrollbar{
  width: 1rem;
}

html::-webkit-scrollbar-track{
  background: transparent;
}

html::-webkit-scrollbar-thumb{
  background: var(--main);
  border-radius: 5rem;
}

section{
  padding: 8rem 7%;
}

.heading{
  text-align: center;
  font-size: 4rem;
  color: var(--main);
  text-transform: uppercase;
  margin-bottom: 3rem;
  padding: 1.2rem 0;
}

.btn{
  font-size: 1.7rem;
  display: inline-block;
  background: var(--main);
  color: var(--white);
  box-shadow: var(--box-shadow);
  border-radius: 5rem;
  padding: 0.9rem 3rem;
  margin-top: 1rem;
  z-index: 0;
  position: relative;
  overflow: hidden;
}

.btn::before{
  content: '';
  position: absolute;
  top: 0;
  height: 100%;
  width: 0%;
  background: #ff9748;
  z-index: -1;
  transition: .3s linear;
  left: 0;
}

.btn:hover::before{
  width: 100%;
}


/* header */

.header{
  position: fixed;
  top: 0; left: 0; right: 0;
  z-index: 1000;
  background: var(--white);
  box-shadow: var(--box-shadow);
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding: 2rem 9%;
}

.header .logo{
  font-size: 2.5rem;
  font-weight: bolder;
  color: var(--black);
}

.header .logo i{
  color: var(--main);
}

.header .navbar a{
  font-size: 1.7rem;
  color: var(--black);
  margin: 0 1rem;
}

.header .navbar a:hover{
  color: var(--main);
}

.header .icons div{
  font-size: 2.5rem;
  margin-left: 1.7rem;
  cursor: pointer;
  color: var(--black);
}

.header .icons div:hover{
  color: var(--main);
}

#menu-btn{
  display: none;
}

/* login form */

.header .login-form{
  position: absolute;
  top: 115%;
  right: -105%;
  background: var(--white);
  border-radius: .5rem;
  box-shadow: var(--box-shadow);
  width: 35rem;
  padding: 2rem;
}

.header .login-form.active{
  right: 2rem;
  transition: .4s linear;
}

.header .login-form h3{
  font-size: 2.2rem;
  color: var(--black);
  text-transform: uppercase;
  margin-bottom: .7rem;
  text-align: center;
}

.header .login-form .box{
  font-size: 1.5rem;
  padding: 1rem 1.2rem;
  border: .1rem solid rgba(0, 0, 0, 0.1);
  margin: .7rem 0;
  color: var(--black);
  width: 100%;
  text-transform: none;
}

.header .login-form .remember{
  display: flex;
  align-items: center;
  gap: .5rem;
  margin: .7rem 0;
}

.header .login-form .remember label{
  font-size: 1.5rem;
  color: var(--black);
  cursor: pointer;
}

.header .login-form .btn{
  width: 100%;
  text-align: center;
}

/* end */

/* home */

.home{
  min-height: 100vh;
  display: flex;
  align-items: center;
  background: url(home.jpg) no-repeat;
  background-size: cover;
  background-position: top;
}

.home .content{
  max-width: 60rem;
}

.home .content h3{
  color: var(--white);
  font-size: 6rem;
  line-height: 1.4;
  font-weight: 400;
}

.home .wave{
  position: absolute;
  bottom: 0; left: 0;
  width: 100%;
  height: 12rem;
}


/* end */

/* about */

.about .box-container{
  display: flex;
  align-items: center;
  flex-wrap: wrap;
  gap: 6rem;
}

.about .deco-title{
  font-size: 10rem;
  font-weight: 700;
  white-space: nowrap;
  line-height: 0.5;
  color: transparent;
  -webkit-text-fill-color: transparent;
  -webkit-text-stroke: 1px rgb(204,204,204);
  transform-origin: top left;
  transform: rotate(0.25turn);
  position: absolute;
  top: 115%;
  left: 48%;
  z-index: -1;
}

.about .box-container .image{
  flex: 1 1 31rem;
}

.about .box-container .image img{
  width: 100%;
}

.about .content{
  flex: 1 1 41rem;
}

.about .content .title{
  font-size: 4rem;
  color: var(--black);
}

.about .content p{
  font-size: 1.7rem;
  color: #444;
  padding: 1rem 0;
  line-height: 2;
}

.about .content .icons-container{
  display: flex;
  flex-wrap: wrap;
  gap: .5rem;
  margin-top: 3rem;
}

.about .content .icons-container .icons{
  flex: 1 1 16rem;
  text-align: center;
  background: var(--bg);
  padding: 3rem 2rem;
}

.about .content .icons-container .icons .fas{
  height: 5rem;
  font-size: 4rem;
  color: var(--main);
}

.about .content .icons-container .icons h3{
  padding-top: 1rem;
  font-size: 1.5rem;
  color: #444;
  font-weight: normal;
}

/* end */

/* gallery */

.gallery{
  background: var(--bg);
}

.gallery .slide .image{
  height: 30rem;
  overflow: hidden;
  position: relative;
}

.gallery .slide .image img{
  height: 100%;
  width: 100%;
  object-fit: cover;
}

.swiper-button-next,
.swiper-button-prev{
  color: var(--white);
}

/* end */

/* animals */

.animal .box-container{
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(25rem,1fr));
  gap: 2rem;
}

.animal .box-container .box{
  height: 100%;
  position: relative;
  overflow: hidden;
}

.animal .box-container .box img{
  height: 100%;
  width: 100%;
  object-fit: cover;
}

.animal .box-container .box:hover img{
  transform: scale(1.1);
}

.animal .box-container .box .content{
  text-align: center;
  position: absolute;
  bottom: 0;
  left: 0; right: 0;
  padding: 20px;
  z-index: 1;
  transition: 0.5s ease;
}

.animal .box-container .box:hover::after{
  content: '';
  position: absolute;
  top: 0; left: 0;
  width: 100%;
  height: 100%;
  background: var(--black);
  opacity: 0.5;
  transition: 0.5s ease;
}

.animal .box-container .box .content h3{
  text-align: center;
  font-size: 3rem;
  color: var(--white);
}

.animal .box-container .box:is(:hover, :focus-within) .content{
  transform: translateY(-20px);
}

/* end */

/* banner */

.banner{
  background: url(banner.png) no-repeat;
}

.banner .row{
  display: flex;
  align-items: center;
  flex-wrap: wrap;
  gap: 6rem;
}

.banner .row .content{
  flex:  1 1 39rem;
}

.banner .row .content h3{
  font-size: 2rem;
  color: var(--main);
  text-transform: uppercase;
}

.banner .row .content p{
  font-size: 1.6rem;
  color: var(--black);
  padding: 1rem 0;
  line-height: 1.8;
}

.banner .row .image{
  flex: 1 1 41rem;
  margin-bottom: -14rem;
}

.banner .row .image img{
  width: 100%;
}

/* end */

/* pricing */

.pricing .box-container{
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(30rem, 1fr));
  gap: 2rem;
}

.pricing .box-container .box{
  background: var(--bg);
  padding: 3rem;
  text-align: center;
  border-radius: 79% 51% 81% 19% / 58% 93% 7% 42%;
}

.pricing .box-container .box:hover{
  border-radius: .5rem;
}

.pricing .box-container .box img{
  height: 15.5rem;
  width: 15.5rem;
  margin-bottom: .5rem;
}

.pricing .box-container .box h3{
  font-size: 2.6rem;
  color: var(--black);
  padding: 1rem 0;
}

.pricing .box-container .box .price{
  font-size: 2.2rem;
  color: var(--main);
  padding: .5rem 0;
}

.pricing .box-container .box p{
  font-size: 1.5rem;
  color: var(--black);
  padding: .5rem 0;
}


/* end */

/* contact */

.contact{
  background: var(--bg);
}

.contact form{
  padding: 2rem 10%;
  text-align: center;
}

.contact form .inputBox{
  display: flex;
  flex-wrap: wrap;
  justify-content: space-between;
}

.contact form .inputBox input,
.contact form textarea{
  font-size: 1.7rem;
  width: 49%;
  padding: 1rem 2rem;
  margin: 1rem 0;
  border-radius: .5rem;
  text-transform: none;
}

.contact form .inputBox input::placeholder,
.contact form textarea::placeholder{
  text-transform: capitalize;
}

.contact form textarea{
  height: 15rem;
  resize: none;
  width: 100%;
}

/* end */

/* footer */

.footer{
  background: url(footer.jpg) no-repeat;
  background-size: cover;
  padding: 3rem 7%;
}

.footer .box-container{
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(25rem, 1fr));
  gap: 1.5rem;
}

.footer .box-container .box h3{
  font-size: 2.5rem;
  color: var(--main);
  padding: 1rem 0;
}

.footer .box-container .box p{
  font-size: 1.5rem;
  line-height: 1.8;
  color: var(--white);
  padding: 1rem 0;
}

.footer .box-container .box .links{
  display: block;
  font-size: 1.5rem;
  color: var(--white);
  padding: 1rem 0;
}

.footer .box-container .box .links i{
  color: var(--main);
  padding-right: .5rem;
}

.footer .box-container .box .links:hover i{
  padding-right: 2rem;
}

.footer .box-container .box .days{
  margin-left: 2.2rem;
  line-height: .2;
}

.footer .box-container .box .email{
  width: 100%;
  margin: .7rem 0;
  padding: 1rem;
  border-radius: .5rem;
  background: var(--white);
  font-size: 1.6rem;
  color: var(--black);
  text-transform: none;
}

.footer .box-container .box .share a{
  height: 3rem;
  width: 3rem;
  line-height: 3rem;
  color: var(--black);
  background: var(--white);
  font-size: 1.2rem;
  border-radius: 5rem;
  margin-right: .8rem;
  text-align: center;
  margin-top: 1.4rem;
}

.footer .box-container .box .share a:hover{
  background: var(--main);
}

.footer .credit{
  font-size: 2rem;
  text-align: center;
  margin-top: 2rem;
  padding-top: 2.5rem;
  color: var(--black);
  border-top: .2rem solid rgba(0, 0, 0, 0.2);
}

.footer .credit .link{
  color: var(--main);
}

/* end */

/* media queries */

@media(max-width: 991px){
  html{
    font-size: 55%;
  }
  .header{
    padding: 2rem;
  }
  section{
    padding: 8rem 2rem;
  }
}

@media (max-width: 768px){

  #menu-btn{
    display: inline-block;
  }

  .header .navbar{
    position: absolute;
    top: 99%;
    left: 0; right: 0;
    background: var(--white);
    border-top: .1rem solid var(--main);
    clip-path: polygon(0 0, 100% 0, 100% 0, 0 0);
  }

  .header .navbar.active{
    clip-path: polygon(0 0, 100% 0, 100% 100%, 0 100%);
  }

  .header .navbar a{
    display: block;
    margin: 2rem;
    font-size: 2rem;
  }

  .home{
    background-position: left;
  }

  .home .content h3{
    font-size: 5rem;
  }

  .deco-title{
    display: none;
  }

}

@media (max-width: 450px){
  html{
    font-size: 50%;
  }

  .home .content h3{
    font-size: 4rem;
  }

}
