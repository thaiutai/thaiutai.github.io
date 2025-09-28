<!DOCTYPE html>
<html lang="en">
<head>

    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link rel="stylesheet" href="styles.css" />

    <!-- Fonts -->
    <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
    <link href="https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap" rel="stylesheet" />

    <!-- Kits -->
    <script src="https://kit.fontawesome.com/ccdf59d458.js" crossorigin="anonymous"></script>
    <title>thaiutai.net Portfolio</title>
</head>

<body>

<!-- Nav section in CSS -->
    <section id="header-and-nav">
        <header id="header">
            <nav id="navbar">
                <ul class="navbar-group start">
                    <li><a href="mailto:saharachthaiutai@outlook.com" target="_blank" class="nav-link">
                        <i class="fa-solid fa-envelope fa-2xl"></i>
                    </a></li>
                    <li><a href="https://www.linkedin.com/in/saharachthaiutai/" target="_blank" class="nav-link">
                        <i class="fa-brands fa-linkedin fa-2xl"></i>
                    </a></li>
                    <li><a href="https://www.github.com/thaiutai" id="profile-link" target="_blank" class="nav-link">
                        <i class="fa-brands fa-github fa-2xl"></i>
                    </a></li>
                </ul>
                
                <ul class="navbar-group end">
                    <li><a class="nav-link" href="./other-pages/about.html">About</a></li>
                    <li><a class="nav-link" href="#projects">Projects</a></li>
                    <li><a class="nav-link" href="#contact-section">Contact</a></li>
                    <i id="mobile-bar" class="fa-solid fa-bars"></i>
                </ul>
            </nav>
        </header>
    </section>

<!-- Welcome section in CSS -->
    <section id="welcome-section">
        <div class="welcome-section-header">
            <img id="welcome-picture" src="/imgs/me_drinking.jpeg"/>
            <!-- Adding picture -->
             <div class="text-container">
                 <h1 class="text-header"  id="main-title">thaiutai</h1>
                 <p class="text-header" id="secondary-title"><em>BSc Biochem Graduate</em></p>
             </div>
        </div>

    </section>

    <section id="projects">
        <h1 class="section-title">My projects</h1>
        <div class="project-container">
            <div class="project-tile">
                <h1 class="project-title">Survey form</h1>
                <a href="https://github.com/thaiutai/fCC-survey-form" target="_blank">
                    <img class="project-img" src="./imgs/survey-form.png" alt=""></a>
                <p><em>click for github repo</em></p>
            </div>

            <div class="project-tile">
                <h1 class="project-title">Tribute page</h1>
                <a href="https://github.com/thaiutai/fCC-kobe-tribute" target="_blank">
                    <img class="project-img" src="./imgs/tribute-screenshot.png" alt=""></a>
                <p><em>click for github repo</em></p>
            </div>

            <div class="project-tile">
                <h1 class="project-title">Mock website for company</h1>
                <a href="https://github.com/thaiutai/fCC-product-landing-page" target="_blank">
                    <img class="project-img" src="./imgs/eczemcare.png" alt=""></a>
                <p><em>click for github repo</em></p>
            </div>

            <div class="project-tile">
                <h1 class="project-title">Google mock</h1>
                <a href="https://github.com/thaiutai/cs50w_project0" target="_blank">
                    <img class="project-img" src="./imgs/google.png" alt=""></a>
                <p><em>click for github repo</em></p>
                </div>
            </div>
        </div>
    </section>

    <section id="contact"></section>

</body>
</html>
