index.html
<!DOCTYPE html>
<html lang = "en">
<head>
    <meta charset = "UTF-8>
    <meta http-equiv = "X-UA-Compatible" content = "IE=edge">
    <meta name = "viewport" content = "width=device-width,initial-scale=1.0">
    <title>SANMAR PROJECTS</title>
    <style>
        body {
          margin-left: 20px; /* Adjust the left margin as needed */
          margin-right: 20px; /* Adjust the right margin as needed */
        }
      </style>
    <link rel = "stylesheet" href = "style.css">
    <script src="https://kit.fontawesome.com/ef1afd39ac.js" crossorigin="anonymous"></script>
</head>
<body>
    <div id = "header">
        <div class = "container">
            <nav>
                <img src = "images/logo.png" class = "logo">
                <ul id = "sidemenu">
                    <li><a href="#header">HOME</a></li>
                    <li><a href="#about">ABOUT</a></li>
                    <li><a href="#certifications">CERTIFICATIONS</a></li>
                    <li><a href="#portfolio">PROJECTS</a></li>
                    <li><a href="#contact">CONTACT</a></li>
                    <i class="fa-solid fa-circle-xmark" onclick = "closemenu()"></i>
                </ul>
                <i class="fa-solid fa-bars" onclick = "openmenu()"></i>
            </nav>
            <div class = "header-text">
                <p>An Aspiring Engineer</p>
                <h1><span>Santhoshkumar</span><br>Anbalagan's Portfolio</h1>
            </div>
        </div>
    </div>
    <div id = "about">
        <div class = "container">
            <div class = "row">
                <div class = "about-col-1">
                    <img src = "images/background2.jpg">
                </div>
                <div class = "about-col-2">
                    <h1 class="sub-title">ABOUT ME</h1>
                    <br>
                    <p>
                        🚀 Final Year ECE Student | Future-Forward Tech Enthusiast | Aspiring Entrepreneur
                    </p>
                    <br>
                    <p>
                        Greetings! I'm Santhoshkumar Anbalagan, a dynamic and forward-thinking Electronics and Communication Engineering (ECE) student in my final year at Sastra University. My academic journey has been a thrilling exploration of cutting-edge technologies, and my passion lies at the intersection of Entrepreneurship and Futuristic Innovations.
                    </p>
                    <br>
                    <p>
                        🔍 Extensive Expertise in Futuristic Technologies:
                    </p>
                    <br>
                    <p>
                        🌐 Passion for Future Tech and Entrepreneurship:
                    </p>
                    <br>
                    <p>
                        I'm not just a student; I'm a tech visionary and aspiring entrepreneur. My enthusiasm extends beyond the classroom, evident in my engagements:
                    </p>
                    <br>
                    <p>
                        🔮 Future-Focused Innovation:
                    </p>
                    <br>
                    <p>
                        My vision extends to creating technologies that define the future. Whether it's integrating Blockchain into secure systems, developing cloud-based solutions, or crafting the next-generation humanoid robot using Arduino and Raspberry Pi, I'm dedicated to pushing the boundaries of what's possible.
                    </p>
                    <br>
                    <p>
                        🚀 Why Connect?
                    </p>
                    <br>
                    <p>
                        I am actively seeking opportunities to collaborate on projects, engage in discussions about the latest tech trends, and explore potential partnerships. Let's connect and explore the limitless possibilities at the intersection of technology, entrepreneurship, and future-forward innovation.Let's redefine the future together!
                    </p>
                </div>
            </div>
        </div>
    </div>
    <div id = "about">
        <div class = "container">
            <div class = "row">
                <div class = "about-col-1">
                    <img src = "images/background3.jpg">
                </div>
                <div class = "about-col-2">
                    <h1 class="sub-title">KNOWN FOR</h1>
                    <br>
                    <p>
                        I possess a formidable skill set coupled with a robust educational background, making me a well-rounded and capable professional. My academic journey has equipped me with a solid foundation in evolving technologies. I have actively pursued internships, where I honed practical skills and gained valuable hands-on experience.With a blend of academic excellence and practical exposure, I am confident in my ability to contribute effectively and thrive in challenging professional environments.
                    </p>
                    <br>
                    <div class = "tab-titles">
                        <p class = "tab-links active-link" onclick = "opentab('skills')">SKILLS</p>
                        <p class = "tab-links" onclick = "opentab('internships')">INTERNSHIPS</p>
                        <p class = "tab-links" onclick = "opentab('education')">EDUCATION</p>
                    </div>
                    <div class = "tab-contents active-tab" id = "skills">
                        <ul>
                            <li><span>Full stack</span><br>Web-development</li>
                            <li><span>Cloud</span><br>Computing</li>
                            <li><span>Product</span><br>Management</li>
                            <li><span>UI/UX</span><br>Designing Web/App interfaces</li>
                            <li><span>And more......</span><br></li>
                        </ul>
                    </div>
                    <div class = "tab-contents" id = "internships">
                        <ul>
                            <li><span>IIT-Bombay</span><br>Campus Executive(E-Cell)</li>
                            <p>
                                As a Campus Executive intern at IIT Bombay's Entrepreneurship Cell (E-Cell). My role  is mostly organizing events, workshops, and networking sessions to promote entrepreneurial spirit among students. I will learn certain things from industry professionals, and fellow students to create a vibrant ecosystem that encourages idea generation and business development. This internship at IIT Bombay's E-Cell provides me with a unique opportunity to gain practical experience in entrepreneurship, connect with influential figures in the industry, and contribute to the growth of the entrepreneurial community within the prestigious institute.
                            </p>
                            <li><span>Intrainz</span><br>Campus Ambassador</li>
                        </ul>
                    </div>
                    <div class = "tab-contents" id = "education">
                        <ul>
                            <li><span>2018</span><br>SSLC at R.Dhaynithi memorial vidyasala matriculation school<br>Grade:-88.8%</li>
                            <li><span>2020</span><br>HSC at Dhanalakshmi Srinivasan maticulation higher secondary school<br>Grade:-76.5%</li>
                            <li><span>2024</span><br>B.Tech at SASTRA University<br>Cgpa:-6.7122</li>
                        </ul>
                    </div>
                </div>    
            </div>        
        </div>            
    </div> 
    <div id = "certifications">
        <div class = "container">
            <h1 class="sub-title">MY CERTIFICATIONS</h1>
            <div class = "certifications-list">
                <div>
                    <i class="fa-solid fa-code"></i>
                    <h2>Web development</h2>
                    <br>
                    <p>
                        I delved into the intricacies of front-end and back-end technologies, honing my expertise in HTML, CSS, JavaScript, and various frameworks.database management, version control, responsive design, and deployment strategies were also covered.
                    </p>
                    <a href = "#">Learn more</a>
                </div>
                <div>
                    <i class="fa-solid fa-cloud"></i>
                    <h2>Cloud computing</h2>
                    <br>
                    <p>
                        I covered a spectrum of cloud services, architectures, and deployment models, ensuring a robust foundation for navigating the complexities of modern IT infrastructure,empowering me with advanced skills ever-evolving realm of cloud technology.
                    </p>
                    <a href = "#">Learn more</a>
                </div>
                <div>
                    <i class="fa-brands fa-product-hunt"></i>
                    <h2>Product management</h2>
                    <br>
                    <p>
                        I am delighted to announce the successful completion of a rigorous Professional Product Management course, where I honed my skills helps in equipping me with strategic and tactical expertise to drive innovation,meet market demands effectively.
                    </p>
                    <a href = "#">Learn more</a>
                </div>
            </div>
        </div>
    </div>
    <div id = "portfolio">
        <div class = "container">
            <h1 class = "sub-title">MY PROJECTS</h1>
            <div class = "projects-list">
                <div class = "projects">
                    <img src = "images/ethical.png">
                    <div class = "layer">
                        <h3> ETHICAL HACKING</h3>
                        <p>
                            Assess the security of blockchain implementations, including smart contract vulnerabilities, consensus algorithm weaknesses, and potential attack vectors
                        </p>
                        <a href = "#"><i class="fa-solid fa-arrow-up-right-from-square"></i></a>
                    </div>
                </div>
                <div class = "projects">
                    <img src = "images/vr.png">
                    <div class = "layer">
                        <h3>VIRTUAL REALITY</h3>
                        <p>
                            Created a VR experience that allows users to travel back in time and experience historical events or visit ancient civilizations. Provide educational content and interactive elements.
                        </p>
                        <a href = "#"><i class="fa-solid fa-arrow-up-right-from-square"></i></a>
                    </div>
                </div>
                <div class = "projects">
                    <img src = "images/robotics2.png">
                    <div class = "layer">
                        <h3>ROBOTICS</h3>
                        <p>
                            Design an exoskeleton that can enhance human strength and mobility. This can be applied in fields like rehabilitation or industrial settings.
                        </p>
                        <a href = "#"><i class="fa-solid fa-arrow-up-right-from-square"></i></a>
                    </div>
                </div>
            </div>
            <a href = "#" class = "btn">SEE MORE</a>
        </div>
    </div>
    <div id="contact">
        <div class="container">
            <div class="row">
                <div class="contact-left">
                    <h1 class = "sub-title">LET'S GET IN TOUCH</h1>
                    <p><i class="fa-solid fa-paper-plane"></i>santhoshanbu700@gmail.com</p>
                    <p><i class="fa-solid fa-phone"></i>+91 8870499700</p>
                    <div class="social-icons">
                        <a href = "https://www.linkedin.com/in/santhoshkumar-anbalagan?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=ios_app"><i class="fa-brands fa-linkedin"></i></i></a>
                        <a href = "https://www.instagram.com/santhoshsanmar/"><i class="fa-brands fa-instagram"></i></a>
                        <a href = ""><i class="fa-brands fa-square-x-twitter"></i></a>
                        <a href = ""><i class="fa-brands fa-facebook"></i></a>
                    </div>
                    <a href = "images/SANTHOSHKUMAR_A_RESUME.pdf" download class = "btn btn2">DOWNLOAD RESUME</a>
                </div>
                <div class="contact-right">
                    <form name = "submit-to-google-sheet">
                        <input type = "text" name = "NAME" placeholder = "YOUR NAME" required>
                        <input type = "email" name = "EMAIL ID" placeholder = "YOUR EMAIL ID " required>
                        <textarea name = "MESSAGE" rows = "6" placeholder = "YOUR MESSAGE"></textarea>
                        <button type = "submit" class = "btn btn2">SUBMIT</button>
                    </form>
                    <span id = "msg"></span>
                </div>
            </div>
        </div>
        <div class="copyright">
            <p>Copyright <span>&copy;</span> Sanmar.Made with <i class="fa-solid fa-heart"></i> by Sanmar</p>
        </div>
    </div>
    <script>
        var tablinks = document.getElementsByClassName("tab-links");
        var tabcontents = document.getElementsByClassName("tab-contents");

        function opentab(tabname){
            for(tablink of tablinks){
                tablink.classList.remove("active-link");
            }
            for(tabcontent of tabcontents){
                tabcontent.classList.remove("active-tab");
            }
            event.currentTarget.classList.add("active-link");
            document.getElementById(tabname).classList.add("active-tab");
        }
    </script>
    <script>
        var sidemenu = document.getElementById("sidemenu");
        function openmenu(){
            sidemenu.style.left = "0"; 
        }
        function closemenu(){
            sidemenu.style.left = "-200px"; 
        }
    </script>
    <script>
        const scriptURL = 'https://script.google.com/macros/s/AKfycbzVhCnkQs_1_Kt4H68MT-c4EZRh3LWXHP0-OznvdbpYKAg3ChgRmIYzrI0ECiH28kvQ/exec'
        const form = document.forms['submit-to-google-sheet']
        const msg = document.getElementById("msg")
      
        form.addEventListener('submit', e => {
          e.preventDefault()
          fetch(scriptURL, { method: 'POST', body: new FormData(form)})
            .then(response => {
                msg.innerHTML = "Message sent successfully"
                setTimeout(function(){
                    msg.innerHTML = ""
                },5000)
                form.reset()
            })
            .catch(error => console.error('Error!', error.message))
        })
      </script>               
