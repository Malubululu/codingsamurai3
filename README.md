<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Personal Portfolio Website</title>
    <link rel="stylesheet" href="style.css">
    <script src="https://kit.fontawesome.com/e674bba739.js" crossorigin="anonymous"></script>
</head>

<body>
    <div id="header">
        <div class="container">
            <nav>
                <img src="logo SD.png" class="logo"></img>
                <ul>
                    <li><a href="#">Home</a></li>
                    <li><a href="#">About</a></li>
                    <li><a href="#">Services</a></li>
                    <li><a href="#">Portfolio</a></li>
                    <li><a href="#">Contact</a></li>
                    <i class="fas fa-times"></i>
                </ul>
                <i class="fas fa-bars"></i>
            </nav>
            <div class="header-text">
                <p>Software Developer</p>
                <h1>Hi, I'm <span>Somesh Mishra </span><br>from odisha,India</h1>
            </div>
        </div>
    </div>
    <!-- ----------ABOUT---------- -->
    <div id="about">
        <div class="container">
            <div class="row">
                <div class="about-col-1">
                    <img src="C:\Users\ASUS\Downloads">
                </div>
                <div class="about-col-2">
                    <h1 class="sub-title">About Me</h1>
                    <p> 
                    Hello Everyone! My self 'Somesh MIshra'
                    I am a student studying at trident academy of technology, Bhubaneswar.I'm a person with a strong interest in software development and am very ambitious and motivated. 
                        Through both academic and personal projects, I have improved my skills in Java programming, html, css, javascript
                        and frameworks. I have an innate ability for picking things up quickly and I enjoy adjusting to new technologies.
                        My strategy is built around problem-solving, and I relish taking on difficult tasks. 
                        In addition to my technical abilities, I also work well in teams and have excellent communication skills. 
                        I am eager to contribute my abilities, advance professionally, and have a positive influence on the business 
                        as I look for an entry-level career in software development.</p>
                    <div class="tab-titles">
                        <p class="tab-links active-link" onclick="openTab('skills')">Skills</p>
                        <p class="tab-links" onclick="openTab('experience')">Experiance</p>
                        <p class="tab-links" onclick="openTab('education')">Education</p>
                    </div>
                    <div class="tab-contents active-tab" id="skills">
                        <ul>
                            <li><span>Java</span><br>Object Oriented Programming, Core Java</li>
                            <li><span>DBMS and SQL</span><br>Sql queries, Normalization, DDL and DML</li>
                            <li><span>Web Development</span><br>Web Programming , Web Design</li>
                        </ul>

                    <div class="tab-contents" id="education">
                        <ul>
                            <li><span>2021-25</span><br>Btech computer science Engineering with AIML Trident Academy Of Technology,BBSR (continuing)</li>
                            <li><span>2020-21</span><br>HSC 12th Narasinghpur college,ctc,odiha india</li>
                            <li><span>2018-19</span><br>chse 10th A.N.H.S,CTC,ODISHA,INDIA</li>
                        </ul>
                    </div>
                </div>
            </div>
        </div>
    </div>
    <!-- ----------SERVICES---------- -->
    <div id="services">
        <div class="container">
            <h1 class="sub-title">My Services</h1>
            <div class="services-list">
                <div>
                    <i class="fa-solid fa-code"></i>
                    <h2>Web Development</h2>
                    <p>Navigate the world of web technology, where I create dynamic, responsive websites utilizing state-of-the-art 
                        coding methods. Learn more about my passion for developing dependable and user-friendly web solutions.
                    </p>
                    <a href="#">Learn more</a>

                </div>
                <div>
                    <i class="fa-solid fa-crop-simple"></i>
                    <h2>UI/UX Design</h2>
                    <p>Experience how I apply creativity and user-centered design concepts to create visually appealing interfaces and 
                        seamless user experiences as I demonstrate the art of UI/UX design. Learn more about how I turn concepts into 
                        visually stunning digital designs.
                    </p>
                    <a href="#">Learn more</a>
                </div>
                <div>
                    <i class="fa-brands fa-android"></i>
                    <h2>App Development</h2>
                    <p>Explore the world of mobile applications by developing innovative user-friendly apps for a variety of demands using 
                        your knowledge in Android development. Find out more about how I transform concepts into useful and 
                        interesting mobile experiences.
                    </p>
                    <a href="#">Learn more</a>
                </div>
            </div>
        </div>
    </div>
    <!-- ----------PORTFOLIO--------- -->
    <div id="portfolio">
        <div class="container">
            <h1 class="sub-title">My Works</h1>
            <div class="work-list">
                <div class="work">
                    <img src="Screenshot (3).png" alt="">
                    <div class="layer">
                        <h2>calculator  Project</h2>
                        <p>designed and built an basic calculator This project allowed me to dive deep into HTML, CSS, and JavaScript, and I've built a versatile calculator that can handle all arithmetic calculations. 🧮

                        </p>
                        <a href="#"><i class="fas fa-external-link-alt"></i></a>
                    </div>
                </div>
                <div class="work">
                    <a href="http://127.0.0.1:5500/CSS/LOGIN%20PROJECT%20NO%206%20(COPY).html"></a>
                    <img src="Screenshot (1).png" alt="">
                    <div class="layer">
                        <h2>flipkart login Clone Project</h2>
                        <p>developed an flipkart clone login page by using html css JavaScript .
                        </p>
                        <a href="#"><i class="fas fa-external-link-alt"></i></a>
                    </div>
                </div>
                <div class="work">
                    <img src="Screenshot (2).png" alt="">
                    <div class="layer">
                        <h2>Student Login Page Project</h2>
                        <p>created a student ,parent ,and childerance login page by using html css JavaScript. 
                        </p>
                        <a href="#"><i class="fas fa-external-link-alt"></i></a>
                    </div>
                </div>
            </div>
            <a href="" class="btn">See more</a>
        </div>
    </div>

    <!-- ----------CONTACT---------- -->
    <div id="contact">
        <div class="container">
            <div class="row">
                <div class="contact-left">
                    <h1 class="sub-title">Contact Me</h1>
                    <p><i class="fas fa-paper-plane"></i> sm666950@gmail.com</p>
                    <p><i class="fas fa-phone-square-alt"></i> +916371166061</p>
                    <div class="social-icons">   
                        <a href="https://www.linkedin.com/in/somesh-mishra-559234224?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app "><i class="fab fa-linkedin"></i></a>
                        <a href=" https://instagram.com/s_mishra_12?igshid=NTc4MTIwNjQ2YQ=="><i class="fab fa-instagram"></i></a>
                    </div>
                    <a href="NEW... CV.... Smishra" download class="btn btn2">Download Resume</a>
                </div>
                <div class="contact-right">
                    <!-- Add the action and method attributes to the form -->
                    <form action="contact_form.php" method="POST">
                        <input type="text" name="Name" placeholder="Your Name" required>
                        <input type="email" name="Email" placeholder="Your Email" required>
                        <textarea name="Message" rows="6" placeholder="Your Message"></textarea>
                        <button type="submit" class="btn btn3">Submit</button>
                    </form>
                </div>
                
        </div>
        <div class="copyright">
            <p>Made with <i class="fas fa-heart"></i> by Somesh Mishra</p>
        </div>
    </div>
