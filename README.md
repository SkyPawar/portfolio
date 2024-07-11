# portfolio
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Personal Portfolio Website - Easy Tutorials</title>
    <link rel="stylesheet" href="style.css">
    <script src="https://kit.fontawesome.com/c4254e24a8.js" crossorigin="anonymous"></script>
</head>

<body>
    <div id="header">
        <div class="container">
            <nav>
                <img src="images/logo.png" class="logo" />
                <ul id="sidemenu">
                    <li><a href="#header"><p style="font-size: 20px">Home</p></a></li>
                    <li><a href="#about"><p style="font-size: 20px">About</p></a></li>
                    <li><a href="#services"><p style="font-size: 20px">Services</p></a></li>
                    <li><a href="#portfolio"><p style="font-size: 20px">Portfolio</p></a></li>
                    <li><a href="#contact"><p style="font-size: 20px">Contact   </p></a></li>
                    <i class="fas fa-times" onclick="closemenu()"></i>
                </ul>
                <i class="fas fa-bars" onclick="openmenu()"></i>
            </nav>
            <div class="header-text">
                <p data-text="Web/Software Developer...">Web/Software Developer</p>
                <h1>Hi There.... I'm <span>Sky</span><br>From India</h1>
            </div>
        </div>
    </div>
    <!----------about---------->
    <div id="about">
        <div class="container">
            <div class="row">
                <div class="about-col-1">
                    <img src="images/user.png" />
                </div>
                <div class="about-col-2">
                    <h1 class="sub-title">About Me</h1>
                    <p>lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed nulla nibh,
                        tincidunt sit amet sapien quis, elementum molestie tellus. Pellentesque
                        habitant morbi tristique senectus et netus et malesuada fames ac turips
                        egesta. Mauris eleifend magna id ante convallis mattis. Quisque in sem
                        tristique, dictum sapien et, accumsan libero.</p>

                    <div class="tab-titles">
                        <p class="tab-links active-link " onclick="opentab('skills')">Skills</p>
                        <p class="tab-links" onclick="opentab('experience')">Experience</p>
                        <p class="tab-links" onclick="opentab('education')">Education</p>
                    </div>
                    <div class="tab-contents active-tab" id="skills">
                        <ul>
                            <li><span>UI/UX</span><br>Designing Web/App interfaces</li>
                            <li><span>Web Development</span><br>Web Applications development</li>
                            <li><span>Software Development</span><br>Software Developing with Secure Policy</li>
                        </ul>
                    </div>
                    <div class="tab-contents" id="experience">
                        <ul>
                            <li><span>2022 - Current</span><br>Software Certification training at IANT Institue</li>
                            <li><span>2019 - 2021</span><br>Working as a Sales Manager in Insurance Company</li>
                            <li><span>2018 - 2019</span><br>Working as a Tele-caller in Insurance Company</li>
                        </ul>
                    </div>
                    <div class="tab-contents" id="education">
                        <ul>
                            <li><span>Feb-2019</span><br>Completed Graduation in BCA From VNSGU</li>
                            <li><span>March-2014</span><br>Completed HSC Board (G.S.H.S.E.B) From Samrat International
                                School</li>
                            <li><span>March-2012</span><br>Completed SSC Board (G.S.E.B) From Karuna Sagar Vidhyalay
                            </li>
                        </ul>
                    </div>
                </div>
            </div>
        </div>
    </div>
    <!----------services---------->
    <div id="services">
        <div class="container">
            <h1 class="sub-title">My Services</h1>
            <div class="services-list">
                <div>
                    <i class="fas fa-code"></i>
                    <h2>Web Develpoment</h2>
                    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed nulla nibh,
                        tincidunt sit amet sapien quis.</p>
                    <a href="#">Learn more</a>
                </div>
                <div>
                    <i class="fas fa-crop-alt"></i>
                    <h2>UI/UX Design</h2>
                    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed nulla nibh,
                        tincidunt sit amet sapien quis.</p>
                    <a href="#">Learn more</a>
                </div>
                <div>
                    <i class="fab fa-app-store"></i>
                    <h2>Software Develpoment</h2>
                    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed nulla nibh,
                        tincidunt sit amet sapien quis.</p>
                    <a href="#">Learn more</a>
                </div>
            </div>
        </div>
    </div>
    <!----------portfolio---------->
    <div id="portfolio">
        <div class="container">
            <h1 class="sub-title">My Work</h1>
            <div class="work-list">
                <div class="work">
                    <img src="images/work-1.png" />
                    <div class="layer">
                        <h3>Social Media App</h3>
                        <p>The app connects you to the talented people around the world.
                            download it from Play store.</p>
                        <a href="#"><i class="fas fa-external-link-alt"></i></a>
                    </div>
                </div>
                <div class="work">
                    <img src="images/work-2.png" />
                    <div class="layer">
                        <h3>Music App</h3>
                        <p>The app connects you to the talented people around the world.
                            download it from Play store.</p>
                        <a href="#"><i class="fas fa-external-link-alt"></i></a>
                    </div>
                </div>
                <div class="work">
                    <img src="images/work-3.png" />
                    <div class="layer">
                        <h3>Online Shopping App</h3>
                        <p>The app connects you to the talented people around the world.
                            download it from Play store.</p>
                        <a href="#"><i class="fas fa-external-link-alt"></i></a>
                    </div>
                </div>
            </div>
            <a href="#" class="btn">See more</a>
        </div>
    </div>
    <!----------contact---------->
    <div class="contact">
        <div class="container">
            <div class="row">
                <div class="contact-left">
                    <h1 class="sub-title">Contact Me</h1>
                    <p><i class="fas fa-paper-plane"></i>psky78935@gmail.com</p>
                    <p><i class="fas fa-phone-square-alt"></i>9016771631</p>
                    <div class="social-icons">
                        <ul>
                            <li><a href="https://instagram.com/skyp_official"><i class="fa-brands fa-instagram instagram"></i></a></li>
                            <li><a href="https://WhatsApp.com/9016771631"><i class="fa-brands fa-whatsapp whatsapp"></i></a></li>
                            <li><a href="https://facebook.com/Skyp.official7"><i class="fa-brands fa-facebook-square facebook"></i></a></li>
                        </ul>
                    </div>
                    <a href="images/my-cv.docx" download class="btn btn2">Download CV</a>
                </div>
                <div class="contact-right">
                    <form>
                        <input type="text" name="Name" placeholder="Your Name" required>
                        <input type="email" name="Email" placeholder="Your Email" required>
                        <textarea name="Message" rows="6" placeholder="Your Message"></textarea>
                        <button type="submit" class="btn btn2">Submit</button>
                    </form>
                </div>
            </div>
        </div>
        <div class="copyright">
            <p>Copyright © skyp_official. Made by <i class="fas fa-heart"></i> SkyWalk Com. PVT LTD.</p>
        </div>
    </div>

    <script>
        var tablinks = document.getElementsByClassName("tab-links");
        var tabcontents = document.getElementsByClassName("tab-contents");

        function opentab(tabname) {
            for (tablink of tablinks) {
                tablink.classList.remove("active-link");
            }
            for (tabcontent of tabcontents) {
                tabcontent.classList.remove("active-tab");
            }
            event.currentTarget.classList.add("active-link");
            document.getElementById(tabname).classList.add("active-tab");
        }
    </script>

    <script>
        var sidemnu = document.getElementById("sidemenu");
        function openmenu(){
            sidemenu.style.right = "0";
        }
        function closemenu(){
            sidemenu.style.right = "-200px";
        }
    </script>

