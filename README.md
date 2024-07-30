<body>
  <style>
    body, html {
    margin: 0;
    padding: 0;
    overflow-x: hidden;
    font-family: 'Montserrat', sans-serif;
}
section {
    height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
    color: white;
    font-size: 2em;
    text-align: center;
    position: relative;
}
.video-background {
    position: relative;
    overflow: hidden;
}
.video-background video {
    position: absolute;
    top: 50%;
    left: 50%;
    min-width: 100%;
    min-height: 100%;
    width: auto;
    height: auto;
    z-index: -1;
    transform: translate(-50%, -50%);
}
.ems h2{
    background: linear-gradient(to right, #d5006d , #2f2a7f );
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent; 
}
.image-background {
    background-image: url('tloems.avif');
    background-size: cover;
    background-position: center;
    background-repeat: no-repeat;
    padding: 10px; 
    position: relative;
    color: white; 
}
.ems p{
    line-height: 35px;
    font-size: 25px;
    color:#020101;
}
.ems p{
    color:#020101;
}
.ems {
    position: relative;
    max-width: 100px; 
    margin: 0 auto;
}

.ems h2 {
    margin: 0;
    padding: 0;
    font-size: 2em; 
    text-align: center; 
}

.ems p {
    text-align: center;
    font-size: 20px;
    color: rgb(255, 246, 246);
}

.image-containere {
    display: flex;
    justify-content: center;
    gap: 10px; 
    margin-top: 10px; 
}

.image-containere img {
    max-width: 100%;
    height: auto;
    border-radius: 4px; 
}

.dark-overlay::before {
    content: "";
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background: rgba(0, 0, 0, 0.5);
    z-index: -1;
}
.linija {
    font-size: 20px;
    position: absolute; 
    top: 0; 
    right: 10px;
    margin: 40px; 
    display: flex; 
    gap: 10px; 
}
.button-link {
    text-decoration: none; 
    color: white;
    padding: 10px; 
    border-radius: 5px; 
    font-weight: bold; 
}
.button-link:active{
    color: #d5006d;
}

.button-link:hover {

    color: #d5006d;
    border-color: #d5006d; 
}

.baner p,
.baner h1{
    margin:20px;
}
.baner h1{
    margin-top: 120px;
    font-size: 100px;
}
.baner img {
    position: absolute;
    top: 20px;
    left: 20px; 
    width: 400px; 
    height: auto; 
}

.container {
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;

}
.przezroczysty {
    background-color: transparent;
    border: 2px solid white;
    color: white;
    padding: 25px 40px;
    font-size: 24px;
    cursor: pointer;
    border-radius: 30px;
    transition: background-color 0.3s, color 0.3s, border 0.3s;
    outline: none;
}
.container {
    max-width: 5000px;

}
.containery {
    width: 70%;
    margin: 250px;
    padding: 50px;

}
.section_title {
    text-align: center;
    margin-bottom: 50px;
}

.section_title h3 {
    font-size: 50px; 
    background: linear-gradient(to right, #d5006d , #2f2a7f ); 
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent; 
    margin: 0; 
}

.section_title p {
    font-size: 25px;
    color: #666;
    width: 100%;
    text-align: center;
}

.accordion {
    border: 1px solid #ddd;
    border-radius: 5px;
    overflow: hidden;
    margin-top: 20px;
    text-align: left;
}

.accordion-item {
    border-top: 10px solid #ddd;
}

.accordion-item-header {
    background-color: white;
    color: black;
    padding: 20px;
    cursor: pointer;
    font-weight: bold;
    text-align: left;
    font-size: 25px;
}

.accordion-item-body {
    display: none;
    padding: 20px;
    background-color: #fff;
}

.accordion-item-body-content {
    font-size: 20px;
    color: #333;
}

.accordion-item-body-content iframe {
    width: 100%;
    height: 400px;
    border: none;
    margin-top: 10px;
}


.accordion-item-header.active + .accordion-item-body {
    display: block;
}
.boxed-btn33 {
    display: inline-block;
    background-color: #2f2a7f;
    color: #fff;
    padding: 10px 20px;
    border-radius: 5px;
    text-decoration: none;
    font-size: 1em;
    text-align: center;
    margin: 10px 0;
    transition: background-color 0.3s ease;
}

.boxed-btn33:hover {
    background-color: #5a2b8d;
}
.center {
    text-align: center;
}

@media (max-width: 768px) {
    .container {
        width: 90%;
    }

    .accordion-item-body iframe {
        height: 250px;
    }

    .section_title h3 {
        font-size: 2em;
    }

    .section_title p {
        font-size: 1em;
    }
}
.image-backgroundg {
    position: relative;
    background-image: url('grupowe.jpg');
    background-size: cover;
    background-position: center;
    height: 1000px; 
    color: white;
    text-align: center;
    display: flex;
    align-items: center;
    justify-content: center;
}

.image-backgroundg::after {
    content: '';
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background: rgba(255, 255, 255, 0.7);
    z-index: 1;
}

.image-backgroundg > div {
    position: relative;
    z-index: 2;
}
.image {
    position: relative;
    background-image: url('grupowe.jpg');
    background-size: cover;
    background-position: center;
    height: 1000px; 
    color: white;
    text-align: center;
    display: flex;
    align-items: center;
    justify-content: center;
}

.image::after {
    content: '';
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background: rgba(255, 255, 255, 0.7);
    z-index: 1;
}

.image > div {
    position: relative;
    z-index: 2; 
}

.image-backgrounds {
    position: relative;
    background-image: url('grupowe.jpg');
    background-size: cover;
    background-position: center;
    height: 1000px; 
    color: white;
    text-align: center;
    display: flex;
    align-items: center;
    justify-content: center;
}

.image-backgrounds::after {
    content: '';
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background: rgba(71, 70, 70, 0.6);
    z-index: 1;
}

.image-backgrounds > div {
    position: relative;
    z-index: 2;
}
.przezroczyste {
    background: transparent; 
    color: #fff; 
    border: 3px solid #fff; 
    padding: 25px 35px;
    cursor: pointer; 
    border-radius: 20px; 
    font-size: 18px;
}
.silka h2{
    font-size: 85px;
    color:white;
}       
.silka p {
    line-height: 35px;
    font-size: 25px;
   
}

.gallery {
    text-align: center; 
    margin-bottom: 20px; 
}

.gallery-img {
    max-width: 100%; 
    height: auto; 
    margin: 10px; 
    border-radius: 5px; 
}
.accordionr {
    border: 1px solid #ddd; 
    border-radius: 5px; 
    overflow: hidden; 
    margin-top: 20px; 
}
.accordion-itemr {
    border-top: 10px solid #ddd; 
}

.accordion-item-headerr {
    background-color: white;
    color: black; 
    padding: 20px; 
    cursor: pointer; 
    font-weight: bold; 
    text-align: left; 
    font-size: 25px;
}
.accordion-item-bodyr {
    display: none; 
    padding: 20px; 
    background-color: #fff; 
}
.accordion-item-body-contentr {
    font-size: 20px;
    color: #333; 
}


.accordion-item-bodyr.show {
    display: block; 
}


.accordion-item-headerr.active {
    background-color: #f0f0f0; 
}

.bodyroll h2{
    margin-top: 2px;

    font-size: 85px;
}
.bodyroll p{
    font-size: 30px;
}

.przezroczyst {
    margin-top: 10px;
    background-color: transparent;
    border: 2px solid white;
    color: white;
    padding: 10px 20px;
    font-size: 24px;
    cursor: pointer;
    border-radius: 10px;
    transition: background-color 0.3s, color 0.3s, border 0.3s;
    outline: none;
}
.video-backgroundr {
    position: relative;
    width: 100%;
    height: 100vh; 
    overflow: hidden;
}

.video-backgroundr video {
    height: 100vh;
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    object-fit: cover; 
}

.video-backgroundr::before {
    height: 100vh;
    content: "";
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background: rgba(0, 0, 0, 0.5); 
    z-index: 1;
}
.bodyroll {
    height: 100vh; 
    position: relative;
    z-index: 2;
    color: #fff;
    text-align: center; 
    padding: 20px;
    background: rgba(0, 0, 0, 0.1); 
    border-radius: 10px; 
    display: flex; 
    flex-direction: column; 
    justify-content: center; 
    align-items: center; 
}

.bodyroll h2 {
    margin-bottom: 0; 
    background: linear-gradient(to right, #d5006d , #2f2a7f );
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent; 
}

.bodyroll p {
    margin-top: 0; 
    margin-left: 50px;
    line-height: 35px;
    font-size: 25px;

}

.bodyroll button {
    text-align: center; 
    margin-top: 20px;
}

.przezroczyst {
    background: transparent; 
    color: #fff; 
    border: 3px solid #fff; 
    padding: 20px 30px;
    cursor: pointer; 
    border-radius: 20px; 
}

.gallery {
    display: flex;
    gap: 80px; 
}

.gallery img {
    width: 150px; 
    height: 150px;
    border-radius: 50%; 
    object-fit: cover;
    display: flex;
    justify-content: center;
    align-items: center;
}
.zdjeciap{
    display: flex;
    justify-content: center;
    align-items: center;
}

.image-backgrounnd {
    position: relative;
    background-image: url('grupowe.jpg');
    background-size: cover;
    background-position: center;
    height: 1000px; 
    color: white;
    text-align: center;
    display: flex;
    align-items: center;
    justify-content: center;
    flex-direction: column;
}

.image-backgrounnd::after {
    content: '';
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background: rgba(255, 255, 255, 0.5);
    z-index: 1;
}

.image-backgrounnd > div {
    position: relative;
    z-index: 2;
}

.strefa p {
    padding: 30px;
    line-height: 35px;
    font-size: 25px;
    color:#020101;
}

.strefa h2 {
    padding-bottom: 5px;
    background: linear-gradient(to right, #d5006d , #2f2a7f );
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent; 
}

.image-containerer {
    display: flex;
    justify-content: center;
    gap: 20px; 
    padding-bottom: 20px; 
}
.image-containerer img {
    width: 300px; 
    height: 300px; 
    object-fit: cover; 
    display: block;
    border-radius: 15px;
}

.button-container {
    margin-top: 10px; 
}

.przezroczystee {
    background: transparent;
    border: 2px solid white;
    color: white;
    padding: 10px 20px;
    font-size: 16px;
    cursor: pointer;
    border-radius: 5px;
}
    
.przezroczystee {
 
    background: linear-gradient(to right, #d5006d, #2f2a7f);
    color: white;
    padding: 20px 30px;
    font-size: 24px;
    cursor: pointer;
    border-radius: 20px;

}


.contact-info {
    text-align: left;
}

.contact-info p, .contact-info a {
    margin: 70px;
    margin-bottom: 20px;
    display: block;
}
.image-background {
    position: relative;
    background-size: cover;
    background-position: center;
    padding: 20px;
}

.ems {
    max-width: 1200px;
    margin: 0 auto;
    padding: 10px;
}

.image-container {
    display: flex;
    justify-content: space-between;
    margin-bottom: 20px;
}

.image-container img {
    width: 28%;
    height: auto;
    border-radius: 8px;
}

.accordion-container {
    border-radius: 8px;
    overflow: hidden;
    width: 100%;
}

.accordion-panel {
    border-top: 10px solid #ddd;
}

.accordion-header {
    background-color: white;
    color: black;
    padding: 20px;
    cursor: pointer;
    font-weight: bold;
    text-align: left;
    font-size: 25px;
}

.accordion-content {
    display: none;
    padding: 20px;
    background-color: #fff;
}

.accordion-text {
    font-size: 20px;
    color: #333;
}

.accordion-text iframe {
    width: 60px;
    height: 200px;
}

.accordion-header.active + .accordion-content {
    display: block;
}
.nacialo p{
    line-height: 30px;
    font-size: 25px;
    color:#020101;
    margin: 20px;
}
.nacialo h2{
background: linear-gradient(to right, #d5006d , #2f2a7f );
-webkit-background-clip: text;
-webkit-text-fill-color: transparent; 
}
.formula {
    color: black;
}
.plus-icon {
    margin-left: 800px;
}
.plus-ico {
    margin-left: 155px;
}
.plus-icn {
    margin-left: 263px;
}
.plus-icone {
    margin-left: 410px;
}
.plus-in {
    margin-left: 730px;
}
.plus-n {
    margin-left: 800px;
}
.medicover{
        background-size: cover;
        background-position: center;
}
.emskarnet{
    background: linear-gradient(to right, #d5006d, #2f2a7f);
    color: white;
    padding: 10px 20px;
    font-size: 15px;
    cursor: pointer;
    border-radius: 20px;
}




.logo2 {
    align-self: flex-start;
    margin-bottom: 30px; 
    width: 300px;
    height: auto;
} 


.accordionne {
    border: 1px solid #ddd;
    border-radius: 10px;
    margin-top: 20px; 
    max-width: 1200px; 
    margin-left: auto; 
    margin-right: auto; 
    background-color: rgba(255, 255, 255, 0.8); 
}
.accordion-item {
    border-top: 10px solid #ddd; 
}
.accordion-item-header {
    background-color: #fff; 
    color: #333; 
    padding: 15px; 
    cursor: pointer;
    font-weight: bold;
    text-align: left;
    font-size: 22px;
    border-bottom: 1px solid #ddd; 
    transition: background-color 0.3s, color 0.3s; 
}

.accordion-item-header:hover {
    background-color: #f0f0f0; 
}


.accordion-item-body {
    display: none;
    padding: 15px; 
    background-color: #fff; 
}
.accordion-item-body-content {
    font-size: 18px; 
    color: #333;
}
.accordion-item-body-content img {
    max-width: 100%; 
    height: auto;
    margin-bottom: 10px; 
}

.accordion-item-body-content iframe {
    width: 100%;
    height: 400px;
    border: none;
    margin-top: 10px;
}
.accordion-item-header.active {
    background-color: #e0e0e0; 
    color: #000; 
}
.accordion-item-header.active + .accordion-item-body {
    display: block;
}
.plusr{
    margin-left: 700px;
}
.pluse{
    margin-left: 870px;
}
.plus{
    margin-left: 803px;
}
.plusg{
    margin-left: 900px;
}
.plust{
    margin-left: 724px;
}
.plusu{
    margin-left: 620px;
}
.plusi{
    margin-left: 710px;
}
.plusj{
    margin-left: 710px;
}


.foto{
    width: 200px;
    height: 100px;

}

.accordionne{
   text-align: left;
}
.button-linkr {
    background: linear-gradient(to right, #d5006d, #2f2a7f);
    color: white;
    padding: 10px 20px;
    font-size: 15px;
    border-radius: 16px;
    text-align: center;
}
.banermedicower {
    max-width: 30%;
    height: auto;
    width: 390px;
    position: absolute;
    left: 450px;
    top: 460px;
}
.banermedicower {
    max-width: 50%;
    height: auto;
    margin-left: 560px;
}




.dulpraw {
    display: flex;
    justify-content: center; 
    align-items: flex-start; 
    background-color: black;
    color: white;
    padding: 20px;
    font-size: 18px; 
    gap: 20px; 
    flex-wrap: wrap; 
}

.wozle1, .godziny, .dulstrefy, .PARTNERZY {
    padding: 20px;
    flex: 1;
    max-width: 300px; 
    box-sizing: border-box; 
    text-align: left;
}

.contact-info, .info-text {
    font-size: 18px; 
    line-height: 1.5;
    text-align: left; 
}
.info-text a { 
    color: white;
}
.contact-link {
    color: white;
    text-decoration: none;
}

.contact-link:hover {
    text-decoration: underline;
}

.social {
    display: flex;
    gap: 10px;
    margin-top: 20px;
}

.social-icon {
    width: 80px; 
    height: auto;
}

.PARTNERZY {
    align-items: center; 
    text-align: center; 
}

.logos {
    display: flex;
    flex-direction: column; 
    align-items: center; 
    gap: 20px;
    margin-top: 10px;
}

.logo2, .logo3, .logo4 {
    width: 150px; 
    height: auto;
}

.section-title {
    font-size: 20px;
    margin-bottom: 20px; 
    font-weight: bold;
    text-align: left; 
    color:white;
}
  </style>
    <section class="video-background">
        <video autoplay muted loop>
            <source src="pomysł_body space concept.mp4" type="video/mp4">
        </video>
        <div class="baner">
                <img src="Body-space-company_logo.png" alt="logo">
                <div class="linija">
                <a href="#strefa" class="button-link"><strong>NASZE STREFY</strong></a>
                <a href="cennik.pdf" class="button-link"><strong>CENNIK</strong></a>
                <a href="https://karnety.bodyspace.pl/" class="button-link"><strong>KUP KARNET</strong></a>
                <a href="tel: +48 502 177 000" class="button-linkr"><strong>ZADZWOŃ</strong></a>
                </div>
                <h1>TRENING<br>PRZYSZŁOŚCI</h1>
                <div class="container">
                    <p>STUDIO MODELOWANIA SYLWETKI W EUROPIE</p>
        </div>
        </div>
    </section>
    
    <section class="menu">
        <div class="featuress_area">
            <div class="containery">
                <div class="row">
                    <div class="col-xl-12">
                        <div class="section_title mb-73">
                            <div class="center">
                                <h3>
                                    TRENING PRZYSZŁOŚCI BODY SPACE
                                </h3>
                                <p style="color:#020101; line-height: 35px;">
                                    Czy wiesz, co łączy Miami, Paryż, Rzym i Katowice? To studia modelowania sylwetki od Body Space! 
                                    Trenuj przy wykorzystaniu najnowszej technologii InfraRed i VacuTherm. 
                                    Istnieje miejsce, które łączy ze sobą siłownię, studio fitness, gabinety zabiegowe i treningi grupowe – to Body Space Concept!
                                </p>
                            
                            </div>
                        </div>
        
                        <div class="accordion">
                            <div class="accordion-item">
                                <div class="accordion-item-header">
                                    Co to jest Body Space?  <span class="plus-icon">✚</span>                      
                                </div>
                                <div class="accordion-item-body">
                                    <div class="accordion-item-body-content">
                                        Miejsce stworzone z myślą o kobietach – tutaj zadbasz o swoje samopoczucie i ciało, korzystając z profesjonalnej opieki oraz najnowocześniejszych technologii fitness i beauty modelujących kobiecą sylwetkę. Miejsce, w którym setki kobiet przeszło już swoją metamorfozę, dzięki szybkim i skutecznym 30-minutowym treningom w podciśnieniu i podczerwieni.<br><br>
                                        Przedstawiamy nasze strefy dedykowane wyłącznie dla kobiet:<br>
                                        •⁠  ⁠Strefa Body Space <br>
                                        •⁠  ⁠Strefa Body Roll<br>
                                        •⁠  ⁠Strefa zabiegów na ciało<br>
                                        •⁠  ⁠Strefa treningu EMS<br>
                                        •⁠  ⁠Strefa kobiecej siłowni <br>
                                        •⁠  ⁠Strefa zajęć grupowych
                                        <iframe width="950" height="700" src="https://www.youtube.com/embed/2q5HBxTlC1s" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
                                    </div>
                                </div>
                            </div>
        
                            <div class="accordion-item">
                                <div class="accordion-item-header">
                                    Mam kartę Multisport Plus / Medicover, czy mogę skorzystać z Body Space Katowice?<span class="plus-ico">✚</span>
                                </div>
                                <div class="accordion-item-body">
                                    <div class="accordion-item-body-content">
                                        Tak! Honorujemy najpopularniejsze karty sportowe takie jak Multisport Plus czy Medicover. W ramach członkostwa możesz skorzystać podczas jednej wizyty z wybranej strefy:
                                        <br><br>
                                        <span style="color:#330495">&#x2713;</span> Strefa Body Space (urządzenia VacuTherm i Infrared)<br>
                                        <span style="color:#330495">&#x2713;</span> Strefa Body Roll (masaże na rollerach)<br>
                                        <span style="color:#330495">&#x2713;</span> Strefa Zajęć Grupowych
                                        <br><br>
                                        Kliknij, zadzwoń i zapisz się teraz:
                                        <br><br>
                                        <a href="tel:502177000" class="boxed-btn33">+48 502 177 000</a>
                                        <img src="baner_medicover_body space concept.webp" alt="baner" class="banermedicower">
                                    </div>
                                </div>
                            </div>
        
                            <div class="accordion-item">
                                <div class="accordion-item-header">
                                    Nigdy nie byłam na siłowni, czy będę wiedzieć jak trenować w Body Space?<span class="plus-icn">✚</span>
                                </div>
                                <div class="accordion-item-body">
                                    <div class="accordion-item-body-content">
                                        Nasze wykwalifikowane trenerki wprowadzą Cię nie tylko w świat maszyn Body Space, ale także wytłumaczą, w jaki sposób ćwiczyć w strefie kobiecej siłowni. Zobacz nasz spacer po Body Space z Kamilą:
                                        <br><br>
                                        <iframe width="950" height="700" src="https://www.youtube.com/embed/l-yll_GxiEY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
                                    </div>
                                </div>
                            </div>
        
                            <div class="accordion-item">
                                <div class="accordion-item-header">
                                    Czy VacuTherm i InfraRed od Body Space naprawdę działają?<span class="plus-icone">✚</span>
                                </div>
                                <div class="accordion-item-body">
                                    <div class="accordion-item-body-content">
                                        Efekty treningu na Bieżni VacuTherm:
                                        Szybsze spalanie kalorii, szczuplejsza sylwetka, eliminacja cellulitu, wyraźnie gładsza i ujędrniona skóra, pozbycie się uczucia tzw. ciężkich nóg, zimnych stóp, przyspieszenie metabolizmu, poprawa kondycji. To absolutny hit na rynku światowym!
                                        Efektywne, 30-minutowe spalanie połączenie treningu cardio z technologią podciśnienia i podczerwieni, aby mobilizować wszystkie procesy niezbędne do spalania tkanki tłuszczowej, walki z cellulitem oraz ujędrnieniem ciała. To zdecydowana przewaga nad tradycyjnym treningiem aerobowym!
                                        <br><br>
                                        <iframe width="950" height="700" src="https://www.youtube.com/embed/63CjY2ZryH4" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>         
        <script>
           document.addEventListener('DOMContentLoaded', function () {
    var accordions = document.querySelectorAll('.accordion-item-header');

    accordions.forEach(function (header) {
        header.addEventListener('click', function () {
            var accordionItem = this.parentElement;
            var body = accordionItem.querySelector('.accordion-item-body');
            this.classList.toggle('active');
            if (body.classList.contains('show')) {
                body.classList.remove('show');
            } else {
                document.querySelectorAll('.accordion-item-body.show').forEach(function (item) {
                    item.classList.remove('show');
                    item.previousElementSibling.classList.remove('active');
                });
                body.classList.add('show');
            }
        });
    });
});

            </script>
            
    </section>

    <section class="image-backgrounnd" style="background-image: url('strefa_body\ space\ concept.webp');">
        <div class="strefa">
            <h2>STREFA BODY SPACE</h2>
            <p style="color:#020101; line-height: 35px;">Spalaj kalorie 4 razy szybciej! Trening w kapsułach to idealny sposób do wyszczuplenia sylwetki oraz utrzymania kondycji fizycznej. Dzięki zastosowaniu dwóch technologii – podciśnienia i podczerwieni następuje czterokrotnie szybsze spalanie tkanki tłuszczowej w porównaniu z tradycyjnym treningiem cardio.</p>
            <div class="image-containerer">
                <img src="bieżnia vacu_body space concept.webp" alt="Zdjęcie 1">
                <img src="bodyroll_body space concept.webp" alt="Zdjęcie 2">
                <img src="rower_leżący_body space concept.webp" alt="Zdjęcie 3">
            </div>
            <div class="button-container">
                <a href="https://karnety.bodyspace.pl/">
                <button class="przezroczystee">KARNETY DO STREFY BODY SPACE</button>
                </a>
            </div>
        </div>
    </section>

    <section class="video-backgroundr">
        <video autoplay muted loop>
            <source src="1 film_bodyroll.mp4" type="video/mp4">
        </video>
        <div class="bodyroll">
            <h2>Strefa Body Roll</h2>
            <p>Body Roll to ujędrniający masaż antycellulitowy oraz urządzenie wspomagające proces odchudzania. Relaksująca sesja roll-masażu dodatkowo rozluźnia napięcia i bóle mięśniowe. Specjalne wyprofilowane, drewniane rolki poruszają się z określoną szybkością i w określonym kierunku pozwalając na drenaż całego ciała. Dla kogo: dzięki szerokiemu spektrum zalet, roll-masaż dedykujemy każdemu Roll-masaż w połączeniu z treningiem Body Space przynosi spektakularne efekty w postaci redukcji tkanki tłuszczowej oraz poprawy jakości skóry.</p>
            <a href="https://karnety.bodyspace.pl/">
            <button class="przezroczyst">KARNETY DO STREFY BODY ROLL</button>
            </a>
        </div>
    </section>


               

 <section class="image" style="background-image: url('na_cialo_body\ space\ concept.webp');">
  
     <div class="nacialo">
            <h2>STREFA ZABIEGÓW NA CIAŁO</h2>
            <p>Body Space to także sale zabiegowe. To propozycja dla tych, którzy chcą poprawić wygląd swojej skóry, zwalczyć cellulit oraz pozbyć się lokalnego nadmiaru tkanki tłuszczowej. Nasze urządzenia wspomagają spalanie tłuszczu, redukcję cellulitu oraz napinają skorę.
                <br><br>
                ✓ Tylko u nas! Do każdego zabiegu sesja na Strefie Body Roll gratis!</p>
                <div class="zdjeciap">
                <div class="gallery">
                    <img src="lipolaser_body space concept.webp" alt="Zdjęcie 1">
                    <img src="bodysculpt_body space concept.webp" alt="Zdjęcie 2">
                    <img src="falauderzeniowa_body space concept.webp" alt="Zdjęcie 3">
                    <img src="bodycrio_body space concept.webp" alt="Zdjęcie 4">
                    <img src="ultracontour 5_body space concept.webp" alt="Zdjęcie 5">
                    </div>
                </div>
    <div class="accordionne">
        <div class="accordion-item">
            <div class="accordion-item-header">
                SZYBKA REDUKCJA OBWODÓW CIAŁA <span class="plusr">✚</span>
            </div>
            <div class="accordion-item-body">
                <div class="accordion-item-body-content">
                    <img src="lipolaser2_body space concept.webp" class="foto"><br>
                    1 sesja: 200 zł<br>
                    1 sesja LipoLaser + Body Roll<br>
                    dostep do sitowni w dniu zabiegu<br><br>
                    <a href="https://karnety.bodyspace.pl/">
                        <button class="emskarnet">KUP KARNET</button>
                        </a> </div>
            
            <div class="accordion-item-body-content">
                <img src="lipolaser2_body space concept.webp" class="foto"><br>
                W karnecie: 590 zł (200 zł 147 zł / jedna sesja)<br>
                4 sesje LipoLaser + Body Roll<br>
                dostep do sitowni w dniu zabiegu<br><br>
                <a href="https://karnety.bodyspace.pl/">
                    <button class="emskarnet">KUP KARNET</button>
                    </a> </div>
        </div>
        </div>
     

        <div class="accordion-item">
            <div class="accordion-item-header">
                REDUKCJA CELLULITU <span class="pluse">✚</span>
            </div>
            <div class="accordion-item-body">
                <div class="accordion-item-body-content">
                    <img src="fala_uderzeniowa_body space concept.webp"class="foto"><br>
                    1 sesja: 220 zł<br>
                    1 sesja Fala Uderzeniowa + Body Roll<br>
                    dostep do sitowni w dniu zabiegu <br><br>
                    <a href="https://karnety.bodyspace.pl/">
                        <button class="emskarnet">KUP KARNET</button>
                        </a> 
                    <div class="accordion-item-body-content">
                        <img src="fala_uderzeniowa_body space concept.webp" class="foto"><br>
                        W karnecie: 620 zł (220 zt 155 zł / jedna sesja)<br>
                        4 sesje Fala Uderzeniowa + Body Roll<br>
                        dostep do sitowni w dniu zabiegu <br><br>
                        <a href="https://karnety.bodyspace.pl/">
                            <button class="emskarnet">KUP KARNET</button>
                            </a> </div>
                </div> </div>
            </div>
 

        <div class="accordion-item">
            <div class="accordion-item-header">
                LIPOSUKCJA BEZ SKALPELA <span class="plus">✚</span>
            </div>
            <div class="accordion-item-body">
                <div class="accordion-item-body-content">
                    - rozbijanie komorek truszczowych
                    ultradzwiekami<br>
                    <img src="liposukcja_body space concept.webp" class="foto"><br>
                    1 sesja: 250 zł<br>
                    1 sesja Liposukcja 5D + Body Roll<br>
                    dostep do sitowni w dniu zabiegu<br><br>
                    <a href="https://karnety.bodyspace.pl/">
                        <button class="emskarnet">KUP KARNET</button>
                        </a>
                    <br><br>

                    <img src="liposukcja_body space concept.webp" class="foto"><br>
                    W karnecie: 650 zł (250 zt 162 zł / jedna sesja)<br>
                    4 sesje Liposukcja 5D + Body Roll<br>
                    dostep do sitowni w dniu zabiegu<br><br>
                    <a href="https://karnety.bodyspace.pl/">
                        <button class="emskarnet">KUP KARNET</button>
                        </a>
                </div>
            </div>
        </div>

        <div class="accordion-item">
            <div class="accordion-item-header">
                SILNE UJĘDRNIENIE <span class="plusg">✚</span>
            </div>
            <div class="accordion-item-body">
                <div class="accordion-item-body-content">
                    - endermomasaz z fala radiowa<br>
                    <img src="cellumasaz_5d_body space concept.webp" class="foto"><br>
                    1 sesja: 250 zł<br>
                    1 sesja CelluMasaz 5D + Body Roll<br>
                    dostep do sitowni w dniu zabiegu<br><br>
                    <a href="https://karnety.bodyspace.pl/">
                        <button class="emskarnet">KUP KARNET</button>
                        </a>

                    <br><br>

                    <img src="cellumasaz_5d_body space concept.webp" class="foto"><br>
                    W karnecie: 650 zł (250 zt 162 zł/ jedna sesja)<br>
                    4 sesje CelluMasaz 5D + Body Roll<br>
                    dostep do sitowni w dniu zabiegu<br><br>
                    <a href="https://karnety.bodyspace.pl/">
                        <button class="emskarnet">KUP KARNET</button>
                        </a>
                    </div>
            </div>
        </div>

        <div class="accordion-item">
            <div class="accordion-item-header">
                INTENSYWNE MODELOWANIE CIAŁA <span class="plust">✚</span>
            </div>
            <div class="accordion-item-body">
                <div class="accordion-item-body-content">
                    - 5 technologii podczas jednego zabiegu<br>
                    <img src="ultracontour 5_body space concept.webp" class="foto"><br>
                    1 sesja: 290 zł<br>
                    1 sesja UltraContour 5D + Body Roll<br>
                    dostep do sitowni w dniu zabiegu<br><br>
                    <a href="https://karnety.bodyspace.pl/">
                        <button class="emskarnet">KUP KARNET</button>
                        </a>
                    <br><br>
                    <img src="ultracontour 5_body space concept.webp" class="foto"><br>
                    W karnecie: 690 zł (290 zł 172 zł / jedna sesja)<br>
                    4 sesje UltraContour 5D + Body Roll<br>
                    dostep do sitowni w dniu zabiegu<br><br>
                    <a href="https://karnety.bodyspace.pl/">
                        <button class="emskarnet">KUP KARNET</button>
                        </a>
                 </div>
            </div>
        </div>

        <div class="accordion-item">
            <div class="accordion-item-header">
                MODELOWANIE MIĘŚNI I UJĘDRNIENIE SKÓRY <span class="plusu">✚</span>
            </div>
            <div class="accordion-item-body">
                <div class="accordion-item-body-content">
                    <img src="bodysculpt2_body space concept.webp" class="foto"><br>
                    1 sesja: 290 zł<br>
                    1 sesja BodySculpt RF + Body Roll<br>
                    dostep do sitowni w dniu zabiegu<br><br>
                    <a href="https://karnety.bodyspace.pl/">
                        <button class="emskarnet">KUP KARNET</button>
                        </a>

                    <br><br>
                    <img src="bodysculpt2_body space concept.webp" class="foto" ><br>
                    W karnecie: 690 zł (290 zł 172 zł / jedna sesja)<br>
                    4 sesje BodySculpt RF + Body Roll<br>
                    dostep do sitowni w dniu zabiegu<br><br>
                    <a href="https://karnety.bodyspace.pl/">
                        <button class="emskarnet">KUP KARNET</button>
                        </a>
                 
                </div>
            </div>
        </div>

        <div class="accordion-item">
            <div class="accordion-item-header">
                WZMACNIANIE MIĘŚNI DNA MIEDNICY <span class="plusi">✚</span>
            </div>
            <div class="accordion-item-body">
                <div class="accordion-item-body-content">
                    <img src="ella_body space concept.webp" class="foto"><br>
                    1 sesja: 250 zł<br>
                    1 sesja BodySculpt ELLA + Body Roll<br>
                    dostep do sitowni w dniu zabiegu  <br><br>
                    <a href="https://karnety.bodyspace.pl/">
                        <button class="emskarnet">KUP KARNET</button>
                        </a>
                <br><br>
                <img src="ella_body space concept.webp" class="foto"><br>
                W karnecie: 650 zł (250 zł 162 zł / jedna sesja)<br>
                4 sesje Body Sculpt ELLA + Body Roll<br>
                dostep do sitowni w dniu zabiegu<br><br>
                <a href="https://karnety.bodyspace.pl/">
                    <button class="emskarnet">KUP KARNET</button>
                    </a>
            </div>
            </div>
        </div>

        <div class="accordion-item">
            <div class="accordion-item-header">
                WYMRAŻANIE TKANKI TŁUSZCZOWEJ <span class="plusj">✚</span>
            </div>
            <div class="accordion-item-body">
                <div class="accordion-item-body-content">
                    <img src="kriolipoliza_body space concept.webp"class="foto" ><br>
                    1 sesja: 390 zł<br>
                    1 sesja Kriolipoliza + Body Roll<br>
                    dostep do sitowni w dniu zabiegu<br><br>
                    <a href="https://karnety.bodyspace.pl/">
                        <button class="emskarnet">KUP KARNET</button>
                        </a>
                    </div>
            </div>
        </div>
    </div>
</div>

</div>
<script>
    document.addEventListener('DOMContentLoaded', function () {
        var headers = document.querySelectorAll('.accordion-header');

        headers.forEach(function (header) {
            header.addEventListener('click', function () {
                var panel = this.parentElement;
                var content = panel.querySelector('.accordion-content');

                this.classList.toggle('active');

            
                document.querySelectorAll('.accordion-content').forEach(function (item) {
                    if (item !== content) {
                        item.classList.remove('visible');
                        item.previousElementSibling.classList.remove('active');
                    }
                });

                if (content.classList.contains('visible')) {
                    content.classList.remove('visible');
                } else {
                    content.classList.add('visible');
                }
            });
        });
    });
</script>

</section>




    <section class="image-background" style="background-image: url('tlo_ems_body\ space\ concept.webp');">
        <div class="ems">
            <h2>STREFA TRENINGU EMS</h2>
            <p  style="color:#020101";>Tylko w Body Space Katowice trening EMS łączymy z ćwiczeniami z podczerwienią, co czyni go jeszcze bardziej efektywnym! Jaki jedni z nielicznych ćwiczymy bezprzewodowo!</p>
            <div class="image-container">
                <img src="ems1_body space concept.webp" alt="Zdjęcie 1">
                <img src="ems2_body space concept.webp" alt="Zdjęcie 2">
                <img src="ems3_body space concept.webp" alt="Zdjęcie 3">
            </div>
            <div class="accordion-container">
                <div class="accordion-panel">
                    <div class="accordion-header">
                        INDYWIDUALNY TRENING EMS <span class="plus-in">✚</span>
                    </div>
                    <div class="accordion-content">
                        <div class="accordion-text" style="text-align: left;">
                            <k style="color:#c53d6e">W karnecie:</k><br>
      <k style="color:#c53d6e"> &#x2022; </k> 4 treningi EMS + Body Roll<BR>
      <k style="color:#c53d6e"> &#x2022; </k>    dostęp do siłowni w dniu zabiegu <br><br>
      <a href="https://karnety.bodyspace.pl/">
        <button class="emskarnet">KUP KARNET</button>
        </a>
                        </div>
                    </div>
                </div>
    
                <div class="accordion-panel">
                    <div class="accordion-header">
                        GRUPOWY TRENING EMS<span class="plus-n">✚</span>
                    </div>
                    <div class="accordion-content">
                        <div class="accordion-text" style="text-align: left;">
                            <k style="color:#c53d6e">W karnecie:</k><br>
                            <k style="color:#c53d6e"> &#x2022; </k> 4 treningi grupowe EMS + Body Roll<BR>
                            <k style="color:#c53d6e"> &#x2022; </k> dostęp do siłowni w dniu zabiegu<br><br>
                            <a href="https://karnety.bodyspace.pl/" >
                            <button class="emskarnet">KUP KARNET</button>
                            </a>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <script>
            document.addEventListener('DOMContentLoaded', function () {
                var accordions = document.querySelectorAll('.accordion-item-header');
                accordions.forEach(function (header) {
                    header.addEventListener('click', function () {
                        var item = header.parentElement;
                        var isActive = item.classList.contains('active');
                        
                        document.querySelectorAll('.accordion-item').forEach(function (item) {
                            item.classList.remove('active');
                            item.querySelector('.accordion-item-body').style.maxHeight = null;
                        });

                        if (!isActive) {
                            item.classList.add('active');
                            var body = item.querySelector('.accordion-item-body');
                            body.style.maxHeight = body.scrollHeight + 'px';
                        }
                    });
                });
            });
        </script>
    </section>
    

    <section class="image-backgrounds" style="background-image: url('silka_body\ space\ concept.webp');">
        <div class="silka">
            <h2>Strefa Kobiecej Siłowni</h2>
            <p>Body Space to także w pełni wyposażona, nowoczesna siłownia z klasycznym sprzętem do ćwiczeń z obciążeniami.
                <br><br>✓ Maszyny siłowe   ✓ Wolne ciężary</p><br>
                <a href="https://karnety.bodyspace.pl/">
                <button class="przezroczyste">SPRAWDŹ KARNET NA SAMĄ SIŁOWNIĘ ZA 149 ZŁ </button>
                </a>
        </div>
    </section>

    

    <section class="dulpraw">
        <div class="wozle1">
            <img src="Body-space-company_logo.png" alt="logo3" class="logo3">
            <h6 class="section-title">Nowoczesne studio modelowania<br>sylwetki, fitness i siłownia dla<br> kobiet w Katowicach</h6>
            <p class="contact-info">
                ul. Gen. Waltera-Jankego 14<br>
                40-620 Katowice, Polska
            </p>
            <a href="tel:+48502177000" class="contact-link">+48 502 177 000</a><br><br> 
            <a href="mailto:recepcja@concept.bodyspace.pl" class="contact-link">recepcja@concept.bodyspace.pl</a>
            <div class="social">
                <a href="https://www.facebook.com/BodySpaceConcept/?locale=pl_PL"><img src="facebook_concept.png" class="social-icon"></a>
                <a href="https://www.instagram.com/body_space_concept/"><img src="instagram_concept.png" class="social-icon"></a>
                <a href="https://www.tiktok.com/@bodyspace.official?_t=8oLGx3diSkS&_r=1"><img src="tiktok_concept.png" class="social-icon"></a>
            </div>
        </div>
        <div class="godziny">
            <h6 class="section-title">GODZINY OTWARCIA</h6>
            <p class="info-text">
                poniedziałek - piątek:<br>
                8:00 - 12:00, 15:00 - 22:00<br><br>
                sobota:<br>
                8:00 - 16:00
            </p>
        </div>
        <div class="dulstrefy">
            <h6 class="section-title">NASZE STREFY</h6>
            <p class="info-text">
                Strefa Body Space<br>
                Strefa Body Roll <br>
                Strefa zabiegów na ciało<br>
                Strefa kobiecej siłowni<br>
                Strefa treningu EMS<br>
                Strefa zajęć grupowych          
            </p>
            <br>
            <h6 class="section-title">INFORMACJE</h6>
            <p class="info-text">
                <a href="https://concept.bodyspace.pl/wp-content/uploads/2022/08/Polityka_prywatnosci_serwisu_v1-RODO-1.pdf">Polityka prywatności</a><br>
                <a href="https://concept.bodyspace.pl/wp-content/uploads/2022/08/Regulamin-serwisu-internetowego-1-3.pdf">Regulaminy</a>
            </p>
        </div>
        <div class="PARTNERZY">
            <h2 class="section-title">PARTNERZY</h2>
            <div class="logos">
                <img src="concept_logo.png" alt="logo2" class="logo2">
                <img src="fashion_logo.png" alt="logo3" class="logo3">
                <img src="cosmobelle_logo.png" alt="logo4" class="logo4">
            </div>
        </div>
    </section>