<style>
* {
    margin: 0;
    padding: 0;
    font-family: 'Poppins', sans-serif;
    box-sizing: border-box;
}

body {
    background: #080808;
    color: #fff;
}

#header {
    width: 100%;
    height: 100vh;
    background-image: url(images/img1.png);
    background-size: cover;
    background-position: center;
}

.container {
    padding: 10px 10%;
}

nav {
    display: flex;
    align-items: center;
    justify-content: space-between;
    flex-wrap: wrap;
}

.logo {
    width: 140px;
}

nav ul li {
    display: inline-block;
    list-style: none;
    margin: 10px 20px;
}

nav ul li a {
    color: #fff;
    text-decoration: none;
    font-size: 18px;
    position: relative;
}

nav ul li a::after {
    content: '';
    width: 0;
    height: 3px;
    background: #ff004f;
    position: absolute;
    left: 0;
    bottom: -6px;
    transition: 0.5s;
}

nav ul li a:hover::after {
    width: 100%;
}

.header-text {
    margin-top: 20%;
    font-size: 20px;
}

.header-text h1 {
    font-size: 60px;
    margin-top: 20px;
}

.header-text h1 span {
    color: #ff004f;
}

/* ----------ABOUT---------- */
#about {
    padding: 80px 0px;
    color: #ababab;
}