</body>
</html>

style.css
*{
    margin: 0;
    padding: 0;
    font-family: 'Poppins' , sans-serif;
    box-sizing: border-box;
}
html{
    scroll-behavior: smooth;
}
body{
    background: #000000;
    color: #fff;
}
#header{
    width: 100%;
    height: 100vh;
    background-image: url("images/background1.png");
    background-position: right 20px;
    background-repeat: no-repeat;
}
.conatiner{
    padding: 10px 10%;
}
nav{
    display: flex;
    align-items: center;
    justify-content: space-between;
    flex-wrap: wrap;
}
.logo{
    width: 140px;
}
nav ul li{
    display: inline-block;
    list-style: none;
    margin: 10px 20px;
}
nav ul li a {
    color:#fff;
    text-decoration: none;
    font-size: 16px;
    position: relative;
}
nav ul li a::after{
    content: '';
    width: 0;
    height: 3px;
    background: #ff004f;
    position: absolute;
    left: 0;
    bottom: -6px;
    transition: 0.5s
}
nav ul li a:hover::after{
    width: 100%;
}
.header-text{
    margin-top: 20%;
    font-size: 30px;
}
.header-text h1{
    font-size: 60px;
    margin-top: 20px;
}
.header-text h1 span{
    color:#ff004f;
}
#about{
    padding: 100px 10px;
    color: #ababab;
    position: center;
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
    width: 70%;
    border-radius: 10px;
}
.about-col-2{
    flex-basis: 65%;
}
.sub-title{
    font-size: 40px;
    font-weight: 600;
    color:#fff;
}
.tab-titles{
    display: flex;
    margin: 20px 0 40px;
}
.tab-links{
    margin-right: 50px;
    font-size: 18px;
    font-weight:500;
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
#certifications{
    padding: 30px 0;
}
.certifications-list{
    display: grid;
    grid-template-columns: repeat(auto-fit,minmax(250px,1fr));
    grid-gap: 40px;
    margin-top: 50px;
}
.certifications-list div{
    background: #262626;
    padding: 40px;
    font-size: 13px;
    font-weight: 300;
    border-radius: 10px;
    transition: background 0.5s, transform 0.5s;
}
.certifications-list div i{
    font-size: 50px;
    margin-bottom: 30px;
}
.certifications-list div h2{
    font-size: 30px;
    font-weight: 500;
    margin-bottom: 15px;
}
.certifications-list div a{
    text-decoration: none;
    color: #fff;
    font-size: 12px;
    margin-top: 20px;
    display: inline-block;
}
.certifications-list div:hover{
    background: #ff004f;
    transform: translateY(-10px);
}
#Portfolio{
    padding: 50px 0;
}
.projects-list{
    display: grid;
    grid-template-columns: repeat(auto-fit,minmax(250px,1fr));
    grid-gap: 40px;
    margin-top: 50px; 
}
.projects{
    border-radius: 10px;
    position: relative;
    overflow: hidden;
}
.projects img{
    width: 100%;
    border-radius: 10px;
    display: block;
    transition: transform 0.5s; 
}
.layer{
    width: 100%;
    height: 0;
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
    margin-bottom: 20px
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
.projects:hover img{
    transform: scale(1.1);
}
.projects:hover .layer{
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
.social-icons a{
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
}
.btn.btn2{
    display: inline-block;
    background: #ff004f;
}
.contact-right form{
    width: 100%;
}
form input,form textarea{
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
    padding: 25px 0;
    background: #262626;
    font-weight: 300;
    margin-top: 20px;
}
.copyright i{
    color: #ff004f;
}
nav .fa-solid{
    display: none;
}
@media only screen and (max-width: 600px){
    #header{
        background-image: url("images/background1.png");
    }
    .header-text{
         margin-top: 100%;
         font-size: 16px;
    }
    .header-text h1{
        font-size: 30px;
    }
    nav .fa-solid{
        display: block;
        font-size: 25px;
    }
    nav ul{
        background: #ff004f;
        position: fixed;
        top: 0;
        left: -200px;
        width: 200px;
        height: 100vh;
        padding-top: 50px;
        z-index: 2;
        transition: left 0.5s;
   } 
   nav ul li{
        display: block;
         margin: 25px;
   }
   nav ul .fa-solid{
        position: absolute;
        top: 25px;
        left : 25px;
        cursor: pointer;
    }
   .sub-title{
       font-size: 20px;
   }
   .about-col-1, .about-col-2{
       flex-basis: 100%;
   }
   .about-col-1{
       margin-bottom: 30px;
   }
   .about-col-2{
       font-size: 15px
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
#msg{
    color: #61b752;
    margin-top: -40px;
    display: block;

}




































