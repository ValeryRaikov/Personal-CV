---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
permalink: /
---

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="../assets/webpage.css">
    <title>CV - {{ site.title }}</title>
</head>

<body>
    <header class="site-header">
        <p class="site-title">Hello everyone 🖐</p>
        
        <nav class="site-navbar">
            <span class="icon">
                <a target="_blank" href="https://www.facebook.com/profile.php?id=100008440088832&locale=bg_BG">
                    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512"><path d="M512 256C512 114.6 397.4 0 256 0S0 114.6 0 256C0 376 82.7 476.8 194.2 504.5V334.2H141.4V256h52.8V222.3c0-87.1 39.4-127.5 125-127.5c16.2 0 44.2 3.2 55.7 6.4V172c-6-.6-16.5-1-29.6-1c-42 0-58.2 15.9-58.2 57.2V256h83.6l-14.4 78.2H287V510.1C413.8 494.8 512 386.9 512 256h0z"/></svg>
                </a>
            </span>
            <span class="icon">
                <a target="_blank" href="https://www.instagram.com/{{ site.instagram_username }}/">
                    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 448 512"><path d="M224.1 141c-63.6 0-114.9 51.3-114.9 114.9s51.3 114.9 114.9 114.9S339 319.5 339 255.9 287.7 141 224.1 141zm0 189.6c-41.1 0-74.7-33.5-74.7-74.7s33.5-74.7 74.7-74.7 74.7 33.5 74.7 74.7-33.6 74.7-74.7 74.7zm146.4-194.3c0 14.9-12 26.8-26.8 26.8-14.9 0-26.8-12-26.8-26.8s12-26.8 26.8-26.8 26.8 12 26.8 26.8zm76.1 27.2c-1.7-35.9-9.9-67.7-36.2-93.9-26.2-26.2-58-34.4-93.9-36.2-37-2.1-147.9-2.1-184.9 0-35.8 1.7-67.6 9.9-93.9 36.1s-34.4 58-36.2 93.9c-2.1 37-2.1 147.9 0 184.9 1.7 35.9 9.9 67.7 36.2 93.9s58 34.4 93.9 36.2c37 2.1 147.9 2.1 184.9 0 35.9-1.7 67.7-9.9 93.9-36.2 26.2-26.2 34.4-58 36.2-93.9 2.1-37 2.1-147.8 0-184.8zM398.8 388c-7.8 19.6-22.9 34.7-42.6 42.6-29.5 11.7-99.5 9-132.1 9s-102.7 2.6-132.1-9c-19.6-7.8-34.7-22.9-42.6-42.6-11.7-29.5-9-99.5-9-132.1s-2.6-102.7 9-132.1c7.8-19.6 22.9-34.7 42.6-42.6 29.5-11.7 99.5-9 132.1-9s102.7-2.6 132.1 9c19.6 7.8 34.7 22.9 42.6 42.6 11.7 29.5 9 99.5 9 132.1s2.7 102.7-9 132.1z"/></svg>
                </a>
            </span>
            <span class="icon">
                <a target="_blank" href="https://github.com/{{ site.github_username }}/">
                    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 496 512"><path d="M165.9 397.4c0 2-2.3 3.6-5.2 3.6-3.3 .3-5.6-1.3-5.6-3.6 0-2 2.3-3.6 5.2-3.6 3-.3 5.6 1.3 5.6 3.6zm-31.1-4.5c-.7 2 1.3 4.3 4.3 4.9 2.6 1 5.6 0 6.2-2s-1.3-4.3-4.3-5.2c-2.6-.7-5.5 .3-6.2 2.3zm44.2-1.7c-2.9 .7-4.9 2.6-4.6 4.9 .3 2 2.9 3.3 5.9 2.6 2.9-.7 4.9-2.6 4.6-4.6-.3-1.9-3-3.2-5.9-2.9zM244.8 8C106.1 8 0 113.3 0 252c0 110.9 69.8 205.8 169.5 239.2 12.8 2.3 17.3-5.6 17.3-12.1 0-6.2-.3-40.4-.3-61.4 0 0-70 15-84.7-29.8 0 0-11.4-29.1-27.8-36.6 0 0-22.9-15.7 1.6-15.4 0 0 24.9 2 38.6 25.8 21.9 38.6 58.6 27.5 72.9 20.9 2.3-16 8.8-27.1 16-33.7-55.9-6.2-112.3-14.3-112.3-110.5 0-27.5 7.6-41.3 23.6-58.9-2.6-6.5-11.1-33.3 2.6-67.9 20.9-6.5 69 27 69 27 20-5.6 41.5-8.5 62.8-8.5s42.8 2.9 62.8 8.5c0 0 48.1-33.6 69-27 13.7 34.7 5.2 61.4 2.6 67.9 16 17.7 25.8 31.5 25.8 58.9 0 96.5-58.9 104.2-114.8 110.5 9.2 7.9 17 22.9 17 46.4 0 33.7-.3 75.4-.3 83.6 0 6.5 4.6 14.4 17.3 12.1C428.2 457.8 496 362.9 496 252 496 113.3 383.5 8 244.8 8zM97.2 352.9c-1.3 1-1 3.3 .7 5.2 1.6 1.6 3.9 2.3 5.2 1 1.3-1 1-3.3-.7-5.2-1.6-1.6-3.9-2.3-5.2-1zm-10.8-8.1c-.7 1.3 .3 2.9 2.3 3.9 1.6 1 3.6 .7 4.3-.7 .7-1.3-.3-2.9-2.3-3.9-2-.6-3.6-.3-4.3 .7zm32.4 35.6c-1.6 1.3-1 4.3 1.3 6.2 2.3 2.3 5.2 2.6 6.5 1 1.3-1.3 .7-4.3-1.3-6.2-2.2-2.3-5.2-2.6-6.5-1zm-11.4-14.7c-1.6 1-1.6 3.6 0 5.9 1.6 2.3 4.3 3.3 5.6 2.3 1.6-1.3 1.6-3.9 0-6.2-1.4-2.3-4-3.3-5.6-2z"/></svg>
                </a>
            </span>
        </nav>
    </header>

    <main class="site-main">
        <section class="top">
            <div class="media">
                <img src="../assets/images/profile_pic.webp" alt="">
            </div>

            <div class="content">
                <h2>{{ site.title }}</h2>
                <p>BCSE student looking for a career</p>
                <a class="download" download href="../assets/personal_cv.pdf">Download CV</a>
            </div>
        </section>

        <section class="middle">
            <h2>About me</h2>
            
            <div class="flex-container">
                <div class="general">
                    <p>I am a university student at TU-Sofia as well as SoftUni, studying computer and software engineering.
                    Willing to expand my knowledge on this topic and find a job where I would be able to contribute to the working process and achieve goals and dreams.
                    Currently working on some front-end projects on HTML CSS and JS.</p>
                    <blockquote>Discipline is the key to success!</blockquote>
                </div>

                <div class="personal">
                    <p><b>Age:</b> 20</p>
                    <p><b>City:</b> Sofia</p>
                    <p><b>Email:</b> {{ site.email }}</p>
                    <p><b>Phone:</b> {{ site.phone_number }}</p>
                </div>
            </div>
        </section>

        <section class="bottom">
            <h2>Skills and experience</h2>

            <div class="languages">
                <h4>Languages</h4>
                <ul>
                    <li>English - level C1</li>
                    <li>French - level B2</li>
                    <li>Bulgarian - native</li>
                </ul>
            </div>

            <div class="programming">
                <h4>Programming languages and technologies</h4>
                <div class="ul-container">
                    <ul>
                        <li>Python</li>
                        <li>C</li>
                        <li>Java</li>
                        <li>JavaScript</li>
                    </ul>

                    <ul>
                        <li>PostgreSQL</li>
                        <li>MySQL</li>
                    </ul>

                    <ul>
                        <li>HTML</li>
                        <li>CSS</li>
                    </ul>
                </div>
            </div>

            <div class="education">
                <h4>Education</h4>
                <ul>
                    <li>French Language school "Alphonse de Lamartine" №9 <b>2017 - 2022</b></li>
                    <li>Techical University Sofia (Computer and software engineering) <b>2022 - present</b></li>
                    <li>Software University <b>2022 - present</b></li>
                </ul>
                
            </div>

            <div class="qualities">
                <h4>Qualities</h4>
                <ul>
                    <li>Discipline</li>
                    <li>Creativity</li>
                    <li>Persistance</li>
                    <li>Critical thinking</li>
                </ul>
            </div>

            <div class="conclusion">
                <h4>Conclusion</h4>
                <p>If you are interested in learning more about my personality and would like to connect, 
                    please feel free to reach out to me. I am open to discussing my background, experiences, 
                    and anything else you'd like to know. Additionally, if you would like to explore some of 
                    the projects I've worked on, you can visit my <a target="_blank" href="https://github.com/{{ site.github_username }}/">Github</a> 
                    account. Thank you for taking the time to read this message. I look forward to potentially 
                    connecting with you!</p>
            </div>
        </section>
    </main>

    <footer class="site-footer">
        <p>This webpage is created by me. Enjoy it...</p>
        <p>04-03-2024</p>
    </footer>
</body>

</html>