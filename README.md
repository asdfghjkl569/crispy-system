# crispy-system<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="shortcut icon" type="image/x-icon" href="favicon.ico">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <title>NK UX/UI Student-Designer Portfolio 2024</title>
    <link rel="stylesheet" href="assets/css/styles.css">
    <!-- ===== BOX ICONS ===== -->
    <link href="https://cdn.jsdelivr.net/npm/boxicons@2.0.5/css/boxicons.min.css" rel="stylesheet">
</head>
<body>
    <!-- ===== HEADER ===== -->
    <header class="l-header">
        <nav class="nav bd-grid">
            <div>
                <a href="#" class="nav__logo">NK Student</a>
            </div>

            <div class="nav__menu" id="nav-menu">
                <ul class="nav__list">
                    <li class="nav__item"><a href="#home" class="nav__link active-link">Home</a></li>
                    <li class="nav__item"><a href="#about" class="nav__link">About</a></li>
                    <li class="nav__item"><a href="#skills" class="nav__link">Skills</a></li>
                    <li class="nav__item"><a href="#work" class="nav__link">Work</a></li>
                    <li class="nav__item"><a href="#contact" class="nav__link">Contact</a></li>
                </ul>
            </div>

            <div class="nav__toggle" id="nav-toggle">
                <i class="bx bx-menu"></i>
            </div>
        </nav>
    </header>

    <main class="l-main">
        <!-- ===== HOME ===== -->
        <section class="home bd-grid" id="home">
            <div class="home__data">
                <h1 class="home__title">Hi,<br>I'm <span class="home__title-color">NK Student</span><br>UX/UI Designer</h1>
                <a href="#" class="button">Contact</a>
            </div>

            <div class="home__social">
                <a href="#" class="home__social-icon"><i class="bx bxl-linkedin"></i></a>
                <a href="#" class="home__social-icon"><i class="bx bxl-behance"></i></a>
                <a href="#" class="home__social-icon"><i class="bx bxl-github"></i></a>
            </div>

            <div class="home__img">
                <svg class="home__blob" viewBox="0 0 479 467" xmlns="http://www.w3.org/2000/svg">
                    <mask id="mask0" mask-type="alpha">
                        <path d="M9.19024 145.964C34.0253 76.5814 114.865 54.7299 184.111 29.4823C245.804 6.98884 311.86 -14.9503 370.735 14.143C431.207 44.026 467.948 107.508 477.191 174.311C485.897 237.229 454.931 294.377 416.506 344.954C373.74 401.245 326.068 462.801 255.442 466.189C179.416 469.835 111.552 422.137 65.1576 361.805C17.4835 299.81 -17.1617 219.583 9.19024 145.964Z"/>
                    </mask>
                    <g mask="url(#mask0)">
                        <path d="M9.19024 145.964C34.0253 76.5814 114.865 54.7299 184.111 29.4823C245.804 6.98884 311.86 -14.9503 370.735 14.143C431.207 44.026 467.948 107.508 477.191 174.311C485.897 237.229 454.931 294.377 416.506 344.954C373.74 401.245 326.068 462.801 255.442 466.189C179.416 469.835 111.552 422.137 65.1576 361.805C17.4835 299.81 -17.1617 219.583 9.19024 145.964Z"/>
                        <image class="home__blob-img" x="50" y="60" href="assets/img/perfil.png"/>
                    </g>
                </svg>
            </div>
        </section>

        <!-- ===== ABOUT ===== -->
        <section class="about section" id="about">
            <h2 class="section-title">About</h2>

            <div class="about__container bd-grid">
                <div class="about__img">
                    <img src="assets/img/about.png" alt="">
                </div>
                
                <div>
                    <h2 class="about__subtitle">I'm NK Student, a UX/UI Designer</h2>
                    <p class="about__text">Driven & adaptable UX/UI designer. I tackle challenges with passion, crafting user-friendly & visually stunning experiences across mobile, web, and marketing materials. Strong communicator, collaborating effectively to achieve shared goals.</p>           
                </div>                                   
            </div>
        </section>

        <!-- ===== SKILLS ===== -->
        <section class="skills section" id="skills">
            <h2 class="section-title">Skills</h2>

            <div class="skills__container bd-grid">          
                <div>
                    <h2 class="skills__subtitle">Professional Skills</h2>
                    <p class="skills__text">Skilled UX/UI designer (85%) with a strong foundation in HTML5 (95%), CSS3 (85%), and JavaScript (65%). Crafts user-centered experiences with a blend of technical proficiency and design expertise.</p>
                    <div class="skills__data">
                        <div class="skills__names">
                            <i class="bx bxl-html5 skills__icon"></i>
                            <span class="skills__name">HTML5</span>
                        </div>
                        <div class="skills__bar skills__html"></div>
                        <div>
                            <span class="skills__percentage">95%</span>
                        </div>
                    </div>
                    <div class="skills__data">
                        <div class="skills__names">
                            <i class="bx bxl-css3 skills__icon"></i>
                            <span class="skills__name">CSS3</span>
                        </div>
                        <div class="skills__bar skills__css"></div>
                        <div>
                            <span class="skills__percentage">85%</span>
                        </div>
                    </div>
                    <div class="skills__data">
                        <div class="skills__names">
                            <i class="bx bxl-javascript skills__icon"></i>
                            <span class="skills__name">JavaScript</span>
                        </div>
                        <div class="skills__bar skills__js"></div>
                        <div>
                            <span class="skills__percentage">65%</span>
                        </div>
                    </div>
                    <div class="skills__data">
                        <div class="skills__names">
                            <i class="bx bxs-paint skills__icon"></i>
                            <span class="skills__name">UX/UI</span>
                        </div>
                        <div class="skills__bar skills__ux"></div>
                        <div>
                            <span class="skills__percentage">85%</span>
                        </div>
                    </div>
                </div>
                
                <div>              
                    <img src="assets/img/work3.png" alt="" class="skills__img">
                </div>
            </div>
        </section>

        <!-- ===== WORK ===== -->
        <section class="work section" id="work">
            <h2 class="section-title">Work</h2>

            <div class="work__container bd-grid">
                <a href="#" class="work__img">
                    <img src="assets/img/work1.png" alt="">
                </a>
                <a href="#" class="work__img">
                    <img src="assets/img/work2.gif" alt="">
                </a>
                <a href="#" class="work__img">
                    <img src="assets/img/work3.png" alt="">
                </a>
                <a href="#" class="work__img">
                    <img src="assets/img/work4.gif" alt="">
                </a>
                <a href="#" class="work__img">
                    <img src="assets/img/work5.png" alt="">
                </a>
                <a href="#" class="work__img">
                    <img src="assets/img/work6.gif" alt="">
                </a>
            </div>
        </section>

        <!-- ===== CONTACT ===== -->
        <section class="contact section" id="contact">
            <h2 class="section-title">Contact</h2>

            <div class="contact__container bd-grid">
                <form action="#" class="contact__form">
                    <input type="text" placeholder="Name" class="contact__input">
                    <input type="email" placeholder="Email" class="contact__input">
                    <textarea name="" id="" cols="0" rows="10" class="contact__input" placeholder="Message"></textarea>
                    <input type="button" value="Send" class="contact__button button">
                </form>
            </div>
        </section>
    </main>

    <!-- ===== FOOTER ===== -->
    <footer class="footer">
        <p class="footer__title">NK Student</p>
        <div class="footer__social">
            <a href="#" class="footer__icon"><i class="bx bxl-facebook"></i></a>
            <a href="#" class="footer__icon"><i class="bx bxl-instagram"></i></a>
            <a href="#" class="footer__icon"><i class="bx bxl-twitter"></i></a>
        </div>
        <p class="footer__copy">&#169; Gifted NK 2024. All rights reserved.</p>
    </footer>

    <!-- ===== SCROLL REVEAL ===== -->
    <script src="https://unpkg.com/scrollreveal"></script>

    <!-- ===== MAIN JS ===== -->
    <script src="assets/js/main.js"></script>