</body>

</html>

CSS Code :-

*{
    margin: 0;
    padding: 0;
    font-family: 'poppins', sans-serif;
    box-sizing: border-box;
}
html{
    scroll-behavior: smooth;
}
body{
    background: #080808;
    color: #fff;
}
#header{
    width: 100%;
    height: 100vh;
    background-image: url(images/background.png.jpeg);
    background-size: cover;
    background-position: center;
}
.container{
    padding: 6px 6%;
}
nav{
    display: flex;
    align-items: center;
    justify-content: space-between;
    flex-wrap: wrap;
}
.logo{
    width: 270px;
    height: 130px;
    margin-left: -60px;
}
nav ul li{
    display: inline-block;
    list-style: none;
    margin: 10px 20px;
}
nav ul li a{
    color: #080808;
    text-decoration: none;
    font-size: 18px;
    position: relative;
}
nav ul li a::after{
    content: '';
    width: 0%;
    height: 3px;
    background: #ff004f;
    position: absolute;
    left: 0;
    bottom: -6px;
    transition: 0.5s;
}
nav ul li a:hover::after{
    width: 100%;
}
.header-text{
    margin-top: 20%;
    font-size: 30px;
}
.header-text p{
    position: relative;
    font-size: 3vw;
    color: #fff;
    -webkit-text-stroke: 0.3vw #fff;
    text-transform: uppercase;
}
.header-text p::before{
    content: attr(data-text);
    position: absolute;
    top: 0;
    left: 0;
    width: 0;
    height: 100%;
    color: #133b53;
    -webkit-text-stroke: 0vw #8a4423;
    border-radius: 2px solid #134564;
    overflow: hidden;
    animation: animate 7s linear infinite;
}
@keyframes animate
{
    0%,10%,100%
    {
        width: 0;
    }
    70%,90%
    {
        width: 100%;
    }
}
.header-text h1{
    font-size: 60px;
    margin-top: 20px;
}
.header-text h1 span{
    color: #ff004f;
}
tabcontents
#about{
    padding: 80px 0;
    color: #ababab;
}
.row{
    display: flex;
    justify-content: space-between;
    flex-wrap: wrap;
}
.about-col-1{
    flex-basis: 35%;
}
.about-col-1 img{
    width: 100%;
    border-radius: 15px;
}
.about-col-2{
    flex-basis: 60%;
}
.sub-title{
    font-size: 60px;
    font-weight: 600;
    color: #fff;
}
.tab-titles{
    display: flex;
    margin: 20px 0 40px;
}
.tab-links{
    margin-right: 50px;
    font-size: 18px;
    font-weight: 500;
    cursor: pointer;
    position: relative;
}
.tab-links::after{
    content: '';
    width: 0;
    height: 3px;
    background: #ff004f;
    position: absolute;
    left: 0;
    bottom: -8px;
    transition: 0.5s;
}
.tab-links.active-link::after{
    width: 50%;  
}
.tab-contents ul li{
    list-style: none;
    margin: 10px 0;
}
.tab-contents ul li span{
    color: #b54769;
    font-size: 14px;
}
.tab-contents{
    display: none;
}
.tab-contents.active-tab{
    display: block;
}