.row {
    display: flex;
    justify-content: space-between;
    flex-wrap: wrap;
}

.about-col-1 {
    flex-basis: 35%;
}

.about-col-1 img {
    width: 100%;
    border-radius: 15px;
}

.about-col-2 {
    flex-basis: 60%;
}

.sub-title {
    font-size: 60px;
    font-weight: 600;
    color: #fff;
}

.tab-titles {
    display: flex;
    margin: 20px 0 40px;
}

.tab-links {
    margin-right: 50px;
    font-size: 18px;
    font-weight: 500;
    cursor: pointer;
    position: relative;
}

.tab-links::after {
    content: '';
    width: 0;
    height: 3px;
    background: #ff004f;
    position: absolute;
    left: 0;
    bottom: -8px;
    transition: 0.5s;
}

/* .tab-links:hover::after{
width: 100%;
} */
.tab-links.active-link::after {
    width: 50%;
}

.tab-contents ul li {
    list-style: none;
    margin: 10px 0;
}

.tab-contents ul li span {
    color: #b54768;
    font-size: 14px;
}

.tab-contents {
    display: none;
}

.tab-contents.active-tab {
    display: block;
}

/* ----------SERVICES---------- */
#services {
    padding: 30px 0;
}

.services-list {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    grid-gap: 40px;
    margin-top: 50px;
}

.services-list div {
    background: #262626;
    padding: 40px;
    font-size: 15px;
    line-height: 30 px;
    font-weight: 300;
    border-radius: 10px;
    transition: background 0.5s, transform 0.5s;
}

.services-list div i {
    font-size: 50px;
    margin-bottom: 30px;
}

.services-list div h2 {
    font-size: 30px;
    font-weight: 500;
    margin-bottom: 15px;
}

.services-list div a {
    text-decoration: none;
    color: #fff;
    font-size: 14px;
    margin-top: 20px;
    display: inline-block;
}

.services-list div:hover {
    background: #ff004f;
    transform: translateY(-10px);
}

/* ----------PORTFOLIO---------- */
#portfolio {
    padding: 50px 0;
}

.work-list {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    grid-gap: 40px;
    margin-top: 50px;
}

.work {
    border-radius: 10px;
    position: relative;
    overflow: hidden;
}

.work img {
    width: 100%;
    border-radius: 10px;
    display: block;
    transition: transform 0.5s;
}

.layer {
    width: 100%;
    height: 0;
    background: #ff004f;
    border-radius: 10px;
    position: absolute;
    left: 0;
    bottom: 0;
    overflow: hidden;
    display: flex;
    align-items: center;
    justify-content: center;
    flex-direction: column;
    padding: 0 40px;
    text-align: center;
    font-size: 16px;
    transition: height 0.5s;
}

.layer h2 {
    margin-bottom: 30px;
}

.layer a {
    margin-top: 30px;
    color: #080808;
    text-decoration: none;
    font-size: 18px;
    line-height: 60px;
    background: #fff;
    width: 60px;
    height: 60px;
    border-radius: 50%;
    text-align: center;
}

.work:hover img {
    transform: scale(1.1);
}

.work:hover .layer {
    height: 100%;
}

.btn {
    display: block;
    margin: 50px auto;
    width: fit-content;
    border: 1px solid #ff004f;
    padding: 14px 50px;
    border-radius: 6px;
    color: #fff;
    text-decoration: none;
    transition: background 0.75s;
}