</body>
</html>


# UX/UI Student-Designer Portfolio 2024

Welcome to the UX/UI Student-Designer Portfolio repository. This project showcases a personal portfolio website for Student, a UX/UI designer. The site includes sections for home, about, skills, work, and contact.

![Portfolio Screenshot](assets/img/portfolio-screenshot.png)

## Table of Contents

- [Demo](#demo)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Demo

You can view the live demo of the portfolio [here](https://worachat-dev.github.io/Student-Portfolio-4Student-dev/).

## Features

- **Responsive Design:** The layout adapts to different screen sizes and devices.
- **Home Section:** Introduction with links to social profiles.
- **About Section:** Information about Student’s background and approach.
- **Skills Section:** Display of technical and design skills with progress indicators.
- **Work Section:** Gallery of previous projects.
- **Contact Section:** Form for visitors to get in touch.

## Technologies Used

- **HTML5**
- **CSS3**
- **JavaScript**
- **[Boxicons](https://boxicons.com/)** for icons
- **[ScrollReveal](https://scrollrevealjs.org/)** for scroll animations

## Installation

To run this project locally:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/portfolio.git
   ```
   
2. **Navigate to the project directory:**
   ```bash
   cd portfolio
   ```

3. **Open `index.html` in your browser:**
   ```bash
   open index.html
   ```
   Or, simply double-click `index.html`.

## Usage

- **Navigation:** Click on the navigation links to jump to different sections of the portfolio.
- **Contact Form:** Fill out the contact form to send a message (Note: Actual form submission functionality needs to be connected to a backend service).
- **Social Links:** Click on social media icons to visit Student’s profiles.

## Contributing

Contributions are welcome! Here's how you can help:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes and commit (`git commit -m 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Open a pull request.

## Acknowledgements

This portfolio project draws significant inspiration and structural foundation from the work of Bedimcode. The original repository, [Bedimcode's Portfolio-Responsive-Complete](https://github.com/bedimcode/portfolio-responsive-complete), provided an excellent starting point for the layout, design patterns, and responsiveness features implemented in this portfolio.

Special thanks to:

- **[Bedimcode](https://github.com/bedimcode)**: For the comprehensive and well-documented codebase that served as a guide in developing this project. Your contribution to the community is greatly appreciated.

- **Open Source Community**: For fostering an environment of collaboration and sharing that allows developers to build on and improve each other's work.

The modifications and enhancements in this project include personalized content, unique styling, and additional features tailored to fit Student’s UX/UI design portfolio. While the base design and layout closely follow the original, all customizations and content changes reflect Student's individual style and professional presentation.

Please visit Bedimcode's [original repository](https://github.com/bedimcode/portfolio-responsive-complete) to explore their fantastic work and other projects.

## Authors

- **Worachat W, Dev.** - *Data Science, Engineering & Full Stack Dev. 2024*

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## Contact
Feel free to reach out for any inquiries or suggestions at [Twitter or X](https://x.com/drcha_tea) , UX/UI Designer | [LinkedIn](https://www.linkedin.com/in/brainwaves-your-ai-playground-9082922ba) | [GitHub](https://github.com/worachat-dev)

---

```

### Notes:

1. **Screenshots:**
   - Include a screenshot of your portfolio website by replacing `assets/img/portfolio-screenshot.png` with the actual path to your screenshot.

2. **Links:**
   - Replace `https://your-live-demo-link.com` with the URL to your live demo.
   - Replace `your-username` with your GitHub username.
   - Update `your-email@example.com` with your contact email.
   - Update social media links with actual URLs.

3. **Badges:**
   - The badges at the bottom are placeholders; you can use shields.io to generate the correct badge URLs for your GitHub repository. Replace `your-username` and `portfolio` with your actual GitHub username and repository name.

This `README.md` provides a comprehensive overview of your portfolio project, making it easier for others to understand and contribute.