/* ----------services---------- */
#services{
    padding: 30px 0;
}
.services-list{
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    grid-gap: 40px;
    margin-top: 50px;
}
.services-list div{
    background: #262626;
    padding: 40px;
    font-size: 13px;
    font-weight: 300;
    border-radius: 10px;
    transition: background 0.5s, transform 0.5s;
}
.services-list div i{
    font-size: 50px;
    margin-bottom: 30px;
}
.services-list div h2{
    font-size: 30px;
    font-weight: 500;
    margin-bottom: 15px;
}
.services-list div a{
    text-decoration: none;
    color: #fff;
    font-size: 12px;
    margin-top: 20px;
    display: inline-block;
}
.services-list div:hover{
    background: #ff004f;
    transform: translateY(-10px);
}

/* ----------portfolio---------- */
#portfolio{
    padding: 50px 0;
}
.work-list{
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    grid-gap: 40px;
    margin-top: 50px;    
}
.work{
    border-radius: 10px;
    position: relative;
    overflow: hidden;
}
.work img{
    width: 100%;
    border-radius: 10px;
    display: block;
    transition: transform 0.5s;
}
.layer{
    width: 100%;
    height: 0%;
    background: linear-gradient(rgba(0,0,0,0.6), #ff004f);
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
    font-size: 14px;
    transition: height 0.5s;
}
.layer h3{
    font-weight: 500;
    margin-bottom: 20px;
}
.layer a{
    margin-top: 20px;
    color: #ff004f;
    text-decoration: none;
    font-size: 18px;
    line-height: 60px;
    background: #fff;
    width: 60px;
    height: 60px;
    border-radius: 50%;
    text-align: center;
}
.work:hover img{
    transform: scale(1.1);
}
.work:hover .layer{
    height: 100%;
}
.btn{
    display: block;
    margin: 50px auto;
    width: fit-content;
    border: 1px solid #ff004f;
    padding: 14px 50px;
    border-radius: 6px;
    text-decoration: none;
    color: #fff;
    transition: background 0.5s;
}
.btn:hover{
    background: #ff004f;
}

/* ----------contact---------- */
.contact-left{
    flex-basis: 35%;
}
.contact-right{
    flex-basis: 60%;
}
.contact-left p{
    margin-top: 30px;
}
.contact-left p i{
    color: #ff004f;
    margin-right: 15px;
    font-size: 25px;
}
.social-icons{
    margin-top: 30px;
}
.social-icons ul{
    position: relative;
    display: flex;
}
.social-icons ul li{
    position: relative;
    list-style: none;
    margin: 0 20px;
    cursor: pointer;
}
.social-icons ul li a{
    text-decoration: none;
}
.social-icons ul li a .fa-brands{
    font-size: 4em;
    color: #222;
}
.social-icons ul li::before{
    font-family: "FontAwesome";
    position: absolute;
    top: 0;
    left: 0;
    font-size: 4em;
    height: 0;
    overflow: hidden;
    transition: 0.5s ease-in-out;
}
.social-icons ul li:nth-child(1)::before{
    content: "\f16d";
    background-image: linear-gradient(45deg, #f09433 0%, #e6683c 25%, #dc2743 50%, #cc2366 75%, #bc1888 100%);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    border-bottom: 4px solid #dc2743;
}
.social-icons ul li:nth-child(2)::before{
    content: "\f232";
    color: #25d366;
    border-bottom: 4px solid #25d366;
}
.social-icons ul li:nth-child(3)::before{
    content: "\f082";
    color: #1da1f2;
    border-bottom: 4px solid #1da1f2;
}
.social-icons li:hover::before{
    height: 100%;
}
/* .social-icons a{
    text-decoration: none;
    font-size: 30px;
    margin-right: 15px;
    color: #ababab;
    display: inline-block;
    transition: transform 0.5s;
}
.social-icons a:hover{
    color: #ff004f;
    transform: translateY(-5px);
} */
.btn.btn2{
    display: inline-block;
    background: #ff004f;
}
.contact-right form{
    width: 100%;
}
form input, form textarea{
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
form .btn2{
    padding: 14px 60px;
    font-size: 18px;
    margin-top: 20px;
    cursor: pointer;
}
.copyright{
    width: 100%;
    text-align: center;
    padding: 25px;
    background: #262626;
    font-weight: 300;
    margin-top: 20px;
}
.copyright i{
    color: #ff004f;
}

/* ----------CSS for small screens---------- */
nav .fas{
    display: none;
}

@media only screen and (max-width: 600px){
    #header{
        background-image: url(images/phone-background.png);
    }
    .header-text{
        margin-top: 100%;
        font-size: 16px;
    }
    .header-text h1{
        font-size: 30px;
    }
    nav .fas{
        display: block;
        font-size: 25px;
    }
    nav ul{
        background: #ff004f;
        position: fixed;
        top: 0;
        right: -200px;
        width: 200px;
        height: 100vh;
        padding-top: 50px;
        z-index: 2;
        transition: right 0.5s;
    }
    nav ul li{
        display: block;
        margin: 25px;
    }
    nav ul .fas{
        position: absolute;
        top: 25px;
        left: 25px;
        cursor: pointer;
    }
    .sub-title{
        font-size: 40px;
    }
    .about-col-1, .about-col-2{
        flex-basis: 100%;
    }
    .about-col-1{
        margin-bottom: 30px;
    }
    .about-col-2{
        font-size: 14px;
    }
    .tab-links{
        font-size: 16px;
        margin-right: 20px;
    }
    .contact-left, .contact-right{
        flex-basis: 100%;
    }
    .copyright{
        font-size: 14px;
    }
}
