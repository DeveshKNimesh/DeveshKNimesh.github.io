<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
       <link rel="stylesheet" href="style.css">
    <link rel="stylesheet" media="screen and (max-width:800px)" href="tablet.css">
    <link rel="stylesheet" media="screen and (max-width:530px)" href="phone.css">
</head>
<body>
    <nav class="navbar">
        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#about">About Me</a></li>
            <li><a href="#portfolio">Portfolio</a></li>
            <li><a href="#services">Services</a></li>
            <li><a href="#contact">Contact Me</a></li>
        </ul>    
    </nav>

    <section id="home">
        <div class="main">
            <h1 class="headings">I AM <br> DEVESH KUMAR NIMESH</h1>
            <button class="btn">
                Hire Me
            </button>
        </div>
    </section>
    <section id="about">
        <h1 class="headings">ABOUT ME</h1>
        <div id="pic">
            <img src="img3.jpg" alt="">
            <div id="intro">
                <h2>DEVESH KUMAR NIMESH</h2>
                <p>
                    I am working in IT Industries since 2010. During this tenure I have worked on various technologies based on the requirement of the projects. I like to learn new technologies. My specialization is data analysis and working in RDBMS. I enjoys writing SQLs in Oracle and MS SQL to analyse data and extract good and useful information for the reports requirement. 
                </p>
            </div>
        </div>
    </section>
    <section id="portfolio">
        <h1 class="headings">PORTFOLIO</h1>
        <div class="gallery">
            <img src="img1.jpg" alt="">
            <img src="Portfolio/img1.jpg" alt="">
            <img src="img2.jpg" alt="">
            <img src="Portfolio/img2.jpg" alt="">
            <img src="img3.jpg" alt="">
            <img src="Portfolio/img3.jpg" alt="">
            <img src="img4.jpg" alt="">
            <img src="Portfolio/img4.jpg" alt="">
            <img src="img5.jpg" alt="">
            <img src="Portfolio/img5.jpg" alt="">
            <img src="img6.jpg" alt="">
            <img src="Portfolio/img6.jpg" alt="">
        </div>
    </section>
    <section id="services">
        <h1 class="headings">SERVICES</h1>
        <div class="row">
            <div class="box">
                <img src="services/ui-design.png" alt="">
                <h1 class="headings">Website Design</h1>
                <p>We designs and develops, high standard website for you business solutions. A wesite which is easy to access sections, attractivte, responsive and includes blogs, customer testimonials, visuals images and videos with high quality. Easy to Understand to attract users.</p>
            </div>
            <div class="box">
                <img src="services/monitor.png" alt="">
                <h1 class="headings">Data Analysis</h1>
                <p>We designs and develops, high standard website for you business solutions. A wesite which is easy to access sections, attractivte, responsive and includes blogs, customer testimonials, visuals images and videos with high quality. Easy to Understand to attract users.</p>
            </div>
            <div class="box">
                <img src="services/strategy.png" alt="">
                <h1 class="headings">ETL - Data Warehouse</h1>
                <p>We designs and develops, high standard website for you business solutions. A wesite which is easy to access sections, attractivte, responsive and includes blogs, customer testimonials, visuals images and videos with high quality. Easy to Understand to attract users.</p>
            </div>
        </div>
    </section>
    <section id="contact">
        <hi class="headings">CONTACT</hi>
        <form action="" class="form">
            <input type="text" name="name" class="input" placeholder="Enter Your Name">
            <input type="email" name="email" class="input" placeholder="Enter Your Email">
            <textarea name="msg" id="msg" cols="30" rows="10" placeholder="Enter Your Message"></textarea>
            <input type="submit" value="SEND" id="send">
            
        </form>
    </section>
</body>
</html>