.btn:hover {
    background: #ff004f;
}

/* ----------CONTACT---------- */
.contact-left {
    flex-basis: 35%;
}

.contact-right {
    flex-basis: 60%;
}

.contact-left p {
    margin-top: 30px;
}

.contact-left p i {
    color: #ff004f;
    margin-right: 15px;
    font-size: 25px;
}

.social-icons {
    margin-top: 30px;
}

.social-icons a {
    text-decoration: none;
    font-size: 30px;
    margin-right: 15px;
    color: #ababab;
    display: inline-block;
    transition: color 0.5s, transform 0.5s;
}

.social-icons a:hover {
    color: #ff004f;
    transform: translateY(-5px);
}

.btn.btn2 {
    display: inline-block
}

.btn.btn3 {
    background: #080808;
    margin-top: 30px;
    transition: background 0.5;

}

.btn.btn3:hover {
    background: #ff004f;
}

.contact-right form {
    width: 100%;
}

form input,
form textarea {
    width: 100%;
    border: 0;
    outline: none;
    background: #262626;
    padding: 15px;
    margin: 15px 0;
    color: #fff;
    font-size: 18px;
    border-radius: 6px;
}

.copyright {
    width: 100%;
    text-align: center;
    padding: 25px 0;
    background: #262626;
    font-weight: 300;
    margin-top: 20px;
}

.copyright i {
    color: #ff004f;
    transition: color 0.5s;
}

.copyright i:hover {
    color: #fff;
}

nav .fas {
    display: none;
}

/* ----------CSS FOR SMALL SCREEN---------- */
@media only screen and (max-width: 600px) {
    #header {
        background-image: url(images/phone-background.png);
    }

    .header-text {
        margin-top: 100%;
        font-size: 16px;
    }

    .header-text h1 {
        font-size: 30px;
    }

    nav .fas {
        display: block;
        font-size: 25px;
    }

    nav ul {
        background: #b54768;
        position: fixed;
        top: 0;
        width: 200;
        right: 0;
        height: 100vh;
        padding-top: 50px;
    }

    nav ul li {
        display: block;
        margin: 25px;
    }

}

/* ----------CSS FOR SMALL SCREEN---------- */
@media only screen and (max-width: 600px) {

    /* Adjust the header image and text size for small screens */
    #header {
        background-image: url(images/phone-background.png);
    }

    .header-text {
        margin-top: 100%;
        font-size: 16px;
    }

    .header-text h1 {
        font-size: 30px;
    }

    /* Show the navigation menu on small screens */
    nav ul {
        display: none;
    }

    nav .fas {
        display: block;
        font-size: 25px;
    }

    nav ul {
        background: #b54768;
        position: fixed;
        top: 0;
        width: 200px;
        /* Increased the width to accommodate the menu items */
        right: 0;
        height: 100vh;
        padding-top: 50px;
        transform: translateX(200px);
        /* Off-canvas menu, initially hidden */
        transition: transform 0.3s ease-in-out;
    }

    nav ul.show {
        transform: translateX(0);
        /* Show the menu when 'show' class is applied */
    }

    nav ul li {
        display: block;
        margin: 25px;
    }
}</style>


    <script>
        var tabLinks = document.getElementsByClassName('tab-links');
        var tabContents = document.getElementsByClassName('tab-contents');

        function openTab(tabName) {
            for (tabLink of tabLinks) {
                tabLink.classList.remove('active-link');
            }
            for (tabContent of tabContents) {
                tabContent.classList.remove('active-tab');
            }
            event.currentTarget.classList.add('active-link');
            document.getElementById(tabName).classList.add('active-tab');
        }

        // JavaScript for handling the mobile navigation menu
        document.querySelector('.fas.fa-bars').addEventListener('click', function () {
            document.querySelector('nav ul').classList.toggle('show');
        });

        document.querySelector('.fas.fa-times').addEventListener('click', function () {
            document.querySelector('nav ul').classList.remove('show');
        });

    </script>
</body>

</html>
