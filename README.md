# MDAP-EX_01-Portfolio
## Date:

## AIM
To create a Portfolio using HTML and CSS.

## ALGORITHM
### STEP 1
Create an HTML file (index.html)

### STEP 2
Create a CSS file (style.css)

### STEP 3
Include a navigation bar with links to different sections.

### STEP 4
Add structured sections for introduction, about, projects, and contact details.

### STEP 5
Define global styles for fonts, colors, and layout.

### STEP 6
Style the header, navigation bar, and sections.

### STEP 7
Use Flexbox or CSS Grid for layout design.

### STEP 8
Add hover effects and transitions for interactivity.

### STEP 9
Add Images and Media.

### STEP 10
Use optimized images for a professional look.

### STEP 11
Open the HTML file in a browser to check layout and functionality.

### STEP 12
Fix styling issues and refine content placement.

### STEP 13
Deploy the Portfolio.

### STEP 14
Upload to GitHub Pages for free hosting.

## PROGRAM
### index.html:

```
    <!DOCTYPE html>
    <html lang="en">
    <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Aishwarya's Portfolio</title>
    <link rel="stylesheet" href="style.css">
    <link rel="stylesheet" href="./responsive.css">
    <!-- boxicon css link -->
    <link href='https://unpkg.com/boxicons@2.1.4/css/boxicons.min.css' rel='stylesheet'>
    <!-- Link Swiper's CSS -->
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/swiper@10/swiper-bundle.min.css" />
    </head>
    <body>
        <div class="overlay"></div>
        <header>
            <a href="#" class="logo"><span>A</span>ishwarya</a>
            <ul class="navlist">
                <li><a href="#home" class="active">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#services">Services</a></li>
                <li><a href="#portfolio">Portfolio</a></li>
                <li><a href="#blog">Blog</a></li>
                <li><a href="#contact">Contact</a></li>
                </ul>
                <div class="right-header">
                    <a href="#" class="btn">Let's chat <i  class='bx bx-message-dots'></i></a>
                    <div class="menu-icon">
                        <div class="bar"></div>
                    </div>
                </div>
        </header>

        <section class="home" id="home">
            <div class="hero-info">
                <h3>Welcome To My World</h3>
                <h1>Hi I'm Aishwarya</h1>

                <div class="text-animate">
                <h2>Frontend Developer</h2>
                </div>

                <p>Lorem ipsum dolor sit amet consectetur 
                adipisicing elit. Odio consequuntur sit dolorem 
                eum id repellendus totam, repudiandae veritatis 
                nulla corrupti impedit, accusantium blanditiis
                minus eius reprehenderit atque. Maiores, ratione 
                impedit.</p>

                <div class="btn-box">
                <a href="aishwarya@example.com" class="btn">Hire Me Now ! <i class='bx bx-right-arrow-alt'></i></a>
                <a href="#" target="_blank" class="btn d-CV">Download CV <i class='bx bx-download'></i></a>
                </div>

                <div class="social-media">
                <div class="bg-icon">
                    <a href="#"><i class='bx bxl-instagram'></i></a>
                    <span></span>
                    </div>

                    <div class="bg-icon"><a href="#"><i class='bx bxl-github'></i></a>
                    <span></span>
                    </div>

                    <div class="bg-icon">
                    <a href="#"><i class='bx bxl-twitter'></i></a>
                    <span></span>
                    </div>

                    <div class="bg-icon">
                    <a href="#"><i class='bx bxl-facebook'></i></a>
                    <span></span>
                    </div>
                    </div>
                    </div>
                    <div class="img-hero">
                    <img src="aish.png" alt="">
                    <div class="rotate-text">
                    <div class="text">
                    <p>I'm Web Developer And I'm UI/UX Designer And I'm Editor</p>
                    </div>
                    <span><i></i></span>
                    </div>
                    </div>
                    </section>

                    <section class="about" id="about">
                    <div class="about-img">
                    <img src="aish.png" alt="" class="aboutHero">
                    <div class="showcase-ring">
                    <img src="shapes/ring.png" class="ring">
                    <img src="shapes/circle.png" class="circle">    
                    </div>
                    </div>
                    <div class="about-content">
                    <h2 class="heading">About Me</h2>
                    <h3>2 Year's Experience on Product Design</h3>
                    <p>Lorem ipsum dolor sit, amet consectetur 
                    adipisicing elit. Ex modi quas nisi eum 
                    odit totam dolor, distinctio ipsum enim 
                    alias deleniti consectetur doloremque! Modi 
                    omnis illum vero, eos sequi eius.</p>
                    <div class="about-btn">
                    <button class="active">Main Skills</button>
                    <button>Awards</button>
                    <button>Education</button>
                    </div>
                    <div class="content-btn">
                    <div class="content">
                    <div class="text-box">
                    <p>User Experience Design - UI / UX</p>   
                    <span>Delight the user and make it work.</span>  
                    </div>
                    <div class="text-box">
                    <p>Web & User Interface Design - Development</p>
                    <span>Website , Web Experience , ...</span>
                    </div>
                    <div class="text-box">
                    <p>Interaction Design - Animation</p>
                    <span>I Like to move it move it</span>
                    </div>
                    </div>

                    <div class="content">
                    <div class="text-box">
                    <p>Web Design Award</p>
                    <span>Award for creativity and user experience.</span>
                    </div>
                    <div class="text-box">
                    <p>Code and Development Award</p>
                    <span>Expectional Coding skills and development 
                    techniques</span>
                    </div>
                    <div class="text-box">
                    <p>Hackathons and Coding Competitions</p>
                    <span>Participating in hackathons and coding.</span>
                    </div>
                    </div>

                    <div class="content">
                    <div class="text-box">
                    <p>Online Courses and Bootcamps</p>
                    <span>Delight the user and make it work.</span>
                    </div>
                    <div class="text-box">
                    <p>Internships and Work Experience</p>
                    <span>Website , Web Experience , ...</span>
                    </div>
                    <div class="text-box">
                    <p>Bachelor's Degree in Computer Science</p>
                    <span>I Like to move it move it</span>
                    </div>
                    </div>
                    </div>
                    <div class="cvContent">
                    <a href="img/resume.pdf" target="_blank" class="btn d-CV">Download CV<i class='bx bx-download'></i></a>
                    </div>
                    </div>
                    </section>
                    
                    <section class="services" id="services">
                    <div class="main-text">
                    <h2 class="heading">My Services</h2>
                    <span>what i will do for you</span>
                    </div>
                    
                    <div class="allServices">
                    <div class="servicesItem">
                    <div class="icon-services">
                    <i class='bx bx-layer'></i>
                    <span></span>
                    </div>
                    <h3>App Development</h3>
                    <p>Lorem ipsum dolor sit amet consectetur 
                    adipisicing elit. Esse similique corporis 
                    facilis blanditiis quis, et consequatur, 
                    cupiditate facere aperiam, neque quidem maxime 
                    hic accusantium explicabo consequuntur nihil 
                    perferendis distinctio soluta.</p>
                    <a href="#" class="readMore">Read More</a>
                    </div>

                    <div class="servicesItem">
                    <div class="icon-services">
                    <i class='bx bx-code-alt'></i>
                    <span></span>
                    </div>
                    <h3>Web Development</h3>
                    <p>Lorem ipsum dolor sit amet consectetur, 
                    adipisicing elit. Exercitationem vero 
                    eaque molestiae, magni quod praesentium 
                    amet nisi enim dicta atque saepe, ut laudantium 
                    optio animi vel quisquam cumque in! Obcaecati?</p>
                    <a href="#" class="readMore">Read More</a>
                    </div>

                    <div class="servicesItem">
                    <div class="icon-services">
                    <i class='bx bx-desktop'></i>
                    <span></span>
                    </div>
                    <h3>UI / UX Design</h3>
                    <p>Lorem, ipsum dolor sit amet consectetur adipisicing 
                    elit. Eum esse ea omnis. Optio fugiat ipsa dicta, 
                    provident dolorum explicabo perferendis excepturi, 
                    voluptatum, sunt placeat porro ipsum quas eos delectus 
                    praesentium.</p>
                    <a href="#" class="readMore">Read More</a>
                    </div>
                   
                    <div class="servicesItem">
                    <div class="icon-services">
                    <i class='bx bxs-party'></i>
                    <span></span>
                    </div>
                    <h3>Digital Marketing</h3>
                    <p>Lorem, ipsum dolor sit amet consectetur adipisicing 
                    elit. Repellendus nam laudantium ut architecto illum 
                    perferendis modi eius saepe quae dolor mollitia voluptatum 
                    nihil incidunt dicta, deleniti atque dignissimos aut vitae!</p>
                    <a href="#" class="readMore">Read More</a>
                    </div>
                    </div>

                    <div class="proposal">
                    <div class="text-box">
                    <span>Get It Touch</span>
                    <h3>Have a Project On Your Mind</h3>
                    <a href="#contact" class="btn">Conatct Me</a>
                    </div>
                    <img src="aish.png" class="first">
                    </div>

                    <div class="showcase">
                    <img src="shapes/ring.png" class="ring">
                    <img src="shapes/circle.png" class="circle">
                    <img src="shapes/circle.png" class="circle2">
                    <img src="shapes/circle.png" class="circle3">
                    <img src="shapes/half-ring.png" class="half-ring">
                    </div>
                    </section>

                    <section class="portfolio" id="portfolio">
                    <div class="main-text">
                    <h2 class="heading">My Services</h2>
                    <span>what i will do for you</span>
                    </div>
                    <div class="fillter-buttons">
                    <button class="button mixitup-control-active" data-filter="all">All Work</button>
                    <button class="button" data-filter=".web">web
                    Development</button>
                    <button class="button" data-filter=".uiux">UI/UX
                    Design</button>
                    <button class="button" data-filter=".
                    branding">Branding Design</button>
                    </div>

                    <div class="portfolio-gallery">
                    <div class="portfolio-box mix uiux">
                    <div class="portfolio-content">
                    <h3>UI/UX Design</h3>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quod iste ipsum, 
                    et dolores perferendis quaerat eveniet adipisci nam fugit sapiente excepturi.</p>
                    <a href="#" class="readMore">Explore More</a>
                    </div>
                    <div class="portfolio-img">
                    <img src="img/portfolio/1.jpg" alt="">
                    </div>
                    </div>

                    <div class="portfolio-box mix web">
                    <div class="portfolio-content">
                    <h3>Web Design</h3>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptatibus illo necessitatibus 
                    architecto deserunt? Velit totam quidem itaque nobis maiores magni iusto ad recusandae repellendus!</p>
                    <a href="#" class="readMore">Explore More</a>
                    </div>
                    <div class="portfolio-img">
                    <img src="img/portfolio/2.jpg" alt="">
                    </div>
                    </div>

                    <div class="portfolio-box mix web">
                    <div class="portfolio-content">
                    <h3>Web Development</h3>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Delectus adipisci ratione voluptatibus omnis 
                    deserunt recusandae magnam, incidunt illo! Dolore beatae non atque praesentium qui excepturi! Labore?</p>
                    <a href="#" class="readMore">Explore More</a>
                    </div>
                    <div class="portfolio-img">
                    <img src="img/portfolio/3.jpg" alt="">
                    </div>
                    </div>

                    <div class="portfolio-box mix web">
                    <div class="portfolio-content">
                    <h3>Web Development</h3>
                    <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Cupiditate quae perspiciatis ab omnis. 
                    Ea, nulla? Totam error deleniti quisquam sunt aliquam maiores quae aperiam explicabo, perferendis tenetur!</p>
                    <a href="#" class="readMore">Explore More</a>
                    </div>

                    <div class="portfolio-img">
                    <img src="img/portfolio/4.jpg" alt="">
                    </div>
                    </div>

                    <div class="portfolio-box mix uiux">
                    <div class="portfolio-content">
                    <h3>UI/UX Design</h3>
                    <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Repellendus natus repellat ex, consectetur eveniet, 
                    placeat provident obcaecati, dolore sapiente nesciunt perspiciatis voluptatem quod consequatur beatae quidem?</p>
                    <a href="#" class="readMore">Explore More</a>
                    </div>
                    <div class="portfolio-img">
                    <img src="img/portfolio/5.jpg" alt="">
                    </div>
                    </div>

                    <div class="portfolio-box mix branding">
                    <div class="pprtfolio-content">
                    <h3>Web Development</h3>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Molestiae totam, placeat asperiores, beatae, voluptate 
                    vero libero quam eos nihil soluta assumenda quos labore quasi possimus? Beatae ad et magnam porro!</p>
                    <a href="#" class="readMore">Explore More</a>
                    </div>
                    <div class="portfolio-img">
                    <img src="img/portfolio/6.jpg" alt="">
                    </div>
                    </div>
                    </div>

                    </section>

                    <section class="blog" id="blog">
                    <div class="main-text">
                    <h2 class="heading">Blog</h2>
                    <span>Latest News & Post</span>
                    </div>

                    <div class="blog-box swiper myswiper">
                    <div class="cards swiper-wrapper">
                    <div class="card swiper-slide">
                    <div class="card-top">
                    <img src="img/blog/1.jpg" alt="">
                    </div>
                    <div class="card-info">
                    <h2>Mobile App Landing Page</h2>
                    <span class="date">sunday, Jan 14, 2023</span>
                    <p class="excerpt">
                    Lorem, ipsum dolor sit amet consectetur adipisicing elit. Facilis, officiis eaque! Id autem omnis qui deleniti 
                    delectus ipsa in, alias quia temporibus porro at quos nostrum officia sapiente magnam dolores.
                    </p>
                    <a href="#" class="readMore">Explore More</a>
                    </div>
                    </div>

                    <div class="card swiper-slide">
                    <div class="card-top">
                    <img src="img/blog/2.jpg" alt="">
                    </div>
                    <div class="card-info">
                    <h2>Mobile App Landing Page</h2>
                    <span class="date">Sunday, Jan 14,2024</span>
                    <p class="excerpt">
                    Lorem ipsum dolor sit, amet consectetur adipisicing elit. Itaque doloremque fugit ex ea recusandae exercitationem 
                    dolorum similique vero hic ratione incidunt architecto nihil accusantium, quaerat, fugiat perferendis officia.
                    </p>
                    <a href="#" class="readMore">Explore More</a>
                    </div>
                    </div>

                    <div class="card swiper-slide">
                    <div class="card-top">
                    <img src="img/blog/3.jpg" alt="">
                    </div>
                    <div class="card-info">
                    <h2>Mobile App Landing Page</h2>
                    <span class="date">Sunday, Jan 14,2024</span>
                    <p class="excerpt">
                    Lorem ipsum dolor sit amet consectetur adipisicing elit. Tempore inventore consequatur maiores quas, repellat quibusdam 
                    provident. Tempora, soluta error culpa dicta quaerat nisi porro inventore iure facere, a aliquam mollitia?
                    </p>
                    <a herf="#" class="readMore">Explore More</a>
                    </div>
                    </div>

                    <div class="card swiper-slide">
                    <div class="card-top">
                    <img src="img/blog/4.jpg" alt="">
                    </div>
                    <div class="card-info">
                    <h2>Mobile App Landing Page</h2>
                    <span class="date">Sunday, Jan 14, 2024</span>
                    <p class="excerpt">
                    Lorem ipsum dolor sit amet consectetur adipisicing elit. Cum, debitis provident. Similique possimus nihil, veritatis autem iste 
                    fugit cumque commodi asperiores. Neque molestias veritatis adipisci, asperiores voluptatem tempore odio optio!
                    </p>
                    <a href="#" class="readMore">Explore More</a>
                    </div>
                    </div>

                    <div class="card swiper-slide">
                    <div class="card-top">
                    <img src="img/blog/5.jpg" alt="">
                    </div>
                    <div class="card-info">
                    <h2>Mobile App Landing Page</h2>
                    <span class="date">Sunday, Jan 14, 2024</span>
                    <p class="excerpt">
                    Lorem ipsum dolor sit amet consectetur, adipisicing elit. Sapiente vitae qui quam asperiores voluptatibus possimus ullam quos, 
                    non molestias? Dolores recusandae ullam sequi ducimus quos dolorem adipisci optio aperiam nemo?
                    </p> 
                    <a href="#" class="readMore">Explore More</a>
                    </div>
                    </div>

                    <div class="card swiper-slide">
                    <div class="card-top">
                    <img src="img/blog/6.jpg" alt="">
                    </div>
                    <div class="card-info">
                    <h2>Mobile App Landing Page</h2>
                    <span class="date">Sunday, Jan 14, 2024</span>
                    <p class="excerpt">
                    Lorem ipsum dolor sit amet, consectetur adipisicing elit. Nostrum et voluptate consectetur facilis, eligendi quidem officia 
                    perferendis tenetur. Error iusto, excepturi suscipit quae repudiandae consequuntur ut beatae cum deserunt fugiat.
                    </p>
                    <a href="#" class="readMore">Explore More</a>
                    </div>
                    </div>

                    </div>
                    </div>

                    <div class="swiper-pagination"></div>

                    <div class="showcase">
                    <img src="shapes/ring.png" class="ring">
                    <img src="shapes/second-circle.png" class="second-circle">
                    <img src="shapes/half-ring.png" class="half-ring">
                    </div>

                    </section>

                    <section class="down-box" id="content">
                    <div class="contactSkills">
                    <div class="contact-info">
                    <div class="main-text">
                    <h2 class="heading">Contact Me</h2>
                    <span>get in touch with</span>
                    </div>
                    <form action="#">
                    <div class="input-box">
                    <input type="text" placeholder="First Name">
                    <input type="text" placeholder="Last Name">
                    </div>
                    <input type="email" placeholder="Email">
                    <input type="text" placeholder="Subject">
                    <textarea name="#" id="" cols="30" rows="10">
                    </textarea>
                    <div class="formBtn">
                    <button type="submit" class="btn">Send Message</button>
                    </div>
                    </form>
                    </div>
                    <div class="skills">
                    <div class="container">
                    <div class="skillBox">
                    <div class="main-text">
                    <h2 class="heading">My Skills</h2>
                    <span>Let Me Help</span>
                    </div>
                    <div class="skill-wrap">
                    <div class="skill">
                    <div class="outer-circle">
                    <div class="inner-circle">
                    <svg xmlns="https://www.w3.org/2000/svg" version="1.
                    1" width="180px" height="180px">
                    <defs>
                    <linearGradient if="GradientColor">
                    <stop offset="0%" stop-color="##e91e63" />
                    <stop offset="100%" stop-color="#673ab7" />
                    </linearGradient>
                    </defs>
                    <circle cx="85" cy="85" r="75" 
                    stroke-linecap="round" />
                    </svg>
                    <h2 class="counter">
                    <span data-target="89">0</span>%
                    </h2>
                    </div>
                    </div>
                    <div class="sk-title">
                    HTML
                    </div>
                    </div>

                    <div class="skill">
                    <div class="outer-circle">
                    <div class="inner-circle">
                    <svg xmlns="https://www.w3.org/2000/svg" version="1.
                    1" width="180px" height="180px">
                    <defs>
                    <linearGradient id="GradientColor">
                    <stop offset="0%" stop-color="#e91e63" />
                    <stop offset="100%" stop-color="#673ab7" />
                    </linearGradient>
                    </defs>
                    <circle cx="85" cy="85" r="75" 
                    stroke-linecap="round" />
                    </svg>
                    <h2 class="counter">
                    <span data-target="47">0</span>%
                    </h2>
                    </div>
                    </div>
                    <div class="sk-title">
                    CSS 
                    </div>
                    </div>

                    <div class="skill">
                    <div class="outer-circle">
                    <div class="inner-circle">
                    <svg xlmns="http://www.w3.org/2000/svg" version="1.
                    1" width="180px" height="180px">
                    <defs>
                    <linearGradient id="GradientColor">
                    <Stop offset="0%" stop-color="#e91e63"/>
                    <stop offset="100%" stop-color="#673ab7"/>
                    </linearGradient>
                    </defs>
                    <circle cx="85" cy="85" r="75"
                    stroke-linecap="round" />
                    </svg>
                    <h2 class="counter">
                    <span data-target="56">0</span>%
                    </h2>
                    </div>
                    </div>
                    <div class="sk-title">
                     JavaScript   
                     </div>
                     </div>

                    <div class="skill">
                    <div class="outer-circle">
                    <div class="inner-circle">
                    <svg xlmns="https://www.w3.org/2000/svg" version="1.
                    1" width="180px" height="180px">.
                    <defs>
                    <linearGradient id="GradientColor">
                    <stop offset="0%" stop-color="#e91e63"/>
                    <stop offset="100%" stop-color="#673ab7">
                    </linearGradient>
                    </defs>
                    <circle cx="85" cy="85" r="75" stroke-linecap="round"/>
                    </svg>
                    <h2 class="counter">
                    <span data-target="19">0</span>%
                    </h2>
                    </div>
                    </div>
                    <div class="sk-title">
                    UI/UX Design
                    </div>
                    </div>
                    </div>
                    </div>
                    </div>
                    </div>
                    </section>

                    <footer>
                    <p>Copyright 2025 by<span> AISHWARYA  
                        </span> || SENIOR Developer.</p>
                    </footer>

                    <div id="progress">
                    <span id="progress-value">
                    <i class="bx bxs-chevrons-up"></i>
                    </span>
                    </div>
    <!-- scroll reveal  -->
    <script src="https://unpkg.com/scrollreveal"></script>
    <!-- Swiper JS -->
    <script src="https://cdn.jsdelivr.net/npm/swiper@10/swiper-bundle.min.js"></script>
    <!-- mixitup cdn js -->
    <script src="https://cdnjs.cloudflare.com/ajax/libs/mixitup/3.3.1/mixitup.min.js"></script>
    <script src="script.js"></script>
    </body>
    </html>
```
### responsive.css:
```

/*======================= @keyframes ============================ */

@keyframes moveText{
    0%,10%,100%{
        background-position: -24rem 0;
    }

    65%,85%{
        background-position: 0rem 0;
    }
}

@keyframes moveCursorText{
    0%,10%,100%{
        width: 0;
    }

    65%,78%,85%{
        width: 100%;
        opacity: 1;
    }

    75%,85%{
        opacity: 0;
    }
}

@keyframes animate{
    0%{
        transform: rotate(0deg);
    }
    100%{
        transform: rotate(360deg);
    }
}

@keyframes rotateText{
    0%{
        transform: rotate(360deg);
    }
    100%{
        transform: rotate(0deg);
    }
}

@keyframes progress{
   to{
    stroke-dashoffset: var(--target);
   }
}

@keyframes floatImage{
    0%{
        transform: translateY(0);
    }
    50%{
        transform: translateY(-22px);
    }
    100%{
        transform: translateY(0);
    }
}




/*======================= BrakPoints ============================ */

@media(max-width:1200px){
    html{
        font-size: 95%;
    }
}

@media(max-width:991px){
    header,section,footer{
        padding-left: 3%;
        padding-right: 3%;
    }
    .home,.portfolio-box{
        flex-direction: column-reverse;
    }
    .about,.contactSkills{
        flex-direction: column;
    }
    .about .about-img .aboutHero{
        width: 100%;
    }
    .proposal img{
        width: 52vw;
    }
    .portfolio-img img{
        width: 100%;
        height: 100%;
    }
    .portfolio-gallery{
        grid-template-columns: repeat(auto-fill,minmax(250px , 1fr));
    }
    .img-hero{
        margin-top: 1rem;
    }
}

@media(max-width:768px){
    .proposal{
        display: none;
    }
    .menu-icon .bar,.menu-icon::after,.menu-icon::before{
        display: block;
    }
    ul.navlist{
        position: absolute;
        top: -1000px;
        transition: all .3s ease;
        width: 100%;
        text-align: center;
        display: block;
        background: var(--gradient-white-bg);
        left: 0;
        border-top: 2px solid rgba(248, 202, 202, .7);
    }
    ul.navlist a{
        font-size: 1.5rem;
        margin: 1rem 0;
    }
    .navlist.active{
        top: 100%;
    }
    .overlay{
        width: 100vw;
        height: 100vh;
        top: 0;
        left: 0;
        position: fixed;
        background: rgba(0,0,0,0.5);
        z-index: 8;
        opacity: 0;
        transform: .3s;
        pointer-events: none;
    }
    body.open .overlay{
        opacity: 1;
        pointer-events: auto;
    }
    .btn{
        padding: 10px;
    }
    .home{
        grid-gap: 0;
    }
    .fillter-buttons button{
        padding: 10px;
        font-size: .8rem;
    }
}

.about-img .ring{
    position: absolute;
    top: 22%;
    right: 1%;
}

.about-img .circle{
    position: absolute;
    top: 0%;
    left: 0%;
}


.about-content{
    padding: 3rem 0;
}
.bg-icon span{
    position: absolute;
    width: 50px;
    height: 50px;
    background: var(--gradient-color-bg);
    border-radius: 50%;
    display: flex;
    align-items: center;
    justify-content: center;
    animation: animate 1s linear infinite;
}

.img-hero{
    position: relative;
    animation: floatImage 4s ease-in-out infinite;
    animation-delay: 3s;
}

.img-hero img{
    position: relative;
    width: 400px;
    height: auto;
    z-index: 20;
    padding-left: 10%;
    padding-top: 10%;
    padding-right: 10%;
    padding-bottom: 10%;

}

.rotate-text{
    position: absolute;
    top: 4%;
    left: -53px;
    display: flex;
    justify-content: center;
    align-items: center;
    overflow: hidden;
    padding: 2rem;
}

.skill{
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
}

.outer-circle{
    width: 170px;
    height: 170px;
    position: relative;
    margin-bottom: 1rem;
    padding: 20px;
    border-radius: 50%;
    box-shadow: rgba(50,50,93,0.25)0px 6px 12px -2px,
    rgba(0,0,0,0.3)0px 3px 7px -3px;
    display: flex;
    align-items: center;
    justify-content: center;
}

.inner-circle{
    width: 130px;
    height: 130px;
    border-radius: 50%;
    box-shadow: rgba(204,219,232)3px 3px 6px 0px inset,
    rgba(255,255,255,0.5)-3px -3px 6px 1px inset;
}
:root{
    --bg-color:#e3edf7;
    --gradient-white-bg:linear-gradient(0deg,#fff 0%,#edf4fa 51%,#e5eef7 100%);
    --gradient-color-bg:linear-gradient(180deg,rgba(247,1,120,1)0%,
                                                rgba(160,8,156,1)51%,
                                                rgba(99,13,178,1)100%);
    --main-color:#e6006d;
    --font-color:#90979f;
    --hover-box-shadow:rgba(0,0,0,0.19)0px 10px 20px,
                       rgba(0,0,0,0.23)0px 6px 6px;     
    --gradient-white-bg2:linear-gradient(98deg,#e5eef7 0%,#fff 100%);                                                          
}

.outer-circle svg{
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
}

.about-content h2{
    color: var(--main-color);
}

@media(max-width:530px){
    html{
        font-size: 80%;
    }
    section{
        padding: 50px 3%;
    }
    .contact-info form .input-box{
        display: block;
    }
    .input-box input {
        width: 100%;
    }
    .rotate-text{
        display: none;
    }
    .img-hero img{
        width: 100%;
    }
    .text-animate{
        width: 23.8rem;
    }
    .btn-box{
        width: 266px;
        margin-bottom: 3rem;
    }
    .about-btn button{
        padding: 10px 15px;
    }
    .fillter-buttons{
        display: grid;
        grid-gap: 1rem;
    }
    .fillter-buttons button{
        width: 100%;
        padding: 13px;
    }
}

.allServices{
    display: grid;
    grid-template-columns: repeat(auto-fit,minmax(220px , auto));
    align-items: center;
    gap: 2rem;
    position: relative;
    z-index: 1;
}

.servicesItem{
    box-shadow: rgba(0,0,0,0.1)0px 1px 3px 0,
                  rgba(0,0,0,0.06)0px 1px 2px 0px;
    padding: 2rem 1rem;
    border-radius: 10px;
    background: var(--gradient-white-bg2);
    text-align: center;
}

.icon-services{
    display: inline-flex;
    position: relative;
}

.icon-services i{
    box-shadow: rgba(0,0,0,0.1)0px 1px 3px 0,
                  rgba(0,0,0,0.06)0px 1px 2px 0px;
    padding: .5rem;
    border-radius: 50%;
    background: var(--gradient-color-bg);
    width: 70px;
    height: 70px;
    color: #fff;
    font-size: 2.5rem;
    display: inline-flex;
    justify-content: center;
    align-items: center;
    transition: .4s;
    z-index: 1;
}

.servicesItem:hover i{
    outline: 1px solid var(--main-color);
    transform: scale(1.2);
}

.icon-services span{
    position: absolute;
    width: 80px;
    height: 80px;
    left: -5px;
    top: -5px;
    background: var(--gradient-color-bg);
    border-radius: 50%;
    animation: animate 1s linear infinite;
}

.servicesItem h3{
    margin: 1rem 0 0.5rem;
}

.servicesItem p{
    margin-bottom: 1.5rem;
    font-size: .9rem;
    color: var(--font-color);
}

 .readMore{
    background: var(--gradient-white-bg2);
    box-shadow: rgba(0,0,0,0.1)0px 1px 3px 0,
                  rgba(0,0,0,0.06)0px 1px 2px 0px;
    padding: 10px 20px;
    border-radius: 5px;
    font-size: 1rem;
    font-weight: 500;
    color: #000;
    margin-right: .8rem;
    cursor: pointer;              
}

.navlist li{
    margin: 0 1rem;
}

.navlist li a{
    display: inline-flex;
    font-weight: 600;
}

.navlist li a:hover,.navlist li a.active{
    background: var(--gradient-color-bg);
    -webkit-background-clip: text;
    color: transparent;
}

.right-header{
    display: flex;
    align-items: center;
    justify-content: end;
    grid-gap: .8rem;
}

.btn{
    background: var(--gradient-color-bg);
    color: #fff;
    padding: 8px 10px;
    border-radius: 5px;
    font-weight: 500;
    transition: all .3s ease;
}

.btn:hover,.btn-box .d-CV:hover{
    box-shadow: var(--hover-box-shadow);
}

.menu-icon{
    position: relative;
    display: block;
    width: 30px;
    height: 30px;
    cursor: pointer;
    /* background: blue; */
}

.text-animate{
    width: 22.8rem;
    position: relative;
}

.social-media{
    display: flex;
    justify-content: space-between;
    width: 220px;
    height: 45px;
}

.social-media a{
    width: 42px;
    height: 42px;
    font-size: 1.5rem;
    color: var(--main-color);
    background: #fff;
    display: inline-flex;
    justify-content: center;
    align-items: center;
    transition: .4s;
    border-radius: 50%;
    z-index: 1;
}


.social-media a:hover{
    background: var(--gradient-color-bg);
    color: #fff;
}

.bg-icon{
    position: relative;
    display: flex;
    justify-content: center;
    align-items: center;
}

.rotate-text span{
    position: relative;
    width: 442px;
    height: 442px;
    background: red;
    border: 6px solid #eaeef0;
    border-radius: 50%;
    z-index: 1;
    overflow: hidden;
}

.text-animate h2{
    font-size: 2rem;
    font-weight: 700;
    margin-bottom: 1rem;
    color: transparent;
    -webkit-text-stroke: 0.1vw #770753;
    background: var(--gradient-color-bg);
    background-repeat: no-repeat;
    -webkit-background-clip: text;
    background-position: 0 0;
    transition: .6s;
    letter-spacing: 2px;
    animation: moveText 3s linear infinite;
    animation-delay: 2s;
}

.text-box p{
    font-size: 1.1rem;
    font-weight: 500;
}

.about-btn{
    margin: .8rem 0;
}

.about-btn button,.cvContent a{
    background: var(--gradient-white-bg2);
    padding: 10px 20px;
    border-radius: 5px;
    border: none;
    font-size: 1rem;
    font-weight: 500;
    color: #000;
    box-shadow: rgba(60,64,67,0.3)0px 1px 2px 0,
                  rgba(60,64,67,0.15)0px 2px 6px 2px;
    margin-right: .5rem;
    cursor: pointer;
    transition: all .3s ease;
}

.proposal{
    position: relative;
    display: flex;
    justify-content: space-between;
    align-items: center;
    width: 100%;
    background: var(--gradient-white-bg2);
    box-shadow: rgba(0,0,0,0.1)0px 1px 3px 0,
    rgba(0,0,0,0.06)0px 1px 2px 0px;
    margin-top: 8rem;
    border-radius: 10px;
    padding: 0rem 2rem;
    z-index: 1;
}

.proposal img{
    width: 40vw;
    height: auto;
    margin: -4rem 0 0;
    z-index: 2;
}

.services .text-box span{
    font-size: 1.2rem;
    font-weight: 600;
}

.services .text-box h3{
    margin-top: 1rem;
    margin-bottom: 2rem;
    font-size: 2.3rem;
    font-weight: 800;
}

.services .text-box .btn{
    padding: 10px 20px;
}


.services .showcase .ring{
    width: 100px;
    height: auto;
    position: absolute;
    top: 2%;
    left: -3%;
}


.about-btn button.active{
    background: var(--gradient-color-bg);
    color: #ffff;
}

.text-box{
    margin: .8rem 0;
}


.fillter-buttons button:hover,button.mixitup-control-active{
    background: var(--gradient-color-bg);
    color: #fff;
}

.portfolio-gallery{
    display: grid;
    grid-template-columns: repeat(auto-fill,minmax(370px , 1fr));
    gap: 1rem;
}

.portfolio-img img{
    display: block;
    width: 100%;
    height: 160px;
    transition: .3s;
}

.portfolio-box{
    display: flex;
    justify-content: space-between;
    align-items: center;
    gap: .5rem;
    padding: .5rem;
    box-shadow: rgba(0,0,0,0.18)0px 2px 4px;
    background: var(--gradient-white-bg2);
    border-radius: 10px;
    transition: all .3s ease;
}

.card img{
    width: 100%;
    height: 100%;
    object-fit: cover;
    transition: .3s;
    display: block;
}

.card:hover img{
    transform: scale(1.1);
}

.card-info{
    padding-bottom: .5rem;
}

.card-info h2{
    font-size: 1.2rem;
    margin-top: 1rem;
}

.data{
    display: block;
    margin: .2rem 0;
}

.card .excerpt{
    color: var(--font-color);
    margin-bottom: 1.5rem;
}

.swiper-pagination{
    position: relative !important;
    margin-top: 3rem;
}

.swiper-pagination-bullet{
    height: 10px !important;
    width: 30px !important;
    border-radius: 25px !important;
    background: var(--gradient-color-bg) !important;
}

.portfolio-content{
    width: 100%;
    padding-left: .5rem;
    padding-bottom: .5rem;
}

.portfolio-img{
    width: 100%;
    border-radius: 5px;
    overflow: hidden;
}
.contact-info form .input-box{
    display: flex;
    justify-content: space-between;
}

.input-box input{
    width: 49%;
}

form input:focus,form textarea:focus{
    filter: brightness(100%);
    background: #d2e9ff;
    border: 2px solid #f8caca;
}
```
### style.css:
```
    @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@100;200;300;400;500;600;700;800&display=swap');

    *{
        padding: 0;
        margin: 0;
        box-sizing: border-box;
        list-style: none;
        scroll-behavior: smooth;
    }

    a{
        text-decoration: none;
        color: #000;
    }

    body{
        font-family: 'Poppins', sans-serif;
        background: car(--bg-color);
        overflow-x: hidden;
    }

    header{
        padding: 15px 8%;
        width: 100%;
        position: fixed;
        top: 0;
        left: 0;
        display: flex;
        align-items: center;
        justify-content: space-between;
        background: var(--gradient-white-bg);
        z-index: 100;
        transition: .3s;
    }

    header.logo{
        font-size: 1.7rem;
        font-weight: 700;
    }
    span{
        background: var(--gradient-color-bg);
        -webkit-background-clip: text;
        color: transparent;
    }

    ul.navlist{
        display: flex;
    }

    .menu-icon .bar,
    .menu-icon::after,
    .menu-icon::before{
        content: "";
        display: none;
        width: 100%;
        height: 4px;
        border-radius: 3px;
        background: #000;
        margin: 6px 0;
        transition: .4s;
    }
    
    .menu-icon.active::before{
        transform: rotate(-45drg) translate(-6px, 6px);
    }

    .menu-icon.active::after{
        transform: rotate(45deg)translate(-8px, -8px);
    }

    .menu-icon.active .bar{
        opacity: 0;
    }

    /* =================== home section css code ============
    ======================*/

    section{
        padding: 90px 8%;
    }

    .home{
        min-height: 100vh;
        height: 100%;
        width: 100%;
        display: flex;
        grid-template-columns: repeat(2,1fr);
        align-items: center;
        grid-gap: 4em;
        background: var(--gradient-white-bg2);
    }

    .hero-info{
        margin-top: 3rem;
    }

    .hero-info h3{
        color: var(--font-color);
        font-weight: 300;
        text-transform: uppercase;
        font-size: 1.1rem;
    }

    .hero-info h1{
        font-size: 3.5rem;
    }

    .text-animate h2::before{
        content: "";
        position: absolute;
        top: 7px;
        left: -3px;
        width: 0;
        height: 70%;
        border-right: 2px solid var(--main-color);
        animation: moveCursorText 3s linear infinite;
        animation-delay: 2s;
    }

    .hero-info p{
        font-size: .9rem;
        color: var(--font-color);
        line-height: 1.rem;
    }

    .btn-box{
        display: flex;
        justify-content: space-between;
        width: 320px;
        margin-top: 2rem;
        margin-bottom: 6rem;
    }

    .btm-box .btn{
        padding: 10px;
        display: flex;
        align-items: center;
        justify-content: space-between;
        gap: 8px;
    }

    .btm-box .d-cv{
        background: var(--gradient-white-bg2);
        padding: 10px;
        border-radius: 5px;
        font-weight: 500;
        color: #000;
        box-shadow: rgba(60,64,67,0.3)0px 1px 2px 0,
                        rgba(60,64,67,0.15)0px 2px 6px 2px;
        transition: all .3s ease;
    }

    .rotate-text span::before{
        content: "";
        position: absolute;
        inset: 20px;
        background: #00aaff;
        border-radius: 50%;
        z-index: 1;
    }
        
    .rotate-text span i{
        position: absolute;
        inset: 0;
        background: var(--gradient-color-bg);
        filter: blur(5px);
        animation: animate 2s linear infinite;

    }
        
    .rotate-text .text{
        position: absolute;
        width: 490px;
        height: 490px;
        background: #f2f6fb;
        border-radius: 50%;
        box-shadow: 0 1px 6px 5.94px rgba(0,0,0,0.2);
        animation: rotateText 30s linear infinite;
    }

    .text b{
        position: absolute;
        transform-origin: 0 247px;
        display: block;
        top: 0;
        left: 50%;
        font-size: 1.2rem;
    }

    /*================================ About section CSS Code ======================
    ==============*/

    .about{
        display: flex;
        justify-content: space-between;
        align-items: center;
        gap: 1rem;
    }
        
    .about .about-img{
        postion: relative;
    }

    .about .about-img .aboutHero{
        width: 40vw;
        height: auto;
    }

    .about-content h3{
        font-size: 2.1rem;
        line-height: 3rem;
        margin: .5rem 0;
    }

    .about-content p{
        color: var(--font-color);
    }

    .content-btm > .content:not(:first-child){
        display: none;
    }

    .about-btn button:hover{
        box-shadow: var(--hover-box-shadow);
    }
    
    .cvContent{
        margin-top: 1.5rem;
    }

    /*============================ Services section css code ===============
    =================*/

    .services{
        position: relative;
    }

    .main-text{
        width: 100%;
        text-align: center;
        margin-bottom: 2rem;
    }

    .main-text .heading{
        color: var(--main-color);
    }

    .main-text span{
        color: var(--font-color);
        font-weight: 200;
        text-transform: uppercase;
    }

    .services .showcase .circle{
        position: absolute;
        width: 70px;
        height: auto;
        top: 2%;
        right: 6%;
        filter: blur(3px);
    }

    .services .showcase .circle2{
        position: absolute;
        width: 40px;
        height: auto;
        filter: blur(3px);
    }

    .services .showcase .circle3{
        position:absolute;
        width: 70px;
        height: auto;
        filter: blur(3px);
        bottom: 36%;
        left: 22%;
    }

    .services .showcase .half-ring{
        position: absolute;
        width: 120px;
        height: auto;
        bottom: 4%;
        right: 6%;
    }

    /*=========================== Services Section css code ========
    =============*/

    .fillter-buttons{
        text-align: center;
        padding: .5rem;
        margin-bottom: 2rem;
    }

    .fillter-buttons button{
        background: var(--gradient-white-bg2);
        padding: 12px 15px;
        border-radius: 5px;
        border: none;
        font-weight: 500;
        color: #000;
        box-shadow: rgba(60,64,67,0.3)0px 1px 2px 0,
        rgba(60,64,67,0.15)0px 2px 6px 2px;
        margin-right: .5rem;
        cursor: pointer;
        transition: all .3s ease;
    }

    .portfolio-box:hover img{
        transform: scale(1.1);
    }

    .portfolio-content a.readMore{
        padding: 8px 12px;
        font-size: .8rem;
    }

    .portfolio-content p{
        font-size: .9rem;
        color: var(--font-color);
        margin: .5rem 0 1rem 0;
    }

    /*=========================== Blog section css code =========
    ====================*/

    .blog-box{
        padding: .5rem !important;
    }

    .blog{
        position: relative;
    }

    .cards{
        padding: 1rem .1rem;
    }

    .card{
        background: var(--gradient-white-bg2);
        box-shadow: rgba(0,0,0,0.18)0px 2px 4px;
        padding: 1rem;
        border-radius: 10px;
    }

    .card-top{
        overflow: hidden;
        border-radius: 10px 10px 0 0;  
    }

    .blog .showcase img{
        position: absolute;
        width: 90px;
        height: 90px;
    }

    .blog .showcase .circle{
        filter: blur(3px);
    }

    .blog .showcase .ring{
        top: 0;
        left: -1%;
    }

    .blog .showcase .half-ring{
        top: 10%;
        right: 10%;
    }

    .blog .showcase .second-circle{
        top: 30%;
        left: 2%;
        filter: blur(1px);
    }

    /*============================== Contact section css code =========================
    =============================*/

    .contactSkills{
        display: flex;
        justify-content: space-between;
        gap 2rem;
    }

    .contact-info,.skills{
        width: 100%;
        background: var(--gradient-white-bg2);
        box-shadow: rgbs(0,0,0,0.18)0px 2px 4px;
        padding: 1rem;
        border-radius: 10px;
    }

    .contact-info input,
    .contact-info form textarea{
        width: 100%;
    }

    .contact-info form input,
    .contact-info form textarea{
        /* width: 100% */
        padding: .8rem;
        border: 2px solid #e8e1e1;
        margin: .5rem 0;
        background: "#e8f1f9";
        border-radius: 5px;
        outline: none;
        transition: .3s;
    }

    form textarea{
        resize: none;
    }

    form .btm{
        padding: 15px 20px;
        cursor: pointer;
        border: none;
    }

    /*======================== Skills Section CSS code ==========
    ===============*/

    .skillBox{
        padding: 0 1rem 1rem;
    }

    .skillBox .main-text{
        margin-bottom: 1 rem;
    }

    .skill-wrap{
        display: grid;
        grid-template-columns: repeat(auto-fit,minmax(150px , auto));
        justify-content: center;
        grid-gap: 2.5rem;    
    }

    .outer-circle svg circle{
        fill: none;
        stroke-width: 15px;
        stroke: url(#GradientColor);
        stroke-linecap: round;
        stroke-dasharray: 465;
        stroke-dashoffset: 464;

    }

    .outer-circle h2.counter{
        position: absolute;
        top: 50%;
        left: 50%;
        transform: translate(-50%, -50%);
        z-index: 1;
        font-size: .9rem;
        font-weight: 400;
    }

    h2.counter span{
        font-size: 1.7rem;
    }

    .sk-title{
        font-size: 1rem;
        font-weight: 500;

    }

    /*====================================== footer =============
    =====================*/

    footer{
        text-align: center;
        margin: 0.8%;
        padding: 2rem 0;
        border-top: 2px solid #e8e1e1;

    }

    #progress{
        position: fixed;
        /* background: #194eb9;*/
        z-index: 1000;
        bottom: 60px;
        right: 10px;
        width: 50px;
        height: 50px;
        display: none;
        place-items: center;
        border-radius: 50%;
        color: "#1d002c";
        cursor: pointer;
        box-shadow: rgba(50,50,93,0.25) 0px 50px 100px -20px,
        rgba(0,0,0,0.3)0px 30px 60px -30px,
        rgbs(10,37,64,0.35)0px -2px 6px 0px inset;
    }   

    #progress-value{
        display: grid;
        height: calc(100% - 12px);
        width: calc(100% -12px);
        background: var(--gradient-color-bg);
        border-radius: 50%;
        color: #fff;
        place-items: center;
        font-size: 25px;
    }
```
## OUTPUT
<img width="1766" height="837" alt="Screenshot 2025-08-11 233851" src="https://github.com/user-attachments/assets/20191857-0d0a-44a0-bbf8-e4acf0510410" />
<img width="1675" height="846" alt="Screenshot 2025-08-11 233930" src="https://github.com/user-attachments/assets/de8706ed-3d25-4593-8966-bee155f74611" />
<img width="1759" height="342" alt="Screenshot 2025-08-11 233943" src="https://github.com/user-attachments/assets/5f243bc2-5ec4-4e03-baec-735355fee5c4" />
<img width="1699" height="851" alt="Screenshot 2025-08-11 233956" src="https://github.com/user-attachments/assets/6bb4641e-5de5-47f7-9c17-de282e513c30" />
<img width="1754" height="458" alt="Screenshot 2025-08-11 234007" src="https://github.com/user-attachments/assets/bcd5e574-9a36-495f-b40c-f3318a14c408" />
<img width="1558" height="267" alt="Screenshot 2025-08-11 234015" src="https://github.com/user-attachments/assets/fe9b2e01-a517-4348-91cd-704d05f5f45f" />
<img width="1679" height="848" alt="Screenshot 2025-08-11 234026" src="https://github.com/user-attachments/assets/8b3ce395-d52b-473b-8cb0-04363f931815" />
<img width="1744" height="589" alt="Screenshot 2025-08-11 234037" src="https://github.com/user-attachments/assets/b0874268-1c22-45ea-92ec-06232bb25018" />

## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
