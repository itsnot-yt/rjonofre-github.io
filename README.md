<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.7.1/css/all.min.css">
    <title>Rodolfo Jose Pinlac Onofre</title>
    <link rel="stylesheet" href="style.css">
    <link rel="stylesheet" href="https://unpkg.com/aos@next/dist/aos.css" />
</head>
<body>
    <nav>
        <div class="nav-container">
            <div class="logo" data-aos="zoom-in" data-aos-duration="1000">
                <span>Rodolfo Jose Onofre</span>
            </div>
            <div class="links">
                <div class="link" data-aos="fade-up" data-aos-duration="1000" data-aos-delay="100"><a href="#">Home</a></div>
                <div class="link" data-aos="fade-up" data-aos-duration="1000" data-aos-delay="200"><a href="#">About</a></div>
                <div class="link" data-aos="fade-up" data-aos-duration="1000" data-aos-delay="300"><a href="#">Skills</a></div>
                <div class="link contact-btn" data-aos="fade-up" data-aos-duration="1000" data-aos-delay="600"><a href="#">Contact Me</a></div>
            </div>
            <i class="fa-solid fa-bars hamburg" onclick="hamburg()"></i>
        </div>
        <div class="dropdown">
            <div class="links">
                <a href="">Home</a>
                <a href="">About</a>
                <a href="">Skills</a>
                <a href="">Contact Me</a>
                <i class="fa-solid fa-xmark cancel" onclick="cancel()"></i>
            </div>
        </div>
    </nav>
        <section>
            <div class="main-container">
                <div class="image" data-aos="zoom-in-right" data-aos-duration="2500">
                    <img src="https://github.com/itsnot-yt/rjonofre-github.io/blob/eb0c8f35a28515cc556d58078fc5a62977538df1/main.jpg"alt="">
                </div>
                <div class="content">
                    <h1 data-aos="fade-left" data-aos-duration="1000" data-aos-delay="800">Hello, I'm <span>Rodolfo Jose Onofre</span></h1>
                    <div class="typewriter" data-aos="fade-right" data-aos-duration="1000" data-aos-delay="900">I'm a <span></span></div>
                    <p data-aos="flip-up" data-aos-duration="1000" data-aos-delay="1000">Currently a 4th year Computer Engineering Student at Don Honorio Ventura State University</p>
                    <span></span>
                    <span></span>
                   
                    
                    
                    <p>Contact Me</p>
                    <p>Email: cpe.rodolfojoseonofre@gmail.com</p>
                    <p>Contact Number: +63 969 064 6295</p>
                    <div class="social-links" data-aos="flip-down" data-aos-duration="1000" data-aos-delay="1200">
                        <a href="#" ><i class="fa-brands fa-github"></i></a>
                        <a href="#"><i class="fa-brands fa-facebook"></i></a>
                        <a href="#"><i class="fa-brands fa-linkedin"></i></a>
                        <a href="#"><i class="fa-brands fa-x-twitter"></i></a>
                    </div>
                    <div class="btn" data-aos="zoom-out-left" data-aos-duration="1000" data-aos-delay="1300">
                        <button>Download CV</button>
                    </div>
                </div>
            </div>
        </section>
        <script src="https://unpkg.com/aos@next/dist/aos.js"></script>
        <script>
          AOS.init({offset:0});
        </script>
        <script>
            function hamburg(){
                const navbar = document.querySelector(".dropdown")
                navbar.style.transform = "translateY(0px)"
            }
            function cancel(){
                const navbar = document.querySelector(".dropdown")
                navbar.style.transform = "translateY(-500px)"
            }
        </script>
</body>
</html>
